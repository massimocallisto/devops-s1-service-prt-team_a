# Servizio della PA - Gestione Pratiche

## Descrizione
Breve introduzione al progetto: spiega cosa fa, a chi è destinato e qual è il suo obiettivo principale.  
Puoi aggiungere informazioni tecniche di base o il contesto in cui il progetto è stato sviluppato.

---

## Struttura del Progetto
Esempio di organizzazione delle cartelle:

```
📦 nome-progetto
 ┣ 📂 src/              # codice sorgente
 ┣ 📂 profiles/         # profili dei partecipanti
 ┣ 📂 docs/             # documentazione e materiali
 ┣ 📄 README.md         # questo file
 ┗ 📄 LICENSE           # licenza del progetto
```

---

## Contributi
1. Crea un branch di sviluppo:
   ```bash
   git checkout -b feature/<nome-feature>
   ```
2. Effettua le modifiche e il commit:
   ```bash
   git commit -m "Aggiunge nuova funzionalità"
   ```
3. Esegui il push e apri una Pull Request su GitHub.

---

## Autori
- [Mario Rossi](profiles/mario.profile.md)  
- [Lucia Bianchi](profiles/lucia.profile.md)  
- [Giovanni Verdi](profiles/giovanni.profile.md)
- [Carmela Anghelone](profiles/canghelone.profile.md)
- [Matteo Contino](profiles/mcontino79-rgb.profile.md)
- [Emanuele Gabbrielli](profiles/EmaGH25.profile.md)
---

## Licenza
Questo progetto è distribuito sotto licenza MIT.  
Consulta il file [LICENSE](LICENSE) per maggiori dettagli.



## Docker Instructions

### Building and Running with Docker

You can run this application using Docker in two ways: using Docker directly or using Docker Compose.

#### Using Docker directly

1. Build the Docker image:

    docker build -t fastapi-status .

2. Run the container:

    docker run -p 8000:8000 --name fastapi-status fastapi-status

### Testing the API

Once the container is running (using either method), you can test the API check http://localhost:8000/status





