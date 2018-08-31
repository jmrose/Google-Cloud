

## App Engine

### Deploy
> gcloud app deploy [DEPLOYABLES …] [--bucket=BUCKET] [--image-url=IMAGE_URL] [--no-promote] [--no-stop-previous-version] [--version=VERSION, -v VERSION] [GCLOUD_WIDE_FLAG …]

* [gcloud app deploy](https://cloud.google.com/sdk/gcloud/reference/app/deploy)
* [gcloud beta app deploy](https://cloud.google.com/sdk/gcloud/reference/beta/app/deploy)
* gcloud beta functions deploy
* gcloud builds submit
* gcloud container builds submit
* gcloud beta debug source upload

### app.yaml

[Reference](https://cloud.google.com/appengine/docs/standard/python3/config/appref)

```
### app.yaml - Sample

runtime: python37
instance_class: F2

env_variables:
  BUCKET_NAME: "example-gcs-bucket"

handlers:
# Matches requests to /images/... to files in static/images/...
- url: /images
  static_dir: static/images

- url: /.*
  secure: always
  redirect_http_response_code: 301
  script: auto
```


### Pycharm Google App Engine Project

$ gcloud components install app-engine-python
