# Reading-list

Interesting articles and reading material about day to day stuff. Rust, Distributed Systems, Obeservabiliy, Systems programming and such

## Main list

### System Design / Distributed Systems

#### Books
- [Designing Data-Intensive Applications](https://github.com/ms2ag16/Books/blob/master/Designing%20Data-Intensive%20Applications%20-%20Martin%20Kleppmann.pdf)

- [Patterns of Distributed Systems](https://martinfowler.com/articles/patterns-of-distributed-systems/)

#### Articles

- [Metastable failures in distributed systems](https://dl.acm.org/doi/abs/10.1145/3458336.3465286)

- [Distributed Systems Shibboleths](https://jolynch.github.io/posts/distsys_shibboleths/)

- [The Perils of Good Abstractions](https://web.archive.org/web/20181006111158/http://www.addsimplicity.com/adding_simplicity_an_engi/2006/12/the_perils_of_g.html)

- [Building on Quicksand](https://arxiv.org/ftp/arxiv/papers/0909/0909.1788.pdf)

- [Your Server as a Function](https://monkey.org/~marius/funsrv.pdf)

- [CAP theorem](https://www.ibm.com/topics/cap-theorem)

- [Eventually Consistent](https://www.allthingsdistributed.com/2007/12/eventually_consistent.html)

- [Fallacies of Distributed Computing Explained](https://www.researchgate.net/publication/322500050_Fallacies_of_Distributed_Computing_Explained)

- [Failure modes in distributed systems](https://alvaro-videla.com/2013/12/failure-modes-in-distributed-systems.html)

- [The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)

- [Redis streams as a pure data structure](http://antirez.com/news/128)

- [The C10K problem](http://www.kegel.com/c10k.html)

- [Rust Crossbeam Learning Resources](https://github.com/crossbeam-rs/rfcs/wiki)

### Resources And Lists

- [The Amazon Builders' Library](https://aws.amazon.com/builders-library/?cards-body.sort-by=item.additionalFields.sortDate&cards-body.sort-order=desc&awsf.filter-content-category=*all&awsf.filter-content-type=*all&awsf.filter-content-level=*all)

- [An Introduction to Distributed Systems](https://github.com/aphyr/distsys-class)

- [Grokking Modern System Design Interview for Engineers & Managers](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers/7AVkpYmjlrG)


### Rust

#### Books

(For the ones who are paid, i own (legit) copies of those books, ask me for more info)

- [The Rust Programming Language](https://doc.rust-lang.org/book/#the-rust-programming-language)
- [Rust for Rustaceans](https://nostarch.com/rust-rustaceans)
- [Zero To Production In Rust](https://www.zero2prod.com/index.html?country=Brazil&discount_code=SA60)
- [Black Hat Rust](https://kerkour.com/black-hat-rust)
- [The Rustonomicon](https://doc.rust-lang.org/nomicon/#the-rustonomicon)

#### Articles

- [Understanding Rust futures by going way too deep](https://fasterthanli.me/articles/understanding-rust-futures-by-going-way-too-deep)
- [Pin and Suffering](https://fasterthanli.me/articles/pin-and-suffering)
- [Frustrated? It's not you, it's Rust ](https://fasterthanli.me/articles/frustrated-its-not-you-its-rust)
- [I am a Java, C#, C or C++ developer, time to do some Rust](https://fasterthanli.me/articles/i-am-a-java-csharp-c-or-cplusplus-dev-time-to-do-some-rust)
- [My ideal Rust workflow](https://fasterthanli.me/articles/my-ideal-rust-workflow)
- [Comparing parallel Rust and C++](https://parallel-rust-cpp.github.io/)
- [Pretty State Machine Patterns in Rust ](https://hoverbear.org/blog/rust-state-machine-pattern/)

#### Videos

- [Crust of Rust series](https://www.youtube.com/playlist?app=desktop&list=PLqbS7AVVErFiWDOAVrPt7aYmnuuOLYvOa)



### Other

[The Grug Brained Developer: A layman's guide to thinking like the self-aware smol brained](https://grugbrain.dev/)

## Expected reading for plataform team/services workgroup interns

Pick something from this list if you have free time during work for some reason. Its not expected that you read stuff in your own time (unless you really want to).

### Rust

- [The Rust Programming Language](https://doc.rust-lang.org/book/)
  - Its not expected that you read the entire book in one sitting, but try reading some chapters every once in a while
- [A Half Hour to Learn Rust](https://fasterthanli.me/articles/a-half-hour-to-learn-rust)

### Redis

- [Redis Data Types](https://redis.io/docs/manual/data-types/)
  - [Redis Data Types Tutorial](https://redis.io/docs/manual/data-types/data-types-tutorial/)
  - [Redis Streams](https://redis.io/docs/manual/data-types/streams/)

### Functional Programming/Domain Modeling/Testing/Etc

- [Boundaries](https://www.destroyallsoftware.com/talks/boundaries)
- [Designing with types](https://fsharpforfunandprofit.com/series/designing-with-types/)
- [Functional Programming Design Patterns](https://fsharpforfunandprofit.com/fppatterns/)

### Distributed Systems

- [Distributed Systems Shibboleths](https://jolynch.github.io/posts/distsys_shibboleths/)

### Observability, Monitoring, Operations

- [Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/)

  - [Principles](https://sre.google/sre-book/part-II-principles/)
    - [Embracing Risk](https://sre.google/sre-book/embracing-risk/)
    - [Service Level Objectives](https://sre.google/sre-book/service-level-objectives/)
    - [Monitoring Distributed Systems](https://sre.google/sre-book/monitoring-distributed-systems/)
  - [Practical Alerting from Time-Series Data](https://sre.google/sre-book/practical-alerting/)
  - [Postmortem Culture: Learning from Failure](https://sre.google/sre-book/postmortem-culture/)

- [Monitoring in the time of Cloud Native](https://copyconstruct.medium.com/monitoring-in-the-time-of-cloud-native-c87c7a5bfa3e)
- [Prometheus](https://prometheus.io/docs/introduction)
  - [Data Model](https://prometheus.io/docs/concepts/data_model/)
  - [Metric Types](https://prometheus.io/docs/concepts/metric_types/)
  - [Metric Naming](https://prometheus.io/docs/practices/naming/)
  - [Instrumentation](https://prometheus.io/docs/practices/instrumentation/)

### Other

- [Writing system software: code comments](http://antirez.com/news/124)
- [The Law of Leaky Abstractions](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/)
