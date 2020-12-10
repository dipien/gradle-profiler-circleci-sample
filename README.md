# Gradle Profiler & CircleCi sample
Sample Integration between Gradle Profiler & Circle CI


### How to run Gradle Profiler

```
curl --request POST \
 --url https://${CIRCLE_CI_TOKEN}:@circleci.com/api/v2/project/gh/dipien/gradle-profiler-circleci-sample/pipeline \
 --header 'content-type: application/json' \
 --data '{"branch":"${BRANCH_NAME}","parameters":{"api":true, "gradleProfiler":true}}'
 ```

## Donations

Donations are greatly appreciated. You can help us to pay for our domain and this project development.

* [Donate cryptocurrency](http://coinbase.dipien.com/)
* [Donate with PayPal](http://paypal.dipien.com/)

## Follow us
* [Twitter](http://twitter.dipien.com)
* [Medium](http://medium.dipien.com)
* [Blog](http://blog.dipien.com)
