Examples

```
cd base
docker image build -t pyjulia/base .
docker image build -t pyjulia/base-1.1.0 --build-arg JULIA_VERSION=1.1.0 .
docker run --rm -it pyjulia/base
```
