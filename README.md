# Penetration Testing — Metasploitable 2 (Lab)

**Autore:** Adriano Tumino  
**Ambiente:** Laboratorio isolato Metasploitable 2 (Ubuntu 8.04)  
**Metodo:** PTES Standard

## ⚠️ Disclaimer e Avviso di Sicurezza
**ATTENZIONE**: Questo repository contiene documentazione di penetration test eseguiti **esclusivamente** sulla VM Metasploitable 2 in ambiente di laboratorio isolato.
### 🚫 Utilizzo Consentito
- Studio e apprendimento
- Ricerca accademica
- Formazione sicurezza informatica

### 🚫 Utilizzo Vietato
- Attacchi a sistemi reali
- Attività non autorizzate
- Utilizzo malevolo

### ⚖️ Aspetti Legali
Tutte le attività di test devono essere autorizzate. La legislazione italiana (Art. 615-ter c.p.) punisce l'accesso abusivo a sistemi informatici.
**L'autore non si assume alcuna responsabilità per l'uso improprio di queste informazioni.**

## Scopo del progetto
Repository che raccoglie il lavoro di penetration testing condotto su un'istanza Metasploitable 2 per scopi didattici: scansioni, analisi vulnerabilità, PoC e raccomandazioni per il remediation.

## Struttura del repository
Penetration-Testing-Metasploitable2/
│
├── 📄 README.md                       # Questo file
├── 📁 report/
│   └── 📄 Report_Completo.md          # Report sintetico finale
│
├── 📁 01_Scansioni/
│   ├── 📄 scansione_completa.txt      # Scansione nmap -p-
│   ├── 📄 Scansione_servizi_SMB.txt   # Scansione SMB approfondita
│   └── 📄 README_Scansioni.md         # Metodologia scansioni
│
├── 📁 02_Vulnerabilita/
│   ├── 📁 CRITICHE/
│   │   ├── 📄 Vuln_Bindshell_1524.md          # Bindshell porta 1524
│   │   ├── 📄 Vuln_VSFTPD_Backdoor.md         # Backdoor vsftpd
│   │   └── 📁 Exploit_vsftpd/
│   │       ├── 📄 vsftpd_234_exploit.py       # Script exploit
│   │       └── 📄 README_Exploit.md           # Documentazione exploit
│   │
│   ├── 📁 ALTE/
│   │   ├── 📄 Vuln_BIND_Obsoleto.md           # BIND 9.4.2 obsoleto
│   │   └── 📄 Vuln_SMB_Anonimo_Access.md      # Accesso anonimo SMB
│   │
│   └── 📁 MEDIE/
│       ├── 📄 Vuln_SSH_Enumeration.md         # Enumerazione SSH
│       └── 📄 Vuln_Web_App.md                 # Vulnerabilità web
│
├── 📁 03_Web_Vulnerabilities/
│   ├── 📁 SQL_Injection/
│   │   ├── 📄 SQL_Injection_Report.md         # Report SQLi
│   │   ├── 📄 payloads_sql.txt                # Payload utilizzati
│   │   └── 📁 screenshots/
│   │       └── 📄 sql_injection_success.png   # Screenshot proof
│   │
│   ├── 📁 XSS/
│   │   ├── 📄 XSS_Report.md                   # Report XSS
│   │   ├── 📄 payloads_xss.txt                # Payload XSS
│   │   └── 📁 screenshots/
│   │       └── 📄 xss_success.png             # Screenshot proof
│   │
│   └── 📄 Credenziali_Trovate.md              # Credenziali scoperte
│
├── 📁 04_Metodologia/
│   └── 📄 Metodologia_PTES.md                 # Standard PTES completo
│
├── 📁 05_Raccomandazioni/
│   └── 📄 Raccomandazioni_Remediation.md      # Piano di remediation


## Come navigare
- Leggi prima `report/Report_Completo.md` per sintesi e priorità.  
- Approfondisci i singoli casi nelle sottocartelle `Vulnerabilita/`.  
- Gli artefatti (output nmap, screenshot) si trovano in `Scansioni/` e `WEB/`. 


