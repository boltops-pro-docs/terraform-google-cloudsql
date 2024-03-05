<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-pro/terraform-google-cloudsql/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# CloudSQL

This module creates a CloudSQL database.

## Examples

An example stack is in the [examples/stacks/cloudsql](examples/stacks/cloudsql) folder. You can copy it to your app/stacks/cloudsql folder.

Configure tfvars for the cloudsql stack.

    app/stacks/cloudsql/tfvars
    ├── dev.tfvars
    └── prod.tfvars

    terraspace up cloudsql -y
    terraspace up cloudsql -i db-1 -y # additional instances of the cloudsql db

Add more tfvars files to create more cloudsql servers with different settings.

