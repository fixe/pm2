# Contributing to PM2

## Fire an issue

When you got an issue by using pm2, you will fire an issue on [github](https://github.com/Unitech/pm2). We'll be glad to help or to fix it but the more data you give the most fast it would be resolved. 
Please try following these rules it will make the task easier for you and for us:

#### 1) Search through issues if it hasn't been resolved yet
#### 2) Make sure that you provide following informations: 
  - pm2 version `pm2 --version`
  - nodejs version `node --version`
  - operating system

#### 3) Provide details about your issue:
  - What are the steps that brought me to the issue?
  - How may I reproduce this? (this isn't easy in some cases)
  - Are you using a cluster module? Are you trying to catch SIGTERM signals? With `code` if possible.

#### 4) Think global if your issue is too specific we might not be able to help

#### 5) Be clear and format issues with [markdown](http://daringfireball.net/projects/markdown/)
Note that we might understand english, german and french

#### 6) Use debugging functions:

```DEBUG=pm2:* PM2_DEBUG=true ./bin/pm2 --no-daemon start my-buggy-thing.js```

If your issue is flagged as `need data` be sure that there won't be any upgrade unless we can have enough data to reproduce. 
## Pull-Requests

@Todo
