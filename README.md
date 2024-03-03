# Helm-Chart-Store

- This is demo repository for helm chart store
  
> [!CAUTION]
> **_There is no guarantee of this repository contents_**

**Helm chart repository** 
$ git clone https://github.com/choonkeun/helm-chart-store.git

git init \
git add README.md \
git commit -m "first commit" \
git branch -M main \
git remote add origin https://github.com/choonkeun/helm-chart-store.git \
git push -u origin main

git remote add origin https://github.com/choonkeun/helm-chart-store.git \
git branch -M main \
git push -u origin main 


- Add below line to helm search list \
$ helm repo add helm-chart-store https://choonkeun.github.io/helm-chart-store/ 
$ helm repo list  \
$ helm repo update  \
$ helm search repo site-search \
$ helm install crawlsite helm-chart-store/site-search 


