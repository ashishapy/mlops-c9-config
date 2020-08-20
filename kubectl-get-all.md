TeamRole:~/environment $ kubectl get all,ing -A
NAMESPACE              NAME                                                               READY   STATUS      RESTARTS   AGE
amazon-cloudwatch      pod/cloudwatch-agent-4jf58                                         1/1     Running     0          103m
amazon-cloudwatch      pod/cloudwatch-agent-86kn4                                         1/1     Running     0          103m
amazon-cloudwatch      pod/cloudwatch-agent-hf9rb                                         1/1     Running     0          103m
amazon-cloudwatch      pod/cloudwatch-agent-lp6cr                                         1/1     Running     0          103m
amazon-cloudwatch      pod/cloudwatch-agent-mg7qp                                         1/1     Running     0          103m
amazon-cloudwatch      pod/cloudwatch-agent-mttvq                                         1/1     Running     0          103m
cert-manager           pod/cert-manager-cainjector-c578b68fc-lnmdk                        1/1     Running     0          103m
cert-manager           pod/cert-manager-fcc6cd946-52vk4                                   1/1     Running     0          103m
cert-manager           pod/cert-manager-webhook-657b94c676-sk9qh                          1/1     Running     1          103m
demo                   pod/podinfo-785c7d877d-5gxrc                                       1/1     Running     0          102m
flux                   pod/flux-5b499cc67c-b94xq                                          1/1     Running     0          109m
flux                   pod/helm-operator-6fd6b7fbfc-49892                                 1/1     Running     0          109m
flux                   pod/memcached-7dd5ff9dcf-7nmjh                                     1/1     Running     0          109m
istio-system           pod/cluster-local-gateway-78f6cbff8d-8jjz6                         1/1     Running     0          103m
istio-system           pod/grafana-68bcfd88b6-67rgv                                       1/1     Running     0          103m
istio-system           pod/istio-citadel-7dd6877d4d-6z79h                                 1/1     Running     0          103m
istio-system           pod/istio-cleanup-secrets-1.1.6-rzlwh                              0/1     Completed   0          103m
istio-system           pod/istio-egressgateway-7c888bd9b9-fccr8                           1/1     Running     0          103m
istio-system           pod/istio-galley-5bc58d7c89-xtzgg                                  1/1     Running     0          103m
istio-system           pod/istio-grafana-post-install-1.1.6-qb4md                         0/1     Completed   0          103m
istio-system           pod/istio-ingressgateway-866fb99878-9gbff                          1/1     Running     0          103m
istio-system           pod/istio-pilot-67f9bd57b-2f6z2                                    2/2     Running     0          103m
istio-system           pod/istio-policy-749ff546dd-2ktwj                                  2/2     Running     1          103m
istio-system           pod/istio-security-post-install-1.1.6-tpn4p                        0/1     Completed   0          103m
istio-system           pod/istio-sidecar-injector-cc5ddbc7-4tgsb                          1/1     Running     0          103m
istio-system           pod/istio-telemetry-6f6d8db656-l78nx                               2/2     Running     2          103m
istio-system           pod/istio-tracing-84cbc6bc8-b7zsd                                  1/1     Running     0          103m
istio-system           pod/kiali-7879b57b46-nh88d                                         1/1     Running     0          103m
istio-system           pod/prometheus-744f885d74-9l82q                                    1/1     Running     0          103m
knative-serving        pod/activator-58595c998d-rp4pg                                     2/2     Running     1          102m
knative-serving        pod/autoscaler-7ffb4cf7d7-xnhrp                                    2/2     Running     2          102m
knative-serving        pod/autoscaler-hpa-686b99f459-cp97d                                1/1     Running     0          102m
knative-serving        pod/controller-c6d7f946-vr75j                                      1/1     Running     0          102m
knative-serving        pod/networking-istio-ff8674ddf-vnjlg                               1/1     Running     0          102m
knative-serving        pod/webhook-6d99c5dbbf-gp8cs                                       1/1     Running     0          102m
kube-system            pod/alb-ingress-controller-7bcbf5c669-h48k2                        1/1     Running     1          103m
kube-system            pod/aws-node-7kg8h                                                 1/1     Running     0          110m
kube-system            pod/aws-node-7l9c8                                                 1/1     Running     0          110m
kube-system            pod/aws-node-mxpcr                                                 1/1     Running     0          110m
kube-system            pod/aws-node-np6ck                                                 1/1     Running     0          110m
kube-system            pod/aws-node-s2x99                                                 1/1     Running     0          110m
kube-system            pod/aws-node-tdxsx                                                 1/1     Running     0          110m
kube-system            pod/cluster-autoscaler-667f7596df-g9djt                            1/1     Running     0          103m
kube-system            pod/coredns-5946c5d67c-frkzg                                       1/1     Running     0          117m
kube-system            pod/coredns-5946c5d67c-kb6zf                                       1/1     Running     0          117m
kube-system            pod/kube-proxy-2bpfl                                               1/1     Running     0          110m
kube-system            pod/kube-proxy-77v27                                               1/1     Running     0          110m
kube-system            pod/kube-proxy-82fmh                                               1/1     Running     0          110m
kube-system            pod/kube-proxy-fkv46                                               1/1     Running     0          110m
kube-system            pod/kube-proxy-pnftk                                               1/1     Running     0          110m
kube-system            pod/kube-proxy-z2mqr                                               1/1     Running     0          110m
kubeflow               pod/admission-webhook-bootstrap-stateful-set-0                     1/1     Running     0          102m
kubeflow               pod/admission-webhook-deployment-59bc556b94-ctr7b                  1/1     Running     0          102m
kubeflow               pod/alb-ingress-controller-d99b66494-6tsrs                         1/1     Running     1          102m
kubeflow               pod/application-controller-stateful-set-0                          1/1     Running     0          103m
kubeflow               pod/argo-ui-5f845464d7-zqj6w                                       1/1     Running     0          102m
kubeflow               pod/centraldashboard-d5c6d6bf-grzzv                                1/1     Running     0          102m
kubeflow               pod/jupyter-web-app-deployment-544b7d5684-z8n8t                    1/1     Running     0          102m
kubeflow               pod/katib-controller-6b87947df8-vs57m                              1/1     Running     1          102m
kubeflow               pod/katib-db-manager-54b64f99b-59jxf                               1/1     Running     0          102m
kubeflow               pod/katib-mysql-74747879d7-sv25c                                   1/1     Running     0          102m
kubeflow               pod/katib-ui-76f84754b6-z4jxd                                      1/1     Running     0          102m
kubeflow               pod/kfserving-controller-manager-0                                 2/2     Running     1          102m
kubeflow               pod/metacontroller-0                                               1/1     Running     0          102m
kubeflow               pod/metadata-db-79d6cf9d94-zljp4                                   1/1     Running     0          102m
kubeflow               pod/metadata-deployment-5dd4c9d4cf-9lg9c                           1/1     Running     0          102m
kubeflow               pod/metadata-envoy-deployment-5b9f9466d9-qwhdb                     1/1     Running     0          102m
kubeflow               pod/metadata-grpc-deployment-74f69954dc-qb8j9                      1/1     Running     4          102m
kubeflow               pod/metadata-ui-8968fc7d9-n2vsp                                    1/1     Running     0          102m
kubeflow               pod/minio-6b88d6499f-qz2hb                                         1/1     Running     0          102m
kubeflow               pod/ml-pipeline-698bcdd747-6wj94                                   1/1     Running     0          102m
kubeflow               pod/ml-pipeline-ml-pipeline-visualizationserver-675656df79-sbcc6   1/1     Running     0          102m
kubeflow               pod/ml-pipeline-persistenceagent-7785884886-mp25b                  1/1     Running     0          102m
kubeflow               pod/ml-pipeline-scheduledworkflow-7b4cb5d959-lzn6j                 1/1     Running     0          102m
kubeflow               pod/ml-pipeline-ui-5fbd94b9fb-lqxwn                                1/1     Running     0          102m
kubeflow               pod/ml-pipeline-viewer-controller-deployment-69fccfff8c-rkgbk      1/1     Running     0          102m
kubeflow               pod/mpi-operator-6494747f88-9m2hq                                  1/1     Running     0          102m
kubeflow               pod/mysql-7994454666-f6nxx                                         1/1     Running     0          102m
kubeflow               pod/notebook-controller-deployment-576589db9d-t597q                1/1     Running     0          102m
kubeflow               pod/nvidia-device-plugin-daemonset-6rgcd                           1/1     Running     0          102m
kubeflow               pod/nvidia-device-plugin-daemonset-js958                           1/1     Running     0          102m
kubeflow               pod/nvidia-device-plugin-daemonset-nfp6j                           1/1     Running     0          102m
kubeflow               pod/nvidia-device-plugin-daemonset-s4r8p                           1/1     Running     0          102m
kubeflow               pod/nvidia-device-plugin-daemonset-z6x9k                           1/1     Running     0          102m
kubeflow               pod/nvidia-device-plugin-daemonset-zw8js                           1/1     Running     0          102m
kubeflow               pod/profiles-deployment-5f77bb94c6-4pmq7                           2/2     Running     0          102m
kubeflow               pod/pytorch-operator-666dd4cd49-qvqd6                              1/1     Running     0          102m
kubeflow               pod/seldon-controller-manager-5d96986d47-5rnlx                     1/1     Running     0          102m
kubeflow               pod/spark-operatorcrd-cleanup-8zhsk                                0/2     Completed   0          102m
kubeflow               pod/spark-operatorsparkoperator-7c484c6859-tp6rn                   1/1     Running     0          102m
kubeflow               pod/spartakus-volunteer-84448b6b69-vpqjw                           1/1     Running     0          102m
kubeflow               pod/tensorboard-6549cd78c9-slqzb                                   1/1     Running     0          102m
kubeflow               pod/tf-job-operator-7574b968b5-dcvh8                               1/1     Running     0          102m
kubeflow               pod/titanic-suvival-prediction-pipeline-knc48-1273295805           0/2     Completed   0          63m
kubeflow               pod/titanic-suvival-prediction-pipeline-knc48-1340137410           0/2     Completed   0          71m
kubeflow               pod/titanic-suvival-prediction-pipeline-knc48-2812484651           0/2     Completed   0          66m
kubeflow               pod/workflow-controller-6db95548dd-s2h2k                           1/1     Running     0          102m
kubernetes-dashboard   pod/dashboard-metrics-scraper-c44b4d655-424g4                      1/1     Running     0          103m
kubernetes-dashboard   pod/kubernetes-dashboard-7789d8fffc-29qf5                          1/1     Running     0          103m
monitoring             pod/alertmanager-prometheus-operator-alertmanager-0                2/2     Running     0          102m
monitoring             pod/metrics-server-f78cb8cd8-6m2hz                                 1/1     Running     0          103m
monitoring             pod/prometheus-operator-grafana-79bd7f8f8c-j4txc                   2/2     Running     0          102m
monitoring             pod/prometheus-operator-kube-state-metrics-66b4c95cd9-qxlm2        1/1     Running     0          102m
monitoring             pod/prometheus-operator-operator-7684f89b74-x4tzc                  2/2     Running     0          102m
monitoring             pod/prometheus-operator-prometheus-node-exporter-9vl9p             1/1     Running     0          102m
monitoring             pod/prometheus-operator-prometheus-node-exporter-9zp4j             1/1     Running     0          102m
monitoring             pod/prometheus-operator-prometheus-node-exporter-d4d4h             1/1     Running     0          102m
monitoring             pod/prometheus-operator-prometheus-node-exporter-djqgb             1/1     Running     0          102m
monitoring             pod/prometheus-operator-prometheus-node-exporter-h7fn2             1/1     Running     0          102m
monitoring             pod/prometheus-operator-prometheus-node-exporter-hsqvh             1/1     Running     0          102m
monitoring             pod/prometheus-prometheus-operator-prometheus-0                    3/3     Running     1          102m

