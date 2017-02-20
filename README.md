# azure-deis-spark cluster script

This script automates building a Azure Container Service cluster running Kubernetes with Deis and Postgres installed.

Use:

1. copy create-test-cluster to a new name
2. edit this script and adjust the SUBSCRIPTION_ID and DEPLOYMENT_PREFIX environment variables.
3. edit azure-disk.yaml to match the final premium storage account name for both the storage and class names, and region, if you changed it from eastus in the script.
4. If running on windows, you can download the kubectrl cli .exe [https://github.com/eirslett/kubectl-windows/releases](here). You should make sure the local version and remote kubernetes versions are the same.
5. run your edited script!
