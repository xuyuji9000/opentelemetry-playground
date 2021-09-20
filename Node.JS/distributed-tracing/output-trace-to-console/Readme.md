This folder contains an example about exporting trace to console with Node.JS.

# Commands

- Add tracing dependencies

``` shell
npm install \
@opentelemetry/sdk-node \
@opentelemetry/api \
@opentelemetry/auto-instrumentations-node \
@opentelemetry/exporter-zipkin
```

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

- [Node.JS](https://opentelemetry.io/docs/js/getting_started/nodejs/#example-application)
    > This is an example

- [Data Sources / traces](https://opentelemetry.io/docs/concepts/data-sources/#traces)

- [Exporters / Zipkin](https://opentelemetry.io/docs/js/exporters/#zipkin)

- [Getting started with OpenTelemetry JS](https://github.com/open-telemetry/opentelemetry-js/blob/main/getting-started/README.md)
