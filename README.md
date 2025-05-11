# UNIT-3-Project-React-Advanced
Unit-3 su React Advanced - Creazione di un App del meteo

# Weather App

Un'applicazione React per controllare il meteo in giro per il mondo, sfruttando **Recharts**, **Leaflet** e le **Open Weather API**. L'utente può selezionare una città e ottenere informazioni dettagliate sul tempo attuale e le previsioni.

## Funzionalità

- **Ricerca città:** Inserisci il nome della città e ottieni i dati meteo.
- **Informazioni meteo:**
  - Condizioni attuali (pioggia, sole, nuvolosità, ecc.).
  - Temperatura attuale.
  - Previsioni per i prossimi giorni.
- **Mappa interattiva:** Visualizza la posizione geografica della città selezionata su una mappa grazie a Leaflet.
- **Grafici meteo:** Visualizza grafici delle temperature giornaliere e altre statistiche meteo con Recharts.

## Tecnologie utilizzate

- **React**: Framework principale per l'interfaccia utente.
- **Leaflet**: Libreria per mappe interattive.
- **Recharts**: Per la visualizzazione di grafici e statistiche.
- **Open Weather API**: Fonte dei dati meteo (https://openweathermap.org/api).

## Requisiti

- Node.js (>= 14.x)
- Una chiave API valida per le Open Weather API.

## Installazione

1. Clona il repository:

   ```bash
   git clone https://github.com/tuo-utente/weather-app.git
   cd weather-app
   ```

2. Installa le dipendenze:

   ```bash
   npm install
   ```

3. Crea un file `.env` nella directory principale e aggiungi la tua chiave API:

   ```env
   REACT_APP_OPENWEATHER_API_KEY=la-tua-chiave-api
   ```

4. Avvia l'applicazione:

   ```bash
   npm start
   ```

5. Apri il browser e visita [http://localhost:3000](http://localhost:3000).

## Struttura del progetto

```plaintext
src/
├── components/          # Componenti React principali
│   ├── WeatherCard.jsx  # Mostra le informazioni meteo principali
│   ├── WeatherMap.jsx   # Mappa interattiva con Leaflet
│   └── ForecastChart.jsx# Grafici delle previsioni con Recharts
├── pages/               # Pagine principali dell'app
│   └── Home.jsx         # Pagina iniziale
├── utils/               # Funzioni di supporto (es. chiamate API)
│   └── api.js           # Gestione chiamate alle Open Weather API
├── App.js               # Componente principale
└── index.js             # Punto di ingresso dell'app
```

## Utilizzo

1. Inserisci il nome di una città nella barra di ricerca.
2. Visualizza le informazioni meteo sulla città selezionata:
   - Condizioni attuali.
   - Temperatura.
   - Previsioni per i prossimi giorni.
3. Esplora la posizione della città su una mappa interattiva.
4. Analizza i grafici delle previsioni meteo.

## Demo

Puoi provare una demo dell'app qui: **[link alla demo, se disponibile]**

## Contribuire

1. Fai un fork del repository.
2. Crea un branch per la tua feature:
   ```bash
   git checkout -b feature-nome-feature
   ```
3. Effettua le modifiche e fai un commit:
   ```bash
   git commit -m "Aggiunta nuova feature"
   ```
4. Fai push delle modifiche:
   ```bash
   git push origin feature-nome-feature
   ```
5. Apri una pull request.

## Licenza

Questo progetto è distribuito sotto la licenza **MIT**. Consulta il file [LICENSE](LICENSE) per maggiori dettagli.

---

### Note
- Consulta la documentazione ufficiale delle **Open Weather API** per personalizzare i dati visualizzati.
- Sentiti libero di migliorare l'interfaccia utente e aggiungere nuove funzionalità!