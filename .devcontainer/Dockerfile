FROM mcr.microsoft.com/devcontainers/typescript-node:dev-18-bullseye
USER node
ENV BASH_ENV ~/.bashrc
ENV VOLTA_HOME=/home/node/.volta
ENV PATH $VOLTA_HOME/bin:$PATH
RUN curl https://get.volta.sh | bash
RUN volta install node@19.7.0
RUN volta install yarn@1.22.19
RUN volta install wrangler@2.12.3