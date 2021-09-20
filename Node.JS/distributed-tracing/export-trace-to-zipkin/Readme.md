This folder contains an example about exporting traces to Zipkin.

# Commands

- Start service

``` shell
# Running app with tracing code loaded
node --require './tracing.js' app.js
```

- Run Zipkin

``` shell
# Run Zipkin with docker
docker run --rm \
-d \
-p 9411:9411 \
--name zipkin \
openzipkin/zipkin
```



# Reference

- [Getting started with OpenTelemetry JS](https://github.com/open-telemetry/opentelemetry-js/blob/main/getting-started/README.md)

- [opentelemetry-js/getting-started/example/](https://github.com/open-telemetry/opentelemetry-js/tree/main/getting-started/example)

    > Reference this for a simple microservice example.
