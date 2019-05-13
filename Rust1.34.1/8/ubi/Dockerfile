FROM registry.access.redhat.com/ubi8/ubi@sha256:12bec5ede6a1b6d23071a735c0d6d3ca59233da71e1a253497e28e52f327b06e

LABEL maintainer="Jordan Gregory <jordan@gregory-dev.io>" \
      repository="https://github.com/Gregory-Development/ubi-go" \
      version="1.0.0"

RUN curl https://sh.rustup.rs -o /tmp/rustup.sh \
  && sh /tmp/rustup.sh -y

ENV PATH=$PATH:$HOME/.cargo/bin

ENTRYPOINT ["/bin/bash"]