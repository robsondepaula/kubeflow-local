# Deploying Kubeflow locally

Follow the Kubeflow on MiniKF [guide](https://www.kubeflow.org/docs/distributions/minikf/minikf-vagrant/).

# Validate

Once set up you can follow the [tutorial](https://medium.com/kubeflow/an-end-to-end-ml-pipeline-on-prem-notebooks-kubeflow-pipelines-on-the-new-minikf-33b7d8e9a836) for a quick validation using the Chicago Taxi (TFX) dataset.

# Persist across reboots

Once finished working with MiniKF, suspend the VM: 
```
vagrant suspend
```
So that you can resume your work later persisting the setup and data.
```
vagrant up
```
