# shipa-django-sample

This is the example project used in the guide ["Python Application"](https://shipa.readme.io/docs/python-application).

## Configuration

Before deploying this application to Shipa, users need to add the host/domain name to `ALLOWED_HOSTS` configuration in `blog/settings.py`:

```
ALLOWED_HOSTS = ['my-app.cloud.example.com', 'example.domain.net', 'lvh.me']
```

To run locally, you can use `lvh.me` domain.
