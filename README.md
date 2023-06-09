## Superset Wrapper
Easily deploy Superset on your local machine

## Getting Started
1. Create `.env` file & specify base image like this
    ```
    SUPERSET_IMAGE=apache/superset
    SUPERSET_VERSION=master
    ```
2. Deploy your app using `docker-compose`
    ```shell
    $ docker-compose up
    ```
3. Wait until `Superset` available, you can access superset on `http://localhost:8088`

## References
- Superset Official Website: https://superset.apache.org
- Superset Docker: https://hub.docker.com/r/apache/superset