# container-networking-ci
Public config for the Container Networking team's CI

Keep credentials and other private config in our [private repo](https://github.com/cloudfoundry/container-networking-deployments)

## to update a pipeline
```
fly -t c2c set-pipeline \
  -p guardian \
  -c ~/workspace/container-networking-ci/pipelines/guardian.yml \
  -l ~/workspace/container-networking-deployments/pipeline-credentials.yml
```
