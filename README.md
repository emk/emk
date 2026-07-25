Some of the more interesting projects I've played a major role in are listed below.

### Serious production stuff

- [falconeri](https://github.com/dbcrossbar/falconeri): A deliberately simple distributed job runner for Kurbernetes. Good for the sort of thing where you need 350 servers for 23 hours straight. Warranty is _definitely_ voided above 2,000 servers.
- [dbcrossbar](https://github.com/dbcrossbar/dbcrossbar): A tool for moving tables between different kinds of databases, with automatic schema conversions. Opinionated.
- (HISTORIC, 2009) [Halyard multimedia engine](https://github.com/emk/halyard): 2D/3D multimedia engine scriptable in PLT Scheme, used to build training sofware for Hazmat teams. Includes an embedded Quake 2 engine modified by [Vadim Zeitlin](https://www.linkedin.com/in/vadim-zeitlin-651a93a/) and a moderately accurate gamma radiation simulation.

### Language learning

- [substudy](https://www.randomhacks.net/substudy/): Turn foreign-language video files into audio flash cards. Whisper transcription, LLM-powered subtitle translation.

### AI-related projects

Tools for using AI, written by supervised AI:

- [redoubtful](https://github.com/emk/redoubtful): A Linux agent sandbox based on `bwrap` and `pasta` with composable profiles.

Dubious AI test projects:

- [vibe-coded-meme-database](https://github.com/emk/vibe-coded-meme-database): Early experiment with Sonnet 3.7. Exercise caution.
- [xcal-rust](https://github.com/emk/xcal/tree/rust/xcal_rust): A clone of the 1977 mainframe Xcaliber chat program. The big experiment here was building a byte-accurate protocol recorder, plus a sensible core, then turning a multi-agent Opus 4.x swarm loose. It did wind up with three copies of the date-formatting routines. Peak implementation throughput was about 3,000 lines in 90 minutes. See also the excellent 1997 [C version](https://github.com/creachadair/xcal) by a friend.
- [fable-retro-shopper-android](https://github.com/emk/fable-retro-shopper-android): Partial clone of the [classic HandyShopper PalmPilot app](https://stuff.mit.edu/afs/sipb/user/golem/tmp/pilot/hs/shop.htm). Supports sorting by per-store aisle numbers, for efficient passes through the store. Fable 5 one-shot, $44.40 in tokens, 1 hour 46 minutes. 
- [fable-wasm-prolog](https://github.com/emk/fable-wasm-prolog). A toy Prolog written in 1,000 lines of WASM WAT assembly language. Fable 5 one-shot, $16.75 in tokens, 61 minutes.

### Lovingly hand-crafted hacks (ongoing)

- [toy-wasm-lisp](https://github.com/emk/toy-wasm-lisp): The thing I work on airplanes and trains. There is no Lisp here yet, but there's an interesting start to a systems language compiler targeting WASM GC. Also there is a _dire_ prototype of a WASM WAT assembler with Lisp-style macros, but that's best avoided. **Strict hand-written code policy,** because this one is pure fun.
