FROM mambaorg/micromamba:0.11.3

COPY env.yml /root/env.yml
RUN micromamba install -y -n base -f /root/env.yml && \
    micromamba clean -a -y
