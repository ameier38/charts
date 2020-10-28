# Base Service Chart
Helm chart used for services.

## Usage
1. Add the repo.
    ```
    helm repo add ameier38 https://ameier38.github.io/charts
    ```
2. Update the repo.
    ```
    helm repo update
    ```
3. Search the charts.
    ```
    helm search repo ameier38
    ```

## Development
1. Make changes.
2. Bump version in [Chart.yaml](./Chart.yaml).
3. Update [CHANGELOG.md](./CHANGELOG.md).
4. Run `helm package charts/base-service`.
5. Move `base-service-<version>.tgz` into `docs` directory.
6. Run `helm repo index docs`. 
7. Commit changes.
8. Create PR.
9. Merge PR (GitHub pages will redeploy).
