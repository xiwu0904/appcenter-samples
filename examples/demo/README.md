# Create a directory app from a Git repo

## Create a directory app
```bash
$ appcenter app create --name demo --repo https://github.com/haoshuwei/appcenter-samples.git --revision latest --path examples/demo --dest-namespace default --dest-server https://kubernetes.default.svc
$ appcenter app sync demo
```

## supported parameters

- `--sync-policy`

    Set the sync policy (one of: automated, none)

- `--directory-recurse`

    Recurse directory
    
- `--revision-history-limit`

    How many items to keep in revision history (default 10)