ARG from=python
FROM $from
#
# See:
# https://docs.docker.com/engine/reference/builder/#understand-how-arg-and-from-interact

ARG julia_version=1.0
RUN curl https://raw.githubusercontent.com/JuliaCI/install-julia/master/install-julia.sh | sed -E "s/\bsudo +//g" | bash -s $julia_version
