`parquet-tools` is a handy tool to inspect parquet files.

Every few months I need it and I realize that I lost the last jar that worked.
It is open source, though, so it should be easy to procure, right?

Well, not if you are dumb.

Their readme show you how to build using the old, mighty Maven, which fails to
compile more often than not. Last time I tried it couldn't resolve some Jackson
libraries. Jackson. The most ubiquitous of all fucking libraries!

There are also some jars around which do not have all the dependencies, so you
can just run them.

I'm ending this pain once and for all. Here's the fucking jar if you need it:

[parquet-tools-1.11.0]()

I also wrapped in docker, why the hell no. Fuck tooling. All tooling. Even you,
oh mighty JVM, go eat my underwear!
