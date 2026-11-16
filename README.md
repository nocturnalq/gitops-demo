# gitops-demo

Источник истины для демо лекции «GitOps» (Flux Operator + podinfo).
Кластер не получает `kubectl apply` от людей: Flux сам забирает этот репозиторий и сводит кластер к нему.

- `clusters/kind/` - что должно быть в кластере kind, сюда смотрит FluxInstance.
- `apps/podinfo/` - само приложение: namespace, Deployment, Service и временный эксперимент.
