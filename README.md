# emulatorjs_helm
EmulatorJS helm chart.
# emulatorjs_helm
Deluge torrent client helm chart.

**emulatorjs_helm**

## installing an emulatorjs_helm

Install emulatorJS service with the following commands:
>You need to install [nfs.csi.k8s.io](https://github.com/kubernetes-csi/csi-driver-nfs) driver to use NFS before proceeding with the deluge installation, or use your own nfs driver.
```
git clone https://github.com/AlexVinet/deluge_helm.git
cd emulatorjs_helm/emulators/
Modify the pv.
helm install emulatorjs -f values.yaml .
```

>\*\*Note: You need to modify the pv.yaml with your own config.\*\*