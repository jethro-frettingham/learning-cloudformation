aws cloudformation deploy \
  --template-file serverless-api.yaml \
  --stack-name my-serverless-api-dev \
  --parameter-overrides AlarmEmail=you@example.com \
  --capabilities CAPABILITY_NAMED_IAM