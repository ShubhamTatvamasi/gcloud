# gcloud

https://shell.cloud.google.com

SSH in cloud shell:
```bash
gcloud cloud-shell ssh
```

Copy a file, 'data.txt', from Cloud Shell to your local machine:
```bash
gcloud cloud-shell scp cloudshell:~/data.txt localhost:~data.txt
```

download iso image from cloud shell server:
```bash
gcloud cloud-shell scp \
  cloudshell:/home/shubhamtatvamasi/Fedora-Workstation-Live-x86_64-34-1.2.iso \
  localhost:/tmp/Fedora-Workstation-Live-x86_64-34-1.2.iso
```
