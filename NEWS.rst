News for kodo-ns3-examples
==========================

This file lists the major changes between versions. For a more
detailed list of every change, see the Git log.

Latest
------
* tbd
* Minor: Added the kodo-wifi-broadcast-object example that transmits a
  large object in memory which is automatically split into multiple
  blocks/generations.
* Minor: Changed the wifi example to use the RandomPropagationLossModel
  which allows us to simulate randomized packet loss on the receivers.
  With the default loss values, the receivers randomly drop 50% of the packets.
* Major: Remove the kodo-cpp dependency, and use kodo-rlnc 13 directly in the
  examples. With this change, the users can leverage the full public API of
  kodo-rlnc in the ns-3 simulations.

1.0.0
-----
* Major: Initial release
