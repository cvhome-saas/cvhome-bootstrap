### cvhome-bootstrap
*. an easy way to deploy cvhome with just few clicks.

## Quickly Deploy

Click the button below to deploy cvhome in your AWS account:

[![Launch Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?stackName=cvhome-bootstrap&templateURL=https://cvhome-saas.s3.eu-central-1.amazonaws.com/assets/bootstrap.yaml)

This will launch the CloudFormation stack in your current AWS region. You'll need to provide:
- **Domain Zone Id**: Select your Route53 hosted zone
- **Keycloak Admin Password**: Set a password for the Keycloak admin user (sys-admin@mail.com)
- **Stripe API Key**: (Optional) Your Stripe API key
- **Stripe Webhook Signing Key**: (Optional) Your Stripe webhook signing key
