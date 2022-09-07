Rezumatul proiectului de disertație al studentului: Ing. Ioana-Daniela TRIFAN

Programul de master: Ingineria Informației și a Sistemelor de Calcul, 2022

Optimizarea simulatoarelor pentru implementarea reţelelor celular neliniare cu aplicaţii în modelarea fenomenelor de propagare şi în prelucrarea imaginilor 

Conducători științifici: Conf. Dr. Ing. Ioana DOGARU, Prof. Dr. Ing. Radu DOGARU

Obiectivele proiectului:  

S-a realizat un studiu al diferențelor dintre simulatoarele cu accelerare GPU și cele simple cu suport CPU, APU, TPU. Au fost dezvoltate două simulatoare atât fără, cât și cu accelerare GPU, acestea analizând simularea unei situații pandemice COVID-19 și un sistem de detectare a marginilor cu ajutorul CNN. S-au realizat cercetări amănunțite pe fiecare dintre abordările menționate și au fost evaluate corespunzător rezultatele și ordonate în funcție de eficiență a timpului de execuție în milisecunde per iterație.
Realizarea proiectului și rezultate obținute: În primă fază a fost dezvoltat simulatorul epidemic COVID-19, iar abordarea simulatorului cu accelerare GPU a fost cea mai eficientă depășind timpul de execuție ale celorlalte abordări de aproape 28 de ori, media fiind de 14 milisecunde per iterație pentru acesta și 404 milisecunde per iterație la următoarea cea mai eficientă metodă, aceasta fiind CPU ONLY.
    
Al doilea simulator a fost acela de detectare a marginilor din fotografii de tip medical, rezultatele fiind relativ asemănătoare, abordarea GPU ONLY fiind cea mai eficientă și în cazul acesteia, dar nu la fel de eficientă ca în cazul simulatorului epidemic. Media a fost de 6 milisecunde per iterație pentru simulatorul GPU ONLY, de aproximativ 6 ori mai eficientă decât abordarea APU ONLY care a fost următoarea ca eficiență cu o medie de 34 milisecunde per iterație.
   
În urma testărilor, simulatoarele funcționează corespunzător, iar rezultatele au fost unele foarte promițătoare, iar pe lângă eficiența simulatorului epidemic, și acuratețea acestuia este apropiată de rezultatele reale.
Simulatorul detector de margini s-a comprotat de asemenea la fel de bine, rezultatele fiind cele așteptate.

        
Analiza rezultatelor experimentale înregistrate de simulatoarelor a dus la următoarele concluzii: 
	Simulatoarele cu accelerare GPU sunt mult mai eficiente decât cele fără suport de accelerare GPU, rezultatele având diferențe enorme în timpul de execuție.
	
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tioanadev/disertatie/blob/main/Dizertatie.ipynb)
