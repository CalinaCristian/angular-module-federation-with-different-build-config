# Purpose
This is a module federation in angular demo where I try to see what happens if you have different build configurations (aot: false on remote app, aot: true on host).

Behavior: The host app fails to inject the remote app and throws a JIT error.

# How to run
These are two separate angular projects.

In order to start them, go to host -> npm i and npm start and do the same for remote.

