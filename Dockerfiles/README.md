# Docker Files

To push new images up to Docker hub

1. `docker login`
2. `docker build -f Dockerfile-py3.12-win64 . --platform=linux/amd64 -t jackmckew/pyinstaller-windows:3.12 -t jackmckew/pyinstaller-windows:latest && docker push jackmckew/pyinstaller-windows:3.12 && docker push jackmckew/pyinstaller-windows:latest`