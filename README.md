This project creates a bucket and policies that can be used in other terraform projects


Usage:

Preview the changes to make

`terraform plan --var env_fqdn=$ENV.$DNS_BASE`

Apply them
`terraform apply --var env_fqdn=$ENV.$DNS_BASE`
