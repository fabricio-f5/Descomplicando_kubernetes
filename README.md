
```markdown
# Descomplicando Kubernetes - Linuxtips

Repositório de exemplos e exercícios do curso **Descomplicando Kubernetes** da Linuxtips.

---

## Conteúdo

- Arquivos YAML de Pods, Deployments e Services
- Exemplos de clusters locais
- Anotações e experimentos do curso

---

## Como usar

1. Clone este repositório:
```bash
git clone https://github.com/seuusuario/Descomplicando_kubernetes.git
cd Descomplicando_kubernetes
````

2. Suba o cluster local (usando `kind` ou outra ferramenta):

```bash
kind create cluster --config cluster.yaml
```

3. Aplique os recursos no Kubernetes:

```bash
kubectl apply -f pod.yaml
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```

---

## Referências

* Curso **Descomplicando Kubernetes** - [Linuxtips](https://www.linuxtips.io/)
* Documentação oficial do Kubernetes: [https://kubernetes.io/docs/](https://kubernetes.io/docs/)

---

## Licença

Este repositório é aberto para estudo e aprendizado.

```
Quer que eu faça essa versão aprimorada?
```
