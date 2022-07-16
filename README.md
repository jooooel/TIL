# .NET
[📝 .NET & GRPC What they forgot to tell you](https://www.faesel.com/blog/dotnet-grpc-forgot-to-tell-you) - More practical advice than just "How to do HelloWorld".

[📝 Performance best practices with gRPC](https://docs.microsoft.com/sv-se/aspnet/core/grpc/performance?view=aspnetcore-5.0)

[📝 dotnet-monitor](https://devblogs.microsoft.com/dotnet/introducing-dotnet-monitor/) - Expose diagnostics via REST API

[📝 ASP.NET Core Apps Observability](https://devblogs.microsoft.com/aspnet/observability-asp-net-core-apps/) - Logging, metrics, tracing

[📝 .NET Core Web API Metrics with Prometheus and Grafana](https://medium.com/@dale.bingham_30375/net-core-web-api-metrics-with-prometheus-and-grafana-fe84a52d9843)

[📝 Improvements in .NET Core 3.0 for troubleshooting and monitoring distributed apps](https://devblogs.microsoft.com/aspnet/improvements-in-net-core-3-0-for-troubleshooting-and-monitoring-distributed-apps/)

[📝 Building End-to-End Diagnostics and Tracing](https://jimmybogard.com/building-end-to-end-diagnostics-and-tracing-a-primer/) - How to implement Open Telemetry

[📝 Increasing Trace Cardinality with Activity Tags and Baggage](https://jimmybogard.com/increasing-trace-cardinality-with-tags-and-baggage/)

[▶️ Distributed Tracing Made Easy with .NET Core and OpenTelemetry](https://m.facebook.com/story.php?story_fbid=2890760374340656&id=511948345523789&_rdr) - Jimmy Bogard on how to implement Open Telemetry

[▶️ Cloud native apps with .NET and AKS](https://www.youtube.com/watch?v=HzQgIng_DNE&app=desktop) - Getting started with Tye. Kubernetes and Observability with Zipkin and Elastic/Kibana.

[📝 6 Best Practices to Keep a .NET Application’s Memory Healthy](https://michaelscodingspot.com/application-memory-health/) - Basic information about garbage collection and memory usage.

[📝 Introduction to Benchmarking in C# and ASP.NET Core Projects](https://code-maze.com/benchmarking-csharp-and-asp-net-core-projects/) - Introduction to BenchmarkDotNet

[📝 Performance Tuning for .NET Core](https://reubenbond.github.io/posts/dotnet-perf-tuning) - A list of things to consider when every nanosecond counts. 
## Debugging

[Kestrel stops serving https (http2) requests after reboot under load](https://github.com/dotnet/aspnetcore/issues/21183) - Great thread with tips on debugging locks, dotnet counters, traces, etc

[📝 .NET Memory Performance Analysis](https://github.com/Maoni0/mem-doc/blob/master/doc/.NETMemoryPerformanceAnalysis.md) - Really extensive document on memory, garbage collection, perfview, etc.

[📝 Find, Fix, and Avoid Memory Leaks in C# .NET: 8 Best Practices](https://michaelscodingspot.com/find-fix-and-avoid-memory-leaks-in-c-net-8-best-practices/)

[📝 8 Ways You can Cause Memory Leaks in .NET](https://michaelscodingspot.com/ways-to-cause-memory-leaks-in-dotnet/)

[📝 Debugging .NET Core memory issues (on Linux) with dotnet dump](https://www.tessferrandez.com/blog/2021/03/18/debugging-a-netcore-memory-issue-with-dotnet-dump.html)

[▶️ Running .NET Core performance investigation on Linux](https://www.youtube.com/watch?v=y4-h3qyDpJo) - _"f you don't know how to run a .NET performance investigation on Linux in this talk I am introducing dotnet trace, speedscope, perfcollect, chromium dev tools, VTune, and Rider and show how to use them to identify perf bottlenecks"_

[📝 What diagnostic tools are available in .NET Core?](https://docs.microsoft.com/en-us/dotnet/core/diagnostics/)

## Memory & Garbage Collection
[📝 Memory Management and Patterns in ASP.NET Core](https://github.com/sebastienros/memoryleak) - A text about how memory management works on ASP.NET Core, and the difference between sever and workstation GC.

# Architecture
[▶️ On .NET Live - Commands, Queries, and Clean Architecture](https://m.youtube.com/watch?v=IRvDGPbxdTs) - A video with Ian Cooper about clean architecture 

[📝 Pattern: Backends For Frontends](https://samnewman.io/patterns/architectural/bff/)

[🌍 Refactoring guru](https://refactoring.guru/) - Refactoring.Guru makes it easy for you to discover everything you need to know about refactoring, design patterns, SOLID principles, and other smart programming topics.

[▶️ ASP.NET Community Standup - Implementing Authentication and Security in ASP.NET Core](https://m.youtube.com/watch?v=eQ7eLOA69T0) - A summary of different authentication flows and when to choose which. 

# Microservices 
[🎧 The monolith vs microservices debate](https://changelog.com/gotime/126)

[🎧 Sam Newman: Monolith to Microservices](https://overcast.fm/+GdnUR3zCs)

# Infrastructure
## Azure
[📝 Azure Application Gateway for dummies](https://dev.to/kaiwalter/azure-application-gateway-for-dummies-dj3)

[▶️ Microsoft Application Gateway deep dive](https://youtu.be/B3O6bXu-NbM) - Great video explaining the concepts of AG.

[▶️ Publish Your AKS Services with Azure Private Link and Front Door](https://www.youtube.com/watch?v=WGXBKMzxci4)

## Docker
[🐋 .NET Client for Docker Remote API](https://github.com/dotnet/Docker.DotNet)

[📝 Run more stuff in Docker](https://jonathan.bergknoff.com/journal/run-more-stuff-in-docker/) - Use Docker and aliases instead of installing a lot of different cli tools.

## Kubernetes
[▶️ Navigating microservices with .NET Core - Ryan Nowak](https://www.youtube.com/watch?v=Z3G5SJQVMno)

[🎧 Ingress and the Service APIs](https://overcast.fm/+MqPmCnAUo)

[🎧 Cert-manager](https://overcast.fm/+MqPmR0VkU)

[📝 Series: Deploying ASP.NET Core applications to Kubernetes](https://andrewlock.net/series/deploying-asp-net-core-applications-to-kubernetes/) - Good series of posts On Kubernetes basics by Andrew Lock.

[📝 Scaling SignalR Core Web Applications With Kubernetes](https://medium.com/swlh/scaling-signalr-core-web-applications-with-kubernetes-fca32d787c7d)

[📝 Use Terraform to Create and Manage a HA AKS Kubernetes Cluster in Azure](https://codersociety.com/sv/blog/articles/terraform-azure-kubernetes)

[📝 Monitoring Health of .NET Core Background Services with TCP Probes on Kubernetes](https://thecloudblog.net/post/monitoring-health-of-aspnet-core-background-services-with-tcp-probes-on-kubernetes/)

[📝 A practical example of GitOps using Azure DevOps, Azure Container Registry, Helm, Flux and Kubernetes](https://www.mytechramblings.com/posts/gitops-with-azure-devops-helm-acr-flux-and-k8s/)

[📝 Managing Helm releases the GitOps way](https://github.com/fluxcd/helm-operator-get-started)

[▶️ Accessing Key Vault secrets from an Azure Kubernetes Cluster](https://www.youtube.com/watch?v=XIahaT2tc3Y) - Great video with examples on how to use both "AAD Pod Identity" and "Azure Key Vault Provider for Secrets Store CSI Driver" to access secrets from an Azure Key Vault from within an AKS cluster. The example code can be found in [this repo](https://github.com/neilpeterson/talk-kubernetes-key-vault).

[📝 A visual guide on troubleshooting Kubernetes deployments](https://learnk8s.io/troubleshooting-deployments) - Hands on tips on how to find out what's wrong with your deployments

[📝 How to debug Kubernetes Pending pods and scheduling failures](https://www.datadoghq.com/blog/debug-kubernetes-pending-pods/)

[📝 How to rightsize the Kubernetes resource limits](https://sysdig.com/blog/kubernetes-resource-limits/) - Prometheus queries to help find and plan resource limits.

[📝 Exploring Kubernetes Operator Pattern](https://iximiuz.com/en/posts/kubernetes-operator-pattern/) - Mostly about CRDs and the kubernetes API.

## Cassandra
[▶️ Introduction to Apache Cassandra](https://www.youtube.com/watch?v=B_HTdrTgGNs)

[▶️ Change Data Capture for Distributed Databases @Netflix](https://www.infoq.com/presentations/netflix-cdc-events-cassandra/)

## Messaging
[📝 The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)

[📝 Comparing Apache Kafka, Amazon Kinesis, Microsoft Event Hubs and Google Pub/Sub](https://blog.scottlogic.com/2018/04/17/comparing-big-data-messaging.html) - A bit old, so might not be exact, but a nice overview.

## Elastic Search
[📝 In depth guide to running Elasticsearch in production](https://facinating.tech/2020/02/22/in-depth-guide-to-running-elasticsearch-in-production/)

## Redis
[📝 SQL index on hash attributes in Redis](https://www.memurai.com/blog/model-hash-attributes-using-secondary-indexes-in-redis-and-memurai) - Exaplains different techniques for setting up a secondary index on Redis.

## Terraform
[📝 Create a Kubernetes cluster with Azure Kubernetes Service using Terraform](https://docs.microsoft.com/en-us/azure/developer/terraform/create-k8s-cluster-with-tf-and-aks)

[📝 Deploying Terraform Infrastructure using Azure DevOps Pipelines Step by Step](https://gmusumeci.medium.com/deploying-terraform-infrastructure-using-azure-devops-pipelines-step-by-step-advanced-1281b4ee15d1)

## Kustomize
[▶️ Kubernetes deployments with Flux v2: introduction to kustomize](https://www.youtube.com/watch?v=btqZkVQIdd8) - Great video with a tutorial showing how Kustomize works

## Monitoring
[🎧 Grafana](https://softwareengineeringdaily.com/2020/06/11/grafana-with-torkel-odegaard/?utm_source=rss&utm_medium=rss&utm_campaign=grafana-with-torkel-odegaard)

[📝 How to drop and delete metrics in Prometheus](https://tanmay-bhat.medium.com/how-to-drop-and-delete-metrics-in-prometheus-7f5e6911fb33)

[📝 Apache Kafka Consumer Lag Monitoring](https://sematext.com/blog/kafka-consumer-lag-offsets-monitoring/)

# Misc
[🎧 Stefan Prodan on Progressive Delivery, Flagger, and GitOps](https://soundcloud.com/infoq-channel/interview-stefan-prodan)

[▶️ Domain-driven refactoring](https://m.youtube.com/watch?v=_dQRAsVhCqA) - Great video by Jimmy Bogard with concrete tips on how to refactor code into domain models

[🌮 Pacco](https://github.com/devmentors/Pacco) - Full Microservice example using Prometheus, Grafana, Jaeger, etc...

[🎧 Azure Pipelines](https://overcast.fm/+Ir1SOLEvE)

[😀 draw.io](Https://draw.io) - Draw charts and architecture diagrams

[🎧 Challenges of distributed messaging systems](https://overcast.fm/+GnKaVgiQM) - Talking about NATS. Fully distributed fast messaging system. 

[▶️ Automated Testing for Terraform, Docker, Packer, Kubernetes, and More](https://www.infoq.com/presentations/automated-testing-terraform-docker-packer/)

[📝 Online migrations at scale](https://stripe.com/blog/online-migrations)

[📝 An Introduction to JQ](https://earthly.dev/blog/jq-select/?utm_source=hackernewsletter&utm_medium=email&utm_term=fav) - Covers the basics of JQ

[📝 How we automatized our release process into just 3 clicks](https://sudolabs.com/blog/how-we-automatized-our-release-process-into-just-3-clicks) - Examples of GitHub Actions to automate creating PRs and merging between branches.

[🐳 Life is to short to use dated cli tools that suck](https://mobile.twitter.com/amilajack/status/1479328649820000256) - Try these instead. A list of alternative (improved) cli tools to use instead of cat, ls, diff, etc.

[👨‍💻 Modern Unix](https://github.com/ibraheemdev/modern-unix) - A collection of modern CLI tools for Unix systems. 

[📝 The Delivery Hero Reliability Manifesto](https://tech.deliveryhero.com/our-reliability-manifesto/)

[📝 Basic Network Troubleshooting](https://www.netmeister.org/blog/basic-network-troubleshooting.html)

[📝 ▶️ Node.js Rocks in Docker](https://github.com/BretFisher/nodejs-rocks-in-docker) - In-depth details on building container images for Node.js projects.

# Golang
[📝 Learn Go in ~5mins](https://gist.github.com/prologic/5f6afe9c1b98016ca278f4d507e65510)

[▶️ GopherCon 2019: Mat Ryer - How I Write HTTP Web Services after Eight Years](https://www.youtube.com/watch?v=rWBSMsLG8po)

[📝 Practical Go lessons](https://www.practical-go-lessons.com)
