## serverless framework
https://www.serverless.com/
### deploy

```shell
$ sls deploy
```

### exec function

#### local

```shell
$ sls invoke local --function ${function_name} --data ${sample_string}
```

#### aws

```shell
$ sls invoke --function ${function_name} --data ${sample_string}
```