# auxo-db-deploy

河北广告监测平台数据库

## 部署

helm upgrade --install --namespace db -f values-dev.yaml db ./postgresql
