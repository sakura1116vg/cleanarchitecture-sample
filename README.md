# cleanarchitecture-sample

Sample REST API demonstrating the clean architecture written in golang based on [hirotakan/go-cleanarchitecture-sample](https://github.com/hirotakan/go-cleanarchitecture-sample).

You can see below for more information on  implementation pattern.
- [en] [Go × Clean Architecture implementation pattern](https://medium.com/@nakabonne/go-clean-architecture-implementation-pattern-9fd5234bc5f2)
- [jp] [Go × Clean Architectureのサンプル実装](http://nakawatch.hatenablog.com/entry/2018/07/11/181453)

## Getting Started

### Installation

```
$ git clone https://github.com/nakabonne/cleanarchitecture-sample.git
```

### Running with docker

Required: Docker more than 17.05

```sh
$ docker-compose up -d
$ curl http://localhost:8080/hc
hello
```

## Tools required for development

- [Go1.11.0+](https://golang.org/dl/)
- [direnv](https://github.com/direnv/direnv)
- [gb](https://github.com/constabulary/gb)
