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
├─ README.md

├─ report/

│ └─ Report_Completo.md

├─ Scansioni/

│ ├─ scansione_completa.txt
│ └─ Scansione_servizi_SMB.txt
├─ Vulnerabilita/
│ ├─ Critiche/
│ │ ├─ Vuln_Critiche_Bindshell1524.txt
│ │ └─ Exploit_vsftpd/
│ │ ├─ Exploit_Readme.txt
│ │ └─ (exploit_py_removed_or_sanitized)
│ └─ Alte/
│ ├─ Vuln_Alte_BindObsoleto.txt
│ └─ Vuln_Alte_SmbAnonimoAccess.txt
├─ WEB/
│ ├─ SQL_Injection_Recap.txt
│ └─ XSS/
│ └─ (screenshots + readme)
├─ Metodologia.txt
└─ Raccomandazioni.txt


## Come navigare
- Leggi prima `report/Report_Completo.md` per sintesi e priorità.  
- Approfondisci i singoli casi nelle sottocartelle `Vulnerabilita/`.  
- Gli artefatti (output nmap, screenshot) si trovano in `Scansioni/` e `WEB/`. 


