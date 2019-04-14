[![Build Status][travis-img]][travis-url]

Examples

```
cd base
docker image build -t pyjulia/base .
docker image build -t pyjulia/base-1.1.0 --build-arg julia_version=1.1.0 .
docker run --rm -it pyjulia/base
```

[travis-img]: https://travis-ci.com/tkf/docker-pyjulia.svg?branch=master
[travis-url]: https://travis-ci.com/tkf/docker-pyjulia
