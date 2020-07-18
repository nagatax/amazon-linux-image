# amazon-linux-image

## Allow password authentication

```bash
# @ /etc/ssh/sshd_config

# To disable tunneled clear text passwords, change to no here!
PasswordAuthentication yes
#PermitEmptyPasswords no
#PasswordAuthentication no
```

## Reference

- [amazon-linux-2-virtual-machine](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/amazon-linux-2-virtual-machine.html)
- [README.cloud-init](https://cdn.amazonlinux.com/os-images/2.0.20190612/README.cloud-init)