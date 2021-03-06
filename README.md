# pub-sub-data-event-bus
Research for pub sub data bus including data capture

HL7 FHIR pub sub method for data distribution.   Note this seems to have replaced both ATOM and RSS as a feed mechanism in FHIR version 4 - 
  * https://www.hl7.org/fhir/subscription.html
  * https://www.hl7.org/fhir/bundle.html 
  * https://www.hl7.org/fhir/messaging.html  See:  Asynchronous Messaging using the RESTful API    
  * FHIRCast - modern, simple application context synchronization http://fhircast.org/ 
  * 

Google Pub Sub overview - https://cloud.google.com/pubsub/docs/overview
  * Using Google Pubsub to enable events for FHIR API https://cloud.google.com/healthcare/docs/how-tos/pubsub

  * Google Pub Sub messaging Architecture - https://cloud.google.com/pubsub/architecture

Microsoft Publish Subscribe Pattern 
  * https://docs.microsoft.com/en-us/azure/architecture/patterns/publisher-subscriber 
  

Pub Sub in agte of cloud - Event driven computing is the way we build software to give you information instantly when it happens.  https://cloudramblings.me/2014/09/22/publish-subscribe-event-driven-architecture-in-the-age-of-cloud-mobile-internet-of-thingsiot-social/

Very nice overview of event bus with core issues like broadcase, polling, etc. https://cloudramblings.me/2014/09/22/publish-subscribe-event-driven-architecture-in-the-age-of-cloud-mobile-internet-of-thingsiot-social/

Apache Qpid - a high speed message broker based on a open source (AMQP protocol)[https://www.amqp.org/product/overview] - https://qpid.apache.org/ 

Comparing Apache Kafka, Amazon Kinesis, Microsoft Event Hubs and Google Pub/Sub - distributed log technologies may on the surface seem very similar to traditional broker messaging technologies, they differ significantly architecturally and therefore have very different performance and behavioural characteristics.  https://blog.scottlogic.com/2018/04/17/comparing-big-data-messaging.html

Microsoft pub sub arch overview: https://docs.microsoft.com/en-us/azure/architecture/patterns/publisher-subscriber  When to use this  pattern:
  * An application needs to broadcast information to a significant number of consumers.
  * An application needs to communicate with one or more independently-developed applications or services, which may use different platforms, programming languages, and communication protocols.
  * An application can send information to consumers without requiring real-time responses from the consumers.
  * The systems being integrated are designed to support an eventual consistency model for their data.
  * An application needs to communicate information to multiple consumers, which may have different availability requirements or uptime schedules than the sender.


ActiveMQ vs RabbitMQ vs ZeroMQ vs Apache Qpid vs Kafka vs IronMQ -Message Queue Comparision - http://kuntalganguly.blogspot.com/2014/08/message-queue-comparision.html

Concurrency using messaging rather than memory sharing - http://wiki.zeromq.org/whitepapers:multithreading-magic
* zeroQ claims 140K messages per second https://github.com/Abc-Arbitrage/Zebus/wiki/Performance
* Queue measuring performance - http://wiki.zeromq.org/whitepapers:measuring-performance
* Zero MQ Broker vs. Brokerless - Broker vs. Brokerless
* Zero MQ Market Analysis - http://wiki.zeromq.org/whitepapers:market-analysis

Go Bindings for AMQP protocol - https://github.com/Azure/go-amqp/graphs/contributors




