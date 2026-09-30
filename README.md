<div align="center">

<img src="banner.svg" alt="Costel I. — DevOps Engineer" width="860" />

<br/>

<a href="mailto:iacobcostel03@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
</a>
<a href="https://github.com/Costel03?tab=repositories">
  <img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"/>
</a>
<a href="https://github.com/Costel03/Costel.I-UTM-Info-ID">
  <img src="https://img.shields.io/badge/UTM%20Notes-0A66C2?style=for-the-badge&logo=gitbook&logoColor=white" alt="UTM Notes"/>
</a>
<img src="https://komarev.com/ghpvc/?username=Costel03&color=58a6ff&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views"/>

<img src="https://img.shields.io/github/followers/Costel03?style=flat-square&color=58a6ff&labelColor=0d1117&logo=github&logoColor=white" alt="Followers"/>
<img src="https://img.shields.io/github/stars/Costel03?style=flat-square&color=58a6ff&labelColor=0d1117&logo=github&logoColor=white" alt="Stars"/>

</div>

---

## 🧑‍💻 About Me

```yaml
name:      "Costel I."
location:  "Bucharest, RO"
education: "UTM — Informatica ID"
role:      "DevOps Engineer"
focus:
  - "Kubernetes & GitOps"
  - "Infrastructure as Code"
  - "CI/CD pipelines"
  - "Observability & secrets management"
currently_learning:
  - "CKA — Certified Kubernetes Administrator"
  - "Platform engineering patterns"
  - "Terraform & AWS at scale"
fun_fact:  "I automate everything — including my free time 🤖"
```

---

## 🧪 What I'm Building

A self-hosted Kubernetes homelab, split the way a real platform is:

