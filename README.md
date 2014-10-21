### for DelayedJob
- Custom JSON設定
```
}
  "delayed_job": {
    "pool_size": 1, "path_to_script": "bin"
  }
}
```

### for PaperTrail
- Custom JSON設定
```
{
  "papertrail": {
    "destination": "logs.papertrailapp.com:[PORT]",
      "log_files": {
        "rails": "/srv/www/[APP_NAME]/shared/log/production.log",
        "batch": "/srv/www/[APP_NAME]/shared/log/batch.log"
      }
  }
}
```

- Custom Chef Recipe
https://github.com/otelic/opsworks_delayed_job#opsworks-set-up
