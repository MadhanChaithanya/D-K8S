### STOPSIGNAL

STOPSIGNAL is used to how to exit the container.
* by default docker request for exit and wait for sometime.
* if it is not exiting it can force kill.
* when your container received STOPSIGNAL your application can perform
    * you can close db connections.
    * you can do some backup