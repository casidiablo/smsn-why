# Semantic Synchrony: An invitation to coders

[Semantic Synchrony](http://www.github.com/synchrony/smsn/wiki/) serves a knowledge graph. Graphs can be selectively shared as a set of [Git](http://www.git-scm.com/) repositories; if so, their full git history is available within the front-end. The graph can be viewed as trees, traversed stepwise, and searched for keywords using boolean logic, using the [Apache Lucene](https://lucene.apache.org/core/) query language.

Here is a brief sample of Semantic Synchrony's many [cool features](https://github.com/synchrony/smsn/wiki/SmSn's-features-in-250-words). The [wiki](https://github.com/synchrony/smsn/wiki) is thorough and friendly; there are even demonstration videos.

More front-ends are possible; the server communicates using simple JSON. [smsn-mode](http://github.com/synchrony/smsn-mode/), the [Emacs](http://www.gnu.org/software/emacs/) font-end, resembles an ordinary text editor. It requires no familiarity with Emacs, and only [25 commands](https://github.com/synchrony/smsn-mode/wiki/Some-critical-shortcuts) to use.

Our shared graph can also be directly [accessed via Gremlin Console](https://github.com/synchrony/smsn/wiki/Gremlin-on-the-Graph). Gremlin is a metalanguage for graph programming, part of Apache Tinkerpop. (If they change the details of Neo4j or Titan, and you write something in Gremlin, your code is safe.)

## Languages

The server code is Java. The front-end code is Emacs Lisp. Those two communicate via JSON. We want to incorporate Eta, a flavor of Haskell that compiles to the JVM.

The graph query language is Gremlin.

[Markdown](https://daringfireball.net/projects/markdown/syntax) is becoming critical to the data model, as is described next.

## Data model in flux

The model is expanding from a graph with unlabeled edges to one with optional edge labels. Labeled edges can be created as Markdown headings, and nodes can serve double-duty as edge-labels.

The concept of a source of data is expanding. It used to have to be a graph, but now it includes git repositories, and more forms are on the way.

## It's not as much code as it appears

The Emacs client, [smsn-mode](https://github.com/synchrony/smsn-mode), is small. The server, [smsn](https://github.com/synchrony/smsn), looks big, but much of that is experimental stuff nobody really uses.

We are only two developers right now. You could have a huge impact.

## Contact us

I mean, you don't have to, but we would love to hear from you. Find us on [Github](https://github.com/synchrony), [Gitter](https://gitter.im/synchrony), or [Facebook](https://facebook.com/semanticsynchrony).
