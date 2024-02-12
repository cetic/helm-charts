# Kubernetes Helm charts by [@cetic](https://cetic.be)

This is a [Helm](https://helm.sh) charts repository for Kubernetes made by [@cetic](https://cetic.be).

### Add Helm repository

To install the [cetic](https://cetic.be) repo just run:

```bash
helm repo add cetic https://cetic.github.io/helm-charts
helm repo update
```

### Helm Charts
  
* [tsaas](https://github.com/cetic/helm-tsimulus-saas)

  ```bash
  helm install your-release-name cetic/tsaas
  ```  

* [mlflow](https://github.com/cetic/helm-mlflow)

  ```bash
  helm install your-release-name cetic/mlflow
  ```

* [microservice](https://github.com/cetic/helm-microservice)

  ```bash
  helm install your-release-name cetic/microservice
  ```

* [job](https://github.com/cetic/helm-job)

  ```bash
  helm install your-release-name cetic/job
  ```

### License

[Apache License 2.0](/LICENSE)
