god
===

god is a scalable, performant, persistent in memory data structure server. It allows massively distributed applications to update and fetch common data in a structured and sorted format.

Its main inspirations are Redis and Chord/DHash. Like Redis it focuses on performance, ease of use and a small, simple yet powerful feature set, while from the Chord/DHash projects it inherits scalability, redundancy and transparent failover behaviour.

# Try it out

<code>go get github.com/zond/god/server</code>, run <code>server</code>, browse to <a href="http://localhost:9192/">http://localhost:9192/</a>.

# Documents

Architectural overview: http://zond.github.com/god/

godoc documentation: http://go.pkgdoc.org/github.com/zond/god

# TODO

* Benchmark
* Example app
 * Implementation
 * Documentation
