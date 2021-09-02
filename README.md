# Practicum-7.4

1) Установил Terraform.
2) Установил Kubectl.
3) Изучил документацию по работе с облаком Яндекса.
4) Создал Terraform-скрипт, который развернет две виртуальные машины с внешними IP-адресами.
5) Установите на обе ваши машины kubeadm, следуя инструкциям из документации.
6) Настроил вторую машину как воркер-ноду, используя kubeadm join.
7) Установил Kubernetes dashboard, выполнив:
  kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.0.0/aio/deploy/recommended.yaml
8) Запустил команду: kubectl proxy
9) Установил ssh-tunnel с мастер ноды до моего PC чтоб получить локальный доступ к  Kubernetes dashboard
