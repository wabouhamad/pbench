# Pbench [![Stories in Ready](https://badge.waffle.io/distributed-system-analysis/pbench.png?label=ready&title=Ready)](https://waffle.io/distributed-system-analysis/pbench)
A Benchmarking and Performance Analysis Framework

The code base includes three sub-systems. The first being the collection agent
or harness, `pbench-agent`, responsible for providing commands for running
benchmarks across one or more systems, while properly collecting the
configuration of those systems, their logs, and specified telemetry from
various tools (`sar`, `vmstat`, `perf`, etc.).

The second sub-system included here is `bgtasks`, or "back-ground tasks",
which is responsible for archiving result tar balls, indexing them, and
unpacking them for display.

The third sub-system included here is the web server used to display various
graphs and results, and any other content generated by the background tasks,
or by the `pbench-agent` during benchmark and tool post-processing steps.

## How is it installed?
Instructions on installing `pbench-agent`, and other components, can be found
in the "[How to
Install](http://distributed-system-analysis.github.io/pbench/pbench-agent.html#sec-5)"
section of the [Getting Started
Guide](http://distributed-system-analysis.github.io/pbench/pbench-agent.html).

For Fedora, CentOS, and RHEL users, we have made available [COPR
builds](https://copr.fedoraproject.org/coprs/ndokos/pbench/) for the
`pbench-agent`, `configtools`, `pbench-server` and some benchmark packages.

## How do I use pbench?
Refer to this [Getting Started
Guide](http://distributed-system-analysis.github.io/pbench/pbench-agent.html)

TL;DR? See [Section
4](http://distributed-system-analysis.github.io/pbench/pbench-agent.html#sec-4) of the
[Getting Started
Guide](http://distributed-system-analysis.github.io/pbench/pbench-agent.html) for a
super quick set of introductory steps.

## Where is the source kept?
The latest source code is at
https://github.com/distributed-system-analysis/pbench.

## Is there a mailing list for discussions?

Yes, we use [Google Groups](https://groups.google.com/forum/#!forum/pbench)

## Is there a place to track current and future work items?
Yes, we are using GitHub Issues and Pull Requests managed via
[Waffle.io](https://waffle.io/distributed-system-analysis/pbench) for that.
