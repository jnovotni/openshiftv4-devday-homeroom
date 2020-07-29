Local Deployment Steps
----------------------

To build the workshop image locally using `docker` you would run:
```
docker build -t openshiftv4-devday:v0.0.8 .
```

To run the image, you would then use:

```
docker run --rm -p 10080:10080 openshiftv4-devday:v0.0.8
```

Open URL in web browser

```
http://localhost:10080/dashboard/
```