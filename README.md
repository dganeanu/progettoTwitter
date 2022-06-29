# Progetto OOP Twitter Metrics

![Twitter](https://cdn.cms-twdigitalassets.com/content/dam/legal-twitter/privacy-policy-2022/Twitter-terms-of-service-share.jpg.twimg.768.jpg)

## Indice 🔖

* [Introduzione](#introduzione)
* [Installazione ed utilizzo](#installazione-ed-utilizzo)
* [Rotte](#rotte)
     _____rotte
    * [Esempi di utilizzo corretto delle rotte](#esempiRotte)
    * [Errori nell'utilizzo delle rotte](#erroriRotte)
* [Interfaccia grafica](#interfaccia-grafica)
* [JUnit test](#JUnit-test)
* [Software utilizzati](#software-utilizzati)
* [Autori](#autori)

<div id='introduzione'/>

## INTRODUZIONE

Attraverso le **Application Programming Interface**, note anche come 'api' drivate dalla pagina [Twitter Developer](https://developer.twitter.com/en) , il programma valuta una lista di tweet di un account scelto per poi analizzare le metriche di engagement dei tweet. L'utente ha la possibilità di imporre le statistiche sull'engagement dei singoli tweet con media e varianza oppure imporre dei filtri per fasce orarie dei tweet.

<div id='installazione-ed-utilizzo'/>

## INSTALLAZIONE ED UTILIZZO 📖

Per poter accedere al programma è necessario clonare la repository in locale utilizzando Github Desktop oppure da terminale digitando
`git clone https://github.com/dganeanu/project-uni-exam.git`.
Successivamente sarà possibile mandare in esecuzione il programma con un IDE (ad esempio Eclipse) o direttamente da terminale.

In seguito l'utente deve accedere alla cartella resources, reperibile attraverso il percorso `esameMetrics\src\main\resources`, e creare il file **apiKey.txt**,  dentro il quale è necessario inserire la propria `apiKey`,utilizzando il token di accesso creato per il corso di OOP.

??WORK IN PROGRESS  Dopodiché l'utente può scegliere se utilizzare il programma con le rotte (che verranno elencate e spiegate nel paragrafo successivo) sul client [Postman](https://www.postman.com/) oppure tramite la Graphic User Interface implementata all'interno del progetto (che verrà spiegata nel paragrafo successivo alle rotte).??
