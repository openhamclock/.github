# GitHub for Open Source HamClock and Backend

HamClock is a kiosk-style application that provides real time space weather, radio propagation models, operating events and other information particularly useful to the radio amateur. HamClock was introduced in an
[October 2017 QST article](https://web.archive.org/web/20251130070310/https://clearskyinstitute.com/ham/HamClock/QST-HamClock.pdf).

In early 2026, the community of HamClock enthusiasts was sad to learn that the
creator of [HamClock was now an SK](https://www.reddit.com/r/amateurradio/comments/1qqdwln/elwood_downey_wb0oew_creator_of_hamclock_is/)
and that the [HamClock site](https://clearskyinstitute.com/ham/HamClock/) announced:

> HamClock has reached end-of-life, the last release is version 4.22.
> All HamClocks will cease to function in June 2026.
> Thank you for your interest.
> Elwood Downey, WB0OEW, <ecdowney@clearskyinstitute.com>

Clearsky's HamClock consisted of an open source front-end client and a closed-source backend server. The client required the backend server to work. Since the news, a few efforts have kicked off to maintain or create something similar for the future.

# Two Projects
## The Client
### HamClock
The HamClock project is the kiosk-style client that users run in their home network. The HamClock client requires a server-based backend to function. An installation requires selection of the backend server to which the client will connect.

## The Server Backend

### hamclock.com
The team at [hamclock.com](https://hamclock.com) have created a closed-source backend compatible with Clear Sky Institute's HamClock client.

### Open HamClock Backend
The Open HamClock Backend ([OHB](https://ohb.works)) project creates an open source project compatible with Clear Sky Institute's HamClock client.

# Standards
To maintain compatibility between variants of the HamClock client and the HamClock backends, this organization includes a [standards](https://github.com/openhamclock/hamclock-standards) repository to define communication between the client and the backend server.

# History
Clearsky's history of revisions, release notes and community contributions are [archived in a respository](https://github.com/openhamclock/hamclock-client-archive), as well.



