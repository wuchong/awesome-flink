[<img src="https://raw.githubusercontent.com/wuchong/awesome-flink/master/flink_squirrel.png" align="right">](https://flink.apache.org/)


# Awesome Flink [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome things related to Apache Flink. Inspired by [Awesome Hadoop](https://github.com/youngwookim/awesome-hadoop) and [Awesome Vue](https://github.com/vuejs/awesome-vue).

- [Packages](#packages)
  - [Notebooks](#notebooks)
  - [Machine Learning](#machine-learning)
  - [Complex Event Processing](#complex-event-processing)
  - [Interfaces](#interfaces)
  - [Connectors](#connectors)
  - [Benchmarks](#benchmarks)
  - [Tests](#Tests)
- [Resources](#resources)
    - [Official Resources](#official-resources)
    - [External Resources](#external-resources)
    - [Community](#community)
    - [Books](#books)
    - [Papers](#papers)
    - [Blogs](#blogs)
    - [Flink Forward](#flink-forward)
    - [Slides](#slides)

# Packages

## Notebooks
- [Apache Zeppelin](http://zeppelin.apache.org/) - Web-based notebook that enables interactive data analytics with plugable backends, integrated plotting, and extensive Flink support out-of-the-box.

## Machine Learning

- [Flink-TensorFlow](https://github.com/FlinkML/flink-tensorflow) - A library for machine intelligence in Apache Flink™, using the TensorFlow library and associated models.

## Complex Event Processing

- [Flink-Siddhi](https://github.com/haoch/flink-siddhi) - A CEP library for Flink to run Siddhi within Apache Flink streaming application

## Interfaces

- [Apache Beam](https://beam.apache.org) - Unified data processing engine supporting both batch and streaming applications. Apache Flink is one of the supported execution environments.

## Connectors
- [Apache Bahir](https://github.com/apache/bahir-flink) -  Collection of the connectors excluded from Flink (Akka, ActiveMQ, Flume, Netty, Redis).

## Benchmarks

- [Yahoo! Streaming benchmark](https://github.com/yahoo/streaming-benchmarks)
- [Yahoo! Streaming benchmark extension](https://github.com/dataArtisans/yahoo-streaming-benchmark)

## Tests
- [Flinnk spector](https://github.com/ottogroup/flink-spector) - provides a framework to define unit tests for Apache Flink data flows. The framework executes data flows locally and verifies the output using predefined expectations.

# Resources
Various resources, such as books, websites and articles.

## Official Resources

- [Flink Documentation](https://ci.apache.org/projects/flink/flink-docs-master/)
- [Flink Wiki](https://cwiki.apache.org/confluence/display/FLINK/Apache+Flink+Home)
- [Flink Training](http://dataartisans.github.io/flink-training/index.html)

## External Resources

- [Flink 中文文档](http://doc.flink-china.org/)
- [Flink 中文文档 v1.2 ing...](https://github.com/Apache-Flink-Docs-ZH/Apache-Flink-Docs-ZH-translation)
- [Flink 台灣](https://blog.flink.tw/)

## Community

- [Twitter](https://twitter.com/ApacheFlink)
- [Meetups](https://www.meetup.com/topics/apache-flink/)

## Books

- [Stream Processing with Apache Flink](http://shop.oreilly.com/product/0636920057321.do) - by Fabian Hueske, Vasiliki Kalavri (Nov 2017)
- [Flink in Action](https://books.google.com/books/about/Flink_in_Action.html?id=QHEzvgAACAAJ) - by Sameer Wadkar, Hari Rajaram (Mar 2017)
- [Learning Apache Flink](https://www.amazon.com/Learning-Apache-Flink-Tanmay-Deshpande/dp/1786466228/ref=pd_lpo_sbs_14_t_0?_encoding=UTF8&psc=1&refRID=N7HD72FCMPB4NHCMZT9R) - by Tanmay Deshpande (Feb 2017)
- [Introduction to Apache Flink](http://shop.oreilly.com/product/0636920061724.do) - by  Ellen Friedman, Kostas Tzoumas (Oct 2016)

## Papers

- [Lightweight Asynchronous Snapshots for Distributed Dataflows](https://arxiv.org/pdf/1506.08603.pdf) - Paper proposed Asynchronous Barrier Snapshotting (ABS) implemented in Flink to support stateful stream processing. (Jun 2015)
- [Apache Flink™: Stream and Batch Processing in a Single Engine](https://kth.diva-portal.org/smash/get/diva2:1059537/FULLTEXT01.pdf) - Paper introducing Apache Flink  for processing streaming and batch data under a single execution model. (Jan 2015)
- [The Dataflow Model: A Practical Approach to Balancing Correctness, Latency, and Cost in Massive-Scale, Unbounded, Out-of-Order Data Processing](http://people.csail.mit.edu/matei/courses/2015/6.S897/readings/google-dataflow.pdf) - Paper introducing the Dataflow model which Flink's streaming model based on. (2015)
- [Efficient Pattern Matching over Event Streams](https://people.cs.umass.edu/~yanlei/publications/sase-sigmod08.pdf) - Flink CEP library inspired by this paper. (2008)

## Blogs

- [Official Flink Blog](http://flink.apache.org/blog/)
- [The data Artisans Blog](https://data-artisans.com/blog)
- [Flink 原理与实现](http://wuchong.me/categories/Flink/)
- [Yanghua's Blog](http://vinoyang.com/tags/Flink/)（中文）
- [THE MUSINGS OF RAWKINTREVO](https://rawkintrevo.org/category/flink/)
- [Data Flair](http://data-flair.training/blogs/category/flink/)
- [Building Applications with Apache Flink](http://bytefish.de/tag/flink/)

## Flink Forward

- Flink Forward Berlín 2017 - [Slides](https://github.com/397090770/FlinkForward201709)
- Flink Forward San Francisco 2017 - [Slides and Videos](https://github.com/flink-china/flink-forward-sf-2017)
- Flink Forward 2016 - [Slides and Videos](http://2016.flink-forward.org/program/sessions/)
- Flink Forward 2015 - [Slides and Videos](http://2015.flink-forward.org/?post_type=session)



## Slides

### 2017
- Timo Walther: **Table & SQL API – unified APIs for batch and stream processing** *Flink Forward San Francisco, April 2017*: [SlideShare](https://www.slideshare.net/FlinkForward/flink-forward-sf-2017-timo-walther-table-sql-api-unified-apis-for-batch-and-stream-processing)
- Kostas Kloudas: **Extending Flink’s Streaming APIs** *Flink Forward San Francisco, April 2017*: [SlideShare](https://www.slideshare.net/FlinkForward/flink-forward-sf-2017-konstantinos-kloudas-extending-flinks-streaming-apis)
- Tzu-Li (Gordon) Tai: **Joining the Scurry of Squirrels: Contributing to Apache Flink** *Flink Forward San Francisco, April 2017*: [SlideShare](https://www.slideshare.net/FlinkForward/flink-forward-sf-2017-tzuli-gordon-tai-joining-the-scurry-of-squirrels-contributing-to-apache-flink)
- Stefan Richter: **Improvements for large state and recovery in Flink** *Flink Forward San Francisco, April 2017*: [SlideShare](https://www.slideshare.net/FlinkForward/flink-forward-sf-2017-stefan-richter-improvements-for-large-state-and-recovery-in-flink)
- Ufuk Celebi: **The Stream Processor as a Database: Building Online Applications directly on Streams** *Flink Forward San Francisco, April 2017*: [SlideShare](https://www.slideshare.net/FlinkForward/flink-forward-sf-2017-ufuk-celebi-the-stream-processor-as-a-database-building-online-applications-directly-on-streams)
- Jamie Grier: **Apache Flink - The Latest and Greatest** *Flink Forward San Francisco, April 2017*: [SlideShare](https://www.slideshare.net/FlinkForward/flink-forward-sf-2017-jamie-grier-apache-flinkthe-latest-and-greatest)
- Stephan Ewen: **Experiences running Flink at Very Large Scale** *Flink Forward San Francisco, April 2017*: [SlideShare](https://www.slideshare.net/FlinkForward/flink-forward-sf-2017-stephan-ewen-experiences-running-flink-at-very-large-scale)
- Stephan Ewen: **Convergence of real-time analytics and data-driven applications** *Flink Forward San Francisco, April 2017*: [SlideShare](https://www.slideshare.net/FlinkForward/flink-forward-sf-2017-stephan-ewen-convergence-of-realtime-analytics-and-datadriven-applications)
- Till Rohrmann: **Redesigning Apache Flink’s Distributed Architecture Back to Sessions overview** *Flink Forward San Francisco, April 2017*: [SlideShare](https://www.slideshare.net/FlinkForward/flink-forward-sf-2017-till-rohrmann-redesigning-apache-flinks-distributed-architecture-back-to-sessions-overview)
- Timo Walther: **Table & SQL API - unified APIs for batch and stream processing** *Apache Flink Meetup Amsterdam, March 2017*: [SlideShare](https://www.slideshare.net/dataArtisans/timo-walther-table-sql-api-unified-apis-for-batch-and-stream-processing)
- Kostas Kloudas: **Extending Flink's Streaming APIs** *Apache Flink Meetup Berlin, February 2017*: [SlideShare](https://www.slideshare.net/dataArtisans/kostas-kloudas-extending-flinks-streaming-apis)
- Fabian Hueske: **Stream Analytics with SQL on Apache Flink** *Big Data Tech Summit, Warsaw February 2017*: [SlideShare](http://www.slideshare.net/dataArtisans/fabian-hueske-stream-analytics-with-sql-on-apache-flink)


### 2016

- Stephan Ewen: **Stream Processing as a Foundational Paradigm and Apache Flink's Approach to It** *Big Data, Berlin v 10.0, December 2016*: [SlideShare](http://www.slideshare.net/dataArtisans/stephan-ewen-stream-processing-as-a-foundational-paradigm-and-apache-flinks-approach-to-it)
- Kostas Tzoumas & Stephan Ewen: **Keynote -The maturing data streaming ecosystem and Apache Flink’s accelerated growth** *Flink Forward, Berlin September 2016*: [SlideShare](http://www.slideshare.net/FlinkForward/kostas-tzoumasstpehan-ewen-keynote-the-maturing-data-streaming-ecosystem-and-apache-flinks-accelerated-growth)
- Robert Metzger: **Connecting Apache Flink to the World - Reviewing the streaming connectors** *Flink Forward, Berlin September 2016*: [SlideShare](http://www.slideshare.net/FlinkForward/robert-metzger-connecting-apache-flink-to-the-world-reviewing-the-streaming-connectors)
- Till Rohrmann & Fabian Hueske: **Declarative stream processing with StreamSQL and CEP** *Flink Forward, Berlin September 2016*: [SlideShare](http://www.slideshare.net/FlinkForward/fabian-huesketill-rohrmann-declarative-stream-processing-with-streamsql-and-cep)
- Jamie Grier: **Robust Stream Processing with Apache Flink** *Flink Forward, Berlin September 2016*: [SlideShare](http://www.slideshare.net/FlinkForward/jamie-grier-robust-stream-processing-with-apache-flink)
- Jamie Grier: **The Stream Processor as a Database- Building Online Applications directly on Streams** *Flink Forward, Berlin September 2016*: [SlideShare](http://www.slideshare.net/FlinkForward/jamie-grier-the-stream-processor-as-a-database-building-online-applications-directly-on-streams)
- Till Rohramnn: **Dynamic Scaling - How Apache Flink adapts to changing workloads** *Flink Forward, Berlin September 2016*: [SlideShare](http://www.slideshare.net/FlinkForward/till-rohrmann-dynamic-scaling-how-apache-flink-adapts-to-changing-workloads)
- Stephan Ewen: **Running Flink Everywhere** *Flink Forward, Berlin September 2016*: [SlideShare](http://www.slideshare.net/FlinkForward/stephan-ewen-running-flink-everywhere)
- Stephan Ewen: **Scaling Apache Flink to very large State** *Flink Forward, Berlin September 2016*: [SlideShare](http://www.slideshare.net/FlinkForward/stephan-ewen-scaling-to-large-state)
- Aljoscha Krettek: **The Future of Apache Flink** *Flink Forward, Berlin September 2016*: [SlideShare](http://www.slideshare.net/FlinkForward/aljoscha-krettek-the-future-of-apache-flink)
- Fabian Hueske: **Taking a look under the hood of Apache Flink's relational APIs** *Flink Forward, Berlin September 2016*: [SlideShare](http://www.slideshare.net/fhueske/taking-a-look-under-hood-of-apache-flinks-relational-apis)
- Kostas Tzoumas: **Streaming in the Wild with Apache Flink** *Hadoop Summit San Jose, June 2016*: [SlideShare](http://www.slideshare.net/KostasTzoumas/streaming-in-the-wild-with-apache-flink-63790942)
- Stephan Ewen: **The Stream Processor as the Database - Apache Flink** *Berlin Buzzwords, June 2016*: [SlideShare](http://www.slideshare.net/stephanewen1/the-stream-processor-as-the-database-apache-flink-berlin-buzzwords)
- Till Rohrmann & Fabian Hueske: **Streaming Analytics & CEP - Two sides of the same coin?** *Berlin Buzzwords, June 2016*: [SlideShare](http://www.slideshare.net/tillrohrmann/streaming-analytics-cep-two-sides-of-the-same-coin)
- Robert Metzger: **A Data Streaming Architecture with Apache Flink** *Berlin Buzzwords, June 2016*: [SlideShare](http://www.slideshare.net/robertmetzger1/a-data-streaming-architecture-with-apache-flink-berlin-buzzwords-2016)
- Stephan Ewen: **Continuous Processing with Apache Flink** *Strata + Hadoop World London, May 2016*: [SlideShare](http://www.slideshare.net/stephanewen1/continuous-processing-with-apache-flink-strata-london-2016)
- Stephan Ewen: **Streaming Analytics with Apache Flink 1.0** *Flink NYC Flink, May 2016*: [SlideShare](http://www.slideshare.net/stephanewen1/apache-flink-myc-flink-meetup)
- Ufuk Celebi: **Unified Stream & Batch Processing with Apache Flink**. *Hadoop Summit Dublin, April 2016*: [SlideShare](http://www.slideshare.net/HadoopSummit/unified-stream-and-batch-processing-with-apache-flink)
- Kostas Tzoumas: **Counting Elements in Streams**. *Strata San Jose, March 2016*: [SlideShare](http://www.slideshare.net/KostasTzoumas/apache-flink-at-strata-san-jose-2016)
- Jamie Grier: **Extending the Yahoo! Streaming Benchmark**. *Flink Washington DC Meetup, March 2016*: [SlideShare](http://www.slideshare.net/JamieGrier/extending-the-yahoo-streaming-benchmark)
- Jamie Grier: **Stateful Stream Processing at In-Memory Speed**. *Flink NYC Meetup, March 2016*: [SlideShare](http://www.slideshare.net/JamieGrier/stateful-stream-processing-at-inmemory-speed)
- Robert Metzger: **Stream Processing with Apache Flink**. *QCon London, March 2016*: [SlideShare](http://www.slideshare.net/robertmetzger1/qcon-london-stream-processing-with-apache-flink)
- Vasia Kalavri: **Batch and Stream Graph Processing with Apache Flink**. *Flink and Neo4j Meetup Berlin, March 2016*: [SlideShare](http://www.slideshare.net/vkalavri/batch-and-stream-graph-processing-with-apache-flink)
- Maximilian Michels: **Stream Processing with Apache Flink**. *Big Data Technology Summit, February 2016*:
[SlideShare](http://de.slideshare.net/MaximilianMichels/big-datawarsaw-animated)
- Vasia Kalavri: **Single-Pass Graph Streaming Analytics with Apache Flink**. *FOSDEM, January 2016*: [SlideShare](http://www.slideshare.net/vkalavri/gellystream-singlepass-graph-streaming-analytics-with-apache-flink)
- Till Rohrmann: **Streaming Done Right**. *FOSDEM, January 2016*: [SlideShare](http://www.slideshare.net/tillrohrmann/apache-flink-streaming-done-right-fosdem-2016)

### 2015

- Till Rohrmann: **Streaming Data Flow with Apache Flink** *(October 29th, 2015)*: [SlideShare](http://www.slideshare.net/tillrohrmann/streaming-data-flow-with-apache-flink-paris-flink-meetup-2015-54572718)
- Stephan Ewen: **Flink-0.10** *(October 28th, 2015)*: [SlideShare](http://www.slideshare.net/stephanewen1/flink-010-bay-area-meetup-october-2015)
- Robert Metzger: **Architecture of Flink's Streaming Runtime** *(ApacheCon, September 29th, 2015)*: [SlideShare](http://www.slideshare.net/robertmetzger1/architecture-of-flinks-streaming-runtime-apachecon-eu-2015)
- Robert Metzger: **Click-Through Example for Flink's KafkaConsumer Checkpointing** *(September, 2015)*: [SlideShare](http://www.slideshare.net/robertmetzger1/clickthrough-example-for-flinks-kafkaconsumer-checkpointing)
- Paris Carbone: **Apache Flink Streaming. Resiliency and Consistency** (Google Tech Talk, August 2015: [SlideShare](http://www.slideshare.net/ParisCarbone/tech-talk-google-on-flink-fault-tolerance-and-ha)
- Andra Lungu: **Graph Processing with Apache Flink** *(August 26th, 2015)*: [SlideShare](http://www.slideshare.net/AndraLungu/flink-gelly-karlsruhe-june-2015)
- Till Rohrmann: **Interactive data analytisis with Apache Flink** *(June 23rd, 2015)*: [SlideShare](http://www.slideshare.net/tillrohrmann/data-analysis-49806564)
- Gyula Fóra: **Real-time data processing with Apache Flink** *(Budapest Data Forum, June 4th, 2015)*: [SlideShare](http://www.slideshare.net/GyulaFra/flink-streaming-budapestdata)
- Till Rohrmann: **Machine Learning with Apache Flink** *(March 23th, 2015)*: [SlideShare](http://www.slideshare.net/tillrohrmann/machine-learning-with-apache-flink)
- Marton Balassi: **Flink Streaming** *(February 26th, 2015)*: [SlideShare](http://www.slideshare.net/MrtonBalassi/flink-streaming-berlin-meetup)
- Vasia Kalavri: **Large-Scale Graph Processing with Apache Flink** *(FOSDEM, 31st January, 2015)*: [SlideShare](http://www.slideshare.net/vkalavri/largescale-graph-processing-with-apache-flink-graphdevroom-fosdem15)
- Fabian Hueske: **Hadoop Compatibility** *(January 28th, 2015)*: [SlideShare](http://www.slideshare.net/fhueske/flink-hadoopcompat20150128)
- Kostas Tzoumas: **Apache Flink Overview** *(January 14th, 2015)*: [SlideShare](http://www.slideshare.net/KostasTzoumas/apache-flink-api-runtime-and-project-roadmap)

### 2014

- Kostas Tzoumas: **Flink Internals** *(November 18th, 2014)*: [SlideShare](http://www.slideshare.net/KostasTzoumas/flink-internals)
- Marton Balassi & Gyula Fóra: **The Flink Big Data Analytics Platform** *(ApachecCon, November 11th, 2014)*: [SlideShare](http://www.slideshare.net/GyulaFra/flink-apachecon)
- Till Rohrmann: **Introduction to Apache Flink** *(October 15th, 2014)*: [SlideShare](http://www.slideshare.net/tillrohrmann/introduction-to-apache-flink)

## License

<p xmlns:dct="http://purl.org/dc/terms/">
<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/publicdomain.svg"
     style="border-style: none;" alt="Public Domain Mark" />
</a>
<br />
This work (<span property="dct:title">Awesome Flink</span>, by <a href="https://github.com/wuchong/awesome-flink" rel="dct:creator">https://github.com/wuchong/awesome-flink</a>), identified by <a href="https://github.com/wuchong" rel="dct:publisher"><span property="dct:title">Jark Wu</span></a>, is free of known copyright restrictions.
</p>



