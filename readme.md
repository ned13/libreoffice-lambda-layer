# LibreOffice for AWS Lambda as a layer

> 95 MB LibreOffice to fit inside AWS Lambda Layer compressed with Brotli

Based on the [serverless-libreoffice](https://github.com/vladgolubev/serverless-libreoffice) project.

## Getting Started

You can add this layer to any Lambda function you want – no matter what runtime

Click on Layers and choose "Add a layer", and "Provide a layer version
ARN" and enter the following ARN.

```
arn:aws:lambda:us-east-1:764866452798:layer:libreoffice:9
```

See the table below for other supported regions.

Works well with [aws-lambda-libreoffice npm package](https://github.com/shelfio/aws-lambda-libreoffice)

## What does this layer contain?

This layer contains `lo.tar.br` file which is LibreOfficee v6.4.0.1 (https://github.com/vladgolubev/serverless-libreoffice/releases/tag/v6.4.0.1).

## Where is LibreOffice inside of Lambda?

It is at `/opt/lo.tar.br`.

## Version ARNs

### LibreOffice v6.4.0.1 (Amazon Linux 2)

Works with the following [AWS Lambda runtimes](https://docs.aws.amazon.com/lambda/latest/dg/lambda-runtimes.html) which run on Amazon Linux 2:

- nodejs12.x
- nodejs10.x
- python3.8
- java11

| AWS Region     | LibreOffice Version | Layer ARN                                                        |
| -------------- | ------------------- | ---------------------------------------------------------------- |
| us-east-1      | 6.4.0.1             | `arn:aws:lambda:us-east-1:764866452798:layer:libreoffice:9`      |
| eu-west-1      | 6.4.0.1             | `arn:aws:lambda:eu-west-1:764866452798:layer:libreoffice:2`      |
| eu-central-1   | 6.4.0.1             | `arn:aws:lambda:eu-central-1:764866452798:layer:libreoffice:2`   |
| us-west-2      | 6.4.0.1             | `arn:aws:lambda:us-west-2:764866452798:layer:libreoffice:2`      |
| us-east-2      | 6.4.0.1             | `arn:aws:lambda:us-east-2:764866452798:layer:libreoffice:2`      |
| ap-southeast-2 | 6.4.0.1             | `arn:aws:lambda:ap-southeast-2:764866452798:layer:libreoffice:2` |
| eu-west-2      | 6.4.0.1             | `arn:aws:lambda:eu-west-2:764866452798:layer:libreoffice:2`      |
| ap-southeast-1 | 6.4.0.1             | `arn:aws:lambda:ap-southeast-1:764866452798:layer:libreoffice:2` |
| ap-south-1     | 6.4.0.1             | `arn:aws:lambda:ap-south-1:764866452798:layer:libreoffice:2`     |
| ca-central-1   | 6.4.0.1             | `arn:aws:lambda:ca-central-1:764866452798:layer:libreoffice:1`   |

### LibreOffice 6.1.0.0.alpha0 (Amazon Linux 1)

Works with the following [AWS Lambda runtimes](https://docs.aws.amazon.com/lambda/latest/dg/lambda-runtimes.html) which run on Amazon Linux 2:

- nodejs8.10
- python3.7
- python3.6
- python2.7
- ruby2.5
- java8
- go1.x
- dotnetcore2.1

| AWS Region     | LibreOffice Version | Layer ARN                                                        |
| -------------- | ------------------- | ---------------------------------------------------------------- |
| us-east-1      | 6.1.0.0.alpha0      | `arn:aws:lambda:us-east-1:764866452798:layer:libreoffice:8`      |
| eu-west-1      | 6.1.0.0.alpha0      | `arn:aws:lambda:eu-west-1:764866452798:layer:libreoffice:1`      |
| eu-central-1   | 6.1.0.0.alpha0      | `arn:aws:lambda:eu-central-1:764866452798:layer:libreoffice:1`   |
| us-west-2      | 6.1.0.0.alpha0      | `arn:aws:lambda:us-west-2:764866452798:layer:libreoffice:1`      |
| us-east-2      | 6.1.0.0.alpha0      | `arn:aws:lambda:us-east-2:764866452798:layer:libreoffice:1`      |
| ap-southeast-2 | 6.1.0.0.alpha0      | `arn:aws:lambda:ap-southeast-2:764866452798:layer:libreoffice:1` |
| eu-west-2      | 6.1.0.0.alpha0      | `arn:aws:lambda:eu-west-2:764866452798:layer:libreoffice:1`      |
| ap-southeast-1 | 6.1.0.0.alpha0      | `arn:aws:lambda:ap-southeast-1:764866452798:layer:libreoffice:1` |
| ap-south-1     | 6.1.0.0.alpha0      | `arn:aws:lambda:ap-south-1:764866452798:layer:libreoffice:1`     |

## License

MIT © [Shelf](https://shelf.io)
