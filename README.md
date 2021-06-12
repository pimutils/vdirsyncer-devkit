# vdirsyncer devkit

This repository contains utilities used for develoment and testing of
vdirsyncer.

Docker images are generated to quickly run CalDAV servers to run integration
tests against them.

These are kept separately since they have a differenty lifecycle from
`vdirsyncer` itself; we only ocasionally need to rebuild these images, and
running in our main repo's pipeline would slow it down too much and waste a lot
of processing power.
