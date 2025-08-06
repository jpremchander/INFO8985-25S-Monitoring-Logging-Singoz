# K8S SigNoz Infra Monitoring [https://s4z.exotrend.live]


## 🛠 Setup Instructions

### Prerequisites

- Kubernetes cluster (tested on vSphere)
- Helm installed
- Ansible installed
- SigNoz running on Docker (collector reachable via host IP)

### 🔼 To Deploy Agent

```bash
ansible-playbook ansible/up.yaml
```

### 🔽 To Uninstall Agent

```bash
ansible-playbook ansible/down.yaml
```

## 📦 What’s Included

- `up.yaml` and `down.yaml`: Ansible playbooks
- `values.yaml`: Helm chart override for OTEL collector IP/port
- `screenshots/`


## 📸 Screenshots

- SigNoz hosts
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/acd17e98-bcb4-4a71-99a8-8100edd6c946" />

- Metrics showing up

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/10b99d75-108f-4802-8eeb-38b59a544f7f" />

- Rolldice telemetry
