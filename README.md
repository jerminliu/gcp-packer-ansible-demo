# GCP Packer Ansible Demo

## Setup

1. Install Packer (see https://www.packer.io/intro/getting-started/install.html)
2. Create a GCP project
3. Create a service account with the "Compute Engine Admin (v1)" role
4. Update packer-template.json with your project ID and service account
5. Authenticate Packer to GCP (see https://www.packer.io/docs/builders/googlecompute.html#authentication)

## Run Demo
`cd debian-10`
`packer build packer-template.json`

