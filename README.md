# CORSO HACKING ETICO ITA 2023/2024 
## Valido per la preparazione alle certificazioni: eJPTv2, eCPPTv2, eWPT

---

### Inizio corso previsto per Inizio Settembre 2023 
### Rimanete aggiornati sui nostri social:
 
1. Discord: https://discord.gg/FEjgBMdAeA
2. Twitter: https://twitter.com/ModernNaval
3. Youtube: https://www.youtube.com/channel/UCAwPX5amsoJBiJyj-vmHhcQ

---

STRUTTURA DEL CORSO:

# CONCETTI DI BASE
1. Indirizzi IP (IPV4 e IPV6)
2. Indirizzi MAC (OUI e NIC)
3. Protocolli comuni (UDP, TCP) e il famoso Three-Way Handshake
4. Il modello OSI: cos'è e come è strutturata l'attività di rete a livelli
5. Subnetting: cos'è una maschera di rete e come viene interpretata
6. Subnetting: CIDRs e calcolo totale degli hosts 
7. Subnetting: maschere di sottorete, tipi di classe e interpretazione dei prefissi di rete
8. Subnetting: Interpretazione degli intervalli di rete 
9. Subnetting: Reti e casi particolari
10. Suggerimenti di subnetting e calcolo rapido dell'indirizzamento nelle reti

---

# RICONOSCIMENTO
1. Nmap e le sue diverse modalità di scansione
2. Tecniche di evasione del firewall (MTU, Data Length, Source Port, Decoy, ecc.)
3. Utilizzo di script e categorie in nmap per applicare il riconoscimento
4. Creare i propri script Lua per nmap
5. Alternative all'enumerazione delle porte utilizzando descrittori di file
6. Scoperta dei computer nella rete locale (ARP e ICMP) 
7. Convalida del target 
8. Scoprire account di posta elettronica
9. Riconoscimento delle immagini
10. Enumerazione dei sottodomini
11. Credenziali e violazioni della sicurezza
12. Identificazione delle tecnologie su una pagina web
13. Fuzzing ed enumerazione di file su un server web (1/2)
14. Fuzzing ed enumerazione di file su un server web (2/2)
15. Google Dorks / Google Hacking (I 18 Dorks più utilizzati)
16. Identificazione e verifica esterna della versione del sistema operativo

---

# CONFIGURAIONE DI LABORATORI LOCALI IN DOCKER
1. Introduzione a Docker
2. Installazione di Docker su Linux
3. Definizione della struttura di base del Dockerfile
4. Creazione e costruzione di immagini
5. Caricamento delle istruzioni in Docker e distribuzione di un container
6. Comandi comuni per la gestione dei contenitori
7. Port Forwarding in Docker e utilizzo dei mount
8. Distribuzione di macchine vulnerabili con Docker-Compose (1/2)
9. Distribuzione di macchine vulnerabili con Docker-Compose (2/2)

---

# ENUMERAZIONE DI SERVIZI COMUNI E GESTORI DI CONTENUTI
1. Enumerazione del servizio FTP
2. Enumerazione del servizio SSH
3. Enumerazione dei servizi HTTP e HTTPS
4. Enumerazione dei servizi SMB
5. Elenco dei sistemi di gestione dei contenuti (CMS) – WordPress (1/2)
6. Elenco dei sistemi di gestione dei contenuti (CMS) – WordPress (2/2)
7. Elenco dei sistemi di gestione dei contenuti (CMS) – Joomla
8. Enumerazione dei gestori di contenuti (CMS) – Drupal
9. Enumerazione dei gestori di contenuti (CMS) – Magento
10. Prendere appunti con Obsidian

---

# NOZIONI DI BASE SU ENUMERAZIONE E SFRUTTAMENTO 
1. Introduzione allo sfruttamento delle vulnerabilità
2. Reverse Shells, Bind Shells e Forward Shells
3. Tipi di payload (organizzati e non organizzati)
4. Tipi di sfruttamento (manuale e automatizzato)
5. Enumerazione del sistema
6. Introduzione a Burp Suite

