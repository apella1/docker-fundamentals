# Docker Fundamentals

## Images

- When no version is provided, the latest version is used by default

## COPY vs ADD

- COPY is used to copy files from the host machine to the container
- ADD is used to copy files from the host machine to the container and also to extract tar files

## CMD vs ENTRYPOINT vs RUN

- CMD is used to run a command when the container is started
- ENTRYPOINT is used to run a command when the container is started and also to run a command when the container is stopped
- RUN is used to run a command when the image is built

## Notes

- Overriding commands
- Building from remote sources
