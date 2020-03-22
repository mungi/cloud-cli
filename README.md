# cloud-cli

CLI tools for Public Cloud

## Usage

It is based on the build of [python:3.8-alpine](https://hub.docker.com/_/python/) docker image.


## Installed tools

- [Terraform](https://www.terraform.io/) (`terraform` : 0.12.24)
- [Packer](https://packer.io/) (`packer` : latest version when run the build)

- [AWS CLI](https://github.com/aws/aws-cli) (`aws` : latest version when run the build)
- [Azure CLI](https://docs.microsoft.com/cli/azure/what-is-azure-cli) (`az` : latest version when run the build)
- [Google Cloud SDK](https://cloud.google.com/sdk/) (`gcloud` : latest version when run the build, also included `gsutil` , `bq`, `anthoscli` )

- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) (`kubectl` : latest version when run the build)
- [helm](https://github.com/helm/helm) (`helm` : v3.1.2)
- [aws-iam-authenticator](https://github.com/kubernetes-sigs/aws-iam-authenticator) (`aws-iam-authenticator` : 0.5.0)
- [eksctl](https://github.com/weaveworks/eksctl) (`eksctl` : latest version when run the build)
- [ansible](https://docs.ansible.com/ansible) (`ansible` : latest version when run the build, also included `ansible-playbook`, etc.)

- [git](https://github.com/git/git) (`git`: latest version when run the build)

Default command is 'terraform'.
You can use this image with the following:

``` bash
docker run --rm -it mungi/cloud-cli 'terraform <command>'
docker run --rm -it mungi/cloud-cli 'packer <command>'
docker run --rm -it mungi/cloud-cli 'aws <command>'
docker run --rm -it mungi/cloud-cli 'az <command>'
docker run --rm -it mungi/cloud-cli 'gcloud <command>'
docker run --rm -it mungi/cloud-cli 'kubectl <command>'
docker run --rm -it mungi/cloud-cli 'helm <command>'
docker run --rm -it mungi/cloud-cli 'eksctl <command>'
docker run --rm -it mungi/cloud-cli 'aws-iam-authenticator <command>'
docker run --rm -it mungi/cloud-cli 'ansible <command>'
docker run --rm -it mungi/cloud-cli 'ansible-playbook <command>'
docker run --rm -it mungi/cloud-cli 'git <command>'
```

Should you have any questions or suggestions, please open an issue on github.
