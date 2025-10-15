# helm-charts
helm charts


# github actions workflow

on k3s cluster control plane:
copy /etc/rancher/k3s/k3s.yaml and edit server to be public ip of ec2 instance
cat this_config | base64

copy this to github actions secret KUBECONFIG_B64

