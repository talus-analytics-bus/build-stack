# Build-Stack

Repository for the `build-stack.yaml` cloudformation template which is used to deploy Talus Analytics' standardized four-environment frontend deployment setup.

Example Setup Command:

```sh
aws cloudformation deploy --stack-name [projectname] --template-file build-stack.yaml --capabilities CAPABILITY_NAMED_IAM
```
