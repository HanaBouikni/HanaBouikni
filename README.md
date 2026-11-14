<!-- Bannière -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:0F3460,100:58A6FF&height=220&section=header&text=Hana%20Bouikni&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Cybersecurity%20%E2%80%A2%20Blue%20Team%20%E2%80%A2%20Network%20Security&descAlignY=60&descSize=18&animation=fadeIn" alt="Hana Bouikni" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=600&lines=Cybers%C3%A9curit%C3%A9;SOC+%26+d%C3%A9tection;Forensique+%26+r%C3%A9ponse+aux+incidents;S%C3%A9curit%C3%A9+r%C3%A9seau;Cloud+security" alt="Cybersécurité · SOC &amp; détection · Forensique · Sécurité réseau · Cloud security" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=HanaBouikni&label=Profile%20views&color=58A6FF&style=flat-square" alt="Vues du profil" />
  <img src="https://img.shields.io/github/followers/HanaBouikni?label=Followers&style=flat-square&color=0F3460" alt="Followers" />
</p>

---

## 🛡️ À propos

```yaml
name:     Hana Bouikni
focus:    [Blue Team, SOC, Digital Forensics, Network Security, Cloud Security]
approach: "Build → Attack → Detect → Respond → Document"
```

Je conçois des **laboratoires de sécurité de bout en bout**. Je monte l'infrastructure, je l'attaque, je mets en place la détection et la réponse, puis je documente le tout dans un rapport technique détaillé.

---

## 🔄 Méthodologie

```mermaid
flowchart LR
    A["🏗️ Build<br/>AD · Linux · GNS3 · Terraform"] --> B["⚔️ Attack<br/>Kali · Impacket · Hydra · Ettercap"]
    B --> C["🔎 Detect<br/>Wazuh · Corrélation Python · MITRE ATT&CK"]
    C --> D["🚨 Respond<br/>Volatility 3 · iptables · YARA · WAF"]
    D --> E["📄 Document<br/>Rapport · IOCs · Remédiation"]
    E -. amélioration continue .-> A

    style A fill:#0F3460,stroke:#58A6FF,color:#fff
    style B fill:#5c1a1a,stroke:#ff6b6b,color:#fff
    style C fill:#0d3b2e,stroke:#39d353,color:#fff
    style D fill:#4a3500,stroke:#f0b429,color:#fff
    style E fill:#2d1b4e,stroke:#b392f0,color:#fff
```

---

## 🏆 Projet phare : Mini-SOC de détection Active Directory

```mermaid
flowchart LR
    K["💀 Kali Linux<br/>Rubeus · Impacket · Hydra"] -- "AS-REP Roasting<br/>Kerberoasting<br/>Brute-force" --> DC["🖥️ Contrôleur de domaine<br/>lab.local"]
    DC -- "Agent Wazuh<br/>Event IDs 4768 · 4769 · 4625" --> W["🛡️ Wazuh SIEM<br/>règles Kerberos custom"]
    W --> P["🐍 Moteur de corrélation<br/>Python + MITRE ATT&CK"]
    P --> R["📊 Rapport d'alertes<br/>JSON · HTML"]

    style K fill:#5c1a1a,stroke:#ff6b6b,color:#fff
    style DC fill:#0F3460,stroke:#58A6FF,color:#fff
    style W fill:#0d3b2e,stroke:#39d353,color:#fff
    style P fill:#4a3500,stroke:#f0b429,color:#fff
    style R fill:#2d1b4e,stroke:#b392f0,color:#fff
```

<p align="center">
  <a href="https://github.com/HanaBouikni/mini-soc-ad-detection"><img src="https://img.shields.io/badge/Voir_le_projet-mini--soc--ad--detection-58A6FF?style=for-the-badge&logo=github" alt="mini-soc-ad-detection" /></a>
</p>

---

## 🚀 Projets

<table>
<tr>
<td width="50%" valign="top">

### 📡 [WPA2-Enterprise](https://github.com/HanaBouikni/Securing-a-WLAN-with-WPA2-Enterprise)
Sécurisation d'un WLAN en 802.1X avec **Windows NPS (RADIUS)**, **AD CS (PKI)** et **hostapd**.

`802.1X` `RADIUS` `PKI` `PowerShell`

</td>
<td width="50%" valign="top">

### 🌐 [MPLS L3VPN sous GNS3](https://github.com/HanaBouikni/MPLS-L3VPN-sous-GNS3)
Réseau opérateur **BGP/MPLS VPN** (RFC 4364) avec deux clients isolés par **VRF** sur Cisco IOS.

