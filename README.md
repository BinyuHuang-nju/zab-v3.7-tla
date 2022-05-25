# ZAB 1.0-tla

## Overview
This project is devoted to providing formal specification and verification using TLA+ for the Zookeeper Atomic Broadcast(ZAB) consensus protocol proposed by apache/zookeeper, with version 3.7.

We have made a formal [specification](ZabWithFLEAndSYNC.tla) for Zab using TLA+ toolbox, and we have done a certain scale of model checking to verify the correctness of Zab.

We have also made a formal [specification](FastLeaderElection.tla) for Fast Leader Election in Zab since ZAB 1.0 depends on FLE to complete the election phase.

There exist some differences between our specification and engineering implementation, which are not contrary to facts. If you have any question, please let us know.