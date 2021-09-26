# ALLOW-OUTSIDE-TRAFFIC-TO-A-VIRTUAL-MACHINE-WITH-IN-MICROSOFT-AZURE-USING-THE-CLI

```
az vm open-port \
    --port "80" \
    --resource-group "resource-group-west" \
    --name "linux-vm-west"
```
