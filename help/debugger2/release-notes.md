---
title: Note sulla versione
description: Note aggiornate sulla versione di Adobe Experience Platform Debugger.
keywords: debugger;estensione Experience Platform Debugger;chrome;estensione;note sulla versione
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Note sulla versione

## Versione 1.3.0 - 28 gennaio 2022

* È stato aggiunto il collegamento Informazioni su per visualizzare la versione e le note della versione corrente.
* È stata aggiunta l’opzione per visualizzare gli hit post-elaborati per le richieste di Analytics. L’opzione è disponibile nella sezione Analytics .
* È stato risolto un problema della sessione di debug remoto quando la sessione era chiusa all’esterno del debugger.
* È stata corretta la notifica di errore visibile nella scheda Transazioni Edge dell’SDK per web.
* È stato corretto l’avviso di rimozione dai tag di Adobe nella pagina quando il debugger ha effettuato l’accesso all’oggetto _satellite .
* Sono stati risolti alcuni casi in cui un’istanza AppMeasurement non veniva trovata sulla pagina.
* È stato risolto un problema di connessione della pagina che si verificava alla prima apertura della finestra del debugger.

## Versione 1.2.0 - 26 ottobre 2021

* Mostra eventi da tutte le schede del browser nella visualizzazione di rete. Per visualizzare solo gli eventi dalla scheda corrente, seleziona l’icona Blocca nell’angolo inferiore destro del debugger.
* Branding aggiornato.

## Versione 1.1.0 - 5 ottobre 2021

* Visualizzazione debug remoto : organizza gli eventi di debug remoto in un grafico a flusso visivo nella sezione Adobe Experience Platform Web SDK > Edge Transactions .
* Richiedi che l’organizzazione Adobe Experience Platform Web SDK IMS utilizzata nella pagina corrisponda all’organizzazione registrata all’avvio di una nuova sessione di debug remoto.
* Mostra solo le transazioni edge per la scheda connessa. I registri di traccia di Target sono ancora disponibili nella sezione Registri > Edge .
* Consenti sostituzione della configurazione ID flusso di dati separata per ogni istanza dell&#39;SDK Web di Adobe Experience Platform sulla pagina. Aggiungi attivazione/disattivazione debug.
* È stato risolto un problema a causa del quale il token di traccia di Adobe Target non veniva sempre inviato con le sessioni di debug remote per Adobe Experience Platform Web SDK.

## Versione 1.0.0 del 5 maggio 2021

* Prima versione principale di Experience Platform Debugger. Destinato a sostituire il Experience Cloud Debugger.
