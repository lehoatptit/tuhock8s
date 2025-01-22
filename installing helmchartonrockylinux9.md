1. Download version
curl -O https://get.helm.sh/helm-v3.16.2-linux-amd64.tar.gz
2. giai nenf fiel cai dat
tar xvf helm-v3.16.2-linux-amd64.tar.gz
3.
mv linux-amd64/helm /usr/local/bin
4. don dep file cai dat va thu muc cai dat 
rm helm-v3.16.2-linux-amd64.tar.gz
rm -rf linux-amd64
5. kiem tra version
helm version