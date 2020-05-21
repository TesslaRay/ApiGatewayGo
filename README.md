# Api Gateway in Go - iOLED Backend

[![iOLEDBackend](https://img.shields.io/badge/iOLED-Backend-%23783578.svg)](https://www.ioled.cl/)

This app is developed with Go and contains the entrance gates to the ioled backend.

## Execution and build

- **Build**:

  sudo docker build --tag api-gateway:1.0 .here

- **Execution**:
  sudo docker run --publish 3000:3080 --detach --name api-g api-gateway:1.0
