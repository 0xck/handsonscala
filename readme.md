# Hands-on Scala Programming

This repository is the online hub for the book
[*Hands-on Scala Programming*](https://handsonscala.com/):

- [Chapter Notes, Errata, and Discussion](https://www.handsonscala.com/discuss):
  go here if you want to leave comments or ask questions about individual
  chapters

- [Code Snippets](https://github.com/handsonscala/handsonscala/tree/master/snippets):
  copy-paste friendly versions of every code snippet in the book

- [Chapter Resource Files](https://github.com/handsonscala/handsonscala/tree/master/resources):
  files used as part of the book's programming exercises

- [Executable Code Examples](https://github.com/handsonscala/handsonscala/tree/master/examples):
  self-contained executable programs for the topics being presented in each
  chapter.

## Executable Code Examples

The executable code examples from *Hands-on Scala* are freely available online,
and open source under an MIT license. Each example is:

- **Self-contained**: to be run either using the
  [Ammonite script runner](http://ammonite.io/) or [Mill build
  tool](http://www.lihaoyi.com/mill/), with no other setup

- **Tested**: with simple test suites provided and instructions on how to run each
  example in that folder's `readme.md` file

- **Executable**: you can download the folder and run the example yourself to
  see it in action

Many of the examples are related, with only small code changes between them to
illustrate a new feature or technique. The `readme.md` file of such downstream
examples will show a diff from the upstream example that it was based upon, so
you can focus your attention on the important code changes that are happening,
with a link back up to the upstream example.

The executable code examples below are organized by each part and each chapter
of the book.
## [Part I Introduction to Scala](https://www.handsonscala.com/part-i-introduction-to-scala.html)
### [Chapter 1: Hands-on Scala](https://www.handsonscala.com/chapter-1-hands-on-scala.html)
### [Chapter 2: Setting Up](https://www.handsonscala.com/chapter-2-setting-up.html)
### [Chapter 3: Basic Scala](https://www.handsonscala.com/chapter-3-basic-scala.html)
### [Chapter 4: Scala Collections](https://www.handsonscala.com/chapter-4-scala-collections.html)
### [Chapter 5: Notable Scala Features](https://www.handsonscala.com/chapter-5-notable-scala-features.html)
## [Part II Local Development](https://www.handsonscala.com/part-ii-local-development-preview.html)
### [Chapter 6: Implementing Algorithms in Scala](https://www.handsonscala.com/part-ii-local-development-preview.html#chapter-6-implementing-algorithms-in-scala)
- [6.1 - MergeSort](https://github.com/handsonscala/handsonscala/tree/master/examples/6.1%20-%20MergeSort): Simple merge-sort implemention, hard-coded to only work on `Array[Int]`
- [6.2 - GenericMergeSort](https://github.com/handsonscala/handsonscala/tree/master/examples/6.2%20-%20GenericMergeSort): Generic merge sort implemention, that can sort any `IndexedSeq[T]` with an `Ordering`
- [6.3 - Trie](https://github.com/handsonscala/handsonscala/tree/master/examples/6.3%20-%20Trie): A simple mutable Trie implemention
- [6.4 - Search](https://github.com/handsonscala/handsonscala/tree/master/examples/6.4%20-%20Search): Breadth-first-search implemention
- [6.5 - SearchPaths](https://github.com/handsonscala/handsonscala/tree/master/examples/6.5%20-%20SearchPaths): Breadth-first-search implemention that keeps track of the shortest paths to every node
- [6.6 - BinarySearch](https://github.com/handsonscala/handsonscala/tree/master/examples/6.6%20-%20BinarySearch): Binary search implementation
- [6.7 - ImmutableTrie](https://github.com/handsonscala/handsonscala/tree/master/examples/6.7%20-%20ImmutableTrie): Immutable trie implementation
- [6.8 - DepthSearchPaths](https://github.com/handsonscala/handsonscala/tree/master/examples/6.8%20-%20DepthSearchPaths): Depth-first search implementation that keeps track of shortest paths
### [Chapter 7: Files and Subprocesses](https://www.handsonscala.com/part-ii-local-development-preview.html#chapter-7-files-and-subprocesses)
- [7.1 - LargestFiles](https://github.com/handsonscala/handsonscala/tree/master/examples/7.1%20-%20LargestFiles): Script to finds the largest 5 files in the current folder tree
- [7.2 - FileSync](https://github.com/handsonscala/handsonscala/tree/master/examples/7.2%20-%20FileSync): Method to batch synchronize files between two local folders
- [7.3 - RemoveBranches](https://github.com/handsonscala/handsonscala/tree/master/examples/7.3%20-%20RemoveBranches): Script to remove all non-active branches from the local Git repository
- [7.4 - InteractivePython](https://github.com/handsonscala/handsonscala/tree/master/examples/7.4%20-%20InteractivePython): Example of how to interact with a running Python process from Scala
- [7.5 - StreamingDownloadProcessReupload1](https://github.com/handsonscala/handsonscala/tree/master/examples/7.5%20-%20StreamingDownloadProcessReupload1): Three-stage streaming subprocess pipeline
- [7.6 - StreamingDownloadProcessReupload2](https://github.com/handsonscala/handsonscala/tree/master/examples/7.6%20-%20StreamingDownloadProcessReupload2): Four-stage streaming subprocess pipeline
- [7.7 - FileSyncDelete](https://github.com/handsonscala/handsonscala/tree/master/examples/7.7%20-%20FileSyncDelete): Method to synchronize files between two folders, with support for deletion
- [7.8 - StreamingDownloadProcessReuploadTee](https://github.com/handsonscala/handsonscala/tree/master/examples/7.8%20-%20StreamingDownloadProcessReuploadTee): Five stage subprocess pipeline, `tee`d streaming data to a file
### [Chapter 8: JSON and Binary Data Serialization](https://www.handsonscala.com/part-ii-local-development-preview.html#chapter-8-json-and-binary-data-serialization)
- [8.1 - Create](https://github.com/handsonscala/handsonscala/tree/master/examples/8.1%20-%20Create): Parsing JSON structures from strings and constructing it directly
- [8.2 - Manipulate](https://github.com/handsonscala/handsonscala/tree/master/examples/8.2%20-%20Manipulate): Querying and modifying JSON structures in-memory
- [8.3 - Traverse](https://github.com/handsonscala/handsonscala/tree/master/examples/8.3%20-%20Traverse): Recursively traversing a JSON structure
- [8.4 - SerializationBuiltins](https://github.com/handsonscala/handsonscala/tree/master/examples/8.4%20-%20SerializationBuiltins): Serializing built-in Scala data types to JSON
- [8.5 - SerializationCaseClass](https://github.com/handsonscala/handsonscala/tree/master/examples/8.5%20-%20SerializationCaseClass): Serializing Scala case classes to JSON
- [8.6 - SerializationBinary](https://github.com/handsonscala/handsonscala/tree/master/examples/8.6%20-%20SerializationBinary): Serializing Scala data types to binary MessagePack blobs
- [8.7 - BiMapClass](https://github.com/handsonscala/handsonscala/tree/master/examples/8.7%20-%20BiMapClass): Using `bimap` to make a non-case class serializable
### [Chapter 9: Self-Contained Scala Scripts](https://www.handsonscala.com/part-ii-local-development-preview.html#chapter-9-self-contained-scala-scripts)
- [9.1 - Printing](https://github.com/handsonscala/handsonscala/tree/master/examples/9.1%20-%20Printing): Listing blog-post-like files in a folder and printing them out
- [9.2 - Index](https://github.com/handsonscala/handsonscala/tree/master/examples/9.2%20-%20Index): Rendering an `index.html` for our static blog using Scalatags
- [9.3 - Markdown](https://github.com/handsonscala/handsonscala/tree/master/examples/9.3%20-%20Markdown): Rendering individual blog posts using Atlassian's Commonmark-Java library
- [9.4 - Links](https://github.com/handsonscala/handsonscala/tree/master/examples/9.4%20-%20Links): Adding links between our `index.html` and the individual blog posts
- [9.5 - Bootstrap](https://github.com/handsonscala/handsonscala/tree/master/examples/9.5%20-%20Bootstrap): Prettifying our static blog using the Bootstrap CSS framework
- [9.6 - Deploy](https://github.com/handsonscala/handsonscala/tree/master/examples/9.6%20-%20Deploy): Optionally deploying our static blog to a Git repository
- [9.7 - DeployTimestamp](https://github.com/handsonscala/handsonscala/tree/master/examples/9.7%20-%20DeployTimestamp): Displaying the `.md` file last-modified time on each blog post
### [Chapter 10: Static Build Pipelines](https://www.handsonscala.com/part-ii-local-development-preview.html#chapter-10-static-build-pipelines)
- [10.1 - Simple](https://github.com/handsonscala/handsonscala/tree/master/examples/10.1%20-%20Simple): Simple linear build pipeline
- [10.2 - Nonlinear](https://github.com/handsonscala/handsonscala/tree/master/examples/10.2%20-%20Nonlinear): Simple non-linear build pipeline with two branches
- [10.3 - Modules](https://github.com/handsonscala/handsonscala/tree/master/examples/10.3%20-%20Modules): Simple non-linear build pipeline, replicated in several modules
- [10.4 - NestedModules](https://github.com/handsonscala/handsonscala/tree/master/examples/10.4%20-%20NestedModules): Nested modules in a Mill build pipeline
- [10.5 - CrossModules](https://github.com/handsonscala/handsonscala/tree/master/examples/10.5%20-%20CrossModules): Using cross-modules to dynamically construct a build graph based on the filesystem
- [10.6 - Blog](https://github.com/handsonscala/handsonscala/tree/master/examples/10.6%20-%20Blog): Our static blog generator, converted into an incremental Mill build pipeline
- [10.7 - ExtendedBlog](https://github.com/handsonscala/handsonscala/tree/master/examples/10.7%20-%20ExtendedBlog): Adding previews and bundled Bootstrap CSS to our static blog build pipeline
- [10.8 - Push](https://github.com/handsonscala/handsonscala/tree/master/examples/10.8%20-%20Push): Re-adding the ability to deploy our static blog by defining a `T.command`
## [Part III Web Services](https://www.handsonscala.com/part-iii-web-services-preview.html)
### [Chapter 11: Scraping Websites](https://www.handsonscala.com/part-iii-web-services-preview.html#chapter-11-scraping-websites)
- [11.1 - ScrapingWiki](https://github.com/handsonscala/handsonscala/tree/master/examples/11.1%20-%20ScrapingWiki): Scraping headlines off the Wikipedia front page using Jsoup
- [11.2 - ScrapingDocs](https://github.com/handsonscala/handsonscala/tree/master/examples/11.2%20-%20ScrapingDocs): Scraping semi-structured content off of the Mozilla Development Network Web API docs
- [11.3 - ApiStatus](https://github.com/handsonscala/handsonscala/tree/master/examples/11.3%20-%20ApiStatus): Using Jsoup to scrape the status annotations for every Web API on MDN
- [11.4 - ExternalLinks](https://github.com/handsonscala/handsonscala/tree/master/examples/11.4%20-%20ExternalLinks): Crawling the pages of a static website to extract every external link on the site
### [Chapter 12: Working with HTTP APIs](https://www.handsonscala.com/part-iii-web-services-preview.html#chapter-12-working-with-http-apis)
- [12.1 - IssueMigrator](https://github.com/handsonscala/handsonscala/tree/master/examples/12.1%20-%20IssueMigrator): Simple Github issue migrator
- [12.2 - IssueMigratorLink](https://github.com/handsonscala/handsonscala/tree/master/examples/12.2%20-%20IssueMigratorLink): Github issue migrator that adds a link back from every new issue to the original issue
- [12.3 - IssueMigratorClosed](https://github.com/handsonscala/handsonscala/tree/master/examples/12.3%20-%20IssueMigratorClosed): Github issue migrator that also preserves issue open/closed status during the migration
### [Chapter 13: Fork-Join Parallelism with Futures](https://www.handsonscala.com/part-iii-web-services-preview.html#chapter-13-fork-join-parallelism-with-futures)
- [13.1 - Hashing](https://github.com/handsonscala/handsonscala/tree/master/examples/13.1%20-%20Hashing): Hashing files in parallel using Futures
- [13.2 - Crawler](https://github.com/handsonscala/handsonscala/tree/master/examples/13.2%20-%20Crawler): Simple sequential wikipedia crawler
- [13.3 - ParallelCrawler](https://github.com/handsonscala/handsonscala/tree/master/examples/13.3%20-%20ParallelCrawler): Simple batch-by-batch parallel wikipedia crawler, using Futures and Requests-Scala
- [13.4 - RecursiveCrawler](https://github.com/handsonscala/handsonscala/tree/master/examples/13.4%20-%20RecursiveCrawler): Parallel wikipedia crawler written in a recursive fashion
- [13.5 - AsyncCrawler](https://github.com/handsonscala/handsonscala/tree/master/examples/13.5%20-%20AsyncCrawler): Asynchronous parallel wikipedia crawler, using the Java AsyncHttpClient
- [13.6 - ParallelScrapingDocs](https://github.com/handsonscala/handsonscala/tree/master/examples/13.6%20-%20ParallelScrapingDocs): Scraping MDN Web API documentation pages in parallel using Futures
- [13.7 - ParallelMergeSort](https://github.com/handsonscala/handsonscala/tree/master/examples/13.7%20-%20ParallelMergeSort): Merge-sort implementation parallelized using Futures
- [13.8 - AsyncCrawlerThrottled](https://github.com/handsonscala/handsonscala/tree/master/examples/13.8%20-%20AsyncCrawlerThrottled): Asynchronous wikipedia crawler which limits the number of open requests
- [13.9 - AsyncThottledScrapingDocs](https://github.com/handsonscala/handsonscala/tree/master/examples/13.9%20-%20AsyncThottledScrapingDocs): Asynchronous parallel MDN scraper that limits the number of open requests
### [Chapter 14: Simple Web and API Servers](https://www.handsonscala.com/part-iii-web-services-preview.html#chapter-14-simple-web-and-api-servers)
- [14.1 - Mock](https://github.com/handsonscala/handsonscala/tree/master/examples/14.1%20-%20Mock): Dummy non-interactive HTML chat website and server
- [14.2 - Forms](https://github.com/handsonscala/handsonscala/tree/master/examples/14.2%20-%20Forms): Form-based interactive chat website
- [14.3 - Ajax](https://github.com/handsonscala/handsonscala/tree/master/examples/14.3%20-%20Ajax): Ajax-based interactive chat website
- [14.4 - Websockets](https://github.com/handsonscala/handsonscala/tree/master/examples/14.4%20-%20Websockets): Websocket-based real-time chat website
- [14.5 - WebsocketsFilter](https://github.com/handsonscala/handsonscala/tree/master/examples/14.5%20-%20WebsocketsFilter): Websocket-based chat website with ability to filter chats
- [14.6 - WebsocketsSynchronized](https://github.com/handsonscala/handsonscala/tree/master/examples/14.6%20-%20WebsocketsSynchronized): Websocket-based chat website with shared mutable state properly synchronized
- [14.7 - WebsocketsJsoup](https://github.com/handsonscala/handsonscala/tree/master/examples/14.7%20-%20WebsocketsJsoup): Websocket-based chat website with HTML validation tests using Jsoup
### [Chapter 15: Querying SQL Databases](https://www.handsonscala.com/part-iii-web-services-preview.html#chapter-15-querying-sql-databases)
- [15.1 - Queries](https://github.com/handsonscala/handsonscala/tree/master/examples/15.1%20-%20Queries): Simple Quill database queries
- [15.2 - Website](https://github.com/handsonscala/handsonscala/tree/master/examples/15.2%20-%20Website): Database-backed websocket chat website
- [15.3 - FancyQueries](https://github.com/handsonscala/handsonscala/tree/master/examples/15.3%20-%20FancyQueries): Fancier Quill database queries with `groupBy` and `sortBy`
- [15.4 - WebsiteTimestamps](https://github.com/handsonscala/handsonscala/tree/master/examples/15.4%20-%20WebsiteTimestamps): Database-backed websocket chat website with timestamps on every chat message
## [Part IV Program Design](https://www.handsonscala.com/part-iv-program-design-preview.html)
### [Chapter 16: Message-based Parallelism with Actors](https://www.handsonscala.com/part-iv-program-design-preview.html#chapter-16-message-based-parallelism-with-actors)
- [16.1 - Simple](https://github.com/handsonscala/handsonscala/tree/master/examples/16.1%20-%20Simple): Simple logging actor that asynchronously uploads log messages to httpbin.org servers
- [16.2 - Batch](https://github.com/handsonscala/handsonscala/tree/master/examples/16.2%20-%20Batch): Batch logging actor that uploads batches of log messages to httpbin.org servers
- [16.3 - StateMachine](https://github.com/handsonscala/handsonscala/tree/master/examples/16.3%20-%20StateMachine): Actor that uploads batches of logs to httpbin.org, with a minimum interval between each batch
- [16.4 - LoggingSimple](https://github.com/handsonscala/handsonscala/tree/master/examples/16.4%20-%20LoggingSimple): Logging actor that asynchronously logs messages to disk
- [16.5 - LoggingPipeline](https://github.com/handsonscala/handsonscala/tree/master/examples/16.5%20-%20LoggingPipeline): Two-stage logging actor pipeline that asynchronously logs base64-encoded messages to disk
- [16.6 - LoggingLongPipeline](https://github.com/handsonscala/handsonscala/tree/master/examples/16.6%20-%20LoggingLongPipeline): Four-actor pipeline that logs sanitized, base64-encoded messages both to disk and to `httpbin.org`
- [16.7 - LoggingRearrangedPipeline1](https://github.com/handsonscala/handsonscala/tree/master/examples/16.7%20-%20LoggingRearrangedPipeline1): Three-actor logging pipeline without sanitization
- [16.8 - LoggingRearrangedPipeline2](https://github.com/handsonscala/handsonscala/tree/master/examples/16.8%20-%20LoggingRearrangedPipeline2): Four-actor pipeline, with only disk logs base64-encoded and only `httpbin.org` uploads sanitized
- [16.9 - WebCrawler](https://github.com/handsonscala/handsonscala/tree/master/examples/16.9%20-%20WebCrawler): A concurrent actor-based web crawler that avoids the limitations of earlier batch-by-batch crawlers
- [16.10 - WebCrawlerPipeline](https://github.com/handsonscala/handsonscala/tree/master/examples/16.10%20-%20WebCrawlerPipeline): A concurrent actor-based web crawler that streams the crawled pages to disk
- [16.11 - WebCrawlerThrottled](https://github.com/handsonscala/handsonscala/tree/master/examples/16.11%20-%20WebCrawlerThrottled): A concurrent actor-based web crawler that limits the number of open connections
### [Chapter 17: Multi-Process Applications](https://www.handsonscala.com/part-iv-program-design-preview.html#chapter-17-multi-process-applications)
- [17.1 - FileSyncer](https://github.com/handsonscala/handsonscala/tree/master/examples/17.1%20-%20FileSyncer): Simple two-process batch file synchronizer that could work over a network
- [17.2 - Pipelined](https://github.com/handsonscala/handsonscala/tree/master/examples/17.2%20-%20Pipelined): Pipelined version of our two-process file synchronizer, minimizing the chattiness of the protocol
- [17.3 - Deletes](https://github.com/handsonscala/handsonscala/tree/master/examples/17.3%20-%20Deletes): Pipelined two-process file synchronizer that supports deletions
### [Chapter 18: Building a Real-time File Synchronizer](https://www.handsonscala.com/part-iv-program-design-preview.html#chapter-18-building-a-real-time-file-synchronizer)
- [18.1 - Simple](https://github.com/handsonscala/handsonscala/tree/master/examples/18.1%20-%20Simple): Simple real-time file synchronizer that uses `os.watch` to react to filesystem changes as they happen
- [18.2 - Pipelined](https://github.com/handsonscala/handsonscala/tree/master/examples/18.2%20-%20Pipelined): Pipelined real-time file synchronizer, allowing RPCs and hashing to take place in parallel
- [18.3 - InitialFiles](https://github.com/handsonscala/handsonscala/tree/master/examples/18.3%20-%20InitialFiles): Real-time file synchronizer that supports syncing an initial set of files
- [18.4 - ForkJoinHashing](https://github.com/handsonscala/handsonscala/tree/master/examples/18.4%20-%20ForkJoinHashing): Real-time file synchronizer that does hashing of files in parallel
### [Chapter 19: Parsing Structured Text](https://www.handsonscala.com/part-iv-program-design-preview.html#chapter-19-parsing-structured-text)
- [19.1 - Phrases](https://github.com/handsonscala/handsonscala/tree/master/examples/19.1%20-%20Phrases): Parser for simple "hello world"-like phrases
- [19.2 - Arithmetic](https://github.com/handsonscala/handsonscala/tree/master/examples/19.2%20-%20Arithmetic): Parser and evaluator for simple english-like arithmetic expressions
- [19.3 - ArithmeticChained](https://github.com/handsonscala/handsonscala/tree/master/examples/19.3%20-%20ArithmeticChained): English-like arithmetic parser, allowing more than one binary operator to be chained together
- [19.4 - ArithmeticPrecedence](https://github.com/handsonscala/handsonscala/tree/master/examples/19.4%20-%20ArithmeticPrecedence): English-like arithmetic parser, supporting operator precedence of chained binary operators
- [19.5 - ArithmeticDirect](https://github.com/handsonscala/handsonscala/tree/master/examples/19.5%20-%20ArithmeticDirect): English-like arithmetic parser that evaluates the arithmetic without constructing a syntax tree
### [Chapter 20: Implementing a Programming Language](https://www.handsonscala.com/part-iv-program-design-preview.html#chapter-20-implementing-a-programming-language)
- [20.1 - Jsonnet](https://github.com/handsonscala/handsonscala/tree/master/examples/20.1%20-%20Jsonnet): Interpreter for a minimal subset of the Jsonnet programming language
- [20.2 - JsonnetNumbers](https://github.com/handsonscala/handsonscala/tree/master/examples/20.2%20-%20JsonnetNumbers): Jsonnet interpreter with added support for simple integer arithmetic
- [20.3 - JsonnetPrettyPrinting](https://github.com/handsonscala/handsonscala/tree/master/examples/20.3%20-%20JsonnetPrettyPrinting): Jsonnet interpreter using the uJson library for pretty-printing the output JSON