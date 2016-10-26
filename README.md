# Awesome Nifi

## Table of Contents

- [Learning NiFi](#learning-nifi)
- [Blogs and Presentations](#blogs-and-presentations)
    - [Blogs](#blogs)
    - [Specific Topics](#specific-topics)
    - [Slides](#slides)
    - [Videos](#videos)
    - [Mailing List Best Of](#mailing-list-best-of)
- [Videos](#videos)
- [Templates](#templates-and-examples)
- [Processors and Bundles](#processors-and-bundles)
- [Deployment](#deployment)
    - [Data Flow Deployment](#data-flow-deployment)
    - [Administration](#administration)
    - [Configuration Management](#configuration-management)
    - [Packages](#packages)
    - [Dockerfiles](#dockerfiles)
    - [Vagrantfiles](#vagrantfiles)
- [Misc](#misc)
- [License](#license)

## Learning NiFi

* [xmlking/nifi-examples](https://github.com/xmlking/nifi-examples) - Apache NiFi example flows
* [simonellistonball/masterclass-hdf](https://github.com/simonellistonball/masterclass-hdf) - Various NiFi labs and class
* [seanorama/masterclass](https://github.com/seanorama/masterclass) - Platform setup for nifi masterclass and other Hadoop workshops
* [aperepel/nifi-workshop](https://github.com/aperepel/nifi-workshop) - A complete custom processor project, for your reference
* [pcgrenier/nifi-examples](https://github.com/pcgrenier/nifi-examples) - Apache Nifi Examples by http://www.nifi.rocks
* [bbende/nifi-example-bundles](https://github.com/bbende/nifi-example-bundles) - Example processor bundles for Apache NiFi
* [abajwa-hw/nifi-network-processor](https://github.com/abajwa-hw/nifi-network-processor) - Sample custom Nifi processor to process tcpdump
* [bbende/nifi-streaming-examples](https://github.com/bbende/nifi-streaming-examples) - Collection of examples integrating NiFi with stream process frameworks
* [DhruvKumar/stocks-dashboard-lab](https://github.com/DhruvKumar/stocks-dashboard-lab) - This lab teaches you how to create a realtime dashboard of stock prices
* [Getting Started With Apache NiFi and Hortonworks HDF](https://dzone.com/articles/getting-started-with-apache-nifi-and-hdf)

## Blogs and Presentations

### Blogs

* [Apache NiFi Blog](https://blogs.apache.org/nifi/)
* [nifi.rocks](http://www.nifi.rocks)
* [Richard's Tech Notes](https://richardstechnotes.wordpress.com/category/apache-nifi/)
* [Fun with Apache NiFi](http://funnifi.blogspot.com)
* [Dataflow Developer](http://dataflowdeveloper.com)

### Specific Topics

* [Monitoring An S3 Bucket in Apache NiFi](https://adamlamar.github.io/2016-01-30-monitoring-an-s3-bucket-in-apache-nifi/)
* [IoT streaming with MQTT and Apache NiFi](https://richardstechnotes.wordpress.com/2015/12/26/iot-streaming-with-mqtt-and-apache-nifi/)
* [Building Data Pipelines for Solr with Apache NiFi](http://www.slideshare.net/BryanBende/building-data-pipelines-for-solr-with-apache-nifi)
* [Using Apache Nifi to Stream Live Twitter Feeds to Hadoop](http://nedsblog.com/2015/09/02/using-apache-nifi-to-stream-live-twitter-feeds-to-hadoop/)
* [Creating a Limited Failure Loop in NiFi](https://kisstechdocs.wordpress.com/2015/01/15/creating-a-limited-failure-loop-in-nifi/)
* [Update NiFi Flow On-the-fly via API](https://community.hortonworks.com/articles/3160/update-nifi-flow-on-the-fly-via-api.html)
* [ExecuteScript Processor Hello, World!](http://funnifi.blogspot.com/2016/02/executescript-processor-hello-world.html)
* [Replacing Flow File Content with the ExecuteScript Processor](http://funnifi.blogspot.com/2016/02/executescript-processor-replacing-flow.html)
* [Using Modules with the ExecuteScript Processor](http://funnifi.blogspot.com/2016/02/executescript-using-modules.html)
* [3 Considerations for Apache NiFi in Financial Services](https://blog.c24tech.com/data-geek/3-considerations-for-apache-nifi-in-financial-services)
* [Custom Processors for Apache NiFi](http://bryanbende.com/development/2015/02/04/custom-processors-for-apache-nifi)
* [Collecting Logs with Apache NiFi](http://bryanbende.com/development/2015/05/17/collecting-logs-with-apache-nifi)
* [Best practices for setting up a high performance NiFi installation](https://community.hortonworks.com/content/kbentry/7882/hdfnifi-best-practices-for-setting-up-a-high-perfo.html)
* [Using Apache NiFi to read children's books](https://www.linkedin.com/pulse/nifi-ocr-using-apache-read-childrens-books-jeremy-dyer)
* [What is Apache NiFi?](http://www.ssglimited.com/what-is-apache-nifi/)
* [Optimizing Performance of Apache NiFi's Network Listening Processors](http://bryanbende.com/development/2016/05/09/optimizing-performance-of-apache-nifis-network-listening-processors)
* [Running NiFi on Raspberry Pi. Best Practices.](https://community.hortonworks.com/articles/32605/running-nifi-on-raspberry-pi-best-practices.html)
* [Examples integrating NiFi with stream process frameworks](https://github.com/bbende/nifi-streaming-examples)
* [Use NiFi to Lessen the Friction of Moving Data](https://www.compose.com/articles/lessen-the-friction-of-moving-data-with-nifi/)
* [Streaming analytics with SAS Event Stream Processing and Apache Nifi](http://blogs.sas.com/content/sascom/2016/07/11/streaming-analytics-sas-event-stream-processing-apache-nifi/)
* [Using the Apache Ranger Authorizer](http://bryanbende.com/development/2016/08/22/apache-nifi-1.0.0-using-the-apache-ranger-authorizer)
* [Overview of X.509 SSL Security on NiFi](http://www.batchiq.com/nifi-overview-ssl-security.html)
* [Configuring Apache NiFi SSL Authentication](http://www.batchiq.com/nifi-configuring-ssl-auth.html)
* [Apache NiFi tls-toolkit multi-node standalone in Docker](https://blog.rosander.ninja/nifi/toolkit/tls/2016/09/20/tls-toolkit-standalone-multi.html)
* [Mongo to Mongo Data Moves with NiFi](https://www.compose.com/articles/mongo-to-mongo-data-moves-with-nifi)
* [Integrating Apache NiFi and Apache Kafka](http://bryanbende.com/development/2016/09/15/apache-nifi-and-apache-kafka)
* [Using Apache NiFi to ingest SNMP tables into Avro](http://www.michalklempa.com/2016/10/17/using-apache-nifi-to-ingest-snmp-tables-into-avro)

### Slides

* [Data Distribution Patterns with Apache NiFi](http://www.slideshare.net/BryanBende/data-distribution-patterns-with-apache-nifi)
* [Integrating NiFi and Flink](http://www.slideshare.net/BryanBende/integrating-nifi-and-flink)

### Videos

* [OSCON 2015 : Beyond messaging - Enterprise Dataflow with Apache NiFi](https://www.youtube.com/watch?v=sQCgtCoZyFQ)
* [Hortonworks DataFlow powered by Apache NiFi](https://www.youtube.com/watch?v=fO-xOrWBZJU)
* [How to navigate and build a dataflow in Apache Nifi](https://www.youtube.com/watch?v=FgTGAWLC170)
* [IoT-Processor for #ApacheNiFi in action. Visualization of Tweets about presidential candidates. #AWSIoT #RaspberryPi](https://twitter.com/KayLerch/status/721455415456882689)

### Mailing List Best Of

* [Re: Persistence of intermediary data in NiFi ?](http://mail-archives.apache.org/mod_mbox/nifi-users/201603.mbox/%3cCALJK9a6t5+B6S0MCCyOOs7hds_4dfnwj-6PjxFR6kXkdp1D3fg@mail.gmail.com%3e)
* [Re: Need help understanding backpressure](http://mail-archives.apache.org/mod_mbox/nifi-users/201604.mbox/%3cBLU436-SMTP24995D5F6EDF5985AADFE23CE680@phx.gbl%3e)

## Templates and Examples

* [hortonworks-gallery/nifi-templates](https://github.com/hortonworks-gallery/nifi-templates) - A collection of templates for use with Apache NiFi
* [bikash/nifiIoT](https://github.com/bikash/nifiIoT) - Data Tracking using Apache NiFi in IoT, IoE
* [BatchIQ/nifi-executescript-samples](https://github.com/BatchIQ/nifi-executescript-samples) - Sample scripts for use with Apache NiFi's ExecuteScript processor
* [ijokarumawak/nifi-deploy-process-group](https://github.com/ijokarumawak/nifi-deploy-process-group) - Deploy ProcessGroup into your LIVE NiFi data-flow
* [tbilou/flickr-nifi](https://github.com/tbilou/flickr-nifi) - Using Nifi to easily fetch all photo data from Flickr

## Processors and Bundles

* [xmlking/nifi-scripting](https://github.com/xmlking/nifi-scripting) - NiFi Dynamic Script Executors
* [SwingDev/nifi-file-from-template-processor](https://github.com/SwingDev/nifi-file-from-template-processor) - Apache NiFi processor to create a new file from a Jinja template
* [fsauer65/NiFi-Extensions](https://github.com/fsauer65/NiFi-Extensions) - This repository contains the source for a json-json transformation processor for apache NiFi
* [qiansl127/nifi-spark-bundle](https://github.com/qiansl127/nifi-spark-bundle) - Customized Spark processor on NiFi
* [richards-tech/RTNiFiStreamProcessors](https://github.com/richards-tech/RTNiFiStreamProcessors) - IoT MQTT sensor stream capture for Apache NiFi
* [MDL/nifi-rabbitmq-bundle](https://github.com/MDL/nifi-rabbitmq-bundle) - NiFi Rabbit MQ bundle
* [xmlking/nifi-websocket](https://github.com/xmlking/nifi-websocket) - Apache NiFi WebSocket Listener
* [ryanleary/nifi-redis](https://github.com/ryanleary/nifi-redis) - NiFi Processors for pulling from Redis
* [jdye64/nifi-gpiorest](https://github.com/jdye64/nifi-gpiorest) - NiFi processor example for controlling REST based GPIO device like a Raspberry PI
* [aperepel/nifi-mqtt-bundle](https://github.com/aperepel/nifi-mqtt-bundle) - A generic support for NiFi interfacing with MQTT brokers
* [jfrazee/nifi-kinesis](https://github.com/jfrazee/nifi-kinesis) - Kinesis processor for Apache NiFi
* [joaohf/nifi-radius](https://github.com/joaohf/nifi-radius) - Apache NiFi process to Radius logs
* [jdye64/nifi-openalpr](https://github.com/jdye64/nifi-openalpr) - NiFi integration for OpenALPR
* [qntfy/nifi-redis](https://github.com/qntfy/nifi-redis) - NiFi Processors for handling data in Redis
* [jahhulbert-ccri/geomesa-nifi](https://github.com/jahhulbert-ccri/geomesa-nifi) - NiFi GeoMesa ingest processor
* [markap14/nifi-nosql-bundle](https://github.com/markap14/nifi-nosql-bundle) - NiFi NoSQL processors (MongoDB, Accumulo)
* [simonellistonball/nifi-OpenCV](https://github.com/simonellistonball/nifi-OpenCV) - Open CV based processors for NiFi
* [simonellistonball/nifi-AccumuloGraph](https://github.com/simonellistonball/nifi-AccumuloGraph) - NiFi processors for AccumuloGraph
* [helicopterman22/nifi\_amqp_processors](https://github.com/helicopterman22/nifi_amqp_processors) - A set of processors for sending and retrieving messages from an AMQP broker
* [bbukacek/nifi-hadoop-libraries-bundle](https://github.com/bbukacek/nifi-hadoop-libraries-bundle) - NiFi Hadoop Library for MapR
* [apiri/nifi-delegated-authorization-bundle](https://github.com/apiri/nifi-delegated-authorization-bundle) - A sample implementation of NiFi extensions working in concert to provide a delegated authorization approach in handling data on a per event basis
* [uwegeercken/nifi_processors](https://github.com/uwegeercken/nifi_processors) - Includes an Apache Velocity template processor
* [acesir/nifi-ConvertJSONtoCSV-bundle](https://github.com/acesir/nifi-ConvertJSONtoCSV-bundle) - Convert multi nested JSON files into denormalized, flattened out version of the CSV
* [acesir/nifi-ParseCSV-bundle](https://github.com/acesir/nifi-ParseCSV-bundle) - CSV parsing with masking, encryption and tokenization
* [withersdb/ALTER-nifi-putgeowave](https://github.com/withersdb/ALTER-nifi-putgeowave) - A NiFi processor that writes data to GeoWave
* [jdye64/nifi-addons](https://github.com/jdye64/nifi-addons) - Additional convenience processors not found in core Apache NiFi (OpenCV, Salesforce, Sphinx, Tesseract)
* [apsaltis/nifi-soap](https://github.com/apsaltis/nifi-soap) - NiFi SOAP processor
* [jfrazee/nifi-provenance-reporting-bundle](https://github.com/jfrazee/nifi-provenance-reporting-bundle) - NiFi provenance reporting tasks
* [KayLerch/apache-nifi-voiceops-skill](https://github.com/KayLerch/apache-nifi-voiceops-skill) - An Alexa skill which can be used to voice-control an Apache NiFi dataflow
* [imaifactory/nifi-processors](https://github.com/imaifactory/nifi-processors) - Includes processors for converting from regex named groups and LTSV to JSON
* [selim-namsi/NifiGroKProcessor](https://github.com/selim-namsi/NifiGroKProcessor) - Grok processor
* [DhruvKumar/nifi-grok-processor-bundle](https://github.com/DhruvKumar/nifi-grok-processor-bundle) - NiFi processor which can parse using Grok like expressions
* [DoxoLogic/nifi-generate-content](https://github.com/DoxoLogic/nifi-generate-content) - Apache nifi processor for creating a new FlowFile content based on property value
* [weaverplatform/weaver-nifi](https://github.com/weaverplatform/weaver-nifi) - Processor implementations for the Apache NiFi platform for connecting to the Weaver Platform
* [kineticadb/kinetica-connector-nifi](kineticadb/kinetica-connector-nifi) - GPUdb NiFi Connector
* [aperepel/nifi-csv-bundle](https://github.com/aperepel/nifi-csv-bundle) - CSV processors
* [minyk/nifi-headlessbrowser-processor](https://github.com/minyk/nifi-headlessbrowser-processor) - Returns the page source in its current state to FlowFile, including any DOM updates that occurred after page load
* [PromonLogicalis/nifi-spoofing-bundle](https://github.com/PromonLogicalis/nifi-spoofing-bundle) - NiFi bundle for IP spoofing
* [mmiklavc/scalable-ocr](https://github.com/mmiklavc/scalable-ocr) - Scalable OCR with Apache NiFi and Tesseract
* [openenergi/nifi-azure-datalake](https://github.com/openenergi/nifi-azure-datalake) - A processor to store NiFi flowfiles in Azure Data Lake
* [simonellistonball/PiWiNiFi](https://github.com/simonellistonball/PiWiNiFi) - A NiFi demo for collecting wifi data from conferences
* [jskora/nifipie](https://github.com/jskora/nifipie) - Python Tools for the Apache NiFi Rest API
* [simonellistonball/nifi-ml-bundle](https://github.com/simonellistonball/nifi-ml-bundle) - A bundle for basic scoring machine learning models in NiFi (PMML).
* [simonellistonball/nifi-audio-bundle](https://github.com/simonellistonball/nifi-audio-bundle) - Various audio related processors for NiFi
* [pinkdevelops/nifi-googlegeocode-bundle](https://github.com/pinkdevelops/nifi-googlegeocode-bundle) - FlowFile enrichment using google geocode service
* [jonathantelfer/nifi-neo4j](https://github.com/jonathantelfer/nifi-neo4j) - Bundle to add data into Neo4J graph databases
* [compose-ex/nifi-compose-bundle](https://github.com/compose-ex/nifi-compose-bundle) - Mongo streaming and RocksDB processors
* [sysunite/sysunite-nifi](https://github.com/sysunite/sysunite-nifi) - Generic Sysunite processors
* [BatchIQ/nifi-file-identity-provider-bundle](https://github.com/BatchIQ/nifi-file-identity-provider-bundle) - Identity Provider for Apache NiFi, allowing username/password authentication backed by a local file store
* [mrcsparker/nifi-edireader-bundle](https://github.com/mrcsparker/nifi-edireader-bundle) - Apache NIFI processor that converts EDI ASC X12 and EDIFACT documents into XML
* [mrcsparker/nifi-r-bundle](https://github.com/mrcsparker/nifi-r-bundle) - R Processor for NIFI
* [pagefault3228/nifi-processor-CheckDiskUsage](https://github.com/pagefault3228/nifi-processor-CheckDiskUsage) - NiFi processor that can monitor flowfile and content repository usage and enable back pressure when limits exceeded
* [pagefault3228/nifi-reportingtask-NagiosNRDPReporter](https://github.com/pagefault3228/nifi-reportingtask-NagiosNRDPReporter) - NiFi Reporting Task that reports NiFi metrics to Nagios via NRDP
* [pinkdevelops/nifi-accumulo-service](https://github.com/pinkdevelops/nifi-accumulo-service) - Apache NiFi Controller Service for connecting to Apache Accumulo 1.7.0

## Deployment

### Data Flow Deployment

* [aperepel/nifi-api-deploy](https://github.com/aperepel/nifi-api-deploy) - Demonstrates NiFi template deployment and configuration via a REST API

### Administration

* [abajwa-hw/ambari-nifi-service](https://github.com/abajwa-hw/ambari-nifi-service) - Ambari service to deploy/manage NiFi on HDP
* [prateek/nifi-parcel](https://github.com/prateek/nifi-parcel) - Apache NiFi service for Cloudera Manager

### Configuration Management

* [data-wranglers/nifi](https://github.com/data-wranglers/nifi) - Chef cookbook for Nifi install
* [45fifteen/charm-nifi](https://github.com/45fifteen/charm-nifi) - juju charm for nifi
* [trevor-vaughan/pupmod-simp-nifi](https://github.com/trevor-vaughan/pupmod-simp-nifi) - Puppet Module for managing Apache NiFi

### Packages

* [thmaung/nifi-builder](https://github.com/thmaung/nifi-builder) - Builds Apache NiFi RPM using rake and mock

### Dockerfiles

* [apiri/dockerfile-apache-nifi](https://github.com/apiri/dockerfile-apache-nifi)
* [mkobit/docker-nifi](https://github.com/mkobit/docker-nifi)
* [randerzander/docker-nifi](https://github.com/randerzander/docker-nifi)
* [aperepel/docker-nifi](https://github.com/aperepel/docker-nifi)
* [ijokarumawak/docker-compose-nifi-cluster](https://github.com/ijokarumawak/docker-compose-nifi-cluster)

### Vagrantfiles

* [minyk/nifi-sandbox](https://github.com/minyk/nifi-sandbox)

## Misc

* [mattyb149/nifi-client](https://github.com/mattyb149/nifi-client) - A NiFi client library for JVM languages
* [sponiro/gradle-nar-plugin](https://github.com/sponiro/gradle-nar-plugin) - A gradle plugin to create nar files for Apache nifi
* [SebastianCarroll/nifi-api](https://github.com/SebastianCarroll/nifi-api) - A ruby wrapper for the nifi rest api
* [jfrazee/nifi-processor-bundle-scala.g8](https://github.com/jfrazee/nifi-processor-bundle-scala.g8) - A giter8 template for generating a new Scala NiFi processor bundle
* [jdye64/go-nifi](https://github.com/jdye64/go-nifi) - Golang implementation of NiFi Site-to-Site protocol
* [SebastianCarroll/nifi-api](https://github.com/SebastianCarroll/nifi-api) - A ruby wrapper for the nifi rest api
* [mattyb149/nifi-script-tester](https://github.com/mattyb149/nifi-script-tester) - A project to create a stub/mock environment for testing ExecuteScript processors
* [bbende/apache-ranger-vagrant](https://github.com/bbende/apache-ranger-vagrant) - Deploys Apache Ranger in a Vagrant VM

## License

Copyright (c) 2016 Joey Frazee. awesome-nifi is licensed under the [Apache License 2.0](LICENSE).
