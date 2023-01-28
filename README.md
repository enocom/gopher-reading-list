# Gopher Reading List [![Build](https://github.com/enocom/gopher-reading-list/workflows/CI/badge.svg)](https://github.com/enocom/gopher-reading-list/actions?query=workflow%3ACI+branch%3Amain+)

[中文版](https://github.com/qichengzx/gopher-reading-list-zh_CN)

Here is a reading list of blog posts about [Go](https://golang.org). It aspires
to include only the most useful and relevant material that anyone writing Go
should eventually read. By definition, the list is a work in progress.

Rather than being comprehensive, the list is a curated selection fixed at 200
entries.

Go is growing fast and so are the number of blog posts about it. If an
interested reader knows of a great post not on this list, please open an issue
with a link to the post. Not every blog post linked in an issue will make its way
into the list. Nonetheless, the [issue list](https://github.com/enocom/gopher-reading-list/issues)
(both open and closed) is a good source of additional reading material.

**NOTE:** Any new additions will need to replace
something else on the list to keep it at a fixed length.

## Start Here

- [Why should you learn Go?](https://medium.com/@kevalpatel2106/why-should-you-learn-go-f607681fad65)
- [An Intro to Go for non-Go developers](https://benhoyt.com/writings/go-intro/)
- [How to Write Go Code](https://golang.org/doc/code.html)
- [A Tour of Go](https://tour.golang.org/welcome/1)
- [Frequently Asked Questions](https://golang.org/doc/faq)
- [Go by Example](https://gobyexample.com/)
- [Go 101](https://go101.org/article/101.html)

See [Go Books](https://github.com/dariubs/GoBooks) for a list of books, both free and paid.

## Beginner

### Some basics

- [Understand Go pointers in less than 800 words or your money back](https://dave.cheney.net/2017/04/26/understand-go-pointers-in-less-than-800-words-or-your-money-back)
- [Don't fear the pointer](https://bitfieldconsulting.com/golang/pointers)
- [Channel Axioms](https://dave.cheney.net/2014/03/19/channel-axioms)
- [Golang channels tutorial](https://guzalexander.com/2013/12/06/golang-channels-tutorial.html)
- [Common Gotchas in Go](https://divan.dev/posts/avoid_gotchas/)
- [50 Shades of Go: Traps, Gotchas, and Common Mistakes for New Golang Devs](https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/)
- [Slices from the ground up](https://dave.cheney.net/2018/07/12/slices-from-the-ground-up)
- [6 Tips for Using Strings in Go](https://www.calhoun.io/6-tips-for-using-strings-in-go/)
- [Go Defer Simplified with Practical Visuals](https://blog.learngoprogramming.com/golang-defer-simplified-77d3b2b817ff)
- [How to Use Go Interfaces](https://blog.chewxy.com/2018/03/18/golang-interfaces/)
- [Different Ways to Initialize Go structs](https://asankov.dev/blog/2022/01/29/different-ways-to-initialize-go-structs/)

### Worth reading, again and again

- [Effective Go](https://golang.org/doc/effective_go.html)
- [Visualizing Concurrency in Go](https://divan.github.io/posts/go_concurrency_visualize/)
- [Strings, bytes, runes and characters in Go](https://blog.golang.org/strings)
- [Arrays, slices (and strings): The mechanics of 'append'](https://blog.golang.org/slices)

### Organization and Style

- [Practical Go: Real world advice for writing maintainable Go programs](https://dave.cheney.net/practical-go/presentations/qcon-china.html)
- [Less is exponentially more](https://commandcenter.blogspot.com.br/2012/06/less-is-exponentially-more.html)
- [Go Proverbs](https://go-proverbs.github.io/)
- [Code Review Comments](https://github.com/golang/go/wiki/CodeReviewComments)
- [Idiomatic Go](https://dmitri.shuralyov.com/idiomatic-go)
- [Error handling and Go](https://blog.golang.org/error-handling-and-go)
- [Go's Error Handling is Elegant](https://davidnix.io/posts/error-handling-in-go/)
- [Working with Errors in Go 1.13](https://blog.golang.org/go1.13-errors)
- [Simple Go project layout with modules](https://eli.thegreenplace.net/2019/simple-go-project-layout-with-modules/)
- [Structuring Tests in Go](https://medium.com/@benbjohnson/structuring-tests-in-go-46ddee7a25c)
- [Standard Package Layout](https://medium.com/@benbjohnson/standard-package-layout-7cdbc8391fc1)
- [Packages as layers, not groups](https://www.gobeyond.dev/packages-as-layers/)
- [Structuring Applications in Go](https://medium.com/@benbjohnson/structuring-applications-in-go-3b04be4ff091)
- [Style guideline for Go packages](https://rakyll.org/style-packages/)
- [Package names](https://blog.golang.org/package-names)
- [What's in a name (slides)](https://talks.golang.org/2014/names.slide#1)

### Web

- [Creating My First Web Application with Go](https://www.rosie.dev/post/building-a-web-app-with-go/)
- [Making a RESTful JSON API in Go](https://thenewstack.io/make-a-restful-json-api-go/)
- [Serving static files and web apps in Go](https://eli.thegreenplace.net/2022/serving-static-files-and-web-apps-in-go/)
- [An Intro To Templates in Go](https://www.calhoun.io/an-intro-to-templates-in-go-part-1-of-3/)
- [JSON APIs Are Just Web Applications](https://www.calhoun.io/apis-are-just-web-applications/)
- [Writing middleware in #golang and how Go makes it so much fun](https://medium.com/@matryer/writing-middleware-in-golang-and-how-go-makes-it-so-much-fun-4375c1246e81)
- [Go and JSON](https://eager.io/blog/go-and-json/)
- [Accessing data in Go](https://husio.github.io/blog/accessing-data-in-go/)
- [How to Use //go:embed](https://blog.carlmjohnson.net/post/2021/how-to-use-go-embed/)

### Concurrency

- [Learning Go's Concurrency Through Illustrations](https://medium.com/@trevor4e/learning-gos-concurrency-through-illustrations-8c4aff603b3)
- [Go’s append is not always thread safe](https://medium.com/@cep21/gos-append-is-not-always-thread-safe-a3034db7975)

### Go Modules

- [Introduction to Go modules](https://roberto.selbach.ca/intro-to-go-modules/)
- [Using Go Modules](https://blog.golang.org/using-go-modules)
- [Modules Part 01: Why And What](https://www.ardanlabs.com/blog/2019/10/modules-01-why-and-what.html)

## Intermediate

### Code Design

- [Go best practices, six years in](https://peter.bourgon.org/go-best-practices-2016/)
- [Aspects of a good Go library](https://medium.com/@cep21/aspects-of-a-good-go-library-7082beabb403)
- [Solid Go Design](https://dave.cheney.net/2016/08/20/solid-go-design)
- [Go for Industrial Programming](https://peter.bourgon.org/go-for-industrial-programming/)
- [Why you shouldn't use func main in Go](https://pace.dev/blog/2020/02/12/why-you-shouldnt-use-func-main-in-golang-by-mat-ryer.html)
- [Failure is your Domain](https://middlemost.com/failure-is-your-domain/)
- [What “accept interfaces, return structs” means in Go](https://medium.com/@cep21/what-accept-interfaces-return-structs-means-in-go-2fe879e25ee8)
- [Pitfalls of context values and how to avoid or mitigate them in Go](https://www.calhoun.io/pitfalls-of-context-values-and-how-to-avoid-or-mitigate-them/)
- [How to organize the go struct, in order to save memory](https://medium.com/@felipedutratine/how-to-organize-the-go-struct-in-order-to-save-memory-c78afcf59ec2)
- [Loose Coupling in Go lang](https://8thlight.com/blog/javier-saldana/2015/02/06/loose-coupling-in-go-lang.html)
- [Self-referential functions and the design of options](https://commandcenter.blogspot.co.nz/2014/01/self-referential-functions-and-design.html)
- [Functional Options for Friendly APIs](https://dave.cheney.net/2014/10/17/functional-options-for-friendly-apis)
- [Functional Options on Steroids](https://sagikazarmark.hu/blog/functional-options-on-steroids/)
- [Object Oriented Inheritance in Go](https://hackthology.com/object-oriented-inheritance-in-go.html)
- [Error handling in Upspin](https://commandcenter.blogspot.com/2017/12/error-handling-in-upspin.html)
- [Passing Loggers in Go: Golang Logging Best Practices](https://gogoapps.io/blog/passing-loggers-in-go-golang-logging-best-practices/)

### Concurrency

- [Concurrency Patterns](https://medium.com/@thejasbabu/concurrency-patterns-golang-5c5e1bcd0833)
- [Stopping goroutines](https://medium.com/@matryer/stopping-goroutines-golang-1bf28799c1cb)
- [Make Ctrl+C cancel the context.Context](https://medium.com/@matryer/make-ctrl-c-cancel-the-context-context-bd006a8ad6ff)
- [How to correctly use context.Context in Go 1.7](https://medium.com/@cep21/how-to-correctly-use-context-context-in-go-1-7-8f2c0fafdf39#.bdz5qnna7)
- [Using contexts to avoid leaking goroutines](https://rakyll.org/leakingctx/)
- [Go Concurrency Patterns: Pipelines and cancellation](https://blog.golang.org/pipelines)
- [Tutorial: Synchronizing State with Mutexes in Go](https://kylewbanks.com/blog/tutorial-synchronizing-state-with-mutexes-golang)
- [Context and Cancellation of goroutines](https://dahernan.github.io/2015/02/04/context-and-cancellation-of-goroutines/)
- [Dancing with Go's Mutexes](https://hackernoon.com/dancing-with-go-s-mutexes-92407ae927bf)
- [GoRoutines, Channels, and Proper Exits](https://rabarar.github.io/blog/2015/02/17/goroutines-channels/)
- [How to Block Forever in Go](https://blog.sgmansfield.com/2016/06/how-to-block-forever-in-go/)
- [Mutex Profile](https://rakyll.org/mutexprofile/)
- [Sane Concurrency with Go](https://blog.mozilla.org/services/2014/03/12/sane-concurrency-with-go/)
- [Error handling patterns in Go](https://mijailovic.net/2017/05/09/error-handling-patterns-in-go/)
- [Does the race detector catch all data races?](https://medium.com/@val_deleplace/does-the-race-detector-catch-all-data-races-1afed51d57fb)
- [Interesting ways of using Go channels](http://nomad.uk.net/articles/interesting-ways-of-using-go-channels.html)
- [Code Review Checklist: Go concurrency](https://github.com/code-review-checklists/go-concurrency)
- [The Pros of Conds](https://lukechampine.com/cond.html)
- [Go concurrency guide](https://github.com/luk4z7/go-concurrency-guide)

### Testing

- [Testing Web Apps in Go](https://markjberger.com/testing-web-apps-in-golang/)
- [An Introduction to Testing in Go](https://tutorialedge.net/golang/intro-testing-in-go/)
- [5 simple tips and tricks for writing unit tests in #golang](https://medium.com/@matryer/5-simple-tips-and-tricks-for-writing-unit-tests-in-golang-619653f90742)
- [5 Advanced Testing Techniques in Go](https://segment.com/blog/5-advanced-testing-techniques-in-go/)
- [Interfaces and Composition for Effective Unit Testing in Golang](https://nathanleclaire.com/blog/2015/10/10/interfaces-and-composition-for-effective-unit-testing-in-golang/)
- [Go Testing Technique: Testing JSON HTTP Requests](https://medium.com/@xoen/go-testing-technique-testing-json-http-requests-76d9ce0e11f#.95p1r8n16)
- [Acceptance Testing Go Web Applications with Cookies](https://www.meetspaceapp.com/2016/05/16/acceptance-testing-go-webapps-with-cookies.html)
- [Testing Your (HTTP) Handlers in Go](https://blog.questionable.services/article/testing-http-handlers-go/)
- [Learn Go with tests](https://github.com/quii/learn-go-with-tests)
- [Lesser-Known Features of Go Test](https://splice.com/blog/lesser-known-features-go-test/)
- [When Writing Unit Tests, Don’t Use Mocks](https://sendgrid.com/blog/when-writing-unit-tests-dont-use-mocks/)
- [Property-based testing in Go](https://earthly.dev/blog/property-based-testing/)

### Web

- [Go for Cloud](https://rakyll.org/go-cloud/)
- [Exposing Go on the Internet](https://blog.gopheracademy.com/advent-2016/exposing-go-on-the-internet/)
- [The complete guide to Go net/http timeouts](https://blog.cloudflare.com/the-complete-guide-to-golang-net-http-timeouts/)
- [HTTP(S) Proxy in Golang in less than 100 lines of code](https://medium.com/@mlowicki/http-s-proxy-in-golang-in-less-than-100-lines-of-code-6a51c2f2c38c)
- [Write a Kubernetes-ready service from zero step-by-step](https://blog.gopheracademy.com/advent-2017/kubernetes-ready-service/)
- [A brief intro of TCP keep-alive in Go’s HTTP implementation](https://nanxiao.me/en/a-brief-intro-of-tcp-keep-alive-in-gos-http-implementation/)
- [Build a Web Crawler in Go](https://jackcanty.com/build-a-web-crawler-in-go.html)
- [Your pprof is showing: IPv4 scans reveal exposed net/http/pprof endpoints:](https://mmcloughlin.com/posts/your-pprof-is-showing)
- [HTTP Request Contexts & Go](https://blog.questionable.services/article/map-string-interface/)
- [Using Object-Oriented Web Servers in Go](https://blog.codeship.com/using-object-oriented-web-servers-go/)
- [Handle HTTP Request Errors in Go](https://pliutau.com/handle-http-request-errors-in-go/)
- [Don't use Go's default HTTP client (in production)](https://medium.com/@nate510/don-t-use-go-s-default-http-client-4804cb19f779)
- [Writing an API Client in Go](https://blog.gopheracademy.com/advent-2016/http-client/)
- [Seeking around in an HTTP object](https://blog.gopheracademy.com/advent-2017/seekable-http/)
- [Using Functions Inside Go Templates](https://www.calhoun.io/intro-to-templates-p3-functions/)
- [Writing a Data Mapper in Go without an ORM](https://www.meetspaceapp.com/2016/05/23/writing-a-data-mapper-in-go-without-an-orm.html)
- [Practical Persistence in Go: Organising Database Access](https://www.alexedwards.net/blog/organising-database-access)
- [How I write Go HTTP services after seven years](https://medium.com/statuscode/how-i-write-go-http-services-after-seven-years-37c208122831)
- [Make resilient Go net/http servers using timeouts, deadlines and context cancellation](https://ieftimov.com/post/make-resilient-golang-net-http-servers-using-timeouts-deadlines-context-cancellation/)
- [Life of an HTTP request in a Go server](https://eli.thegreenplace.net/2021/life-of-an-http-request-in-a-go-server/)
- [Gotchas in the Go Network Packages Defaults](https://martin.baillie.id/wrote/gotchas-in-the-go-network-packages-defaults/)
- [Graceful shutdown of a TCP server in Go](https://eli.thegreenplace.net/2020/graceful-shutdown-of-a-tcp-server-in-go/)
- [How to handle signals with Go to graceful shutdown HTTP server](https://rafallorenz.com/go/handle-signals-to-graceful-shutdown-http-server/)

### JSON

- [Go JSON Cookbook](https://eli.thegreenplace.net/2019/go-json-cookbook/)
- [Custom JSON Marshalling in Go](http://choly.ca/post/go-json-marshalling/)
- [Advanced Encoding and Decoding Techniques](https://blog.gopheracademy.com/advent-2016/advanced-encoding-decoding/)
- [Go json.Decoder Considered Harmful](https://ahmet.im/blog/golang-json-decoder-pitfalls/)

### Tools

- [An Overview of Go's Tooling](https://www.alexedwards.net/blog/an-overview-of-go-tooling)
- [Go tooling essentials](https://rakyll.org/go-tool-flags/)
- [Profiling Go Programs](https://blog.golang.org/profiling-go-programs)
- [Go Tooling in Action](https://medium.com/google-cloud/go-tooling-in-action-eca6882ff3bc#.d9ob4wyj4)
- [Statically compiling Go programs](https://www.arp242.net/static-go.html)
- [Tutorial: Getting started with fuzzing](https://go.dev/doc/tutorial/fuzz)
- [Go mod's lesser known features](https://verdverm.com/go-mods/)

### Trivia

- [10 things you (probably) don't know about Go](https://talks.golang.org/2012/10things.slide)
- [Advanced Go Tips And Tricks](https://scene-si.org/2016/06/13/advanced-go-tips-and-tricks/)
- [Golang slices gotcha](https://allegro.tech/2017/07/golang-slices-gotcha.html)

### Performance

- [Diagnostics](https://golang.org/doc/diagnostics.html)
- [Profiling Go](https://www.integralist.co.uk/posts/profiling-go/)
- [Five things that make Go fast](https://dave.cheney.net/2014/06/07/five-things-that-make-go-fast)
- [Debugging Go Applications using Delve](https://golangbot.com/debugging-go-delve/)
- [Easy memory-saving tricks in Go](https://github.com/enocom/gopher-reading-list/issues/203)

### Language

- [Golang: pass by pointer vs pass by value](https://goinbigdata.com/golang-pass-by-pointer-vs-pass-by-value/)
- [There is no pass-by-reference in Go](https://dave.cheney.net/2017/04/29/there-is-no-pass-by-reference-in-go)
- [Variadic functions in Go](https://medium.com/golangspec/variadic-functions-in-go-13c33182b851)
- [Function Types in Go (golang)](https://jordanorelli.com/post/42369331748/function-types-in-go-golang)
- [research!rsc: Go Data Structures](https://research.swtch.com/godata)
- [The Relationship Between Interfaces and Reflection](https://blog.gopheracademy.com/advent-2018/interfaces-and-reflect/)

### Generics

- [An Introduction to Generics](https://go.dev/blog/intro-generics)
- [When to Use Generics in Go?](https://teivah.medium.com/when-to-use-generics-in-go-36d49c1aeda)
- [Faster sorting with Go generics](https://github.com/enocom/gopher-reading-list/issues/195)

### Miscellaneous

- [Always Be Closing](https://medium.com/square-corner-blog/always-be-closing-3d5fda0e00da)
- [Don't defer Close() on writable files](https://joeshaw.org/dont-defer-close-on-writable-files/)
- [How to Use go:generate](https://blog.carlmjohnson.net/post/2016-11-27-how-to-use-go-generate/)
- [Writing worker queues, in Go](https://nesv.github.io/golang/2014/02/25/worker-queues-in-go.html)
- [Job Queues in Go - OpsDash](https://www.opsdash.com/blog/job-queues-in-go.html)
- [Reading files in Go](https://kgrz.io/reading-files-in-go-an-overview.html)
- [Vanity Go Import Paths](https://blog.bramp.net/post/2017/10/02/vanity-go-import-paths/)
- [Tags in Golang](https://medium.com/golangspec/tags-in-golang-3e5db0b8ef3e)
- [Handling Errors from Deferred Functions in Go](https://trstringer.com/golang-deferred-function-error-handling/)
- [Why Go modules are faster than GOPATH](https://dev.to/tbpalsulich/why-go-modules-are-faster-than-gopath-blj)

## Advanced

### Low Level Concerns

- [The Go Memory Model](https://go.dev/ref/mem)
- [Go's work-stealing scheduler](https://rakyll.org/scheduler/)
- [The Go scheduler](https://morsmachine.dk/go-scheduler)
- [Illustrated Tales of Go Runtime Scheduler](https://medium.com/@ankur_anand/illustrated-tales-of-go-runtime-scheduler-74809ef6d19b)
- [Go: Asynchronous Preemption](https://medium.com/a-journey-with-go/go-asynchronous-preemption-b5194227371c)
- [Go Assembly by Example](https://davidwong.fr/goasm/)
- [Address Alignments in Go](https://www.tapirgames.com/blog/golang-memory-alignment)
- [Hacking the Scheduler](https://github.com/golang/go/blob/master/src/runtime/HACKING.md)
- [Scheduling In Go - Part II](https://www.ardanlabs.com/blog/2018/08/scheduling-in-go-part2.html)
- [Anatomy of a function call in Go](https://syslog.ravelin.com/anatomy-of-a-function-call-in-go-f6fc81b80ecc)
- [Scheduler Tracing in Go](https://www.ardanlabs.com/blog/2015/02/scheduler-tracing-in-go.html)
- [unsafe.Pointer and system calls](https://blog.gopheracademy.com/advent-2017/unsafe-pointer-and-system-calls/)
- [Type-Unsafe Pointers](https://go101.org/article/unsafe.html)
- [Looking at your program’s structure in Go 1.7](https://pauladamsmith.com/blog/2016/08/go-1.7-ssa.html)
- [Managing Syscall Overhead with crypto/rand](https://blog.sgmansfield.com/2016/06/managing-syscall-overhead-with-crypto-rand/)
- [Optimized abs() for int64 in Go](http://cavaliercoder.com/blog/optimized-abs-for-int64-in-go.html)
- [Go: Introduction to the Escape Analysis](https://medium.com/a-journey-with-go/go-introduction-to-the-escape-analysis-f7610174e890)
- [Monkey Patching in Go](https://bou.ke/blog/monkey-patching-in-go/)
- [Interface method calls with the Go register ABI](https://eli.thegreenplace.net/2022/interface-method-calls-with-the-go-register-abi/)

### Performance

- [Allocation Efficiency in High-Performance Go Services](https://segment.com/blog/allocation-efficiency-in-high-performance-go-services/)
- [Handling 1 Million Requests per Minute with Go](http://marcio.io/2015/07/handling-1-million-requests-per-minute-with-golang/)
- [Go code refactoring : the 23x performance hunt](https://medium.com/@val_deleplace/go-code-refactoring-the-23x-performance-hunt-156746b522f7)
- [A Million WebSockets and Go](https://medium.freecodecamp.org/million-websockets-and-go-cc58418460bb)
- [go-perfbook](https://github.com/dgryski/go-perfbook)
- [Simple techniques to optimise Go programs](https://stephen.sh/posts/quick-go-performance-improvements)
- [High Performance Go Workshop](https://dave.cheney.net/high-performance-go-workshop/gophercon-2019.html)
- [Reducing Memory Allocations in Golang](https://chris124567.github.io/2021-06-21-go-performance/)

### Garbage Collection

- [A Guide to the Go Garbage Collector](https://go.dev/doc/gc-guide)
- [Getting to Go: The Journey of Go's Garbage Collector](https://go.dev/blog/ismmkeynote)
- [Avoiding high GC overhead with large heaps](https://blog.gopheracademy.com/advent-2018/avoid-gc-overhead-large-heaps/)
- [Golang's Real-time GC in Theory and Practice](https://making.pusher.com/golangs-real-time-gc-in-theory-and-practice/)
- [How to Optimize Garbage Collection in Go](https://www.cockroachlabs.com/blog/how-to-optimize-garbage-collection-in-go/)
- [Garbage Collection in Go](https://www.ardanlabs.com/blog/2018/12/garbage-collection-in-go-part1-semantics.html)

### Concurrency

- [Advanced Go Concurrency Patterns](https://blog.golang.org/advanced-go-concurrency-patterns)
- [The X-Files: Avoiding Concurrency Boilerplate with golang.org/x/sync](https://rodaine.com/2018/08/x-files-sync-golang/)
- [Golang lock-free values with atomic.Value](https://texlution.com/post/golang-lock-free-values-with-atomic-value/)
- [Go Concurrency Patterns: Context](https://blog.golang.org/context)
- [Go Concurrency Patterns: Timing out, moving on](https://blog.golang.org/go-concurrency-patterns-timing-out-and)
- [Concurrency, Goroutines and GOMAXPROCS](https://www.ardanlabs.com/blog/2014/01/concurrency-goroutines-and-gomaxprocs.html)
- [Data Race Patterns in Go](https://eng.uber.com/data-race-patterns-in-go/)
