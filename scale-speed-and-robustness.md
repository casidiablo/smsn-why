Semantic Synchrony can use any graph backend, because it uses Gremlin, a meta-language for graph APIs. It currently supports Neo4j, but it would only takes a couple new Java classes to add support for Titan or something else.

In a graph with hundreds of thousands of notes, on a three-year-old Lenovo laptop, most Semantic Synchrony views load with zero perceptible lag. (Big queries, such as `every note containing the word "for"`, can still take a long time.)

The folks at Neo4j provide a sense for how it scales [here](https://neo4j.com/news/how-much-faster-is-a-graph-database-really/).
