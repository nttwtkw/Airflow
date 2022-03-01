Images Version
git-sync : alpine/git:latest
airflow-web : chinnapatke01/airflow-vaex:1.1.4
airflow-scheduler : chinnapatke01/airflow-vaex:1.1.4
airflow-postgresql : bitnami/postgresql:11.7.0-debian-10-r9


Procedure
kubectl create -f template/<sub folder> 
kubectl create -f charts/postgresql/template
kubectl create cm pod-template --from-file=template/config/pod-template.yaml
