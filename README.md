# Kubernetes Helm charts by @cetic

This is a [Helm](https://helm.sh) charts repository for Kubernetes made by @cetic.

### Add Helm repository

To install the [cetic](https://cetic.be) repo just run:

```bash
helm repo add cetic https://cetic.github.io/helm-charts
helm repo update
```

### Helm Charts

* [pgAdmin](https://github.com/cetic/helm-pgadmin)

  ```bash
  helm install --name your-release cetic/pgadmin
  ```
* [apache nifi](https://github.com/cetic/helm-nifi)

  ```bash
  helm install --name your-release cetic/nifi
  ```

* [phpldapadmin](https://github.com/cetic/helm-phpLDAPadmin)

  ```bash
  helm install --name your-release cetic/phpldapadmin
  ```

* [fadi](https://github.com/cetic/helm-fadi)

  ```bash
  helm install --name your-release cetic/fadi
  ```

* [postgresql](https://github.com/cetic/helm-postgresql)

  ```bash
  helm install --name your-release cetic/postgresql
  ```
  
* [tsaas](https://github.com/cetic/helm-tsimulus-saas)

  ```bash
  helm install --name your-release cetic/tsaas
  ```  
  
* [swaggerui](https://github.com/cetic/helm-swagger-ui)

  ```bash
  helm install --name your-release cetic/swaggerui
  ```

### License

[Apache License 2.0](/LICENSE)
