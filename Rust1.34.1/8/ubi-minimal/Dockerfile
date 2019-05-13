FROM registry.access.redhat.com/ubi8/ubi-minimal@sha256:7b7a9336b681f779b239141db4fd27fed9a7cc50e7ef7a727fc9490559b4e1df

LABEL maintainer="Jordan Gregory <jordan@gregory-dev.io>" \
      repository="https://github.com/Gregory-Development/ubi-go" \
      version="1.0.0"

RUN curl https://sh.rustup.rs -o /tmp/rustup.sh \
  && sh /tmp/rustup.sh -y

ENV PATH=$PATH:$HOME/.cargo/bin

ENTRYPOINT ["/bin/bash"]