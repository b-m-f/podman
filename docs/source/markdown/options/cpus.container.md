####> This option file is used in:
####>   podman create, run, update
####> If you edit this file, make sure your changes
####> are applicable to all of those.
#### **--cpus**=*number*

Number of CPUs. The default is *0.0* which means no limit. This is shorthand
for **--cpu-period** and **--cpu-quota**, so you may only set either
**--cpus** or **--cpu-period** and **--cpu-quota**.

On some systems, changing the CPU limits may not be allowed for non-root
users. For more details, see
https://github.com/containers/podman/blob/main/troubleshooting.md#26-running-containers-with-resource-limits-fails-with-a-permissions-error

This option is not supported on cgroups V1 rootless systems.
