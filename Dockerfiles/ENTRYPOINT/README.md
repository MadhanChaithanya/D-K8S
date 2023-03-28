### ENTRYPOINT

ENTRYPOINT is also used to run the container just like CMD. But there are some few differences.

1. We can't override ENTRYPOINT, but we can override the ENTRYPOINT.
2. We can't override ENTRYPOINT, if you try to do so it will go and append to the ENTRYPOINT command.