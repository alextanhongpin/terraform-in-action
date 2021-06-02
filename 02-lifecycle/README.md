# Create a local file

```bash
$ terraform init

# Stores the plan in binary format.
$ terraform plan -out plan.out

# View the state as json
$ terraform show -json plan.out > plan.json
$ jq < plan.json

$ terraform apply plan.out

$ brew install graphviz
$ terraform graph | dot -Tpng > graph.png

# Cleanup the resource.
$ terraform destroy -auto-approve
```
