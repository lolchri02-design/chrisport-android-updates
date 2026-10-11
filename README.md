# ChriSport Android

Aggiornamenti interni firmati per ChriSport Android. Il player resta nella base nativa; schermate, loghi e categorie possono essere aggiornati senza reinstallare l’APK.

## Collaudo iniziale

Le versioni 1.21 qui pubblicate sono riservate al collaudo concordato su Galaxy A14 e Poco. La distribuzione generale resta sospesa fino al completamento delle prove sui due telefoni.

- **Standard**: migrazione dalla base standard 1.18.1.
- **Hotspot**: migrazione dalla base personale/hotspot 1.20.5.

Installare la variante corretta sopra ChriSport esistente, senza disinstallare. La prima installazione può richiedere la conferma Android. I moduli interni si attivano soltanto agli ingressi sicuri, con ripiego sulla versione funzionante quando rete o verifica falliscono.

[APK per il collaudo](https://github.com/lolchri02-design/chrisport-android-updates/releases/tag/android-1.21-pilot)

La release `modules` contiene i manifest firmati `standard.json` e `personal.json` e i relativi bundle immutabili. Le app precedenti alla migrazione non consultano questi feed. Fire TV, web e vecchio telecomando separato sono esclusi.
