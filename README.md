# Collection of frameworks and libraries

Frameworks and Libraries for the development

## Messaging

- [RabbitMQ](https://www.rabbitmq.com/): popular open source message broker
- [RocketMQ](https://github.com/alibaba/spring-cloud-alibaba/wiki/RocketMQ-en): an open-source distributed message system. It is based on highly available distributed cluster technologies and provides message publishing and subscription service with low latency and high stability
- [ActiveMQ Artemis](https://activemq.apache.org/): an open source project to build a multi-protocol, embeddable, very high performance, clustered, asynchronous messaging system
- [Kafka](https://kafka.apache.org/): a distributed streaming platform
- [Pulsar](https://pulsar.apache.org/): an open-source distributed pub-sub messaging system originally created at Yahoo and now part of the Apache Software Foundation


## Streaming

- [Flink](https://flink.apache.org/): a framework and distributed processing engine for stateful computations over unbounded and bounded data streams
- [Spark](https://spark.apache.org/): a unified analytics engine for large-scale data processing
- [Storm](https://storm.apache.org/): a free and open source distributed realtime computation system
- [Spring Cloud Stream](https://spring.io/projects/spring-cloud-stream):  framework for building highly scalable event-driven microservices connected with shared messaging systems
- [Apache Samze](https://samza.apache.org/): a distributed stream processing framework
- [Google Dataflow](https://cloud.google.com/dataflow/): unified stream and batch data processing that's serverless, fast, and cost-effective.
- [Apache Beam](https://beam.apache.org/): implement batch and streaming data processing jobs that run on any execution engine.

## Serverless

- [Flink Statefun](https://flink.apache.org/stateful-functions.html): an API that simplifies building distributed stateful applications. It’s based on functions with persistent state that can interact dynamically with strong consistency guarantees.
- [Cloudstate](https://cloudstate.io/): allows developers to rapidly build stateful, highly scalable serverless applications.
- [Dapr](https://github.com/dapr/dapr): a portable, serverless, event-driven runtime that makes it easy for developers to build resilient, stateless and stateful microservices that run on the cloud and edge and embraces the diversity of languages and developer frameworks.
- [Argo](https://argoproj.github.io/): open source Kubernetes native workflows, events, CI and CD
- [TriggerMesh](https://triggermesh.com/): provides a real-time cloud native integration platform that allows you to connect services together to automate workflows and accelerate the flow of information across your organization.
- [Nats](https://nats.io/): a simple, secure and high performance open source messaging system for cloud native applications, IoT messaging, and microservices architectures.

## Protocol

### Misc

- [RSocket](https://rsocket.io/): Application protocol providing Reactive Streams semantics
- [Aeron](https://github.com/real-logic/aeron): efficient reliable UDP unicast, UDP multicast, and IPC message transport. Java and C++ clients are available in this repository, and a .NET client is available from a 3rd party. 
- []():
- []():
- []():

### RPC

- [Finagle](https://github.com/twitter/finagle):  an extensible RPC system for the JVM, used to construct high-concurrency servers
- [Dubbo](https://dubbo.apache.org/): a high-performance, java based open source RPC framework
- [gRPC](https://grpc.io/): a high-performance, open source universal RPC framework


## Java & Kotlin

### JDK

- [Amazon Corretto](https://aws.amazon.com/corretto): a no-cost, multiplatform, production-ready distribution of the Open Java Development Kit (OpenJDK)
- [AdaptOpenJDK](https://adoptopenjdk.net/): AdoptOpenJDK uses infrastructure, build und test scripts to produce prebuilt binaries from OpenJDK™ class libraries and a choice of either OpenJDK or the Eclipse OpenJ9 VM.
- [OpenJDK](https://github.com/openjdk): open-source JDK

### MicroServer

- [Helidon](https://helidon.io/#/): reactive WebServer provides a modern functional programming model and runs on top of Netty. From Oracle
- [Quarkus](https://quarkus.io/):  Kubernetes Native Java stack tailored for OpenJDK HotSpot and GraalVM, crafted from the best of breed Java libraries and standards. From RedHat
- [Micronaut](https://micronaut.io/): a modern, JVM-based, full-stack framework for building modular, easily testable microservice and serverless applications
- [Javalin](https://javalin.io/): a simple web framework for Java and Kotlin
- [Jooby](https://jooby.io/): is a modern, performant and easy to use web framework for Java and Kotlin built on top of your favorite web server.
- [Spark](http://sparkjava.com/): a micro framework for creating web applications in Kotlin and Java 8 with minimal effort
- [Spring Boot](https://spring.io/projects/spring-boot): Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can "just run".
- [Vert.x](https://vertx.io/): a tool-kit for building reactive applications on the JVM
- [Ratpack](https://ratpack.io/): a set of Java libraries for building scalable HTTP applications
- [JHipster](https://www.jhipster.tech/): a development platform to quickly generate, develop, & deploy modern web applications & microservice architectures.
- [http4k](https://www.http4k.org/): a lightweight but fully-featured HTTP toolkit written in pure Kotlin
- [Ktor](https://ktor.io/): a framework for building asynchronous servers and clients in connected systems using the powerful Kotlin programming language
- [Dropwizard](https://www.dropwizard.io/en/latest/): pulls together stable, mature libraries from the Java ecosystem into a simple, light-weight package that lets you focus on getting things done


### Serializer

- [Kryo](https://github.com/EsotericSoftware/kryo): a fast and efficient binary object graph serialization framework for Java
- [Avro](https://avro.apache.org/): a data serialization system.
- [Protocol Buffers](https://developers.google.com/protocol-buffers): Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data 
- [Jackson](https://github.com/FasterXML)
- [Boon](https://github.com/boonproject/boon/wiki/Boon-JSON-in-five-minutes): is the probably the fastest way to serialize and parse JSON in Java so far for your project
- [Gson](https://github.com/google/gson): a Java library that can be used to convert Java Objects into their JSON representation
- [fast-serialization](https://github.com/RuedigerMoeller/fast-serialization): up to 10 times faster 100% JDK Serialization compatible drop-in replacement
- [MicroStream](https://microstream.one/serialization): Next Generation Java Serialization
- [Thrift](http://thrift.apache.org/): scalable cross-language services development, combines a software stack with a code generation engine to build services that work efficiently and seamlessly between C++, Java, Python, PHP, Ruby, Erlang, Perl, Haskell, C#, Cocoa, JavaScript, Node.js, Smalltalk, OCaml and Delphi and other languages.

### Mapping

- [MapStruct](https://mapstruct.org/): a code generator that greatly simplifies the implementation of mappings between Java bean types based on a convention over configuration approach
- [Orika](https://github.com/orika-mapper/orika): a Java Bean mapping framework that recursively copies (among other capabilities) data from one object to another
- [fastJson](https://github.com/alibaba/fastjson): a Java library that can be used to convert Java Objects into their JSON representation. It can also be used to convert a JSON string to an equivalent Java object


### Docker Pluins

- [jib](https://github.com/GoogleContainerTools/jib): builds optimized Docker and OCI images for your Java applications without a Docker daemon - and without deep mastery of Docker best-practices
- [Docker Gralde Plugin](https://github.com/palantir/gradle-docker): three Gradle plugins for working with Docker containers
- [Docker Maven Plugin](https://github.com/fabric8io/docker-maven-plugin): a Maven plugin for building Docker images and managing containers for integration tests
- [Gradle Docker Plugin](https://github.com/bmuschko/gradle-docker-plugin): Gradle plugin for managing Docker images and containers using the Docker remote API

### Misc

- [vavr](https://www.vavr.io/): vavr core is a functional library for Java. It helps to reduce the amount of code and to increase the robustness. 
- [Caffeine](https://github.com/ben-manes/caffeine): a high performance, near optimal caching library based on Java 8
- [HikariCP](https://github.com/brettwooldridge/HikariCP): a "zero-overhead" production ready JDBC connection pool. At roughly 130Kb, the library is very light
- [Bouny Castle](https://www.bouncycastle.org/): crypto library

### Query Languages

#### SQL

- [jOOQ](https://www.jooq.org/): generates Java code from your database and lets you build type safe SQL queries through its fluent API
- [Liquibase](https://www.liquibase.org/): an open source project that helps millions of developers rapidly manage database schema changes
- [Flyway](https://flywaydb.org/): Version control for your database. Robust schema evolution across all your environments

#### Misc

- [GraphQL](https://graphql.org/): a query language for APIs and a runtime for fulfilling those queries with your existing data
- [Cipher](https://neo4j.com/developer/cypher-basics-i/): Query language for Neo4j 

### Reactive

- [SmallRye Mutiny](https://smallrye.io/smallrye-mutiny/): a reactive programming library
- [Project Reactor](https://projectreactor.io/): a fourth-generation reactive library, based on the Reactive Streams
specification, for building non-blocking applications on the JVM
- [akka](https://akka.io/): a toolkit for building highly concurrent, distributed, and resilient message-driven applications for Java and Scala
- [RxJava](https://github.com/ReactiveX/RxJava): a Java VM implementation of Reactive Extensions: a library for composing asynchronous and event-based programs by using observable sequences

### Testing

- [WireMock](http://wiremock.org/): a simulator for HTTP-based APIs. Some might consider it a service virtualization tool or a mock server. 
- [MockServer](https://www.mock-server.com/): easy mocking of any system you integrate with via HTTP or HTTPS
- [Testcontainers](https://www.testcontainers.org/): a Java library that supports JUnit tests, providing lightweight, throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container.
- [AssertJ](https://assertj.github.io/doc/): fluent assertions java library
- [Mockito](https://site.mockito.org/): mocking framework for unit tests in Java
- [JUnit 5](https://junit.org/junit5/): the next generation of JUnit
- [Togglz](https://www.togglz.org/): Feature Flags for the Java platform
- [ArchUnit](https://www.archunit.org/): a free, simple and extensible library for checking the architecture of your Java code using any plain Java unit test framework.
- [JBehave](https://jbehave.org/): a framework for Behaviour-Driven Development (BDD). 

### UI

- [PrimeFace](https://www.primefaces.org/): a lightweight library with one jar, zero-configuration and no required dependencies
- [Wicket](https://wicket.apache.org/): open source Java web framework servicing websites and applications 

### Template Engines

- [Rocker](https://github.com/fizzed/rocker): a Java 8 optimized (runtime compat with 6+), near zero-copy rendering, speedy template engine that produces statically typed, plain java object templates that are compiled along with the rest of your project.
- [Thymeleaf](https://www.thymeleaf.org/): a modern server-side Java template engine for both web and standalone environments.
- [Freemarker](https://freemarker.apache.org/): a Java library to generate text output (HTML web pages, e-mails, configuration files, source code, etc.) based on templates and changing data
- [Velocity](https://velocity.apache.org/): a Java-based template engine. It permits anyone to use a simple yet powerful template language to reference objects defined in Java code.

## ByteCode

- [ByteBuddy](https://bytebuddy.net/#/): a code generation and manipulation library for creating and modifying Java classes during the runtime of a Java application and without the help of a compiler
- [ASM](https://asm.ow2.io/): an all purpose Java bytecode manipulation and analysis framework

## Machine Learning & AI

### Mix

- [PyCaret](https://pycaret.org/): an open source, low-code machine learning library in Python that allows you to go from preparing your data to deploying your model within minutes in your choice of notebook environment
- [PyTorch](https://pytorch.org/): an open source machine learning framework that accelerates the path from research prototyping to production deployment
- [Pandas](https://pandas.pydata.org/): a fast, powerful, flexible and easy to use open source data analysis and manipulation tool,
built on top of the Python programming language
- [NumPy](https://numpy.org/): fundamental package for scientific computing with Python
- [TensorFlow](https://www.tensorflow.org/): an end-to-end open source machine learning platform
- [Keras](https://keras.io/): an API designed for human beings, not machines. Keras follows best practices for reducing cognitive load
- [MXNet](https://mxnet.apache.org/versions/1.6/): a open source deep learning framework suited for flexible research prototyping and production.
- [Singa](https://singa.apache.org/): focusing on distributed training of deep learning and machine learning models

### JavaScript

- [Danfo](https://github.com/opensource9ja/danfojs): an open source, JavaScript library providing high performance, intuitive, and easy to use data structures for manipulating and processing structured data.
- [Tensorflow](https://www.tensorflow.org/js): a library for machine learning in JavaScript
- []():

### Java

- [DL4J](https://deeplearning4j.org/): the first commercial-grade, open-source, distributed deep-learning library written for Java and Scala
- [Weka](https://www.cs.waikato.ac.nz/ml/weka/): open source machine learning software that can be accessed through a graphical user interface, standard terminal applications, or a Java API
- [MOA](https://github.com/Waikato/moa): the most popular open source framework for data stream mining, with a very active growing community

## JavaScript

### Misc

- [Leafletjs](https://leafletjs.com/): an open-source JavaScript library for mobile-friendly interactive maps
- [fullPage](https://alvarotrigo.com/fullPage/): open-source library helps you create full-screen scrolling websites
- [anime](https://animejs.com/): a lightweight JavaScript animation library with a simple, yet powerful API
- [screenfull](https://github.com/sindresorhus/screenfull.js): simple wrapper for cross-browser usage of the JavaScript Fullscreen API, which lets you bring the page or any element into fullscreen
- [Moment.js](https://momentjs.com/): parse, validate, manipulate, and display dates and times in JavaScript
- [Hammer](http://hammerjs.github.io/): lets you add multi-touch gestures to your Web Apps.
- [Masonry](https://masonry.desandro.com/): a JavaScript grid layout library
- [D3.js](https://d3js.org/): library for manipulating documents based on data
- [Slick](https://kenwheeler.github.io/slick/):  fully responsive, swipe-enabled, infinite looping, and more
- [Popper](https://popper.js.org/): provides a reliable and extensible positioning engine you can use to ensure all your popper elements are positioned in the right place.
- [Babel](https://babeljs.io/): a JavaScript compiler
- [Sanity](https://www.sanity.io/): he fastest, most flexible platform for delivering content to digital devices and products 


### Builder

- [Webpack](https://webpack.github.io/): a modern JavaScript tool that serves as a static module bundler
- [npm](https://www.npmjs.com/): build tool
- [Parcel](https://parceljs.org/): blazing fast, zero configuration web application bundler
- [Browserify](http://browserify.org/): lets you require('modules') in the browser by bundling up all of your dependencies
- [Brunch](https://brunch.io/): build tool
- [Rollup](https://rollupjs.org): a module bundler for JavaScript which compiles small pieces of code into something larger and more complex, such as a library or application.
 

### Repository Manager

- [Lerna](https://github.com/lerna/lerna): a tool for managing JavaScript projects with multiple packages.
- [Bit](https://github.com/teambit/bit): platform for collaborating on components
- [Nrwl-Nx](https://nx.dev/): a set of extensible dev tools for monorepos, which helps you develop like Google, Facebook, and Microsoft
- []():

### Rich Text Editor

- [summernote](https://summernote.org/): WYSIWYG editor
- [Quill](https://quilljs.com/): powerful rich text editor 


## Testing

- [Karma](https://karma-runner.github.io/latest/index.html): the main goal for Karma is to bring a productive testing environment to developers
- [Jasmine](https://jasmine.github.io/): behavior-Driven JavaScript
- [Selenium](https://www.selenium.dev/): a collection of language specific bindings to drive a browser
- [Jest](https://jestjs.io/): a delightful JavaScript Testing Framework with a focus on simplicity.
- [Nightwatch](https://nightwatchjs.org/): End-to-end testing, the easy way.
- [Cypress](https://www.cypress.io/): fast, easy and reliable testing for anything that runs in a browser. 

### Frameworks

- [Flutter](https://flutter.dev/): Google’s UI toolkit for building beautiful, natively compiled applications for mobile, web, and desktop from a single codebase.
- [React](https://reactjs.org/): JavaScript library for building user interfaces
- [Vue.js](https://vuejs.org/):  a progressive framework for building user interfaces.
- [Preact](https://preactjs.com/): fast 3kB alternative to React with the same modern API
- [Svelte](https://svelte.dev/): a radical new approach to building user interfaces
- [Meteor](https://www.meteor.com/): an open source platform for web, mobile, and desktop
- [Next.js](https://nextjs.org/):  a free and open source web application framework based on React.js, Node.js, webpack and Babel.js for building server-side rendered and/or static web applications using React
- [Nuxt.js](https://nuxtjs.org/): an open source framework based on Vue.js
- [Gatsby](https://www.gatsbyjs.org/): is a free and open source framework based on React that helps developers build blazing fast websites and apps
- [Node.js](https://nodejs.org/en/): a JavaScript runtime built on Chrome's V8 JavaScript engine
- [Express](https://expressjs.com/): fast, unopinionated, minimalist web framework for Node.js

### UI

- [Bootstrap](https://getbootstrap.com/): popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins
- [Material](https://material.io/): design system that helps teams build high-quality digital experiences.
- [Semantic](https://semantic-ui.com/): a development framework that helps create beautiful, responsive layouts using human-friendly HTML
- [Foundation](https://get.foundation/): most advanced responsive front-end framework in the world
- [Font Awesome](https://fontawesome.com/): get vector icons and social logos on your website
- [Bulma](https://bulma.io/): a free, open source CSS framework based on Flexbox

### Complete Stack

- [Next.js]():
- [Chakra UI](https://chakra-ui.com/): a simple, modular and accessible component library that gives you all the building blocks you need to build your React applications
- [Playroom](https://github.com/seek-oss/playroom): simultaneously design across a variety of themes and screen sizes, powered by JSX and your own component library.
- [Storybook](https://storybook.js.org/): an open source tool for developing UI components in isolation for React, Vue, Angular, and more
- [Playwright](https://github.com/microsoft/playwright): a Node library to automate Chromium, Firefox and WebKit with a single API.
- [Preconstruct](https://github.com/preconstruct/preconstruct): dev and build your code painlessly in monorepos
- [Manypkg](https://github.com/Thinkmill/manypkg): a linter for package.json files in Yarn, Bolt or pnpm monorepos
- [ESLint](https://eslint.org/): find and fix problems in your JavaScript code
- [Prettier](https://prettier.io/): an opinionated code formatter
