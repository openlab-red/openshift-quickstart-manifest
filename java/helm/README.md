# openshift-quickstart

## Configuration

The following table lists the configurable parameters and their default values.

| Parameter | Description | Default |
|  ---  |  ---  |  ---  |
| `app.envs.WORKSPACE_NAMESPACE` |   | bit-play |
| `app.image` | The container image to use. | quay.io/bit-play/openshift-quickstart:1.0.0-SNAPSHOT |
| `app.ports.http` | The http port to use for the probe. | 8080 |

Specify each parameter using the `--set key=value[,key=value]` argument to `helm install`.
Alternatively, a YAML file that specifies the values for the above parameters can be provided while installing the chart. For example,
```
$ helm install --name chart-name -f values.yaml .
```
> **Tip**: You can use the default [values.yaml](values.yaml)
