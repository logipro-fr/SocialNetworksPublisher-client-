# Social Networks Publisher Client

A PHP component to interact with the SocialNetworksPublisher API in your PHP project.

**Social Networks Publisher** allows you to publish posts on various social networks.

## Features

### Available Methods
**Social Networks Publisher Client** provides the following public methods:

* `publishOnSocialNetworks(string $socialNetworks, string $text, string $hashtag): bool`: Publishes a post to the specified `socialNetworks` with the provided `text` and `hashtag`. Returns a boolean indicating success.

### Installation

```shell
composer require logipro/SmsSender-client
```

## To contribute to Sms Sender Client 
### Requirements:
* Docker
* Git
* A bash shell

### Unit tests
Run unit tests with:

```shell
bin/phpunit
```

### Integration tests
Run integration tests with:

```shell
bin/phpunit-integration
```
**integration tests can only be run if you have a running [weather](https://github.com/logipro-fr/SocialNetworksPublisher) instance**

### Quality
#### Some indicators:
* PHP CodeSniffer (PSR12)
* PHPStan level 9
* Test coverage = 100%
* Mutation Score Indicator (MSI) = 100%


#### Quick check with:
```shell
./codecheck
```


#### Check coverage with:
```shell
bin/phpunit --coverage-html var
```
Then, view the coverage report in your browser at 'var/index.html'.


#### Check infection with:
```shell
bin/infection
```
Then, view the infection report in your browser at 'var/infection.html'.