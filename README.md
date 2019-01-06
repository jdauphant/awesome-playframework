# awesome-playframework
A collaborative curated list of awesome Play Framework 2.X resources.
- All projects here should support Play 2.6 at mininum (expect for the last section).
- Don't hesitate to report new projects or errors in PR.

---
## Documentations
- [Play Documentation](https://www.playframework.com/documentation/2.6.x/Home) - Play is a high-productivity Java and Scala web application framework that integrates the components and APIs you need for modern web application development.
- [Play Modules](https://www.playframework.com/documentation/2.6.x/ModuleDirectory) - Public modules list managed by Play Project

## Examples
- [Boilerplay](https://github.com/KyleU/boilerplay) - Using the latest technology in the Scala ecosystem, Boilerplay is a reactive web application built on Play 2.6, ScalaJS, Silhouette 5, Sangria/GraphQL, and PostgreSQL. 
- [Play 2.6 and Slick 3.2](https://github.com/nemoo/play-slick3-example) - An example app using Play Framework 2.6 and Slick 3.2.
- [Play REST API](https://github.com/playframework/play-scala-rest-api-example) - Example Play Scala application showing REST API
- [Play Scala Secure Session Example](https://github.com/playframework/play-scala-secure-session-example) - Shows how to do simple secure session management in Play, using the Scala API and session cookies.
- [Play Scala Starter Example](https://github.com/playframework/play-scala-starter-example) - This is a starter application that shows how Play works. 
- [Play with Slick 3.1](https://github.com/playframework/play-scala-isolated-slick-example) - This project shows Play working with Slick.
- [Play Websocket](https://github.com/playframework/play-scala-websocket-example) - Example Play Scala application showing WebSocket use with Akka actors

## Libraries

### Databases
- [Anorm](https://github.com/playframework/anorm) - Anorm is a simple data access layer that uses plain SQL to interact with the database and provides an API to parse and transform the resulting datasets.
- [Flyway](https://github.com/flyway/flyway-play) - Flyway module for Play 2.4 or later. It aims to be a substitute for play-evolutions - Version control for your database. - Robust schema evolution across all your environments
- [Memcached Plugin](https://github.com/mumoshu/play2-memcached) - Memcached Plugin for Play framework 2.x
- [play-slick](https://github.com/playframework/play-slick) - Slick Plugin for Play - Functional Relational Mapping for Scala
- [ReactiveMongo for Play Framework](https://github.com/ReactiveMongo/Play-ReactiveMongo) - This is a plugin for Play Framework 2.4 and 2.5, enabling support for ReactiveMongo – a reactive, asynchronous and non-blocking Scala driver for MongoDB.
- [Redis Cache module](https://github.com/KarelCemus/play-redis) - Play framework 2 cache plugin as an adapter to redis-server

### Security/Authentification
- [jwt-scala](https://github.com/pauldijou/jwt-scala) - JWT support for Scala. Bonus extensions for Play, Play JSON.
- [Play reCAPTCHA Module](https://github.com/chrisnappin/play-recaptcha) - Module that provides reactive (non-blocking) integration with Google ReCaptcha.
- [Play2 Guard Module](https://github.com/sief/play-guard) - Play2 module for rate limiting, based on token bucket algorithm
- [Silhouette](https://github.com/mohiva/play-silhouette) - Silhouette is an authentication library for Play Framework applications that supports several authentication methods.

### Testing
- [Play MockWS](https://github.com/leanovate/play-mockws) - Play MockWS is a mock WS client for Play Framework.
- [ScalaTest Plus Play](https://github.com/playframework/scalatestplus-play) - ScalaTest + Play provides integration support between ScalaTest and Play Framework.

### Others
- [Pagelets](https://github.com/splink/pagelets) - Build modular applications in an elegant and concise manner.
- [Play JsMessages](https://github.com/julienrf/play-jsmessages) - This library allows you to compute localized messages on client-side, in Play projects.
- [play-html-compressor](https://github.com/mohiva/play-html-compressor) - Google's HTML Compressor for Play Framework 2
- [play-mailer](https://github.com/playframework/play-mailer) - Play Mailer is a powerful Scala Mailing library. It provides a simple configurable mailer.
- [play-metrics](https://github.com/kenshoo/metrics-play) - This module provides some support for @codahale Metrics library in a Play2 application (Scala)
- [play-s3](https://github.com/kaliber-scala/play-s3) - Amazon Simple Storage Service (S3) module for Play 2.6
- [Play2 SocksJS](https://github.com/fdimuccio/play2-sockjs) - A SockJS server implementation for Play Framework.

## Templates
- [Play Framework with Scala.js](https://github.com/vmunier/play-scalajs.g8) - This is a Giter8 template showing how you can integrate a Play project with a Scala.js project.
- [Slim Play App](https://github.com/lloydmeta/slim-play) - Wanna build a really, really slim Play project?


## Resources for old Play version (before 2.6)
- [AnormCypher](https://github.com/AnormCypher/AnormCypher) - Play 2.5 - Neo4j client library for the HTTP Cypher transactional endpoints.
- [Full Stack Scaka Starter](https://github.com/Algomancer/Full-Stack-Scala-Starter) - Play 2.5 - This is a simple example application showing how you can integrate a Play project with a Scala.js, Binding.scala project.
- [MongoDB Salat plugin](https://github.com/cloudinsights/play-salat) - Play 2.4 - Salat is a ORM for MongoDBs scala driver called Casbah.
- [Play Autosource](https://github.com/mandubian/play-autosource) - Play 2.3 - An automatic full REST + Typesafe CRUD abstract Datasource for bootstrapping a Play Framework App
- [Play Iteratees Extras](https://github.com/jroper/play-iteratees-extras) - Play 2.5 - This is an unofficial library for extra Play iteratees that you may find useful.
- [play2-auth](https://github.com/t2v/play2-auth) - Play 2.4 - Offers Authentication and Authorization features to Play2.x applications
- [Play2-HTML5Tags](https://github.com/loicdescotte/Play2-HTML5Tags) - Play 2.5 - This module brings client side validation attributes (required, max|min length, ...) and formats support (date, number, email, ...) to Play templates.
- [sample-applications](https://github.com/playforscala/sample-applications) - Play 2.1 - Sample applications that go with the book Play for Scala
- [sse-chat](https://github.com/matthiasn/sse-chat) - Play 2.3 - Chat example app using Server Sent Events plus REST calls. Scala, Play Framework 2.3, AngularJS or React (alternatively).
