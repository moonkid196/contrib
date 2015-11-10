# CFEngine Contrib

*Contributed promises. (Practical examples of using Cfengine 3 to automate
system administration). NOT FROM CFENGINE.ORG/CFENGINE.COM -- contributed by
Cfengine users.*

This is a fork of the original cfengine/contrib repository. It was seeing
little activity, so I decided to have a go at contributing my own work and make
this more robust. Hopefully, this might generate some interest in such a thing
again.

The text from the origin is at the bottom. Enjoy!

## Goals

Here are some of the bundles/services/etc, which I'd like to see bundles
created to manage (whether I make them or someone else):

- A good, stand-alone *IPTables* set of bundles
- Similarly a good UFW bundle-set
- More SELinux management. I'm working on this one.
- More bundles which implement the new, module-based packages API in 3.7. This
  includes at least the following:
  - PIP package handling
  - YUM groups package handling
  Some perl/CPAN or ruby-gems would be good contributions
- Some of the more interesting *systemd* features (via *unit files*) would be
  interesting to have (e.g. the *systemd timers*)


## Origin

```
Contributions welcome!  

Best,
Aleksey
```
