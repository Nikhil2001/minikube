---
title: "tunnel"
description: >
  Connect to LoadBalancer services
---


## minikube tunnel

Connect to LoadBalancer services

### Synopsis

tunnel creates a route to services deployed with type LoadBalancer and sets their Ingress to their ClusterIP. for a detailed example see https://minikube.sigs.k8s.io/docs/tasks/loadbalancer

```shell
minikube tunnel [flags]
```

### Options

```
  -c, --cleanup   call with cleanup=true to remove old tunnels (default true)
```

### Options inherited from parent commands

```
      --add_dir_header                   If true, adds the file directory to the header of the log messages
      --alsologtostderr                  log to standard error as well as files
  -b, --bootstrapper string              The name of the cluster bootstrapper that will set up the Kubernetes cluster. (default "kubeadm")
  -h, --help                             
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory
      --log_file string                  If non-empty, use this log file
      --log_file_max_size uint           Defines the maximum size a log file can grow to. Unit is megabytes. If the value is 0, the maximum file size is unlimited. (default 1800)
      --logtostderr                      log to standard error instead of files
      --one_output                       If true, only write logs to their native severity level (vs also writing to each lower severity level)
  -p, --profile string                   The name of the minikube VM being used. This can be set to allow having multiple instances of minikube independently. (default "minikube")
      --rootless                         Force to use rootless driver (docker and podman driver only)
      --skip_headers                     If true, avoid header prefixes in the log messages
      --skip_log_headers                 If true, avoid headers when opening log files
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
      --user string                      Specifies the user executing the operation. Useful for auditing operations executed by 3rd party tools. Defaults to the operating system username.
  -v, --v Level                          number for the log level verbosity
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

