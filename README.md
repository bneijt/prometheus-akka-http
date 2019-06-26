# prometheus-akka-http

[![Join the chat at https://gitter.im/lonelyplanet/prometheus-akka-http](https://badges.gitter.im/lonelyplanet/prometheus-akka-http.svg)](https://gitter.im/lonelyplanet/prometheus-akka-http?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/lonelyplanet/prometheus-akka-http.svg?branch=master)](https://travis-ci.org/lonelyplanet/prometheus-akka-http)
[![codecov](https://codecov.io/gh/lonelyplanet/prometheus-akka-http/branch/master/graph/badge.svg)](https://codecov.io/gh/lonelyplanet/prometheus-akka-http)
[![Download](https://api.bintray.com/packages/lonelyplanet/maven/prometheus-akka-http/images/download.svg) ](https://bintray.com/lonelyplanet/maven/prometheus-akka-http/_latestVersion)


Collection of utilities to allow exposing prometheus metrics from akka-http endpoint using the prometheus java client

    "com.lonelyplanet" %% "prometheus-akka-http" % "0.4.1"
    
You might need to also add our repository:

```
resolvers ++= Seq(
  Resolver.bintrayRepo("lonelyplanet", "maven")
)
```

### Example

Example project is available here: https://github.com/wlk/prometheus-akka-http-example

### Publishing

We use `bintray-sbt` plugin for publishing artifacts, to publish newer version of the library run:
```
sbt +publish
```

That's all what is required
