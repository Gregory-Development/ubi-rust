FROM registry.access.redhat.com/ubi7/ubi-init@sha256:35a331c670a921ae6195d39d81468645384ea39b533296b813bf879658632fee

LABEL maintainer="Jordan Gregory <jordan@gregory-dev.io>" \
      repository="https://github.com/Gregory-Development/ubi-go" \
      version="1.0.0"

RUN curl https://sh.rustup.rs -o /tmp/rustup.sh \
  && sh /tmp/rustup.sh -y

ENV PATH=$PATH:$HOME/.cargo/bin

ENTRYPOINT ["/bin/bash"]