---

# OWASP TOP 10 E VULNERABILITA' WEB
1. Iniezione SQL (SQLI)
2. Cross-Site Scripting (XSS) [1/2]
3. Cross-Site Scripting (XSS) [2/2]
4. Iniezione di entità esterne XML (XXE)
5. Local File Inclusion (LFI)
6. Remote File Inclusion (RFI)
7. Log Poisoning (LFI -> RCE)
8. Falsificazione di richieste tra siti (CSRF)
9. Falsificazione di richieste lato server (SSRF)
10. Iniezione di modelli lato server (SSTI)
11. Iniezione di modelli lato client (CSTI)
12. Imbottitura Oracle Attack
13. Tipo Attacco di giocoleria
14. Iniezioni NoSQL
15. Iniezioni LDAP
16. Attacchi di deserializzazione
17. Iniezioni di LaTeX
18. Abuso dell'API
19. Abuso di caricamento di file
20. Prototipo Inquinamento
21. Attacchi di trasferimento di zona (AXFR – Full Zone Transfer)
22. Attacchi di assegnazione di massa / associazione di parametri
23. Apri Reindirizzamento
24. Enumerazione e sfruttamento WebDAV
25. Enumerazione e sfruttamento dei proxy SQUID
26. Attacco Shell Shock
27. Iniezioni di XPath
28. Riferimenti diretti a oggetti non sicuri (IDOR)
29. Condivisione delle risorse tra le origini (CORS)
30. Attacco SQL Truncation
31. Enigma della sessione / Fissazione della sessione / Sovraccarico variabile della sessione
32. Enumerazione e sfruttamento di Json Web Tokens (JWT)
33. Condizioni di gara (Race Condition)
34. Iniezioni di CSS (CSSI)
35. Python – Attacco di deserializzazione Yaml (DES-Yaml)
36. Python – Attacco di deserializzazione Pickle (DES-Pickle)
37. GraphQL Introspezione, Mutazioni e IDOR

---

# TECNINCHE DI SCALATA DI PRIVILEGI
1. Abuso dei privilegi a livello di Sudoers
2. Abuso dei privilegi SUID
3. Rilevamento e sfruttamento delle attività Cron
4. Dirottamento Percorso
5. Dirottamento della libreria Python
6. Abuso di autorizzazioni implementate in modo errato
7. Rilevamento e sfruttamento delle capacità
8. Sfruttamento del kernel
9. Abuso di gruppi di utenti speciali
10. Abuso dei servizi di sistema interni
11. Abuso di binari specifici
12. Hijacking della libreria di oggetti condivisi collegata dinamicamente
13. Evasione Docker

---

# BUFFER OVERFLOW
1. Introduzione al Buffer Overflow
2. Creazione del nostro laboratorio di test e installazione di Immunity Debuger
3. Fase iniziale di Fuzzing e presa di controllo del registro EIP
4. Assegnazione dello spazio per lo shellcode
5. Generazione di bytearray e rilevamento di badchar
6. Ricerca OpCodes per entrare nell'ESP e caricare il nostro Shellcode
7. Utilizzo di NOP, offset dello stack e interpretazione dello shellcode per ottenere RCE
8. Modifica dello shellcode per controllare il comando da eseguire
9. Sfruttamento di un nuovo binario per rafforzare ciò che è stato appreso
10 Funzionamento e creazione manuale di Shellcode

---

# Risoluzione delle macchine
1. Risoluzione macchina #1 (Easy)
2. Risoluzione macchina #2 (Medium)
3. Risoluzione macchina #3 (Hard)
4. Risoluzione macchina #4 (Hard)
5. Risoluzione macchina #5 (Insane)

---

# STRUMENTI AUTOMATIZZATI
1. Introduzione a Metasploit
2. Introduzione a SQLMap
3. Introduzione al Pivoting

---

# STESURA REPORT
1. Creazione di un report professionale in LaTeX (1/2)
2. Creazione di un report professionale in LaTeX (2/2)

