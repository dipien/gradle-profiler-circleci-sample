# Gradle Profiler & CircleCi sample
Sample Integration between Gradle Profiler & Circle CI


### How to run Gradle Profiler

```
curl --request POST \
 --url https://${CIRCLE_CI_TOKEN}:@circleci.com/api/v2/project/gh/dipien/gradle-profiler-circleci-sample/pipeline \
 --header 'content-type: application/json' \
 --data '{"branch":"${BRANCH_NAME}","parameters":{"api":true, "gradleProfiler":true}}'
 ```
