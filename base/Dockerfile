ARG from=python
FROM $from
#
# See:
# https://docs.docker.com/engine/reference/builder/#understand-how-arg-and-from-interact

ARG JULIA_VERSION
ENV JULIA_VERSION ${JULIA_VERSION:-1.0}
RUN curl https://raw.githubusercontent.com/JuliaCI/install-julia/master/install-julia.sh | sed -E "s/\bsudo +//g" | bash -s $JULIA_VERSION
