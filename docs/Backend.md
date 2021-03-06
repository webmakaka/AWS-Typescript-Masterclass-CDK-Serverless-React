# [Alex Horea] AWS &amp; Typescript Masterclass - CDK, Serverless, React [ENG, 2021]

<br/>

## 03 Serverless project with CDK and Typescript

<br/>

### 003 AWS CDK Typescript project from scratch

    $ cd backend
    $ npm init -y
    $ npm install -D aws-cdk aws-cdk-lib constructs ts-node typescript

<br/>

### 004 CDK project implementation - part 2

    $ npx tsc --init
    $ cdk synth

```
Resources:
  CDKMetadata:
    Type: AWS::CDK::Metadata
***
```

<br/>

### 005 Basic AWS Lambda

    $ npm install @types/node
    $ cdk bootstrap
    $ cdk synth
    $ cdk deploy

<br/>

### 006 AWS API Gateway and Lambda

    $ cdk deploy

<br/>

![Application](/img/pic-m03-p01.png?raw=true)

<br/>

### 007 AWS DynamoDB with CDK

    $ cdk synth
    $ cdk deploy

<br/>

---

<br/>

**Marley**

Any questions in english: <a href="https://jsdev.org/chat/">Telegram Chat</a>  
Любые вопросы на русском: <a href="https://jsdev.ru/chat/">Телеграм чат</a>
