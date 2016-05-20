### for DelayedJob
- Custom JSON設定
```
}
  "delayed_job": {
    "pool_size": 1
  }
}
```

### for PaperTrail
- Custom JSON設定
```
{
  "remote_syslog2": {
    "files": ["/srv/www/rails/current/log/production.log", "/srv/www/rails/current/log/batch.log"],
    "exclude_patterns": [],
    "destination": {
      "host": "logs.papertrailapp.com",
      "port": "12345"
    }
  }
}
```

- Custom Chef Recipe
https://github.com/otelic/papertrail-cookbook#attributes
