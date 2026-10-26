# État du SI au 23/10/2026

## SRV-DC01 - 10.10.0.10

- Windows Server
- AD DS installé
- DNS installé
- DHCP installé
- GPO_MAJ_Windows configurée

## SRV-WEB01 - 10.10.0.20

- Debian 13
- SSH actif
- UFW configuré
- Compte ansible configuré
- rsyslog installé
- Envoi des journaux vers SRV-ADM01

## SRV-ADM01 - 10.10.0.30

- Debian 13
- Ansible installé
- apt-cacher-ng installé
- UFW configuré
- Réception centralisée des journaux rsyslog
- Synchronisation NTP via SRV-DC01

## Points ouverts

- Étape 5 non réalisée : scripts de panne non fournis
- Validation finale en attente