NAMESPACE              NAME                                                   TYPE        CLUSTER-IP       EXTERNAL-IP   PORT(S)                                                                                                                                      AGE
cert-manager           service/cert-manager                                   ClusterIP   10.100.17.176    <none>        9402/TCP                                                                                                                                     103m
cert-manager           service/cert-manager-webhook                           ClusterIP   10.100.186.145   <none>        443/TCP                                                                                                                                      103m
default                service/kubernetes                                     ClusterIP   10.100.0.1       <none>        443/TCP                                                                                                                                      117m
demo                   service/podinfo                                        ClusterIP   10.100.143.160   <none>        9898/TCP,9999/TCP                                                                                                                            102m
flux                   service/memcached                                      ClusterIP   10.100.157.170   <none>        11211/TCP                                                                                                                                    109m
istio-system           service/cluster-local-gateway                          ClusterIP   10.100.58.102    <none>        80/TCP,443/TCP,31400/TCP,15011/TCP,8060/TCP,15029/TCP,15030/TCP,15031/TCP,15032/TCP                                                          103m
istio-system           service/grafana                                        ClusterIP   10.100.111.83    <none>        3000/TCP                                                                                                                                     103m
istio-system           service/istio-citadel                                  ClusterIP   10.100.88.172    <none>        8060/TCP,15014/TCP                                                                                                                           103m
istio-system           service/istio-egressgateway                            ClusterIP   10.100.215.217   <none>        80/TCP,443/TCP,15443/TCP                                                                                                                     103m
istio-system           service/istio-galley                                   ClusterIP   10.100.91.51     <none>        443/TCP,15014/TCP,9901/TCP                                                                                                                   103m
istio-system           service/istio-ingressgateway                           NodePort    10.100.54.19     <none>        15020:31196/TCP,80:31380/TCP,443:31390/TCP,31400:31400/TCP,15029:32628/TCP,15030:32316/TCP,15031:32545/TCP,15032:32095/TCP,15443:30843/TCP   103m
istio-system           service/istio-pilot                                    ClusterIP   10.100.204.224   <none>        15010/TCP,15011/TCP,8080/TCP,15014/TCP                                                                                                       103m
istio-system           service/istio-policy                                   ClusterIP   10.100.137.142   <none>        9091/TCP,15004/TCP,15014/TCP                                                                                                                 103m
istio-system           service/istio-sidecar-injector                         ClusterIP   10.100.85.198    <none>        443/TCP                                                                                                                                      103m
istio-system           service/istio-telemetry                                ClusterIP   10.100.137.134   <none>        9091/TCP,15004/TCP,15014/TCP,42422/TCP                                                                                                       103m
istio-system           service/jaeger-agent                                   ClusterIP   None             <none>        5775/UDP,6831/UDP,6832/UDP                                                                                                                   103m
istio-system           service/jaeger-collector                               ClusterIP   10.100.0.135     <none>        14267/TCP,14268/TCP                                                                                                                          103m
istio-system           service/jaeger-query                                   ClusterIP   10.100.115.247   <none>        16686/TCP                                                                                                                                    103m
istio-system           service/kiali                                          ClusterIP   10.100.247.70    <none>        20001/TCP                                                                                                                                    103m
istio-system           service/prometheus                                     ClusterIP   10.100.106.155   <none>        9090/TCP                                                                                                                                     103m
istio-system           service/tracing                                        ClusterIP   10.100.156.176   <none>        80/TCP                                                                                                                                       103m
istio-system           service/zipkin                                         ClusterIP   10.100.139.242   <none>        9411/TCP                                                                                                                                     103m
knative-serving        service/activator-service                              ClusterIP   10.100.162.215   <none>        80/TCP,81/TCP,9090/TCP                                                                                                                       102m
knative-serving        service/autoscaler                                     ClusterIP   10.100.182.64    <none>        8080/TCP,9090/TCP,443/TCP                                                                                                                    102m
knative-serving        service/controller                                     ClusterIP   10.100.178.1     <none>        9090/TCP                                                                                                                                     102m
knative-serving        service/webhook                                        ClusterIP   10.100.34.136    <none>        443/TCP                                                                                                                                      102m
kube-system            service/kube-dns                                       ClusterIP   10.100.0.10      <none>        53/UDP,53/TCP                                                                                                                                117m
kube-system            service/prometheus-operator-coredns                    ClusterIP   None             <none>        9153/TCP                                                                                                                                     102m
kube-system            service/prometheus-operator-kube-controller-manager    ClusterIP   None             <none>        10252/TCP                                                                                                                                    102m
kube-system            service/prometheus-operator-kube-etcd                  ClusterIP   None             <none>        2379/TCP                                                                                                                                     102m
kube-system            service/prometheus-operator-kube-proxy                 ClusterIP   None             <none>        10249/TCP                                                                                                                                    102m
kube-system            service/prometheus-operator-kube-scheduler             ClusterIP   None             <none>        10251/TCP                                                                                                                                    102m
kube-system            service/prometheus-operator-kubelet                    ClusterIP   None             <none>        10250/TCP,10255/TCP,4194/TCP                                                                                                                 102m
kubeflow               service/admission-webhook-service                      ClusterIP   10.100.90.72     <none>        443/TCP                                                                                                                                      102m
kubeflow               service/application-controller-service                 ClusterIP   10.100.68.207    <none>        443/TCP                                                                                                                                      103m
kubeflow               service/argo-ui                                        NodePort    10.100.193.105   <none>        80:31556/TCP                                                                                                                                 102m
kubeflow               service/centraldashboard                               ClusterIP   10.100.64.75     <none>        80/TCP                                                                                                                                       102m
kubeflow               service/jupyter-web-app-service                        ClusterIP   10.100.243.16    <none>        80/TCP                                                                                                                                       102m
kubeflow               service/katib-controller                               ClusterIP   10.100.125.224   <none>        443/TCP,8080/TCP                                                                                                                             102m
kubeflow               service/katib-db-manager                               ClusterIP   10.100.127.68    <none>        6789/TCP                                                                                                                                     102m
kubeflow               service/katib-mysql                                    ClusterIP   10.100.28.127    <none>        3306/TCP                                                                                                                                     102m
kubeflow               service/katib-ui                                       ClusterIP   10.100.143.42    <none>        80/TCP                                                                                                                                       102m
kubeflow               service/kfserving-controller-manager-metrics-service   ClusterIP   10.100.144.119   <none>        8443/TCP                                                                                                                                     102m
kubeflow               service/kfserving-controller-manager-service           ClusterIP   10.100.135.21    <none>        443/TCP                                                                                                                                      102m
kubeflow               service/kfserving-webhook-server-service               ClusterIP   10.100.138.135   <none>        443/TCP                                                                                                                                      101m
kubeflow               service/metadata-db                                    ClusterIP   10.100.196.156   <none>        3306/TCP                                                                                                                                     102m
kubeflow               service/metadata-envoy-service                         ClusterIP   10.100.97.142    <none>        9090/TCP                                                                                                                                     102m
kubeflow               service/metadata-grpc-service                          ClusterIP   10.100.230.253   <none>        8080/TCP                                                                                                                                     102m
kubeflow               service/metadata-service                               ClusterIP   10.100.22.65     <none>        8080/TCP                                                                                                                                     102m
kubeflow               service/metadata-ui                                    ClusterIP   10.100.15.132    <none>        80/TCP                                                                                                                                       102m
kubeflow               service/minio-service                                  ClusterIP   10.100.210.172   <none>        9000/TCP                                                                                                                                     102m
kubeflow               service/ml-pipeline                                    ClusterIP   10.100.230.173   <none>        8888/TCP,8887/TCP                                                                                                                            102m
kubeflow               service/ml-pipeline-ml-pipeline-visualizationserver    ClusterIP   10.100.54.36     <none>        8888/TCP                                                                                                                                     102m
kubeflow               service/ml-pipeline-tensorboard-ui                     ClusterIP   10.100.55.133    <none>        80/TCP                                                                                                                                       102m
kubeflow               service/ml-pipeline-ui                                 ClusterIP   10.100.223.104   <none>        80/TCP                                                                                                                                       102m
kubeflow               service/mysql                                          ClusterIP   10.100.249.178   <none>        3306/TCP                                                                                                                                     102m
kubeflow               service/notebook-controller-service                    ClusterIP   10.100.84.151    <none>        443/TCP                                                                                                                                      102m
kubeflow               service/profiles-kfam                                  ClusterIP   10.100.214.169   <none>        8081/TCP                                                                                                                                     102m
kubeflow               service/pytorch-operator                               ClusterIP   10.100.81.20     <none>        8443/TCP                                                                                                                                     102m
kubeflow               service/seldon-webhook-service                         ClusterIP   10.100.104.203   <none>        443/TCP                                                                                                                                      102m
kubeflow               service/tensorboard                                    ClusterIP   10.100.69.60     <none>        9000/TCP                                                                                                                                     102m
kubeflow               service/tf-job-operator                                ClusterIP   10.100.67.120    <none>        8443/TCP                                                                                                                                     102m
kubernetes-dashboard   service/dashboard-metrics-scraper                      ClusterIP   10.100.46.166    <none>        8000/TCP                                                                                                                                     103m
kubernetes-dashboard   service/kubernetes-dashboard                           ClusterIP   10.100.179.52    <none>        443/TCP                                                                                                                                      103m
monitoring             service/alertmanager-operated                          ClusterIP   None             <none>        9093/TCP,9094/TCP,9094/UDP                                                                                                                   102m
monitoring             service/metrics-server                                 ClusterIP   10.100.125.176   <none>        443/TCP                                                                                                                                      103m
monitoring             service/prometheus-operated                            ClusterIP   None             <none>        9090/TCP                                                                                                                                     102m
monitoring             service/prometheus-operator-alertmanager               ClusterIP   10.100.187.108   <none>        9093/TCP                                                                                                                                     102m
monitoring             service/prometheus-operator-grafana                    ClusterIP   10.100.119.44    <none>        80/TCP                                                                                                                                       102m
monitoring             service/prometheus-operator-kube-state-metrics         ClusterIP   10.100.232.82    <none>        8080/TCP                                                                                                                                     102m
monitoring             service/prometheus-operator-operator                   ClusterIP   10.100.113.126   <none>        8080/TCP,443/TCP                                                                                                                             102m
monitoring             service/prometheus-operator-prometheus                 ClusterIP   10.100.215.206   <none>        9090/TCP                                                                                                                                     102m
monitoring             service/prometheus-operator-prometheus-node-exporter   ClusterIP   10.100.245.197   <none>        9100/TCP                                                                                                                                     102m

