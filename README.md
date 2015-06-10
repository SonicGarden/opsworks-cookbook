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
    "remote_host": "logs2.papertrailapp.com",
    "remote_port": "[PORT]",
    "watch_files": {
      "/srv/www/[APP_NAME]/shared/log/production.log" : "rails" ,
      "/srv/www/[APP_NAME]/shared/log/batch.log" : "batch"
    }
  }
}
```

- Custom Chef Recipe
https://github.com/otelic/papertrail-cookbook#attributes
