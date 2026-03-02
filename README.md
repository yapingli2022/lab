CDK S3 project

Minimal AWS CDK (v2) TypeScript project that creates an S3 bucket.

Quickstart

1. Install dependencies: npm install
2. Build: npm run build
3. Bootstrap (once per account/region): cdk bootstrap aws://ACCOUNT-NUMBER/REGION
4. Deploy: npm run deploy

Notes

- Configure AWS credentials (AWS CLI or environment variables) before bootstrapping/deploying.
- To run the CDK app locally: npx ts-node --prefer-ts-exts bin/cdk-s3.ts
