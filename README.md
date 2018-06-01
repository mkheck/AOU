# AOU
Meta repository for second iteration of session/workshop: _Services Assemble! Apply MVP Principles to Create Microservices Without Chaos with Spring Cloud/Netflix OSS_

## Component repos

* [Configuration](https://github.com/mkheck/aou-config)
* [Spring Cloud Config service](https://github.com/mkheck/aou-config-service)
* [Eureka service registry](https://github.com/mkheck/aou-eureka-service)
* [Coffee (backing) service](https://github.com/mkheck/aou-coffee-service)
* [Edge service](https://github.com/mkheck/aou-edge-service)
* [Hystrix dashboard](https://github.com/mkheck/aou-hystrix-dashboard)

## Notes

* To clone this in one pass, you must issue this command to clone submodules as well:
```
git clone --recursive https://github.com/mkheck/AOU
```

* If you've already cloned the project & missed picking up the submodules, simply run this to set it right:
```
git submodule update --init --recursive
```

* Note that you can still clone all projects independently by following the links above to each individual repo
* Comment/remove Spring Cloud Stream (RabbitMQ) related code from Coffee & Edge services if not using async/MQ capabilities

## Contact information

* Mark Heckler
* @MkHeck
* mark.heckler@gmail.com