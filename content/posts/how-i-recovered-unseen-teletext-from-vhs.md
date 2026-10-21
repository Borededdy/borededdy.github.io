+++
title = "Ho Trovato il Teletext Dimenticato di TELE+ in una Vecchia VHS (ed è un Lost Media)"
date = "2026-10-21T17:41:15+02:00"
author = "Borededdy"
authorTwitter = "" #do not include @
cover = ""
coverCaption = ""
tags = ["teletext", "vhs", "televideo"]
keywords = ["teletext", "vhs"]
description = ""
showFullContent = false
readingTime = true
hideComments = false
color = "" #color from the theme settings
draft = true
+++

Ho da sempre amato il televideo, probabilmente molti di voi non se lo ricorderanno, altri invece lo associano spesso a un "trauma", altri ad un caloroso e nostalgico ricordo... Per molto tempo quella schermata piena di forme, scritte e colori che appariva sui canali tv alla pressione di un pulsante ha rappresentato per molti la fonte primaria di notizie, informazioni e divertimento. Insomma, il televideo è stato un vero e proprio precursore di internet. Prima di imbarcarci in quella che è stata la mia avventura nel recupero di un lost media che non ha mai visto la luce dal 2003 è bene fare un passo indietro e capire che cos'è e come funziona il **teletext**

# Com'è nato il teletext

Anni '70, Gran Bretagna. Negli studi della BBC alcuni tecnici stanno cercando di inventare un sistema dedicato alla trasmissione di dati via etere che potessero contenere del testo e che fossero visibili alla pressione di un pulsante. L'invenzione di questo sistema di telecomunicazione aggiuntivo avrebbe permesso ai possessori di televisori residenti in alcune delle zone più rurali dell'inghilterra (ma anche delle grandi città) di ottenere informazioni e notizie in modo rapido ed immediato, si sarebbe inoltre risolto il problema delle trascrizioni audio in tempo reale per i non udenti. 

È nel 1971 che, grazie all'allora ingegnere **John Adams** dei laboratori CAL di Philips viene proposto un primo modello di quello che poi diventerà effettivamente il teletext. Il tutto funziona tramite l'utilizzo del **VBI** (Vertical Blanking Interval), segnale presente e necessario per il funzionamento dei segnali TV analogici, VGA, DVI ecc... Il suo scopo principale è quello di creare un "intervallo di bianco" tra un frame e l'altro, questo permette al raggio del cannone ad elettroni di un tubo catodico di potersi riposizionare all'inizio della prima linea di "scrittura" sui fosfori, citando da Wikipedia:

>[!quote] ""
>*The VBI was originally needed because of the inductive inertia of the magnetic coils which deflect the electron beam vertically in a CRT; the magnetic field, and hence the position being drawn, cannot change instantly. Additionally, the speed of older circuits was lower than today’s. For horizontal deflection, there is also a pause between successive lines, to allow the beam to return from right to left, called the horizontal blanking interval. Modern CRT circuitry does not require such a long blanking interval, and thin panel displays require none, but the standards were established when the delay was needed (and to allow the continued use of older equipment). Blanking of a CRT may not be perfect due to equipment faults or brightness set very high; in this case a white retrace line shows on the screen, often alternating between fairly steep diagonals from right to left and less-steep diagonals back from left to right, starting in the lower right of the display.*
>
>{{< image src="https://ars.els-cdn.com/content/image/3-s2.0-B9780122095511500428-f09-05-9780122095511.gif" style="width: 35%;" position="center" caption="Funzionamento del VBI source: ScienceDirect" captionPosition="center">}}

Il segnale che trasporta i bit del teletext viene dunque furbamente inserito in questo piccolo spazio vuoto, invisibile (poiché nascosto dai normali schermi) e relativamente poco oneroso in termini di banda, garantendone inoltre un continuo aggiornamento, dato che il VBI viene trasmesso continuamente tra un frame e l'altro. Il modello classico del teletext contiene e può rappresentare una vasta gamma di forme e colori (vengono scelti i colori primari: giallo, rosso, verde, blu, ciano, magenta e bianco) e quasi tutti i caratteri ASCII standard. La possibilità di poter disegnare varie forme permette dunque di realizzare veri e propri disegni a schermo, oltre a loghi, banner e molto altro.

{{< figure src="https://oldcomputers.net/pics/bbc-micro-left.jpg" caption="Il BBC Micro, uno dei primi PC (8 bit) utilizzati per la realizzazione delle pagine del CEEFAX" >}}

{{< image src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQRhZMHTUqWSIcYDWY5B8pod-2PJVqdeDuNs0EB_0ZxtjwV2ROMvJ64xeg&s=10" position="left" style="width: 25%; float: left; margin-right: 5px;">}}

Una volta che il segnale del teletext viene iniettato nel VBI, esso viene trasmesso in etere contemporaneamente alla trasmissione del programma. Per poter interpretare i dati ricevuti è stata necessaria l'introduzione nelle tv dell'epoca di appositi **decoder** che memorizzavano il segnale ricevuto in una piccola memoria aggiornandolo costantemente. Alla pressione di un semplice tasto sul telecomando si poteva dunque far comparire la schermata. 

Il primo servizio di teletext ad essere lanciato è lo storico CEEFAX, edito da BBC. Le cui trasmissioni di prova iniziano nel 1972. In Italia invece, il primo servizio a vedere la luce, come ben sappiamo è il TELEVIDEO, le sue trasmissioni tecniche iniziano però ben 12 anni dopo, nel 1984 su RAI1. 

{{< gallery cols="3" >}}
  {{< gallery-img src="https://i.imgur.com/fe3je0T.png" alt="Teletext 1" caption="Indice generale del Televideo durante le prove tecniche del 1984" >}}
  {{< gallery-img src="https://i.imgur.com/q7NPIx9.png" alt="Teletext 2" caption="Pagina che mostra gli orari dei treni espressi" >}}
  {{< gallery-img src="https://i.imgur.com/UW0HeOU.png" alt="Teletext 3" caption="Pagina che mostra le previsioni del nord" >}}
{{< /gallery >}}

# Come si recupera il televideo dalle VHS?

Molti di voi non sapranno che i VCR (Video Cassette Recorder) non registrano sulle cassette VHS solamente la parte video "a schermo" di un segnale, essi bensì memorizzano l'intera trasmissione, **incluso ovviamente il VBI**.\
*Questo significa quindi che dalle mie videocassette posso vedere il vecchio televideo?* Si e no... la risposta **non è molto semplice**. 
Il principale problema che __non__ ci permette di visualizzare il teletext semplicemente premendo il pulsantino dedicato sul telecomando sta tutto nel modo in cui i VCR registrano e mandano in output il segnale. Il segnale Teletext originale viaggia ad **altissima frequenza** (circa 5,7 MHz) nelle linee VBI, ma la banda passante della videoregistrazione VHS è limitata a poco più di **3 MHz**! Questo provoca una drastica attenuazione e uno "smussamento" degli impulsi digitali, rendendo i bit indecifrabili per il chip decoder integrato nel televisore. A ciò si aggiungono le **micro-oscillazioni meccaniche del nastro** (jitter temporale, rumore di tracking e imperfezioni del tamburo testine) che sfasano costantemente il sincronismo di riga.

Allo scopo dunque di poter visionare e recuperare queste "gemme perdute" nel tempo troviamo su github un software creato ad-hoc, [vhs-teletext](https://github.com/ali1234/vhs-teletext)
