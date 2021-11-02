# vue-dynamodb

### DynamoDB Local
----
+ 참고
```
    - https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/DynamoDBLocal.DownloadingAndRunning.html
    - https://docs.aws.amazon.com/ko_kr/sdk-for-javascript/v2/developer-guide/dynamodb-examples-using-tables.html
```

#### DynamoDB Local 실행
+ 실행 (해당 디렉토리)
```
    java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
```