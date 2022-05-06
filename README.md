mackerel-plugin-nvidia-smi
==========================

GPU custom metrics plugin using nvidia-smi for mackerel.io agent.

## Synopsis

```shell
mackerel-plugin-nvidia-smi [-metric-key-prefix=<Metric key prefix>]
```

## Example of mackerel-agent.conf

```
[plugin.metrics.nvidia-smi]
command = "/path/to/mackerel-plugin-nvidia-smi"
```

