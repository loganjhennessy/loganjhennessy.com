# loganjhennessy.com

Personal website.

## Deployment steps

```
docker build -t gcr.io/logan-hennessy/loganjhennessy.com .
docker push gcr.io/logan-hennessy/loganjhennessy.com
sudo gcloud beta run deploy loganjhennessy.com --image gcr.io/logan-hennessy/loganjhennessy.com
```