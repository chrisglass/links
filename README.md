# Links

A collection of useful and insightful links found on the internet.
This is basically a personal reference that also happens to be public

## Programming practices and patterns

- [Antirez on writing comments](http://antirez.com/news/124) Taxonomy of comments, and how to write useful comments
- [Writing maintainable code is a communication skill](https://max.engineer/maintainable-code) A very well put article about comments and communication
- [The rule of three](https://en.wikipedia.org/wiki/Rule_of_three_(computer_programming)) and [a longer form take on it](https://andrewbrookins.com/technology/the-rule-of-three/)
- [The law of least surprise](https://en.wikipedia.org/wiki/Principle_of_least_astonishment)
- [YAGNI](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it) Don't add functionality until deemed necessary
- [POSIX locks in Go/Python/Rust](https://github.com/chrisglass/posix-locks) (by me :metal:) Example implementations of mutually-locking POSIX locks in different languages.
- [General Orchestrator pattern](https://kislayverma.com/software-architecture/architecture-pattern-orchestration-via-workflows/)
- [Why duck typing is safe](http://www.jerf.org/iri/post/2954)
- [Don't mock what you don't own](https://hynek.me/articles/what-to-mock-in-5-mins/) A great article about unit testing and mocking
- [Mocks aren't stubs](https://martinfowler.com/articles/mocksArentStubs.html) Taxonomy of test mocks/stubs and when to use them
- [The C4 model for visualizing software architecture](https://c4model.com/) A framework for documenting software architecture
- [69 ways to mess up your deploy](https://kellyshortridge.com/blog/posts/69-ways-to-mess-up-your-deploy/) A reflexion on pitfalls in a Devops world
- [OWASP Security guidelines](https://cheatsheetseries.owasp.org/index.html) A very digestible collection of articles on practical security.
- [No YAML](https://noyaml.com/) Some gotchas about YAML and why we should avoid to use it.
- [GyShiDo](https://gyshido.com) The art of getting your shit done 
- [Sans-IO](https://sans-io.readthedocs.io/) A collection of links to protocols implemented as bring-your-own-IO

## AI Stuff

In the middle of the AI craze, it's good to have a list of products that actually show promise.

- [Reclaim](https://reclaim.ai/) Let AI organize your calendar
- [Copilot](https://github.com/features/copilot) Your AI peer programmer
- [Should I solve it with AI?](https://tiferet.github.io/posts/should-i-solve-it-with-ai/) A great take on what to ask yourself before jumping on the AI bandwagon

## Programming languages

A collection of language-specific links.

### Rust

- [Anyhow](https://docs.rs/anyhow/latest/anyhow/) and [Thiserror](https://docs.rs/thiserror/latest/thiserror/) for error handling.
- [Meuse](https://github.com/mcorbin/meuse) A private crates registry with tons of features.
- [Reshape](https://github.com/fabianlindfors/reshape) provides 0-downtime schema migrations (see [the blog post](https://fabianlindfors.se/blog/schema-migrations-in-postgres-using-reshape/), too)
- [Writing an OS in Rust](https://os.phil-opp.com/) a series of articles/tutorials on building a minimal (bootable) OS in Rust.
- [Cargo bloat](https://github.com/RazrFalcon/cargo-bloat) a nifty tool giving you the worst offenders in your build deps for build time/space.
- [Idiomatic rust](https://github.com/mre/idiomatic-rust)
- [A gentle introduction to Rust](https://stevedonovan.github.io/rust-gentle-intro/) great beginner-friendly tutorial, narrated (as opposed to reference-like)
- [Cheats.rs](https://cheats.rs) a Rust cheatsheet
- [Axum](https://github.com/tokio-rs/axum) a Rust web framework
- [Polars](https://pola.rs) a Rust data framework/library that interfaces natively with the python ecosystem as well
- [Maturin](https://www.maturin.rs/) a Rust build system to trivially build Python extensions in Rust.
- [Egui](https://www.egui.rs/) an outstanding immediate mode UI library
- [remoc](https://github.com/ENQT-GmbH/remoc/) an amazing library to make interacting with remote rust programs a breeze
- [Databend](https://github.com/datafuselabs/databend) a modern alternative to snowflake, written in Rust

### Python

- [Hy](https://github.com/hylang/hy) a dialect of lisp that embeds in python
- [Lark](https://github.com/lark-parser/lark) a parsing toolkit/DSL framework for python. [This blog post](http://blog.erezsh.com/how-to-write-a-dsl-in-python-with-lark/) is pretty nice to explain some of the usage, too.
- [Hypothesis](https://hypothesis.readthedocs.io/en/latest/) fuzzing python programs, the smart way
- [A list and comparison of Python package managers](https://bas.codes/posts/python-virtualenv-venv-pip-pyenv-poetry) pip, pipenv, poetry, venv, virtualenv, pipx...
- [Pre-commit](https://pre-commit.com/) A python package to make pre-commit hooks much easier to write/run
- [Memray](https://github.com/bloomberg/memray) A pretty good memory profiler
- [Scalene](https://github.com/plasma-umass/scalene) A high performance profiler
- [Slipcover](https://github.com/plasma-umass/slipcover) a near-zero overhead coverage tool for python
- [Writing a weechat plugin in Python](https://weechat.org/files/doc/stable/weechat_scripting.en.html)
- [Pretend](https://github.com/alex/pretend) a library to write stubs easily
- [Ruff](https://github.com/charliermarsh/ruff) a really fast linter written in Rust
- [Streamlit](https://streamlit.io) an amazing data visualization library


### Clojure

- [How to write a Clojure application](https://www.exoscale.com/syslog/clojure-application-tutorial/) (by me :metal:) how to write a Clojure webapp with DB from scratch.
- [Today in Clojure](https://todayinclojure.com/) a simple news aggregator for the clojure world.
- [The clojure cheatsheet](https://clojure.org/api/cheatsheet) for those times when you really can't remember what `mapcat` does
- [Clojure for the brave and true](https://www.braveclojure.com/) great beginner book, one of my favorite technical books ever
- [Loopr](https://aphyr.com/posts/360-loopr-a-loop-reduction-macro-for-clojure) a loop/reduction macro for clojure, by Aphyr
- [Jank](https://jank-lang.org/) an LLVM-backed implemention of Clojure

### Golang

- [The zen of Go](https://dave.cheney.net/2020/02/23/the-zen-of-go) a pretty good article on some aspects of "idiomatic" Go.
- [Maps and memory leaks](https://teivah.medium.com/maps-and-memory-leaks-in-go-a85ebe6e7e69) some important highlights of go's memory management.
- [Go vuln check](https://go.dev/blog/vuln) A security scanner for your go dependencies

## Ubuntu

- [Pending SRUs](https://people.canonical.com/~ubuntu-archive/pending-sru.html) The list of SRUs currently in progress. Helpful to help validate/track status when waiting for a fix.
- [Sponsorship queue](http://reqorts.qa.ubuntu.com/reports/sponsoring/) The list of patches to packages by non-maintainers/non-developers awaiting a maintainer sponsorship to land.
- [Upload queue](https://launchpad.net/ubuntu/impish/+queue?queue_state=1)
- [The launchpad build farm](https://launchpad.net/builders)
- [Proposed migration excuses](https://people.canonical.com/~ubuntu-archive/proposed-migration/update_excuses.html)
- [Merge-o-matic](https://merges.ubuntu.com/)
- [Transitions tracker](https://people.canonical.com/~ubuntu-archive/transitions/html/)
- [Components mismatches](http://people.canonical.com/~ubuntu-archive/component-mismatches.txt)
- [Ubuntu Amazon EC2 AMI Finder](https://cloud-images.ubuntu.com/locator/ec2/)

## Data/databases
- [Hadoop and Kerberos: The madness beyond the gate](https://steveloughran.gitbooks.io/kerberos_and_hadoop/content/sections/kerberos_the_madness.html)
- [Materialize](https://github.com/MaterializeInc/materialize) "materialized views" over streaming data sources such as kafka topics

## CLI tools

- [termshark](https://termshark.io/) when normal wireshark is too heavy, or you don't have a GUI
- [fzf](https://github.com/junegunn/fzf) a command-line fuzzy finder
- [spotifyd](https://github.com/Spotifyd/spotifyd) a spotify-compatible daemon (appears in your list of spotify devices)
- [gh-prs](https://github.com/dlvhdr/gh-prs) View and interact with github PRs in the terminal
- [barrier](https://github.com/debauchee/barrier) an open-source software KVM switch that works seamlessly across Mac, Windows and Linux.
- [Never use git push --force](https://salferrarello.com/never-git-push-force/) never use --force, always --force-with-lease (or a "please" alias)


## Dealing with people

- [How to Deal with Difficult People on Software Projects](https://people.neilon.software/)
- [Unlearning toxic behaviors in a code review culture](https://medium.com/@sandya.sankarram/unlearning-toxic-behaviors-in-a-code-review-culture-b7c295452a3c)
- [On being a senior Engineer](https://www.kitchensoap.com/2012/10/25/on-being-a-senior-engineer/)
- [Communication in a remote setting](https://basecamp.com/guides/how-we-communicate) Basecamp is 100% remote, some reflections about communicating in that setting.
- [Remote communication guidelines](https://shiphero.com/careers/communication-guidelines/) another communications guide by a fully remote company, Shiphero
- [Encouraging a culture of remote communication](https://www.mcls.io/blog/encouraging-a-culture-of-written-communication)
- [The rules of civil conversation](https://therulesofcivilconversation.org/)
- [We need someone who has done "it" before](https://cutlefish.substack.com/p/tbm-1852-we-need-someone-who-has?s=r) A common trap when hiring
- [Untools](https://untools.co/) A repository of tools about communicating and other topics
- [A Gentler, Better way to change minds](https://www.theatlantic.com/family/archive/2022/04/arguing-with-someone-different-values/629495/) A take on convincing people

## Meta: other lists of links and TILs
- [Pawel's](https://github.com/pawroman/links)
- [Simon Willison's](https://til.simonwillison.net)
- [Josh Branchaud's](https://github.com/jbranchaud/til)
- [Srinivas's](https://shireenrao.github.io/til/)

## Meta
My <a rel="me" href="https://hachyderm.io/@tribaal">Mastodon</a> (on hachyderm.io)
