# [PGO](https://github.com/CrunchyData/postgres-operator), Crunchy [Postgres Operator](https://github.com/CrunchyData/postgres-operator) Helm chart repo

This is helm repository holding (sample) helm charts for Postgres operator.

To install the helm chart run:
```sh
helm repo add pgo-postgres https://raw.githubusercontent.com/pavel-jancik/postgres-operator-examples/helm-repo/
# "pgo-postgres" has been added to your repositories

helm repo update pgo-postgres
# Hang tight while we grab the latest from your chart repositories...
# ...Successfully got an update from the "pgo-postgres" chart repository
# Update Complete. ⎈Happy Helming!⎈


# List charts in the repo
helm search repo pgo-postgres
# NAME                            CHART VERSION   APP VERSION     DESCRIPTION
# pgo-postgres/pgo                5.3.1           5.3.1           Installer for PGO, the open source Postgres Ope...
# pgo-postgres/postgrescluster    5.3.1           5.3.1           A Helm chart for Kubernetes
```