NAMESPACE           NAME                                                          DESIRED   CURRENT   READY   UP-TO-DATE   AVAILABLE   NODE SELECTOR   AGE
amazon-cloudwatch   daemonset.apps/cloudwatch-agent                               6         6         6       6            6           <none>          103m
kube-system         daemonset.apps/aws-node                                       6         6         6       6            6           <none>          117m
kube-system         daemonset.apps/kube-proxy                                     6         6         6       6            6           <none>          117m
kubeflow            daemonset.apps/nvidia-device-plugin-daemonset                 6         6         6       6            6           <none>          102m
monitoring          daemonset.apps/prometheus-operator-prometheus-node-exporter   6         6         6       6            6           <none>          102m

NAMESPACE              NAME                                                          READY   UP-TO-DATE   AVAILABLE   AGE
cert-manager           deployment.apps/cert-manager                                  1/1     1            1           103m
cert-manager           deployment.apps/cert-manager-cainjector                       1/1     1            1           103m
cert-manager           deployment.apps/cert-manager-webhook                          1/1     1            1           103m
demo                   deployment.apps/podinfo                                       1/1     1            1           102m
flux                   deployment.apps/flux                                          1/1     1            1           109m
flux                   deployment.apps/helm-operator                                 1/1     1            1           109m
flux                   deployment.apps/memcached                                     1/1     1            1           109m
istio-system           deployment.apps/cluster-local-gateway                         1/1     1            1           103m
istio-system           deployment.apps/grafana                                       1/1     1            1           103m
istio-system           deployment.apps/istio-citadel                                 1/1     1            1           103m
istio-system           deployment.apps/istio-egressgateway                           1/1     1            1           103m
istio-system           deployment.apps/istio-galley                                  1/1     1            1           103m
istio-system           deployment.apps/istio-ingressgateway                          1/1     1            1           103m
istio-system           deployment.apps/istio-pilot                                   1/1     1            1           103m
istio-system           deployment.apps/istio-policy                                  1/1     1            1           103m
istio-system           deployment.apps/istio-sidecar-injector                        1/1     1            1           103m
istio-system           deployment.apps/istio-telemetry                               1/1     1            1           103m
istio-system           deployment.apps/istio-tracing                                 1/1     1            1           103m
istio-system           deployment.apps/kiali                                         1/1     1            1           103m
istio-system           deployment.apps/prometheus                                    1/1     1            1           103m
knative-serving        deployment.apps/activator                                     1/1     1            1           102m
knative-serving        deployment.apps/autoscaler                                    1/1     1            1           102m
knative-serving        deployment.apps/autoscaler-hpa                                1/1     1            1           102m
knative-serving        deployment.apps/controller                                    1/1     1            1           102m
knative-serving        deployment.apps/networking-istio                              1/1     1            1           102m
knative-serving        deployment.apps/webhook                                       1/1     1            1           102m
kube-system            deployment.apps/alb-ingress-controller                        1/1     1            1           103m
kube-system            deployment.apps/cluster-autoscaler                            1/1     1            1           103m
kube-system            deployment.apps/coredns                                       2/2     2            2           117m
kubeflow               deployment.apps/admission-webhook-deployment                  1/1     1            1           102m
kubeflow               deployment.apps/alb-ingress-controller                        1/1     1            1           102m
kubeflow               deployment.apps/argo-ui                                       1/1     1            1           102m
kubeflow               deployment.apps/centraldashboard                              1/1     1            1           102m
kubeflow               deployment.apps/jupyter-web-app-deployment                    1/1     1            1           102m
kubeflow               deployment.apps/katib-controller                              1/1     1            1           102m
kubeflow               deployment.apps/katib-db-manager                              1/1     1            1           102m
kubeflow               deployment.apps/katib-mysql                                   1/1     1            1           102m
kubeflow               deployment.apps/katib-ui                                      1/1     1            1           102m
kubeflow               deployment.apps/metadata-db                                   1/1     1            1           102m
kubeflow               deployment.apps/metadata-deployment                           1/1     1            1           102m
kubeflow               deployment.apps/metadata-envoy-deployment                     1/1     1            1           102m
kubeflow               deployment.apps/metadata-grpc-deployment                      1/1     1            1           102m
kubeflow               deployment.apps/metadata-ui                                   1/1     1            1           102m
kubeflow               deployment.apps/minio                                         1/1     1            1           102m
kubeflow               deployment.apps/ml-pipeline                                   1/1     1            1           102m
kubeflow               deployment.apps/ml-pipeline-ml-pipeline-visualizationserver   1/1     1            1           102m
kubeflow               deployment.apps/ml-pipeline-persistenceagent                  1/1     1            1           102m
kubeflow               deployment.apps/ml-pipeline-scheduledworkflow                 1/1     1            1           102m
kubeflow               deployment.apps/ml-pipeline-ui                                1/1     1            1           102m
kubeflow               deployment.apps/ml-pipeline-viewer-controller-deployment      1/1     1            1           102m
kubeflow               deployment.apps/mpi-operator                                  1/1     1            1           102m
kubeflow               deployment.apps/mysql                                         1/1     1            1           102m
kubeflow               deployment.apps/notebook-controller-deployment                1/1     1            1           102m
kubeflow               deployment.apps/profiles-deployment                           1/1     1            1           102m
kubeflow               deployment.apps/pytorch-operator                              1/1     1            1           102m
kubeflow               deployment.apps/seldon-controller-manager                     1/1     1            1           102m
kubeflow               deployment.apps/spark-operatorsparkoperator                   1/1     1            1           102m
kubeflow               deployment.apps/spartakus-volunteer                           1/1     1            1           102m
kubeflow               deployment.apps/tensorboard                                   1/1     1            1           102m
kubeflow               deployment.apps/tf-job-operator                               1/1     1            1           102m
kubeflow               deployment.apps/workflow-controller                           1/1     1            1           102m
kubernetes-dashboard   deployment.apps/dashboard-metrics-scraper                     1/1     1            1           103m
kubernetes-dashboard   deployment.apps/kubernetes-dashboard                          1/1     1            1           103m
monitoring             deployment.apps/metrics-server                                1/1     1            1           103m
monitoring             deployment.apps/prometheus-operator-grafana                   1/1     1            1           102m
monitoring             deployment.apps/prometheus-operator-kube-state-metrics        1/1     1            1           102m
monitoring             deployment.apps/prometheus-operator-operator                  1/1     1            1           102m

