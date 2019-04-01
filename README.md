# Software Versions
## RabbitMQ

- Software Name: RabbitMQ
- Classification: Public
- Software Version: 3.7.14
- Package Type (COTS, GOTS or Unknown): COTS
- Supported ISR Mission System: MISS/Madlet
- Functionality/Purpose (paragraph): Provides a distributed queuing service for the application framework.
- Justification/Mission Impact (paragraph): Provides a means of communication between distributed service components within the application framework.  Improves applications stability, scalability, and fault tolerance.
- Operating System: Linux
- Country of Origin: US
- Open Source? Yes
- Type Software (Freeware, Shareware, Demoware, Trialware, Other): Freeware
- Is current or previous version of software on an APL/EPL? No
- If yes, where?
- If yes, what version?
- If software has been through Security Vulnerability evaluation list the testing, tools used: None
- Is there support for providing security-related fixes or a history of security fixes? yes
- Has the application undergone and been approved for use through an A&A process within the DoD or US federal gov’t? No
- Are there known security weaknesses associated with this software? No
- Vendor name: Pivotal Software ( https://pivotal.io )
- Vendor address: 875 Howard Street, San Francisco, CA 94103
- Technical POC name: 
- Technical POC organization: 
- Technical POC phone: 
- Technical POC email: 
- Notes:
- Tracking/Shipping Number:
- Others to Notify:

## Erlang 

- Software Name: Erlang
- Classification: Public
- Software Version: 20.3
- Package Type (COTS, GOTS or Unknown): COTS
- Supported ISR Mission System: MISS/Madlet
- Functionality/Purpose (paragraph): Provides the underlying runtime for the RabbitMQ queuing software.
- Justification/Mission Impact (paragraph): This runtime is highly scalable, and extremely fault tolerant.  
- Operating System: Linux
- Country of Origin: Europe
- Open Source? Yes
- Type Software (Freeware, Shareware, Demoware, Trialware, Other): Freeware
- Is current or previous version of software on an APL/EPL? No
- If yes, where?
- If yes, what version?
- If software has been through Security Vulnerability evaluation list the testing, tools used: None
- Is there support for providing security-related fixes or a history of security fixes? Yes
- Has the application undergone and been approved for use through an A&A process within the DoD or US federal gov’t? No
- Are there known security weaknesses associated with this software? No
- Vendor name: Ericcson ( https://www.ericsson.com/en ) , Various 
- Vendor address: 6300 Legacy Drive Plano, TX 75024
- Technical POC name: 
- Technical POC organization:
- Technical POC phone:
- Technical POC email:
- Notes:
- Tracking/Shipping Number:
- Others to Notify:

## NodeJS

- Software Name: NodeJS
- Classification: Public
- Software Version: 11.13.0
- Package Type (COTS, GOTS or Unknown): COTS
- Supported ISR Mission System: MISS/Madlet
- Functionality/Purpose (paragraph): This software provides the overall runtime for various custom application specific components that are not third party software.
- Justification/Mission Impact (paragraph): This software is used by many open source and production quality products.  It's use provides a simpler overal deployment model and a high qualityruntime for the underlying software.
- Operating System: Linux
- Country of Origin: US
- Open Source? Yes
- Type Software (Freeware, Shareware, Demoware, Trialware, Other): Freeware
- Is current or previous version of software on an APL/EPL? No
- If yes, where?
- If yes, what version?
- If software has been through Security Vulnerability evaluation list the testing, tools used: None
- Is there support for providing security-related fixes or a history of security fixes? Yes
- Has the application undergone and been approved for use through an A&A process within the DoD or US federal gov’t? No
- Are there known security weaknesses associated with this software? No
- Vendor name: Various ( Open Source ) Joyent ( Enterprise Support, https://www.joyent.com/ ) 
- Vendor address: 
- Technical POC name:
- Technical POC organization:
- Technical POC phone:
- Technical POC email:
- Notes:
- Tracking/Shipping Number:
- Others to Notify:

## Amqplib

- Software Name: Amqplib
- Classification: Public
- Software Version: 0.5.3
- Package Type (COTS, GOTS or Unknown): COTS
- Supported ISR Mission System: MISS/Madlet
- Functionality/Purpose (paragraph): This software provides the custom component's interface to the RabbitMQ queuing software.
- Justification/Mission Impact (paragraph): The software provides a quality controlled, community assessed component that is already being used as the NodeJs interface to AMQP-based queuing systems such as RabbitMQ.
- Operating System: Linux
- Country of Origin: US
- Open Source? Yes
- Type Software (Freeware, Shareware, Demoware, Trialware, Other): Freeware
- Is current or previous version of software on an APL/EPL? No
- If yes, where?
- If yes, what version?
- If software has been through Security Vulnerability evaluation list the testing, tools used: None
- Is there support for providing security-related fixes or a history of security fixes? Yes
- Has the application undergone and been approved for use through an A&A process within the DoD or US federal gov’t? No
- Are there known security weaknesses associated with this software? No
- Vendor name: Various
- Vendor address:
- Technical POC name: Michael Bridgen
- Technical POC organization:
- Technical POC phone:
- Technical POC email:
- Notes:
- Tracking/Shipping Number:
- Others to Notify:

## Redis

- Software Name: Redis
- Classification: Public
- Software Version: 5.0.4
- Package Type (COTS, GOTS or Unknown): COTS
- Supported ISR Mission System: MISS/Madlet
- Functionality/Purpose (paragraph): This software provides an in-memory, unstructured database.
- Justification/Mission Impact (paragraph): This software provides a scalable, simple, high quality means of storing and communicating state information between service components in non-durable, but high speed system using various well known data structures.
- Operating System: Linux
- Country of Origin: US
- Open Source? Yes
- Type Software (Freeware, Shareware, Demoware, Trialware, Other): Freeware
- Is current or previous version of software on an APL/EPL? No
- If yes, where?
- If yes, what version?
- If software has been through Security Vulnerability evaluation list the testing, tools used: None
- Is there support for providing security-related fixes or a history of security fixes? Yes
- Has the application undergone and been approved for use through an A&A process within the DoD or US federal gov’t? No
- Are there known security weaknesses associated with this software? No
- Vendor name: Redis Labs ( https://redislabs.com/ )
- Vendor address: 700 E El Camino Real Suite 250, Mountain View, CA 94040
- Technical POC name:
- Technical POC organization:
- Technical POC phone:
- Technical POC email:
- Notes:
- Tracking/Shipping Number:
- Others to Notify:

## S4 Client

- Software Name: S4 Client
- Classification: None
- Software Version: 1.0.0.0
- Package Type (COTS, GOTS or Unknown): Software
- Supported ISR Mission System: MISS/Madlet
- Functionality/Purpose (paragraph): This software provides a service for communicating with the MSSS Sump publish/subscribe server.
- Justification/Mission Impact (paragraph): This service converts previously formatted S-expression messages into more understandable JSON messages for other services within the application framework to consume.
- Operating System: Linux
- Country of Origin: US
- Open Source? No
- Type Software (Freeware, Shareware, Demoware, Trialware, Other): Proprietary
- Is current or previous version of software on an APL/EPL? No
- If yes, where?
- If yes, what version?
- If software has been through Security Vulnerability evaluation list the testing, tools used:
- Is there support for providing security-related fixes or a history of security fixes? Yes
- Has the application undergone and been approved for use through an A&A process within the DoD or US federal gov’t? No
- Are there known security weaknesses associated with this software? Does not use TLS for communication between components.
- Vendor name: Pacific Defense Solutions
- Vendor address: 535 Lipoa Pkwy #101, Kihei, HI 96753
- Technical POC name: Jason Hirata
- Technical POC organization: Pacific Defense Solutions
- Technical POC phone: 808-330-0364
- Technical POC email: jhirata@integrity-apps.com
- Notes:
- Tracking/Shipping Number:
- Others to Notify:

## HTTP Api

- Software Name: HTTP Api
- Classification: None
- Software Version: 1.0.0.0
- Package Type (COTS, GOTS or Unknown): Software
- Supported ISR Mission System: MISS/Madlet
- Functionality/Purpose (paragraph): This software provides a ReSTful interface to the RabbitMQ service customized for the MISS/Madlet deployment.
- Justification/Mission Impact (paragraph): This software enables components on the application frameork to communicate in the more widely used HTTP protocol instead of the AMQP protocol used by RabbitMQ.
- Operating System: Linux
- Country of Origin: US
- Open Source? No
- Type Software (Freeware, Shareware, Demoware, Trialware, Other): Proprietary
- Is current or previous version of software on an APL/EPL? No
- If yes, where?
- If yes, what version?
- If software has been through Security Vulnerability evaluation list the testing, tools used:
- Is there support for providing security-related fixes or a history of security fixes? Yes
- Has the application undergone and been approved for use through an A&A process within the DoD or US federal gov’t? No
- Are there known security weaknesses associated with this software? Does not use TLS for communication between components.
- Vendor name: Pacific Defense Solutions
- Vendor address: 535 Lipoa Pkwy #101, Kihei, HI 96753
- Technical POC name: Jason Hirata
- Technical POC organization: Pacific Defense Solutions
- Technical POC phone: 808-330-0364
- Technical POC email: jhirata@integrity-apps.com
- Notes:
- Tracking/Shipping Number:
- Others to Notify:

## Tensorflow API

- Software Name: Tensorflow API
- Classification: None
- Software Version: 1.0.0.0
- Package Type (COTS, GOTS or Unknown): Software
- Supported ISR Mission System: MISS/Madlet
- Functionality/Purpose (paragraph): This software listens for JSON messages from the RabbitMQ queuing service that need to be processed by SatNet.
- Justification/Mission Impact (paragraph): This software allows more standardized distributed components to receive incoming processing request rather than to have to customize a AMQP protocol based interface.
- Operating System: Linux
- Country of Origin: US
- Open Source? No
- Type Software (Freeware, Shareware, Demoware, Trialware, Other): Proprietary
- Is current or previous version of software on an APL/EPL? No
- If yes, where?
- If yes, what version?
- If software has been through Security Vulnerability evaluation list the testing, tools used:
- Is there support for providing security-related fixes or a history of security fixes? Yes
- Has the application undergone and been approved for use through an A&A process within the DoD or US federal gov’t? No
- Are there known security weaknesses associated with this software? Does not use TLS for communication between components.
- Vendor name: Pacific Defense Solutions
- Vendor address: 535 Lipoa Pkwy #101, Kihei, HI 96753
- Technical POC name: Jason Hirata
- Technical POC organization: Pacific Defense Solutions
- Technical POC phone: 808-330-0364
- Technical POC email: jhirata@integrity-apps.com
- Notes:
- Tracking/Shipping Number:
- Others to Notify:

## SatNet Results Server

- Software Name: SatNet Results Server
- Classification: None
- Software Version: 1.0.0.0
- Package Type (COTS, GOTS or Unknown): Software
- Supported ISR Mission System: MISS/Madlet
- Functionality/Purpose (paragraph): This service receives messages that are processed by SatNet and converts them into messages destined for the Sump Publish/Subscribe server.
- Justification/Mission Impact (paragraph): This service is needed to convert the more standardized JSON messages and HTTP protocol into S-expressions.  This component removes a direct dependency on any post-processing components.
- Operating System: Linux
- Country of Origin: US
- Open Source? No
- Type Software (Freeware, Shareware, Demoware, Trialware, Other): Proprietary
- Is current or previous version of software on an APL/EPL? No
- If yes, where?
- If yes, what version?
- If software has been through Security Vulnerability evaluation list the testing, tools used:
- Is there support for providing security-related fixes or a history of security fixes? Yes
- Has the application undergone and been approved for use through an A&A process within the DoD or US federal gov’t? No
- Are there known security weaknesses associated with this software? Does not use TLS for communication between components.
- Vendor name: Pacific Defense Solutions
- Vendor address: 535 Lipoa Pkwy #101, Kihei, HI 96753
- Technical POC name: Jason Hirata
- Technical POC organization: Pacific Defense Solutions
- Technical POC phone: 808-330-0364
- Technical POC email: jhirata@integrity-apps.com
- Notes:
- Tracking/Shipping Number:
- Others to Notify:


