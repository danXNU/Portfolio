# Portfolio
Sono attualmente uno sviluppatore indipendente da quando avevo 17 anni (2017).
Nel corso degli anni ho pubblicato diverse applicazioni sull’App Store e creato altrettanti progetti presenti nel mio profilo GitHub.
In questo portfolio troverai tutto quello su cui ho lavorato negli anni e una breve spiegazione comprendente delle tecnologie/librerie utilizzate.

* [App su App Store](#app-su-app-store)
* [App su Google Play](#app-su-google-play)
* [Elettronica (Internet of Things)](#elettronica-internet-of-things) 
* [Augmented Reality](#augmented-reality)
* [Altri progetti](#altri-progetti)

- - - -
# App su App Store
Qua sono elencate le app che ho pubblicato sull’App Store di Apple.


* ## [WatchNotes](https://apps.apple.com/it/app/watch-notes/id1299477480) (iOS, iPadOS, watchOS, macOS) 
![](WNicon.png)
WatchNotes è un’app che permette di creare note su iPhone, iPod, iPad e Mac. C’è poi un’app su Apple Watch che permette di leggere le note sul proprio polso.

* Anno di pubblicazione su App Store: 2017
* Ultimo aggiornamento: Febbraio 2021

Framework e tecnologie utilizzate: 
1. UIKit
2. WatchKit
3. SwiftUI
4. Catalyst
5. WidgetKit
6. CoreData + CloudKit
7. WatchCommunication
8. Combine
9. Foundation


* ## [Home Inventory+](https://apps.apple.com/it/app/home-inventory/id1537446653) (iOS, iPadOS)
![](Inventory+.png)
Home Inventory+ è un’app che permette di catalogare tutti i propri averi all’interno della casa. Permette poi di ritrovarli facilmente e ottenere delle statistiche oppure esportare tutti i dati in CSV

* Anno di pubblicazione su App Store: 2020
* Ultimo aggiornamento: Gennaio 2021

Framework e tecnologie utilizzate:
1. SwiftUI
2. Combine
3. CoreData + CloudKit
4. Foundation
5. Siri Shortcuts (Intents, IntentsUI)
6. [CodableCSV](https://github.com/dehesa/CodableCSV)



* ## [FileEncryptor](https://apps.apple.com/it/app/fileencryptor/id1527000197) (iOS, iPadOS, macOS)
![](FileEncryptor.png)
FileEncryptor è un’app che permette di cifrare e decifrare file utilizzando una password. All’interno viene usato un algoritmo di cifratura standard utilizzato dal framework CryptoKit.

* Anno di pubblicazione su App Store: 2020
* Ultimo aggiornamento: luglio 2020

Framework e tecnologie utilizzate:
1. SwiftUI
2. CoreData
3. CryptoKit
4. Foundation



* ## [iRingTunes+](https://apps.apple.com/it/app/iringtunes/id1253595081) (iOS, iPadOS, macOS)
![](iringtunes.png)
Questa app è stata la mia prima app in assoluto e permette di esportare un file m4r (suonerie iPhone) dalla libreria musicale del telefono o da un file su Mac.

* Anno di pubblicazione su App Store: 2017
* Ultimo aggiornamento: dicembre 2020

Framework e tecnologie utilizzate:
1. SwiftUI
2. UIKit
3. AVFoundation
4. Foundation


* ## [CNC Studenti](https://apps.apple.com/it/app/cnc-studenti/id1221038173) (iOS, iPadOS)
![](studentu.png)
Questa app inizialmente permetteva di vedere le verifiche e i compiti assegnati dai professori. Gli utenti potevano poi inserire i voti che ricevevano nei test e da questo l’app mostrava la media complessiva e per ogni materia.
Il mio passaggio ad un’altra scuola ha causato la rimozione di molte delle funzioni visto che non erano più necessarie nella nuova scuola.

* Anno di pubblicazione su App Store: 2018
* Ultimo aggiornamento: Febbraio 2020

Framework e tecnologie utilizzate:
1. UIKit
2. UserNotification
3. SwiftUI
4. CoreData
5. Firebase
6. Siri Shortcuts (Intents, IntentsUI)
7. [BlueSocket](https://github.com/Kitura/BlueSocket)
8. Foundation




* ## [iGio](https://apps.apple.com/it/app/igio/id1493029812) (iOS, iPadOS)
![](igio.png)
iGio è un’app che ho scritto e che continuo a sviluppare per Marco Begato (Ispettoria Salesiana Lombardo Emiliana). 
iGio è pensata come strumento  per l’accompagnamento personale per i giovani.

* Anno di pubblicazione su App Store: Gennaio 2020
* Ultimo aggiornamento: Gennaio 2021

Framework e tecnologie utilizzate:
1. UIKit
2. Realm Database
3. Foundation (Codable)
4. SwiftUI
5. [OneSignal](https://github.com/OneSignal/OneSignal-iOS-SDK) (remote notifications)



- - - -
# App su Google Play
App pubblicate su Google Play


* ## [iGio](https://apps.apple.com/it/app/igio/id1493029812) (Android)
![](igio.png)
iGio è un’app che ho scritto e che continuo a sviluppare per Marco Begato (Ispettoria Salesiana Lombardo Emiliana). 
iGio è pensata come strumento  per l’accompagnamento personale per i giovani.

* Anno di pubblicazione su Google Play: Gennaio 2020
* Ultimo aggiornamento: Gennaio 2021

Framework e tecnologie utilizzate:
1. Kotlin
2. Realm Database
3. [Gson](https://github.com/google/gson) (Codable-like JSON)
4. [OneSignal](https://github.com/OneSignal/OneSignal-Android-SDK) (remote notifications)
5. [Groupie](https://github.com/lisawray/groupie) for RecyclerViews


- - - -
# Elettronica (Internet of Things)
Qui sono elencati tutti i progetti che ho svolto nel corso degli anni legati all’IoT.


* ## danHome (Linux, macOS, Arduino) - Ancora in sviluppo



* ## danHome-Android (Android) - Ancora in sviluppo
Client per controllare I dispositivi e le impostazioni del mio progetto danHome.


* ## ToxHomePy (Linux, macOS)
Progetto di una Smart-Home utilizzato per il talent show di Padernello a settembre 2018. 
È stato scritto in Python e aveva la caratteristica di essere estremamente dinamico. Permetteva ai vari dispositivi di comunicare tra loro attraverso una runtime, simile a come funziona il linguaggio di programmazione Objective-C.
Questo runtime poi mandava i comandi all’Arduino tramite seriale.
Per controllare il sistema, ho scritto un'app client per iOS (chiamata [ToxCoreHome](#toxcorehome-ios)).

Tecnologie e librerie utilizzate:
1. Python
	* json
	* pyserial
2. C/C++ (Arduino)
	* Servo
	* OneWire
	* Stepper 

Apparecchiature utilizzate:
1. Servo motor
2. Leds
3. Buzzers
4. IR Sensors
5. Arduino Mega


* ## ToxCoreHome (iOS)
Questo progetto è il client che permette di controllare [ToxHomePy](#toxhomepy-linux-macos).
Interfaccia e funzionalità simili al funzionamento dell’app Shortcuts/Comandi di Apple. 
Anche questo permetteva di aggiungere delle Siri Shortcuts per far funzionare tutto con l’assistente vocale.

Tecnologie utilizzate:
1. UIKit
2. Siri Shortcuts (Intents)
3. [BlueSocket](https://github.com/Kitura/BlueSocket)

* Carthage (framework manager)


- - - -
# Augmented Reality
Qui sono elencate le app o piccoli progetti che implementano funzionalità di realtà aumentata.


### ARPortal-Hogwarts
Piccolo progetto per testare la creazione di un portale che permette di entrare in un mondo virtuale. In questo caso


- - - -
# Altri progetti
Qui sono elencati gli altri progetti che non appartengono a nessuna delle precedenti categorie
