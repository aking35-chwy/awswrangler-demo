# awswrangler-demo

In addition to the ipy-notebook, you will need to create two configuration files

`aws_credentials.py`

```
aws_credentials = {
    "access_key_id": "[ACCESS_KEY]",
    "secret_access_key": "[SECRET_KEY]",
    "session_token": "[SESSION_TOKEN]",
    "region": "[REGION]"
}
```

`config.py`

```
database = "[DATACATALOG_NAME]"
ATHENA_QUERY_RESULTS_BUCKET = "[ATHENA_QUERY_OUTPUT_BUCKET]"
REPLENISHMENT_KMS_KEY = "[REPLEN_KMS_ARN]"
```
