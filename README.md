I build models. The field renamed itself four times while I was in it.

- 🌊 **Started in physics.** Water systems, nuclear plant models, build
  costs off terabytes of point cloud data.
- 📉 **Then a few banks.** Forecasting, for policy work.  OR became DS became ML became AI. Same math, new letterhead.
- ⚙️ **Still, both at once.** Models on markets daily, plus the systems under
  them: schedulers, supervisors, control planes, and enough observability to
  catch any of it lying to me. C++ longest, Python most fluent, Go for the
  infrastructure, Rust when a project asks.
- 🛡️ **And now securing them.** Security engineering, architecture, and governance for AI
  systems in production. Most of it is old problems arriving faster: identity,
  authorization, data lineage. The new part is threat modeling something that
  answers differently twice.

**[k3sm](https://k3sm.io)** · macOS-native Kubernetes for Apple Silicon.
Everything else claiming "Kubernetes on Mac" is a Linux VM with good manners.
This one isn't: upstream control plane built from source for darwin/arm64, pods
running as sandboxed native arm64 processes. Linux images still run — opt-in,
each in its own micro-VM on a kernel I build and pin. It also serves models:
an `MLXModel` CRD schedules LLMs onto Apple GPUs behind an OpenAI-compatible
API, because of course it does. Started as a bet it was impossible. It nearly
was. The first design died on contact with a real machine, SIP on; the current
one closes milestones only on real hardware. Solo engineer, Apache-2.0.

**[papers](https://github.com/kitsumiko/papers)** · 200+ papers, 40+ policy
documents, 14 domains, arranged as learning paths instead of a pile. A reading
list sorted by citation count tells you what's famous, not what to read first.

Elsewhere: output routing in a Rust MUD client. Yes, MUDs. Some of us never
left. I'm miko on [swmud.org](https://swmud.org).
