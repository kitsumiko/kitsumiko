I build models, and I've done it long enough that the field has renamed itself
four times while I was standing in it. I still build them. Somewhere along the
way I started building the systems they run on too.

- **Physics first.** Water systems, a nuclear plant cooling model, build costs
  off terabytes of point cloud data. Concrete doesn't care what your regression
  says, which is a useful thing to learn before anyone hands you a GPU.
- **Then macroeconomics** at a central bank, forecasting for policy work. I have
  strong opinions about seasonal adjustment and I will not be sharing them here.
- **Then the renamings.** Operations research became data science became machine
  learning became AI. I did each of them, mostly in finance. The math kept its
  receipts even when the job titles didn't.
- **Now:** both at once. Models daily, on markets, and the systems underneath
  them: schedulers, process supervisors, control planes, and enough
  observability to notice when any of it is lying to me. C++20 and Go, Rust when
  a project asks for it.

**[k3sm](https://k3sm.io)** · macOS-native Kubernetes for Apple Silicon.
Everything else claiming "Kubernetes on Mac" is a Linux VM with good manners.
This one builds the control plane from upstream source for darwin/arm64 and
runs pods as sandboxed native arm64 processes. It began as a bet that this was
impossible, which it nearly was: the first design died on contact with a real
machine with SIP enabled. Sole engineer, Apache-2.0, repositories open at
v0.1.0.

**[papers](https://github.com/kitsumiko/papers)** · 160+ papers and 40+ policy
documents across 14 domains, arranged into learning paths by role. Built
because a reading list sorted by citation count tells you what's famous, not
what to read first.

Also: a large C++20 distributed research platform, seventh major version, sole
author. Where most of my current modeling lives, and private for that reason.
Six previous versions are in the ground; the seventh is the first one I'd defend
in a code review. There is also a server rack in my house, now demoted to the
legacy tier, which is a polite word for loud.

Occasional contributions to other people's projects, most recently output
routing in a Rust MUD client. Yes, MUDs. Some of us never left.

The day job is security for AI systems at a large company, which is why this
page talks about the work and not the org.

Off keyboard: two black belts (kempo, iaido), a bicycle I take too seriously,
and enough Japanese to get into trouble in a bookstore.
