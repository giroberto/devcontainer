FROM cgr.dev/chainguard/wolfi-base:latest
RUN apk update
RUN apk add libstdc++ bash curl git
RUN curl -fsSL https://bun.sh/install | bash
RUN echo 'export BUN_INSTALL="$HOME/.bun"' >> /etc/profile.d/bun.sh
RUN echo 'export PATH="$BUN_INSTALL/bin:$PATH"' >> /etc/profile.d/bun.sh
WORKDIR /srv/app
