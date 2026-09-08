# Thinq, for Windows

Installers, and the `latest.yml` the installed app reads to update itself.
Nothing else lives here: the app is built from a private repository and only
its binaries come out.

Download the newest `Thinq-Setup-*.exe` from
[Releases](https://github.com/canmenzo/thinq-releases/releases/latest). After
that the app fetches its own updates and says so in the corner: one relaunch
and it is in.

## Windows says it protected your PC

It does that to an installer it has never seen, from a publisher it cannot
name. This one is unsigned, and that is the whole of the complaint: **More
info**, then **Run anyway**.

Windows only asks about files marked as coming from the internet, which is
something browsers do when they save one. The updates the app fetches for
itself are not marked, so the question is asked once, about the file you
downloaded yourself, and never again.
