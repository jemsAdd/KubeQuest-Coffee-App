# ☕ KubeQuest: The Ethiopian Coffee App
**Status:** Lab Complete 🚀 | **Focus:** Kubernetes Networking & High Availability

## 📖 Overview
This project demonstrates the transition from ephemeral pod management to a stable, self-healing Kubernetes infrastructure using Rancher Desktop.

---

## 🛠️ Skills Demonstrated

### 1. Deployment Management (Scaling)
* **Goal:** Moving from single points of failure to multiple replicas.
* **Code:** ```powershell
  kubectl create deployment coffee-machine --image=nginx --replicas=3
