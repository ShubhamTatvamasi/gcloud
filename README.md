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
DOWNLOAD_FILE=Lens-5.0.0-beta.2.20210429.2.amd64.deb

gcloud cloud-shell scp \
  cloudshell:~/$DOWNLOAD_FILE \
  localhost:/tmp/$DOWNLOAD_FILE
```

mount current folder to remote:
```bash
gcloud cloud-shell get-mount-command .
```
> folder should be empty

