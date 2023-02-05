## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add chart-releaser-spike https://github.dev.global.tesco.org/pages/Hue12370907/chart-releaser-spike/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
chart-releaser-spike` to see the charts.

To install the chart-releaser-spike chart:

    helm install my-chart-releaser-spike chart-releaser-spike/chart-releaser-spike

To uninstall the chart:

    helm delete my-chart-releaser-spike