`MPLS` `BGP` `OSPF` `LDP` `VRF`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔥 [Log4Shell Incident Report](https://github.com/HanaBouikni/Log4Shell-Incident-Report-CVE-2021-44228)
Réponse à **CVE-2021-44228** : détection JNDI, confinement, éradication, règles **WAF / YARA** et IOCs.

`Incident Response` `YARA` `WAF`

</td>
<td width="50%" valign="top">

### 🧠 [Volatility 3 Forensics](https://github.com/HanaBouikni/Volatility3-Forensics-Incident-Response)
Exploitation de **CVE-2021-3156**, capture mémoire **LiME** et analyse **Volatility 3**.

`Memory Forensics` `LiME` `Hydra`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☁️ [Cloud IAM Security Lab](https://github.com/HanaBouikni/cloud-iam-security-lab)
Identités, politiques et **moindre privilège** en Infrastructure as Code avec **Terraform**.

`IAM` `Terraform` `IaC`

</td>
<td width="50%" valign="top">

### 🔐 [Secure PGP Messaging](https://github.com/HanaBouikni/Secure-PGP-Messaging)
Messagerie client/serveur **chiffrée et signée** sur le modèle PGP.

`Cryptographie` `PGP` `Python`

</td>
</tr>
</table>

<details>
<summary><b>🧪 Autres laboratoires</b></summary>
<br/>

| Lab | Thème |
|-----|-------|
| [AppArmor-Simulation-CVE-2021-3156](https://github.com/HanaBouikni/AppArmor-Simulation-CVE-2021-3156) | Confinement AppArmor face à Baron Samedit |
| [Lynis-chkrootkit-Timeshift-Forensique-SSH](https://github.com/HanaBouikni/Lynis-chkrootkit-Timeshift-Forensique-SSH) | Audit et durcissement Linux, forensique des logs SSH |
| [ARP-Spoofing-Man-in-the-Middle-Attack](https://github.com/HanaBouikni/ARP-Spoofing-Man-in-the-Middle-Attack) | MITM avec Ettercap, Wireshark et sslstrip |
| [Configuration-serveur-NGINX](https://github.com/HanaBouikni/Configuration-serveur-NGINX) | Reverse proxy, load balancing, failover et HTTPS |
| [Systeme-d-Authentification-Securise](https://github.com/HanaBouikni/Systeme-d-Authentification-Securise) | Hachage, salage et gestion des sessions |
| [Cryptosystem](https://github.com/HanaBouikni/Cryptosystem) | Cryptographie classique, symétrique et asymétrique |

</details>

---

## 🧰 Outils et technologies

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,kali,ubuntu,windows,bash,powershell,python,c,docker,terraform,nginx,git,githubactions&perline=13" alt="Technologies" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Wazuh-SIEM-3595F9?style=for-the-badge" alt="Wazuh" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
  <img src="https://img.shields.io/badge/Volatility_3-Forensics-8B0000?style=for-the-badge" alt="Volatility 3" />
  <img src="https://img.shields.io/badge/MITRE_ATT%26CK-Mapping-C8102E?style=for-the-badge" alt="MITRE ATT&amp;CK" />
  <img src="https://img.shields.io/badge/YARA-Rules-4B0082?style=for-the-badge" alt="YARA" />
  <br/>
  <img src="https://img.shields.io/badge/Cisco_IOS-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" alt="Cisco IOS" />
  <img src="https://img.shields.io/badge/GNS3-Labs-2E8B57?style=for-the-badge" alt="GNS3" />
  <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Active Directory" />
  <img src="https://img.shields.io/badge/AppArmor-Hardening-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="AppArmor" />
  <img src="https://img.shields.io/badge/802.1X-RADIUS-555555?style=for-the-badge" alt="802.1X RADIUS" />
</p>

---

## 📊 Statistiques GitHub

<p align="center">
  <img src="https://raw.githubusercontent.com/HanaBouikni/HanaBouikni/main/profile-summary-card-output/github_dark/0-profile-details.svg" width="98%" alt="Profil" />
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/HanaBouikni/HanaBouikni/main/profile-summary-card-output/github_dark/1-repos-per-language.svg" width="32%" alt="Repos par langage" />
  <img src="https://raw.githubusercontent.com/HanaBouikni/HanaBouikni/main/profile-summary-card-output/github_dark/2-most-commit-language.svg" width="32%" alt="Langages les plus commités" />
  <img src="https://raw.githubusercontent.com/HanaBouikni/HanaBouikni/main/profile-summary-card-output/github_dark/3-stats.svg" width="32%" alt="Stats" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=HanaBouikni&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="Série de contributions" />
</p>

---

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/HanaBouikni/HanaBouikni/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/HanaBouikni/HanaBouikni/output/snake.svg" />
  <img alt="Animation du serpent sur le graphe de contributions" src="https://raw.githubusercontent.com/HanaBouikni/HanaBouikni/output/snake.svg" />
</picture>

<!-- Pied de page -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,50:0F3460,100:0D1117&height=120&section=footer" width="100%" alt="" />
</p>
