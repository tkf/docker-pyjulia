Examples

```
cd plain
docker image build -t pyjulia/plain .
docker image build -t pyjulia/plain-1.1.0 --build-arg JULIA_VERSION=1.1.0 .
docker run --rm -it pyjulia/plain
```
