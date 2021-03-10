# my-helm-charts

#### gitlab-4.9.3.tgz dosyasını local'e çekmek için çalıştırılan komutlar
- helm repo add gitlab https://charts.gitlab.io/
- helm pull gitlab/gitlab

#### git'e dosya eklemek için kullanılan komutlar
- git init
- git config --global user.name "cantahmazoglu"
- git config --global user.email "alicantahmazoglu11@gmail.com
- git add gitlab-4.9.3.tgz
- git commit -m "helm pull gitlab-master" 
- git remote add alican https://github.com/cantahmazoglu/my-helm-charts.git
- git fetch alican 
- git merge alican/main --allow-unrelated-histories
- git push alican main
