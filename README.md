# kubeschemas

`kubeschemas` contains massive public maintained kubernetes json schema (3200+ types), including all kubernetes buitin resource types, well known CRDs and kubernetes related configuration file.

## kubeschema.nvim

These schemas are used by [kubeschema.nvim](https://github.com/imroc/kubeschema.nvim).

## kubernetes builtin resource types

All Kubernetes builtin resource types are supported (e.g. `Deployment`, `ConfigMap`, `StatefulSet` and etc).

## CRDs

A lot of public well known CRDs are supported (generated by [kubeschema](https://github.com/imroc/kubeschema)):

CRDs from cloud vendor:

- [Tencent Cloud TKE](https://cloud.tencent.com/product/tke)
- [Huawei Cloud CCE](https://www.huaweicloud.com/product/cce.html)
- [Google Cloud GKE](https://cloud.google.com/kubernetes-engine)
- [Alibaba Cloud ACK](https://www.aliyun.com/product/kubernetes)
- [AWS EKS](https://aws.amazon.com/eks/)

CRDs from open source project:

- [Gateway API](https://gateway-api.sigs.k8s.io/guides/#install-standard-channel)
- [MCS API](https://github.com/kubernetes-sigs/mcs-api/tree/master/config/crd)
- [Istio](https://istio.io/latest/docs/setup/install/helm/)
- [Envoy Gateway](https://github.com/envoyproxy/gateway/tree/main/charts/gateway-helm/crds) (including [ai-gateway](https://github.com/envoyproxy/ai-gateway/tree/main/manifests/charts/ai-gateway-helm/crds))
- [Cilium](https://github.com/cilium/cilium/tree/main/pkg/k8s/apis/cilium.io/client/crds) and [Tetragon](https://github.com/cilium/tetragon/tree/main/install/kubernetes/tetragon/crds-yaml)
- [APISIX](https://github.com/apache/apisix-helm-chart/tree/master/charts/apisix-ingress-controller/crds)
- [Higress](https://github.com/alibaba/higress/tree/main/helm/core/crds)
- [Traefik](https://github.com/traefik/traefik-helm-chart/tree/master/traefik/crds)
- [Kong](https://github.com/Kong/kubernetes-configuration/tree/main/config/crd)
- [Contour](https://github.com/projectcontour/contour/blob/main/examples/contour/01-crds.yaml)
- [cert-manager](https://github.com/cert-manager/cert-manager/tree/master/deploy/crds)
- [opentelemetry-operator](https://github.com/open-telemetry/opentelemetry-helm-charts/tree/main/charts/opentelemetry-operator/conf/crds)
- [Ambassador Edge Stack](https://www.getambassador.io/docs/edge-stack/latest/tutorials/getting-started)
- [karmada](https://github.com/karmada-io/karmada/tree/master/charts/karmada/_crds) and [karmada-operator](https://github.com/karmada-io/karmada/tree/master/charts/karmada-operator/crds)
- [clusternet](https://github.com/clusternet/clusternet/tree/main/manifests/crds)
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
- [volcano](https://github.com/volcano-sh/volcano/tree/master/config/crd)
- [linkerd](https://linkerd.io/2.17/getting-started/#step-3-install-linkerd-onto-your-cluster)
- [agones](https://agones.dev/site/docs/installation/install-agones/yaml/)
- [crane](https://github.com/gocrane/helm-charts/tree/main/charts/crane/crds)
- [KubeEdge](https://github.com/kubeedge/kubeedge/tree/master/manifests/charts/cloudcore/crds)
- [OpenYurt](https://github.com/openyurtio/openyurt)
- [tidb-operator](https://github.com/pingcap/tidb-operator/tree/master/manifests/crd)
- [prometheus-operator](https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack/charts/crds/crds)
- [kuberhealthy](https://github.com/kuberhealthy/kuberhealthy/tree/master/deploy/helm/kuberhealthy/crds)
- [k3s](https://github.com/k3s-io/k3s)
- [k0s](https://github.com/k0sproject/k0s/tree/main/static/_crds)
- [mongodb atlas-operator](https://github.com/mongodb/helm-charts/tree/main/charts/atlas-operator-crds), [mongodb community-operator](https://github.com/mongodb/helm-charts/tree/main/charts/community-operator-crds) and [mongodb enterprise-operator](https://github.com/mongodb/helm-charts/tree/main/charts/enterprise-operator/crds)
- [dragonfly-operator](https://raw.githubusercontent.com/dragonflydb/dragonfly-operator/refs/heads/main/manifests/crd.yaml)
- [fluxcd](https://github.com/fluxcd/flux2/blob/main/manifests/crds/kustomization.yaml)
- [flagger](https://raw.githubusercontent.com/fluxcd/flagger/refs/heads/main/charts/flagger/crds/crd.yaml)
- [actions-runner-controller](https://github.com/actions/actions-runner-controller/tree/master/config/crd)
- [Sealed Secrets](https://raw.githubusercontent.com/bitnami-labs/sealed-secrets/refs/heads/main/helm/sealed-secrets/crds/bitnami.com_sealedsecrets.yaml)
- [kapp-controller](https://raw.githubusercontent.com/carvel-dev/kapp-controller/refs/heads/develop/config/config/crds.yml)
- [terraform-controller](https://github.com/kubevela/terraform-controller/tree/master/chart/crds)
- [SMI](https://github.com/servicemeshinterface/smi-sdk-go/tree/main/crds)
- [kaito](https://github.com/kaito-project/kaito/tree/main/config/crd)
- [calico](https://github.com/projectcalico/calico)
- [kserve](https://github.com/kserve/kserve/tree/master/config/crd)
- [MetalLB](https://github.com/metallb/metallb/tree/main/config/crd)
- [FRR-k8s](https://github.com/metallb/frr-k8s/tree/main/config/crd)
- [KusionStack](https://www.kusionstack.io/) ([kuperator](https://github.com/KusionStack/kuperator/tree/main/config/crd), [rollout](https://github.com/KusionStack/rollout), [controller-mesh](https://github.com/KusionStack/controller-mesh/tree/main/config/crd))
- [KubeVirt](https://kubevirt.io/quickstart_cloud/)
- [KubeOVN](https://github.com/kubeovn/kube-ovn/blob/master/charts/kube-ovn/templates/kube-ovn-crd.yaml)
- [Meshery](https://github.com/meshery/meshery/blob/master/install/kubernetes/helm/meshery-operator/crds/crds.yaml)
- [Consul](https://github.com/hashicorp/consul-k8s/tree/main/charts/consul/templates)
- [Kuma](https://github.com/kumahq/kuma/tree/master/deployments/charts/kuma/crds)
- [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt-operator)
- [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh/tree/master/config/crd)
- [Kubewarden](https://github.com/kubewarden/kubewarden-controller/tree/main/config/crd)
- [kmesh](https://github.com/kmesh-net/kmesh/tree/main/deploy/yaml/crd)
- [Litmus Chaos](https://docs.litmuschaos.io/docs/getting-started/installation)
- [Network Service Mesh](https://github.com/networkservicemesh/nsm-operator/tree/master/config/crd)
- [Keycloak Operator](https://www.keycloak.org/operator/installation#_installing_by_using_kubectl_without_operator_lifecycle_manager)
- [Kuadrant](https://kuadrant.io/) ([Kuadrant Operator](https://github.com/Kuadrant/kuadrant-operator/tree/main/config/crd), [dns-operator](https://github.com/Kuadrant/dns-operator/tree/main/charts/dns-operator), [Limitador Operator](https://github.com/Kuadrant/limitador-operator/tree/main/config/crd), [Authorino Operator](https://github.com/Kuadrant/authorino-operator/tree/main/config/crd))
- [fluid](https://github.com/fluid-cloudnative/fluid/tree/master/config/crd)
- [KubeBlocks](https://github.com/apecloud/kubeblocks/tree/main/config/crd)
- [lws](https://github.com/kubernetes-sigs/lws/tree/main/config/crd)(LeaderWorkerSet)
- [LoxiLB](https://github.com/loxilb-io/kube-loxilb/tree/main/manifest/crds)
- [AIBrix](https://github.com/vllm-project/aibrix/tree/main/config/crd)
- [KubeAI](https://github.com/substratusai/kubeai/tree/main/charts/kubeai/templates/crds)
- [kagent](https://github.com/kagent-dev/kagent/tree/main/helm/crds)
- [Kairos](https://github.com/kairos-io/cluster-api-provider-kairos)
- [tke-extend-network-controller](https://github.com/tkestack/tke-extend-network-controller)
- [kgateway](https://github.com/kgateway-dev/kgateway/tree/main/install/helm/kgateway-crds/templates)
- [external-dns](https://github.com/kubernetes-sigs/external-dns/tree/master/charts/external-dns/crds)
- [fdb-operator](https://github.com/FoundationDB/fdb-kubernetes-operator/tree/main/config/crd/bases)
- [OpenShift](https://github.com/openshift) ([operator-framework-olm](https://github.com/openshift/operator-framework-olm/tree/master), [microshift](https://github.com/openshift/microshift/tree/main/assets/crd), [hypershift](https://github.com/openshift/hypershift), [lvm-operator](https://github.com/openshift/lvm-operator/tree/main/config/crd/bases), [sriov-network-operator](https://github.com/openshift/sriov-network-operator/tree/master/config/crd), [cloud-credential-operator](https://github.com/openshift/cloud-credential-operator) and etc).
- [Rancher](https://www.rancher.com/) ([fleet](https://github.com/rancher/fleet/blob/main/charts/fleet-crd/templates/crds.yaml), [cis-operator](https://github.com/rancher/cis-operator/tree/main/crds), [k3k](https://github.com/rancher/k3k/tree/main/charts/k3k/crds) and etc).
- [KubeSphere](https://kubesphere.io/) (include [KubeKey](https://github.com/kubesphere/kubekey))

## Configuration File

Some kubernetes related configuration file schemas are also included:

- [Kubernetes Configuration APIs](https://kubernetes.io/docs/reference/config-api/) (e.g. kubeconfig, kubeadm/kubelet/kube-proxy/kube-apiserver/controller-manager/kube-scheduler configuration files and etc)
- [Kind Configuration](https://kind.sigs.k8s.io/docs/user/configuration/)
- [K3D Config File](https://k3d.io/stable/usage/configfile/)
- [EnvoyGateway Config File](https://github.com/envoyproxy/gateway/blob/main/api/v1alpha1/envoygateway_types.go)

## Contributing

You can add more schemas by running `kubeschema dump --index` in the root directory of git repo to dump schemas from current kubernetes cluster.

PRs are welcome!
