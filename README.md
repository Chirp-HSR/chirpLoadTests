# Chirp Load Tests

Gatling load tests to benchmark the Chirp service.

## Getting Started

The following software must be available to setup and run the Chirp service:

* JDK 8 or newer
* Maven 3 or newer

### Setup

Just checkout this repository: `git clone https://github.com/Chirp-HSR/chirpLoadTests.git`

### Start Benchmark

The uri of the chirp instance under test can be configured in `src/test/scala/ChirpLoadTest.scala` by changing the `chirpUrl` value accordingly.

Afterwards, the load tests can be started with `mvn gatling:execute`.
