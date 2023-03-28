# ARG VERSION
# FROM almalinux:${VERSION}
# while running the above command user can override at docker run time.
# FROM almalinux:${VERSION:-8}
# to use default version value we can use this

# RUN echo "$VERSION"

# ARG VERSION
# FROM almalinux
# ARG GREETING
# RUN echo "$VERSION"
# RUN echo "$GREETING"

# ARG VERSION
# FROM almalinux
# ARG GREETING="Hello Good Afternoon"
# RUN echo "$VERSION"
# RUN echo "$GREETING"


ARG VERSION
FROM almalinux
ARG GREETING="Hello Good Afternoon"
ENV GREET=${GREETING}
RUN echo "$VERSION"
RUN echo "$GREETING"