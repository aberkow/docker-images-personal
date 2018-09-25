A base node image for creating other images. It creates

- A `/project` directory for relevant files
- An entrypoint script that can be overriden by mounting a new one
- An open port at 3000

It then executes the entrypoint script.