# Readme
A note about HTTP Cookie.

### HTTP Cookie

User Agent每次发送HTTP请求的时候都会带上HTTP Cookie中的全部字段，而不仅仅是本次HTTP调用和服务需要的那些字段。
- 导致这些HTTP请求的语义显得含糊。
- 给HTTP Caching带来很大的干扰。

### Credits
- [Architectural Styles and the Design of Network-based Software Architectures](https://ics.uci.edu/~fielding/pubs/dissertation/top.htm)
