## bjacobel/lynx-ssl
Provides a Lynx browser built with SSL support.

This image is configured to visit a single url and exit, dumping its view to the console. To override this behavior, inherit `FROM` this image and customize the `ENTRYPOINT`.

### Use

    docker run --rm bjacobel/lynx-ssl https://www.google.com
