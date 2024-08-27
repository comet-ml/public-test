# public-test

## Usage
Helm must be installed to use the charts. Please refer to Helm’s documentation to get started.

Once Helm has been set up correctly, add the repo as follows:
``` bash
helm repo add public-test https://comet-ml.github.io/public-test
```
If you had already added this repo earlier, run helm repo update to retrieve the latest versions of the packages. You can then run helm search repo public-test to see the charts.

To install the public-test chart:
``` bash
helm install public-test public-test/public-test
```
To uninstall the chart:
```
helm delete public-test
```