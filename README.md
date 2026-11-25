# WMO First Mile Data Exchange tools

This repository contains tools which implement the [WMO First Mile Data Exchange standard](https://wmo-im.github.io/fmde/standard/fmde-DRAFT.html), specifically example implementations of first mile protocol senders and receivers.

## Contents

* [`schemas/first-mile-message-encoding.proto`](schemas/first-mile-message-encoding.proto) - copy of the First Mile message encoding protobuf schema from the [FMDE standard repository](https://github.com/wmo-im/fmde/blob/main/schemas/first-mile-message-encoding.proto), used by the examples
* [`reference-implementations/python-example`](reference-implementations/python-example) - Python node (sender), host (receiver) and payload generator
* [`reference-implementations/c-nanopb-example`](reference-implementations/c-nanopb-example) - C encoder for embedded devices, using nanopb
