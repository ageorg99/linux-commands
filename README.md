# linux-commands

## All My Useful Linux Commands

---

### 1. SSH Host Configuration for Easy Access

Create or edit your SSH config file:


nano ~/.ssh/config

Host grafana
    HostName XXXX.h-1.compute.amazonaws.com
    User ubuntu
    IdentityFile /home/alexandros-g/Documents/ubuntu.pem

```bash
ssh grafana
