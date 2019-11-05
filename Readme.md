# Addon to update cloud-provide.ini

- Update `jobs/update-master/templates/config/cloud-provider.ini.erb`
- `bosh cr && bosh ur`
- Update release version, aws_region, and aws_endpoint_url in `runtime-config.yml`
- `bosh urc --name k8s-cloud-provider runtime-config.yml`
