ARG from=pyjulia/plain
FROM $from
#
# See:
# https://docs.docker.com/engine/reference/builder/#understand-how-arg-and-from-interact

ARG pip_options=""
ARG pyjulia_spec="julia[test]"
RUN pip install --upgrade ${pip_options} "${pyjulia_spec}"
