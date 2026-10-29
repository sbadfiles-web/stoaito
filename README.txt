GIONGIO GEST — pacchetto PWA per pubblicazione HTTPS

File:
- index.html: applicazione
- manifest.webmanifest: metadati per installazione PWA
- sw.js: cache base delle risorse

Per provarla/pubblicarla:
1. Carica tutti e tre i file nella radice di un hosting statico HTTPS.
2. Apri il sito con Chrome su Android.
3. Menu ⋮ > Installa app oppure Aggiungi a schermata Home.

ATTENZIONE:
- Non c'è ancora backend/database online: i dati restano nel browser del dispositivo.
- Le icone PWA non sono ancora incluse; alcuni servizi di creazione APK possono richiederle.
- Il backup tenta di aprire il menu di condivisione Android con un file JSON. Se il browser non supporta la condivisione di file, scarica il JSON per allegarlo manualmente a un'email.
- Il pacchetto non è un APK già compilato.
