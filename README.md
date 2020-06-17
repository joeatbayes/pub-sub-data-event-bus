# pub-sub-data-event-bus
Research for pub sub data bus including data capture

HL7 FHIR pub sub method for data distribution.   Note this seems to have replaced both ATOM and RSS as a feed mechanism in FHIR version 4 - https://www.hl7.org/fhir/subscription.html  https://www.hl7.org/fhir/bundle.html https://www.hl7.org/fhir/messaging.html  See:  Asynchronous Messaging using the RESTful API  

Google Pub Sub overview - https://cloud.google.com/pubsub/docs/overview

Google Pub Sub messaging Architecture - https://cloud.google.com/pubsub/architecture

Pub Sub in agte of cloud - Event driven computing is the way we build software to give you information instantly when it happens.  https://cloudramblings.me/2014/09/22/publish-subscribe-event-driven-architecture-in-the-age-of-cloud-mobile-internet-of-thingsiot-social/

Very nice overview of event bus with core issues like broadcase, polling, etc. https://cloudramblings.me/2014/09/22/publish-subscribe-event-driven-architecture-in-the-age-of-cloud-mobile-internet-of-thingsiot-social/

Comparing Apache Kafka, Amazon Kinesis, Microsoft Event Hubs and Google Pub/Sub - distributed log technologies may on the surface seem very similar to traditional broker messaging technologies, they differ significantly architecturally and therefore have very different performance and behavioural characteristics.  https://blog.scottlogic.com/2018/04/17/comparing-big-data-messaging.html

Microsoft pub sub arch overview: https://docs.microsoft.com/en-us/azure/architecture/patterns/publisher-subscriber  When to use this  pattern:
  * An application needs to broadcast information to a significant number of consumers.
  * An application needs to communicate with one or more independently-developed applications or services, which may use different platforms, programming languages, and communication protocols.
  * An application can send information to consumers without requiring real-time responses from the consumers.
  * The systems being integrated are designed to support an eventual consistency model for their data.
  * An application needs to communicate information to multiple consumers, which may have different availability requirements or uptime schedules than the sender.