NAMESPACE              NAME                                                                     DESIRED   CURRENT   READY   AGE
cert-manager           replicaset.apps/cert-manager-cainjector-c578b68fc                        1         1         1       103m
cert-manager           replicaset.apps/cert-manager-fcc6cd946                                   1         1         1       103m
cert-manager           replicaset.apps/cert-manager-webhook-657b94c676                          1         1         1       103m
demo                   replicaset.apps/podinfo-785c7d877d                                       1         1         1       102m
flux                   replicaset.apps/flux-5b499cc67c                                          1         1         1       109m
flux                   replicaset.apps/helm-operator-6fd6b7fbfc                                 1         1         1       109m
flux                   replicaset.apps/memcached-7dd5ff9dcf                                     1         1         1       109m
istio-system           replicaset.apps/cluster-local-gateway-78f6cbff8d                         1         1         1       103m
istio-system           replicaset.apps/grafana-68bcfd88b6                                       1         1         1       103m
istio-system           replicaset.apps/istio-citadel-7dd6877d4d                                 1         1         1       103m
istio-system           replicaset.apps/istio-egressgateway-7c888bd9b9                           1         1         1       103m
istio-system           replicaset.apps/istio-galley-5bc58d7c89                                  1         1         1       103m
istio-system           replicaset.apps/istio-ingressgateway-866fb99878                          1         1         1       103m
istio-system           replicaset.apps/istio-pilot-67f9bd57b                                    1         1         1       103m
istio-system           replicaset.apps/istio-policy-749ff546dd                                  1         1         1       103m
istio-system           replicaset.apps/istio-sidecar-injector-cc5ddbc7                          1         1         1       103m
istio-system           replicaset.apps/istio-telemetry-6f6d8db656                               1         1         1       103m
istio-system           replicaset.apps/istio-tracing-84cbc6bc8                                  1         1         1       103m
istio-system           replicaset.apps/kiali-7879b57b46                                         1         1         1       103m
istio-system           replicaset.apps/prometheus-744f885d74                                    1         1         1       103m
knative-serving        replicaset.apps/activator-58595c998d                                     1         1         1       102m
knative-serving        replicaset.apps/autoscaler-7ffb4cf7d7                                    1         1         1       102m
knative-serving        replicaset.apps/autoscaler-hpa-686b99f459                                1         1         1       102m
knative-serving        replicaset.apps/controller-c6d7f946                                      1         1         1       102m
knative-serving        replicaset.apps/networking-istio-ff8674ddf                               1         1         1       102m
knative-serving        replicaset.apps/webhook-6d99c5dbbf                                       1         1         1       102m
kube-system            replicaset.apps/alb-ingress-controller-7bcbf5c669                        1         1         1       103m
kube-system            replicaset.apps/cluster-autoscaler-667f7596df                            1         1         1       103m
kube-system            replicaset.apps/coredns-5946c5d67c                                       2         2         2       117m
kubeflow               replicaset.apps/admission-webhook-deployment-59bc556b94                  1         1         1       102m
kubeflow               replicaset.apps/alb-ingress-controller-d99b66494                         1         1         1       102m
kubeflow               replicaset.apps/argo-ui-5f845464d7                                       1         1         1       102m
kubeflow               replicaset.apps/centraldashboard-d5c6d6bf                                1         1         1       102m
kubeflow               replicaset.apps/jupyter-web-app-deployment-544b7d5684                    1         1         1       102m
kubeflow               replicaset.apps/katib-controller-6b87947df8                              1         1         1       102m
kubeflow               replicaset.apps/katib-db-manager-54b64f99b                               1         1         1       102m
kubeflow               replicaset.apps/katib-mysql-74747879d7                                   1         1         1       102m
kubeflow               replicaset.apps/katib-ui-76f84754b6                                      1         1         1       102m
kubeflow               replicaset.apps/metadata-db-79d6cf9d94                                   1         1         1       102m
kubeflow               replicaset.apps/metadata-deployment-5dd4c9d4cf                           1         1         1       102m
kubeflow               replicaset.apps/metadata-envoy-deployment-5b9f9466d9                     1         1         1       102m
kubeflow               replicaset.apps/metadata-grpc-deployment-74f69954dc                      1         1         1       102m
kubeflow               replicaset.apps/metadata-ui-8968fc7d9                                    1         1         1       102m
kubeflow               replicaset.apps/minio-6b88d6499f                                         1         1         1       102m
kubeflow               replicaset.apps/ml-pipeline-698bcdd747                                   1         1         1       102m
kubeflow               replicaset.apps/ml-pipeline-ml-pipeline-visualizationserver-675656df79   1         1         1       102m
kubeflow               replicaset.apps/ml-pipeline-persistenceagent-7785884886                  1         1         1       102m
kubeflow               replicaset.apps/ml-pipeline-scheduledworkflow-7b4cb5d959                 1         1         1       102m
kubeflow               replicaset.apps/ml-pipeline-ui-5fbd94b9fb                                1         1         1       102m
kubeflow               replicaset.apps/ml-pipeline-viewer-controller-deployment-69fccfff8c      1         1         1       102m
kubeflow               replicaset.apps/mpi-operator-6494747f88                                  1         1         1       102m
kubeflow               replicaset.apps/mysql-7994454666                                         1         1         1       102m
kubeflow               replicaset.apps/notebook-controller-deployment-576589db9d                1         1         1       102m
kubeflow               replicaset.apps/profiles-deployment-5f77bb94c6                           1         1         1       102m
kubeflow               replicaset.apps/pytorch-operator-666dd4cd49                              1         1         1       102m
kubeflow               replicaset.apps/seldon-controller-manager-5d96986d47                     1         1         1       102m
kubeflow               replicaset.apps/spark-operatorsparkoperator-7c484c6859                   1         1         1       102m
kubeflow               replicaset.apps/spartakus-volunteer-84448b6b69                           1         1         1       102m
kubeflow               replicaset.apps/tensorboard-6549cd78c9                                   1         1         1       102m
kubeflow               replicaset.apps/tf-job-operator-7574b968b5                               1         1         1       102m
kubeflow               replicaset.apps/workflow-controller-6db95548dd                           1         1         1       102m
kubernetes-dashboard   replicaset.apps/dashboard-metrics-scraper-c44b4d655                      1         1         1       103m
kubernetes-dashboard   replicaset.apps/kubernetes-dashboard-7789d8fffc                          1         1         1       103m
monitoring             replicaset.apps/metrics-server-f78cb8cd8                                 1         1         1       103m
monitoring             replicaset.apps/prometheus-operator-grafana-79bd7f8f8c                   1         1         1       102m
monitoring             replicaset.apps/prometheus-operator-kube-state-metrics-66b4c95cd9        1         1         1       102m
monitoring             replicaset.apps/prometheus-operator-operator-7684f89b74                  1         1         1       102m

