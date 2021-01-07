<p align="center">
<ul>
<li><strong>Source</strong>: https://github.com/nsqio/nsq
<li><strong>Issues</strong>: https://github.com/nsqio/nsq/issues
<li><strong>Mailing List</strong>: <a href="https://groups.google.com/d/forum/nsq-users">nsq-users@googlegroups.com</a>
<li><strong>IRC</strong>: #nsq on freenode
<li><strong>Docs</strong>: https://nsq.io
<li><strong>Twitter</strong>: <a href="https://twitter.com/nsqio">@nsqio</a>
</ul>
</p>


**NSQ** is a realtime distributed messaging platform designed to operate at scale, handling
billions of messages per day.

It promotes *distributed* and *decentralized* topologies without single points of failure,
enabling fault tolerance and high availability coupled with a reliable message delivery
guarantee.  See [features & guarantees][features_guarantees].

Operationally, **NSQ** is easy to configure and deploy (all parameters are specified on the command
line and compiled binaries have no runtime dependencies). For maximum flexibility, it is agnostic to
data format (messages can be JSON, MsgPack, Protocol Buffers, or anything else). Official Go and
Python libraries are available out of the box (as well as many other [client
libraries][client_libraries]) and, if you're interested in building your own, there's a [protocol
spec][protocol].

We publish [binary releases][installing] for linux, darwin, freebsd and windows as well as an official [Docker image][docker_deployment].


