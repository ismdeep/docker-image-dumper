# Docker Image Dumper

This project is a GitHub action for user to dump docker image and transfer to target server via scp command line.

You can just fork this repository and add GitHub action secrets and variables to use.

GitHub action secrets:

- `SERVER_ADDR` target server address, required.
- `SERVER_PORT` target server port, default: 22, optional.
- `SERVER_USER` target server user, default: root, optional.
- `SERVER_PASSWORD` target server password, required.
- `SERVER_PATH` target server path, required.

GitHub action variables:

- `EXPOSE_URL` output url link in job.