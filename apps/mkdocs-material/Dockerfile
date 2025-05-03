ARG TARGETPLATFORM
ARG VERSION
ARG CHANNEL

FROM squidfunk/mkdocs-material:${VERSION}

RUN \
	pip install mkdocs-awesome-nav \
    pip install mkdocs-git-revision-date-localized-plugin

LABEL org.opencontainers.image.source="https://github.com/squidfunk/mkdocs-material"