NAMESPACE    NAME                                                             READY   AGE
kubeflow     statefulset.apps/admission-webhook-bootstrap-stateful-set        1/1     102m
kubeflow     statefulset.apps/application-controller-stateful-set             1/1     103m
kubeflow     statefulset.apps/kfserving-controller-manager                    1/1     102m
kubeflow     statefulset.apps/metacontroller                                  1/1     102m
monitoring   statefulset.apps/alertmanager-prometheus-operator-alertmanager   1/1     102m
monitoring   statefulset.apps/prometheus-prometheus-operator-prometheus       1/1     102m

NAMESPACE         NAME                                                        REFERENCE                          TARGETS   MINPODS   MAXPODS   REPLICAS   AGE
istio-system      horizontalpodautoscaler.autoscaling/cluster-local-gateway   Deployment/cluster-local-gateway   30%/80%   1         5         1          103m
istio-system      horizontalpodautoscaler.autoscaling/istio-egressgateway     Deployment/istio-egressgateway     20%/80%   1         5         1          103m
istio-system      horizontalpodautoscaler.autoscaling/istio-ingressgateway    Deployment/istio-ingressgateway    30%/80%   1         5         1          103m
istio-system      horizontalpodautoscaler.autoscaling/istio-pilot             Deployment/istio-pilot             30%/80%   1         5         1          103m
istio-system      horizontalpodautoscaler.autoscaling/istio-policy            Deployment/istio-policy            20%/80%   1         5         1          103m
istio-system      horizontalpodautoscaler.autoscaling/istio-telemetry         Deployment/istio-telemetry         11%/80%   1         5         1          103m
knative-serving   horizontalpodautoscaler.autoscaling/activator               Deployment/activator               1%/100%   1         20        1          102m

NAMESPACE      NAME                                          COMPLETIONS   DURATION   AGE
istio-system   job.batch/istio-cleanup-secrets-1.1.6         1/1           26s        103m
istio-system   job.batch/istio-grafana-post-install-1.1.6    1/1           24s        103m
istio-system   job.batch/istio-security-post-install-1.1.6   1/1           14s        103m
kubeflow       job.batch/spark-operatorcrd-cleanup           1/1           33s        102m