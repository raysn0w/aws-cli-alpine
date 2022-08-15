[![raysn0w](https://circleci.com/gh/raysn0w/aws-cli-alpine.svg?style=shield)](https://app.circleci.com/pipelines/github/raysn0w/aws-cli-alpine)
## Usage:

```
COPY --from=raysn0w/aws-cli-alpine:latest /aws/aws-cli/ /usr/local/aws-cli/
COPY --from=raysn0w/aws-cli-alpine:latest /aws/bin/ /usr/local/bin/
```

## Source:

https://stackoverflow.com/questions/60298619/awscli-version-2-on-alpine-linux