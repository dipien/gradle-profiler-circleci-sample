# Gradle Profiler & CircleCi sample
Sample Integration between Gradle Profiler & Circle CI


### How to run Gradle Profiler

```
curl --request POST \
 --url https://${CIRCLE_CI_TOKEN}:@circleci.com/api/v2/project/gh/dipien/gradle-profiler-circleci-sample/pipeline \
 --header 'content-type: application/json' \
 --data '{"branch":"${BRANCH_NAME}","parameters":{"api":true, "gradleProfiler":true}}'
 ```

## Sponsor this project

Sponsor this open source project to help us get the funding we need to continue working on it.

* [Donate cryptocurrency](http://coinbase.dipien.com/)
* [Donate with PayPal](http://paypal.dipien.com/)
* [Donate on Patreon](http://patreon.dipien.com/)
* [Become a member of Medium](https://maxirosson.medium.com/membership) [We will receive a portion of your membership fee]

## Follow us
* [Twitter](http://twitter.dipien.com)
* [Medium](http://medium.dipien.com)
* [Instagram](http://instagram.dipien.com)
* [Pinterest](http://pinterest.dipien.com)
* [GitHub](http://github.dipien.com)
