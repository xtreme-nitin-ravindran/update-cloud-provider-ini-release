# Addon to update cloud-provide.ini

- Update `src/cloud-provider.ini`
- `bosh cr && bosh ur`
- Update release version `in runtime-config.yml`
- `bosh urc --name k8s-cloud-provider runtime-config.yml`
