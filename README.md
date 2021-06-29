# Helm Charts by Gluo

[Gluo](https://www.gluo.be) is your one-stop DevOps shop. Whether you are looking for automation, configuration management, Linux expertise, containerization of your workload, migration to the cloud, continuous integration, continuous delivery, continuous deployment,… we have got you covered!

## Quick start

To use one of our Helm charts, add this repository to your Helm configuration:
```bash
helm repo add gluo https://gluobe.github.io/helm-charts
helm repo update
```

## Add a new chart

1. Pull this repository 
```bash
https://github.com/gluobe/helm-charts/
```
2. Create a new branch to add your chart safely.
```bash
git checkout -b my-new-chart
```
3. Copy your chart to the `charts/` directory
```bash
cp -ra ../my-new-chart charts/
```
4. Commit and push
```bash
git add charts/
git commit -m "add my new chart"
git push -u origin my-new-chart
```

After the Pull Request is approved, the chart will be published to this Chart repository
```bash
helm repo update
helm search repo my-new-chart
```




