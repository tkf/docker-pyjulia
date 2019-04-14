ARG from=pyjulia/base
FROM $from
#
# See:
# https://docs.docker.com/engine/reference/builder/#understand-how-arg-and-from-interact

RUN pip install julia
RUN python -c 'from julia import install; install()'
