# kubeschemas

Kubernetes json schemas generated by [kubeschema](https://github.com/imroc/kubeschema).

## kubernetes.nvim

These schemas are used by [kubernetes.nvim](https://github.com/imroc/kubernetes.nvim).

## Schemas

`kubeschemas` is include kubernetes buitin resource types and some public well known CRDs:

- [Gateway API](https://gateway-api.sigs.k8s.io/guides/#install-standard-channel)
- [MCS API](https://github.com/kubernetes-sigs/mcs-api/tree/master/config/crd)
- [Istio](https://istio.io/latest/docs/setup/install/helm/)
- [Envoy Gateway](https://github.com/envoyproxy/gateway/tree/main/charts/gateway-helm/crds)
- [Cilium](https://github.com/cilium/cilium/tree/main/pkg/k8s/apis/cilium.io/client/crds)
- [APISIX](https://github.com/apache/apisix-helm-chart/tree/master/charts/apisix-ingress-controller/crds)
- [Higress](https://github.com/alibaba/higress/tree/main/helm/core/crds)
- [Traefik](https://github.com/traefik/traefik-helm-chart/tree/master/traefik/crds)
- [Kong](https://github.com/Kong/kubernetes-configuration/tree/main/config/crd)
- [cert-manager](https://github.com/cert-manager/cert-manager/tree/master/deploy/crds)
- [opentelemetry-operator](https://github.com/open-telemetry/opentelemetry-helm-charts/tree/main/charts/opentelemetry-operator/conf/crds)
- [Ambassador Edge Stack](https://www.getambassador.io/docs/edge-stack/latest/tutorials/getting-started)
- [Karmada](https://github.com/karmada-io/karmada/tree/master/charts/karmada/_crds) and [Karmada Operator](https://github.com/karmada-io/karmada/tree/master/charts/karmada-operator/crds)
- [Clusternet](https://github.com/clusternet/clusternet/tree/main/manifests/crds)
- [Tencent Cloud TKE](https://cloud.tencent.com/product/tke)
- [Huawei Cloud CCE](https://www.huaweicloud.com/product/cce.html)
- [Google Cloud GKE](https://cloud.google.com/kubernetes-engine)
- [AWS EKS](https://aws.amazon.com/eks/)
- [spark-operator](https://github.com/kubeflow/spark-operator/tree/master/charts/spark-operator-chart/crds)
- [flink-operator](https://github.com/apache/flink-kubernetes-operator/tree/main/helm/flink-kubernetes-operator/crds)
- [karpenter](https://github.com/kubernetes-sigs/karpenter/tree/main/pkg/apis/crds)
- [kruise](https://openkruise.io/docs/installation/), [kruise-rollout](https://openkruise.io/rollouts/installation) and [kruise-game](https://openkruise.io/kruisegame/installation)
- [argo-cd](https://github.com/argoproj/argo-cd/tree/master/manifests/crds), [argo-workflows](https://github.com/argoproj/argo-workflows/tree/main/manifests/base/crds), [argo-rollouts](https://github.com/argoproj/argo-rollouts/tree/master/manifests/crds) and [argo-events](https://github.com/argoproj/argo-events/tree/master/manifests/base/crds)
- [tekton-operator](https://github.com/tektoncd/operator/blob/main/docs/install.md), [tekton-pipeline](https://github.com/tektoncd/pipeline/blob/main/docs/install.md), [tekton-triggers](https://github.com/tektoncd/triggers/blob/main/docs/install.md)
- [zalando postgres-operator](https://github.com/zalando/postgres-operator/tree/master/charts/postgres-operator/crds) and [CrunchyData postgres-operator](https://github.com/CrunchyData/postgres-operator-examples/tree/main/helm/install/crds)
- [OPA gatekeeper](https://github.com/open-policy-agent/gatekeeper/tree/master/charts/gatekeeper/crds)
- [velero](https://github.com/vmware-tanzu/velero/tree/main/config/crd)
- [knative-operator](https://knative.dev/docs/install/operator/knative-with-operators/#install-the-knative-operator), [knative-serving](https://knative.dev/docs/install/yaml-install/serving/install-serving-with-yaml/#install-the-knative-serving-component) and [knative-eventing](https://knative.dev/docs/install/yaml-install/eventing/install-eventing-with-yaml/#install-knative-eventing)

And some kubernetes related configuration file schemas are also included:

- kubeconfig
- kind configuration
- k3d configuration

## Contributing

You can add more schemas by running `kubeschema dump --index` in the root directory of git repo to dump schemas from current kubernetes cluster.

PRs are welcome!
