Some of the more interesting projects I've played a major role in are listed below.

### Serious production stuff

- [falconeri](https://github.com/dbcrossbar/falconeri): A deliberately simple distributed job runner for Kurbernetes, written in Rust. Has spent many years in production, regularly processing hundreds of gigabytes of data at a time. Good for the sort of thing where you need 350 servers for 23 hours straight. Warranty is _definitely_ voided above 2,000 servers.
- [dbcrossbar](https://github.com/dbcrossbar/dbcrossbar): A tool for moving tables between different kinds of databases. Supports a bunch of different databases. Has been in production a long time.
- (HISTORIC, 2009) [Halyard multimedia engine](https://github.com/emk/halyard): A hybrid 2D/3D multimedia engine scriptable in PLT Scheme, used to build training sofware for Hazmat teams. The 3D part is provided by an embedded Quake 2 engine modified by [Vadim Zeitlin](https://www.linkedin.com/in/vadim-zeitlin-651a93a/), and the 2D part can display transparent overlays over 3D. It also includes a moderately accurate gamma radiation simulation with support for time, distance and shielding (TDS). This was a large and fascinating project back in the day.

### Language learning

- [substudy](https://www.randomhacks.net/substudy/): A langugage-learning tool for making audio flash cards and multi-lingual subtitles from foreign-language video files. Supports Whisper transcription and LLM-powered subtitle translation. (Or it did the last time I checked, but you might need to update the model names and API calls.)

### AI-related projects (personal)

These involve significant amounts of AI coding, though with a human in the loop.

- [redoubtful](https://github.com/emk/redoubtful): A Linux agent sandbox based on `bwrap` and `pasta`. Supports composable profiles, so you can lock things down pretty tightly as required by a specific project. Needs some more network proxy enhancements. Designed for clueless but helpful local agents, not the sort of frontier models that can find kernel zero-days. 

### AI test projects

These are some of the projects I've used to test the state of AI-assisted coding over the years. Very little human code, if any, is involved.

- [xcal-rust](https://github.com/emk/xcal/tree/rust/xcal_rust): A clone of the 1977 mainframe Xcalibur chat program originally written for the Dartmouth College Time Sharing System (DCTS). The big experiment here was building a byte-accurate protocol recorder (with normalization for times and dates), plus a sensible core, then turning a multi-agent Opus 4.x swarm loose. The code isn't terrible, but it did wind up with three copies of the date-formatting routines. Peak implementation throughput was about 3,000 lines in 90 minutes. Actually a neat bit of history, but it only works for real-time synchronous chats. See also the excellent 1997 [C version](https://github.com/creachadair/xcal) by a friend.
- [fable-retro-shopper-android](https://github.com/emk/fable-retro-shopper-android): A clone of my favorite features of the [classic HandyShopper PalmPilot app](https://stuff.mit.edu/afs/sipb/user/golem/tmp/pilot/hs/shop.htm). Specifically, it supports sorting by _per-store aisle numbers_, for efficient passes through the store. This was a Fable 5 one-shot, using $44.40 in tokens and taking 1 hour 46 minutes. 
- [fable-wasm-prolog](https://github.com/emk/fable-wasm-prolog). An actual working (toy) Prolog written in 1,000 lines of WASM WAT assembly language. This was a Fable 5 one-shot, using $16.75 in tokens and taking 61 minutes. Honestly this is the most impressive thing I've seen Fable 5 do.

### Lovingly hand-crafted hacks (ongoing)

- [toy-wasm-lisp](https://github.com/emk/toy-wasm-lisp): The thing I work on airplanes and trains. There is no Lisp here yet, but there's an interesting start to a systems language compiler targeting WASM GC. Also there is a _dire_ prototype of a WASM WAT assembler with Lisp-style macros, but that's best avoided. **Strict hand-written code policy,** because this one is pure fun.
