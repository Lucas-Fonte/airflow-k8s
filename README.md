# airflow-k8s

Airflow instance on K8s, using KubernetesPodOperator

---

## Summary

The whole purpose of this project is to setup a proof of concept on how a company would use Airflow running on Kubernetes to create ETLs, run tasks or any other Airflow usecase, containerizing workflows.

---

## TO-DO:

- [ ] Start project, install all dependencies, `kubectl`, `helm`, etc.
- [ ] It would be interesting to have monitoring right away due to intentions of the project
- [ ] Configure Airflow
- [ ] Create one or two containerized workflows to use the KubernetesPodOperator
- [ ] It would be really interesting deploying it to any Cloud provider, I'm thinking of GCP right now due to a free tier GKE, but this could be changed as I go 


---

## Useful links:

- Cloud Composer: https://cloud.google.com/composer/docs/how-to/using/using-kubernetes-pod-operator
- Deploying Apache Airflow on GCP: https://medium.com/apache-airflow/a-simple-guide-to-start-using-apache-airflow-2-on-google-cloud-1811c2127445
- Airflow Deployment: https://airflow.apache.org/docs/apache-airflow/stable/production-deployment.html
- Deploying Airflow on Kubernetes: https://medium.com/@olivertosky/deploying-apache-airflow-to-google-kubernetes-engine-a72c7db912ee
- K8s + Prometheus + Grafana: https://www.youtube.com/watch?v=QoDqxm7ybLc&t=976s
- Airflow on K8s: https://www.youtube.com/watch?v=3VDeKmxHWYA&t=10s
