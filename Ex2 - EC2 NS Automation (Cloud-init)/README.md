# How to Use - EC2 DNS Configuration

Make sure the EC2 instance has the following tags:

- `AUTO_DNS_ZONE` - The Route53 zone ID
- `AUTO_DNS_NAME` - The subdomain name of the zone, for example: `dor.aws.cts.care`

---

## Steps

1. Edit `inventory.ini` to match the remote EC2 instance you want to configure

2. Run the playbook:

```bash
ansible-playbook -i inventory.ini main.yaml
```

The instance will now run a script that automatically updates the nameserver to match the instance's IP on every boot

