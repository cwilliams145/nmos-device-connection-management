IS-05 is an AMWA NMOS Specification for connection of networked media devices

### What does it do?

- Provides a transport-independent way of connecting Media Nodes
- Supports single + bulk connections, immediate + delayed connections

### Why does it matter?

- ST 2110 does not specify how to do this
- Danger of multiple proprietary approaches
- Provides extensibility to other types of IP transport
  - e.g. for  IS-07 events

### How does it work?

- IS-04 provides information about Senders and Receivers
- Control application sends instructions to Media Nodes
- ``transportfile`` parameter conveys the connection information for ST 2110 streams