| Layer | Repo | What lives there |
|---|---|---|
| **Bootstrap** | [homelab-cluster](https://github.com/Costel03/homelab-cluster) | VirtualBox VMs + kubeadm, MetalLB and Argo CD — the pieces GitOps cannot install for itself |
| **GitOps** | [homelab-gitops](https://github.com/Costel03/homelab-gitops) | Everything Argo CD syncs: ingress, monitoring, Vault, ESO, cert-manager — one directory per tool |
| **Cloud** | [aws-kubernetes-automation](https://github.com/Costel03/aws-kubernetes-automation) | The same cluster story on AWS, with Terraform + Ansible |
| **Config mgmt** | [Ansible-demo](https://github.com/Costel03/Ansible-demo) | LAMP + WordPress + NFS across four Vagrant VMs |

Not everything lives on GitHub. At work I built an **RKE2** cluster from scratch with **mixed Linux and Windows node pools** — Windows workers rule out a default install: they need their own container runtime, a CNI that supports them, and per-OS scheduling so workloads land on the right nodes.

And a teaching tool I wrote for myself:

**[`linux-curs-interactiv.sh`](https://github.com/Costel03/Costel.I-UTM-Info-ID/blob/Anul-II/Anul%20I/Semestrul%20II/Sisteme%20de%20operare/Teme/linux-curs-interactiv.sh)** — an interactive Bash script for practising Linux commands, built on the **InfoAcademy Linux** course (chapters 3–8, 12, 13). Menu-driven: each chapter gives the theory, then you run the commands yourself and see the output framed with its exit code. Covers the filesystem, users and permissions, processes and signals, shell scripting, package management, networking, Postfix and chrony.

---

## 🛠️ Tech Stack

| | |
|---|---|
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Amazon EKS](https://img.shields.io/badge/Amazon%20EKS-FF9900?style=flat-square&logo=amazoneks&logoColor=white) ![Azure AKS](https://img.shields.io/badge/Azure%20AKS-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) |
| **Containers & Orchestration** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![Ingress NGINX](https://img.shields.io/badge/Ingress%20NGINX-009639?style=flat-square&logo=nginx&logoColor=white) ![Rancher](https://img.shields.io/badge/Rancher-0075A8?style=flat-square&logo=rancher&logoColor=white) ![RKE2](https://img.shields.io/badge/RKE2-0075A8?style=flat-square&logo=rancher&logoColor=white) ![Kubernetes Dashboard](https://img.shields.io/badge/K8s%20Dashboard-326CE5?style=flat-square&logo=kubernetes&logoColor=white) |
| **GitOps & CI/CD** | ![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Infrastructure as Code** | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![AWX](https://img.shields.io/badge/AWX-EE0000?style=flat-square&logo=ansible&logoColor=white) ![Vagrant](https://img.shields.io/badge/Vagrant-1563FF?style=flat-square&logo=vagrant&logoColor=white) ![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=flat-square&logo=virtualbox&logoColor=white) |
| **Observability** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-F46800?style=flat-square&logo=grafana&logoColor=white) |
| **Secrets & Certificates** | ![Vault](https://img.shields.io/badge/HashiCorp%20Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black) ![External Secrets Operator](https://img.shields.io/badge/External%20Secrets%20Operator-5A67D8?style=flat-square&logo=kubernetes&logoColor=white) ![cert-manager](https://img.shields.io/badge/cert--manager-326CE5?style=flat-square&logo=letsencrypt&logoColor=white) |
| **Registries & Artifacts** | ![Zot](https://img.shields.io/badge/Zot-4A4A4A?style=flat-square&logo=opencontainersinitiative&logoColor=white) ![Amazon ECR](https://img.shields.io/badge/Amazon%20ECR-FF9900?style=flat-square&logo=amazonecs&logoColor=white) ![Azure ACR](https://img.shields.io/badge/Azure%20ACR-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Artifactory](https://img.shields.io/badge/Artifactory-41BF47?style=flat-square&logo=jfrog&logoColor=white) |
| **OS & Scripting** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![Rocky Linux](https://img.shields.io/badge/Rocky%20Linux-10B981?style=flat-square&logo=rockylinux&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat-square&logo=yaml&logoColor=white) ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) |

**Day-to-day**

![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white)
![ServiceNow](https://img.shields.io/badge/ServiceNow-62D84E?style=flat-square&labelColor=293e40)
![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?style=flat-square&logo=visualstudiocode&logoColor=white)
![Notepad++](https://img.shields.io/badge/Notepad%2B%2B-90E59A?style=flat-square&logo=notepadplusplus&logoColor=black)
![KeePass](https://img.shields.io/badge/KeePass-6CAC4D?style=flat-square&logo=keepassxc&logoColor=white)
![Citrix NetScaler](https://img.shields.io/badge/Citrix%20NetScaler-452170?style=flat-square&logo=citrix&logoColor=white)
![VMware Horizon](https://img.shields.io/badge/VMware%20Horizon-607078?style=flat-square&logo=vmware&logoColor=white)
![MobaXterm](https://img.shields.io/badge/MobaXterm-2E4053?style=flat-square&logo=windowsterminal&logoColor=white)
![Terminator](https://img.shields.io/badge/Terminator-121011?style=flat-square&logo=gnometerminal&logoColor=white)
![Vim](https://img.shields.io/badge/Vi%20%2F%20Vim-019733?style=flat-square&logo=vim&logoColor=white)
![nano](https://img.shields.io/badge/nano-4A4A4A?style=flat-square&logo=gnu&logoColor=white)

**Familiar with** — used, but not my strongest ground

![Jenkins](https://img.shields.io/badge/Jenkins-4A5568?style=flat-square&logo=jenkins&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-4A5568?style=flat-square&logo=istio&logoColor=white)
![GCP](https://img.shields.io/badge/GCP%20%2F%20GKE-4A5568?style=flat-square&logo=googlecloud&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk%20(infrastructure)-4A5568?style=flat-square&logo=splunk&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4A5568?style=flat-square&logo=sonarqube&logoColor=white)
![JFrog Xray](https://img.shields.io/badge/JFrog%20Xray-4A5568?style=flat-square&logo=jfrog&logoColor=white)
![LDAP](https://img.shields.io/badge/LDAP-4A5568?style=flat-square&logo=openid&logoColor=white)
![RHEL](https://img.shields.io/badge/RHEL%20%2F%20CentOS-4A5568?style=flat-square&logo=redhat&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4A5568?style=flat-square&logo=postgresql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-4A5568?style=flat-square&logo=mariadb&logoColor=white)

---

## 📌 Featured Projects

<div align="center">

[![homelab-cluster](https://github-readme-stats-git-master-rickstaa.vercel.app/api/pin/?username=Costel03&repo=homelab-cluster&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=cdd9e5&icon_color=58a6ff)](https://github.com/Costel03/homelab-cluster)
[![homelab-gitops](https://github-readme-stats-git-master-rickstaa.vercel.app/api/pin/?username=Costel03&repo=homelab-gitops&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=cdd9e5&icon_color=58a6ff)](https://github.com/Costel03/homelab-gitops)

[![aws-kubernetes-automation](https://github-readme-stats-git-master-rickstaa.vercel.app/api/pin/?username=Costel03&repo=aws-kubernetes-automation&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=cdd9e5&icon_color=58a6ff)](https://github.com/Costel03/aws-kubernetes-automation)
[![Ansible-demo](https://github-readme-stats-git-master-rickstaa.vercel.app/api/pin/?username=Costel03&repo=Ansible-demo&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=cdd9e5&icon_color=58a6ff)](https://github.com/Costel03/Ansible-demo)

[![Costel.I-UTM-Info-ID](https://github-readme-stats-git-master-rickstaa.vercel.app/api/pin/?username=Costel03&repo=Costel.I-UTM-Info-ID&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=cdd9e5&icon_color=58a6ff)](https://github.com/Costel03/Costel.I-UTM-Info-ID)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="165em" src="https://github-readme-stats-git-master-rickstaa.vercel.app/api?username=Costel03&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=cdd9e5" alt="GitHub Stats"/>
<img height="165em" src="https://github-readme-stats-git-master-rickstaa.vercel.app/api/top-langs/?username=Costel03&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=cdd9e5&langs_count=8" alt="Top Languages"/>

<img src="https://streak-stats.demolab.com/?user=Costel03&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=58a6ff&ring=58a6ff&fire=ff6b6b&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e" alt="GitHub Streak"/>

<img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Costel03&theme=github_dark" alt="Repos per Language"/>
<img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Costel03&theme=github_dark&utcOffset=3" alt="Productive Time"/>

</div>

---

<div align="center">

*"The best infrastructure is the one you never have to think about."*

**Thanks for stopping by — feel free to explore my repos and reach out! 🚀**

</div>
