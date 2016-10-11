aws-lambda-with-ses
==============

AWS Lambda Service With SES

config-format.json 파일을 config.json 으로 파일명 변경 후 아래 내용을 수정하여 사용하면 됩니다.
```
{
  "aws": {
    "accessKeyId": "{INPUT AWS.ACCESS.KEY.ID}",
    "secretAccessKey": "{INPUT AWS.SECRET.ACCESS.KEY}",
    "region": "{INPUT AWS.REGION}"
  },
  "mail": {
    "from": "frommailaddress@email.com",
    "to": "tomailaddres@email.com",
    "cc": "cc@email.com, cc2@email.com",
    "subject": "{INPUT Subject}"
  }
}
```
