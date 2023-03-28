### ARG

ARG is used to supply few variables at the Image creation.
ARG is the only instruction you can use before FROM.
ARG declared before can't be accessed after FROM.

### Using ENV and ARG for Best Results:
* Create one ENV variable and assign the value of ARG to that.
* Then we can access ARG values through ENV both in image and container.