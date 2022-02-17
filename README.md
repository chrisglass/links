# Links

A collection of useful and insightful links found on the internet.
This is basically a personal reference for stuff.

Inspired by [Pawel's links repository](https://github.com/pawroman/links). Many thanks!

## General programming practices

- [Antirez on writing comments](http://antirez.com/news/124) Taxonomy of comments, and how to write useful comments
- [The rule of three](https://en.wikipedia.org/wiki/Rule_of_three_(computer_programming)) and [a longer form take on it](https://andrewbrookins.com/technology/the-rule-of-three/)
- [The law of least surprise](https://en.wikipedia.org/wiki/Principle_of_least_astonishment)
- [YAGNI](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it) Don't add functionality until deemed necessary

## Programming languages

A collection of language-specific tips and tricks.
### Rust

- [Anyhow](https://docs.rs/anyhow/latest/anyhow/) and [Thiserror](https://docs.rs/thiserror/latest/thiserror/) for error handling.
- [Meuse](https://github.com/mcorbin/meuse) A private crates registry with tons of features.
- [Reshape](https://github.com/fabianlindfors/reshape) provides 0-downtime schema migrations (see [the blog post](https://fabianlindfors.se/blog/schema-migrations-in-postgres-using-reshape/), too)

### Python

- [Hy](https://github.com/hylang/hy) a dialect of lisp that embeds in python
- [Lark](https://github.com/lark-parser/lark) a parsing toolkit/DSL framework for python. [This blog post](http://blog.erezsh.com/how-to-write-a-dsl-in-python-with-lark/) is pretty nice to explain some of the usage, too.
- [Hypothesis](https://hypothesis.readthedocs.io/en/latest/) fuzzing python programs, the smart way

### Clojure

- [How to write a Clojure application](https://www.exoscale.com/syslog/clojure-application-tutorial/) (by me :metal:) how to write a Clojure webapp with DB from scratch.
- [Today in Clojure](https://todayinclojure.com/) a simple news aggregator for the clojure world.
- [The clojure cheatsheet](https://clojure.org/api/cheatsheet) for those times when you really can't remember what `mapcat` does

### Golang

- [The zen of Go](https://dave.cheney.net/2020/02/23/the-zen-of-go) a pretty good article on some aspects of "idiomatic" Go.

### Multiple

- [POSIX locks in Go/Python/Rust](https://github.com/chrisglass/posix-locks) (by me :metal:) Example implementations of mutually-locking POSIX locks in different languages.

## Ubuntu

- [Pending SRUs](https://people.canonical.com/~ubuntu-archive/pending-sru.html) The list of SRUs currently in progress. Helpful to help validate/track status when waiting for a fix.
- [Sponsorship queue](http://reqorts.qa.ubuntu.com/reports/sponsoring/) The list of patches to packages by non-maintainers/non-developers awaiting a maintainer sponsorship to land.
- [Upload queue](https://launchpad.net/ubuntu/impish/+queue?queue_state=1)
- [The launchpad build farm](https://launchpad.net/builders)
- [Proposed migration excuses](https://people.canonical.com/~ubuntu-archive/proposed-migration/update_excuses.html)
- [Merge-o-matic](https://merges.ubuntu.com/)
- [Transitions tracker](https://people.canonical.com/~ubuntu-archive/transitions/html/)
- [Components mismatches](http://people.canonical.com/~ubuntu-archive/component-mismatches.txt)
- [Kernel SRU workflows](http://kernel.ubuntu.com/sru/kernel-sru-workflow.html)
- [Ubuntu Amazon EC2 AMI Finder](https://cloud-images.ubuntu.com/locator/ec2/)

## Hadoop
- [Hadoop and Kerberos: The madness beyond the gate](https://steveloughran.gitbooks.io/kerberos_and_hadoop/content/sections/kerberos_the_madness.html)

## CLI tools

- [termshark](https://termshark.io/) when normal wireshark is too heavy, or you don't have a GUI
- [fzf](https://github.com/junegunn/fzf) a command-line fuzzy finder
- [spotifyd](https://github.com/Spotifyd/spotifyd) a spotify-compatible daemon (appears in your list of spotify devices)


## Dealing with people

- [How to Deliver Constructive Feedback in Difficult Situations](https://medium.dave-bailey.com/the-essential-guide-to-difficult-conversations-41f736e63ccf) a summary of Rosenberg's excellent "Nonviolent communication" book.
- [How to Deal with Difficult People on Software Projects](https://people.neilon.software/)
- [Unlearning toxic behaviors in a code review culture](https://medium.com/@sandya.sankarram/unlearning-toxic-behaviors-in-a-code-review-culture-b7c295452a3c)
- [On being a senior Engineer](https://www.kitchensoap.com/2012/10/25/on-being-a-senior-engineer/)
- [Communication in a remote setting](https://basecamp.com/guides/how-we-communicate) Basecamp is 100% remote, some reflections about communicating in that setting.

## Meta: other lists of links and TILs
- [Pawel's](https://github.com/pawroman/links)
- [Simon Willison's](https://til.simonwillison.net)
- [Josh Branchaud's](https://github.com/jbranchaud/til)
- [Srinivas's](https://shireenrao.github.io/til/)