# Pascal J. Bourguignon

Language implementer and systems engineer. I design and build
compilers, interpreters, runtimes and the tooling around them, mostly
in Common Lisp and C, and I run **[Ogamita Ltd](https://www.ogamita.com)**,
a small software engineering company working on macOS/iOS, Linux,
systems and developer-tool projects.

Paris, France · [ogamita.com](https://www.ogamita.com) ·
[LinkedIn](https://www.linkedin.com/in/pascal-bourguignon-a100a48/)

## Current work

- **[clautolisp](https://gitlab.com/ogamita/clautolisp)**: a
  specification, an implementation and a conformance test suite for
  AutoLISP / Visual LISP, the scripting language of AutoCAD and
  BricsCAD. It runs, debugs and compiles AutoLISP outside the CAD
  application, so that CAD code can be tested in CI. Validation
  against real AutoCAD and BricsCAD is in progress. Written in Common
  Lisp.
  Video walkthroughs: [@clautolisp](https://www.youtube.com/@clautolisp).
- **[bocl](https://gitlab.com/bocl/bocl)**: a Common Lisp
  implementation designed to be built on any POSIX system with nothing
  but a standard C compiler. It has a small, strictly portable C kernel
  with its own garbage collector, and the rest is written in Lisp.
- **[delta-ota](https://gitlab.com/ogamita/delta-ota)**: over-the-air
  distribution for multi-gigabyte software. After the first install,
  each upgrade ships only a binary delta between releases. It has an
  SBCL server and single-binary Go agents for Linux, macOS and Windows,
  and an interrupted upgrade never breaks the installed version.
  Dual-licensed (AGPL / commercial) Ogamita product.
- **[ALPM](https://gitlab.com/ogamita/alpm)**: ASDF-style system
  definitions and dependency-ordered loading for AutoLISP, on AutoCAD,
  BricsCAD and clautolisp. Released, with a specification and a user
  manual.

## Earlier and long-running work

- **[com.informatimago](https://gitlab.com/com-informatimago/com-informatimago)**:
  my collection of Common Lisp libraries: portable utilities, parsers,
  POSIX bindings, Objective-C reader macros, and many small programs.
- **[PatchWork](https://github.com/informatimago/patchwork)**: porting
  IRCAM's PatchWork computer-aided composition environment from MCL
  to Clozure CL on macOS, including a re-implementation of the MCL GUI
  library ([mclgui](https://github.com/informatimago/mclgui)).
- **[lisp-1-5](https://github.com/informatimago/lisp-1-5)**: a
  machine-readable transcription of the LISP 1.5 sources (1962).
- **[commands](https://github.com/informatimago/commands)**:
  command-line tools written in Common Lisp, built into one executable.

## Tools

Common Lisp (SBCL, CCL, ECL, CLISP) · C · AutoLISP / Visual LISP ·
Emacs Lisp · Go · Swift / Objective-C · macOS, Linux, Windows ·
GitLab CI

## Where the code lives

Active development is on GitLab, in the
[ogamita](https://gitlab.com/ogamita),
[bocl](https://gitlab.com/bocl) and
[com-informatimago](https://gitlab.com/com-informatimago) groups.
Some projects are mirrored on GitHub.

## How I work

Specifications and tests come first. Since 2026 I also use AI coding
assistants, under close review; many recent commits say so in a
`Co-Authored-By` trailer.
