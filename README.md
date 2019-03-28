## Using the docker image

You can run `mender-artifact` with bind mounting using the following command:

```sh
./mender-artifact <args>
```

Or directly with docker:

```sh
docker run -it --rm -v $(pwd):$(pwd) -w $(pwd) outstand/mender-artifact:latest <args>
```
