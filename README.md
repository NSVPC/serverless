# serverless
serverless framework

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Installation
```
$ sudo apt update
$ sudo apt install nodejs
$ sudo apt install npm
$ sudo npm install -g serverless
$ serverless create --help
$ serverless
$ sls
```

## Configure aws credentials:
```
$ sls config credentials --provider aws --key AKxxxxxxxxxxxxx --secret 90xxxxxxxxxxxxxxxxxxxxxxx
```

## create project:
```
$ sls create --help
$ sls create --template aws-python3
$ sls create --template aws-nodejs
```

## Deploying functions + invoking them:
```
$ sls deploy
$ sls invoke --function hello
```


## Debug Logs
enable debug logs 
``` 
 $ export SLS_DEBUG=*
 ``` 
 disable sls debug log
 ``` 
 $ unset SLS_DEBUG
``` 
 

## References

[AWS Template Reference](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-reference.html)

[Videos-for-beginners](https://www.youtube.com/watch?v=lUTGk64jppM&list=PLzvRQMJ9HDiT5b4OsmIBiMbsPjfp4kfg3)

