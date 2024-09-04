# Útskýra hvernig eigi að keyra kóðann ykkar (og hvaða pakka þarf að setja upp, ef við á).

Fyrst þurfti að setja upp neðantalda pakka til að setja upp verkefnið á réttan hátt
pip3 install numpy - Það er sérstaklega öflugt fyrir útreikninga á fylkjum og fylkjaröðum.
pip3 install network - Það er notað til að meðhöndla og greina grafasafn og net. 
pip3 install matplotlib - Það er notað til að teikna og setja fram sjónræna framsetningu gagna.

Síðan til þess að keyra sjálft forritið þarf að skrifa: python "Mengi og vensl - liður 4.py"

##### Býr til slembifylki út frá afmælisdögum
Með skipuninni "seed" var hægt að gera 4x4 slembifylki út frá dagsetningum (afmælisdögum hópmeðlima), og voru fylkin skráð með tölunum 0 eða 1. Sett var upp fall með degi, mánuði og ári sem hægt var að setja mismunandi dagsetningar inn fyrir sem gat út mismunandi fylki sem forritið gat lesið og ályktað hvort væri sjálfhverf, samhverf, andsamhverf eða gegnvirk. 

##### Athugar eiginleika fylkja
* Sjálfhverf fylki: Hvert stak er tengt við sjált sig.
* Samhverf fylki: Ef stak a er tengt við stak b, þá er b tengt við a.
* Andsamhverf fylki: Ef stak a er tengt við stak b, þá tengist b ekki a. 
* Gegnvirk fylki: Ef stak a er tengt við b, og b er tengt við c, þá tengist stak a við c. 

##### Prentar og teiknar niðurstöður
Pakkinn "network" teiknaði örvanet út frá fylkjunum og pakkinn "matplotlib" opnaði nýja glugga með myndum af örvaneti fyrir hverja dagsetningu (afmælisdag) sem lýsti tengslum fylkjanna.  

##### Niðurstaða
Þá kemur í ljós að örvanetið er mismunandi eftir ólíkum dagsetningum þar sem fylkin eru ýmist sjálfhverf, samhverf, andsamhverf eða gegnvirk.  