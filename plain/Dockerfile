FROM python
ARG JULIA_VERSION
ENV JULIA_VERSION ${JULIA_VERSION:-1.0}
RUN curl https://raw.githubusercontent.com/JuliaCI/install-julia/master/install-julia.sh | bash -s $JULIA_VERSION
