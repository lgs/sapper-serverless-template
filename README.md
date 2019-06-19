# AWS Serverless Sapper

Boilerplate template for a universal Sapper app running on top of AWS Lambda and Amazon API Gateway.

## Build/deploy

```sh
npm install
npm run config -- \
  --account-id="<accountId>" \
  --bucket-name="<bucketName>" \
  --hostname="<hostname>" \
  --certificate-id="<certificateId>" \
  [--region="<region>"]
npm run setup
```

## Local sandbox

```sh
API_BASE_URL=<APIG URL> npm run dev
```

or:

```sh
npm run build
API_BASE_URL=<APIG URL> npm run start
```

## References

- [aws-serverless-express/basic-starter](https://github.com/awslabs/aws-serverless-express/tree/master/examples/basic-starter)
- [sapper-template](https://github.com/sveltejs/sapper-template)
