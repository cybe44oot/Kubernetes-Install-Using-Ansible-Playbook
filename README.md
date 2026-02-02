# Kubernetes Installation Using Ansible

This repository provides an Ansible-based setup to install Kubernetes.

---

## Prerequisites

- Ansible installed
- Access to target nodes
- Kubernetes binaries installed by the playbook

---

## Installation

From the project directory, run:

```bash
ansible-playbook main.yml
```

## Verify the Cluster

- After the playbook completes, verify that the nodes are up and ready:
```yaml
kubectl get nodes
```

## Enable kubectl Autocompletion (Optional but Recommended)

- Adding kubectl autocompletion makes CLI usage easier.

Append the following line to your .bashrc file:

```yaml
echo 'source <(kubectl completion bash)' >> ~/.bashrc
```

Reload the configuration:

```yaml
source ~/.bashrc
```



---

### ✅ Why this README works
- Simple and professional
- Clear execution steps
- No assumptions beyond what you said

