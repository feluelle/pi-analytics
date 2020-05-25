# pi-analytics
An analytics stack on a dockerized raspberry pi.

0. The environment - [k3s](https://github.com/rancher/k3s)
and [k3sup](https://github.com/alexellis/k3sup)
1. The database - [druid](https://github.com/apache/druid)
`helm install --namespace "druid" --name "druid" incubator/druid`
2. The orchestration - [airflow](https://github.com/apache/airflow)
`helm install --namespace "airflow" --name "airflow" astronomer/airflow`
3. The visualisation - [superset](https://github.com/apache/incubator-superset)
`helm install --namespace "superset" --name "superset" stable/superset`

## Examples

- COVID-19

## Notes

TODO: Read https://blog.alexellis.io/test-drive-k3s-on-raspberry-pi/
TODO: Deploy helm charts
