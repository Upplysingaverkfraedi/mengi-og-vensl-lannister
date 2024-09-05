# 1. Mengjafræði 
Látum $A$ og $B$ vera hlutmengi alsherjarmengisins U. Notið skilgreiningar á mengjahugtökum og þekktar umritunarreglur til að sýna að:

## a. Sýnið að sniðmengi $A \cap B$ má skrifa sem

$$
        A \cap B = A \setminus(A \setminus B)
$$
### Svar: 
##### Byrjum á því að skilgreina sniðmengi ($\cap$) og mismengi ($\setminus$): 
Sniðmengi $A \cap B$ er samansett af öllum gildum sem tilheyra bæði hlutmengis $A$ og $B$, það er táknað með eftirfarandi formúlunni 
        $A \cap B = \{x \in U \mid x \in A \text{ og } x \in B\}$
        
Mismengi tveggja mengja A og B er mengi þeirra staka sem eru í $A$ en ekki í $B$, samanber formúlunni 
        $A \setminus B = \{x \in U \mid x \in A, x \notin B\}$

##### Næst skoðum við mengið $A \setminus (A \setminus B)$: 
Þetta mengi er úr öllum þeim stökum sem tilheyra $A$ en ekki mismenginu $(A \setminus B)$.
Mengið $(A \setminus B)$ er úr gildum hlutmengisins $A$ en ekki $B$. 
Því getum við sagt að mengið $A \setminus (A \setminus B)$ er samansett af öllum gildunum sem eru í $A$ og í $B$ sem jafngildir sniðmenginu $A \cap B$. 


## b. Sýnið að sammengi $(A \cup B)$ má skrifa með hjálp mismunamengja:

$$
        A \cup B = (A \setminus B) \cup B
$$
### Svar: 
Sammengi $A \cup B$ er mengi allra þeirra staka sem tilheyra hlutmengis $A$, $B$ eða þeim báðum. 
        $A \cup B = \{x \in U \mid x \in A \text{ eða } x \in B\}$

Eins og í lið a. þá er mengið $(A \setminus B)$ úr stökum hlutmengisins sem er í $A$ en ekki í $B$. 
$(A \setminus B) \cup B$ er því mengi stakana sem eru annaðhvort í $A \setminus B$ eða $B$. 
Því er jafngilt því að segja $A \cup B$ og $(A \setminus B) \cup B$. 


# 2. Veldismengi 
Látum $P(A)$ vera veldismengið af menginu $A$. Sýnið hvort að $P(A) \subseteq P(P(A))$ sé alltaf það sama. Rökstyðjið af hverju eða af hverju ekki.

### Svar: 

##### Við skulum fyrst byrja á því að skilgreina mengin okkar: 
$P(A)$ er veldismengi sem er venslað af mengi $A$ svo að stök $A$ eru öll hlutmengi mengisins $A$, $P(A)$. 
Sem dæmi ef að $A = \lbrace 1, 2, 3 \rbrace$ þá er $P(A) = \lbrace \emptyset, \lbrace 1 \rbrace, \lbrace 2 \rbrace, \lbrace 3 \rbrace, \lbrace 1,2 \rbrace, \lbrace 1,3 \rbrace, \lbrace 2,3 \rbrace, \lbrace 1,2,3 \rbrace \rbrace$.
$P(P(A))$ er veldismengi af veldismenginu $P(A)$ og inniheldur því öll hlutmengi $P(A)$.

##### Næst skoðum við $P(A) \subseteq P(P(A))$: 
Til að setningin sé sönn þá þarf hvert einasta stak í $P(A)$ einnig stak í $P(P(A))$, þ.e.a.s hvert stak í $P(A)$ þarf að vera hlutmengi í $P(P(A))$. 

### Skoðum dæmi: 
  Látum $A = \lbrace 7 \rbrace$.

- Þá er $P(A) = \lbrace \emptyset, \lbrace 7 \rbrace \rbrace$.
- Þá er $P(P(A)) = \lbrace \emptyset, \lbrace \emptyset \rbrace, \lbrace \lbrace 7 \rbrace \rbrace, \lbrace \emptyset, \lbrace 7 \rbrace \rbrace \rbrace$.

Ef við tökum nú setninguna $P(A) \subseteq P(P(A))$ og niðurstöðurnar að ofan þá sést að: 

  - $\emptyset \in P(A)$
- $\{7\} \in P(A)$
- $\emptyset \in P(P(A))$
- $\{7\} \notin P(P(A))$


Þá er í þessi tilfelli er $P(A)$ ekki hlutmengi af $P(P(A))$, því $\{7\} \in P(A)$ en $\{7\} \notin P(P(A))$. Því getum við fullyrt að $P(A) \subseteq P(P(A))$ er **ekki** alltaf sönn. 

# Liður 3

##### Sýnið og skýrið eftirfarandi:

a. Dæmi um vensl á mengi sem eru bæði samhverf og andsamhverf. (10 stig)

b. Munur á milli falla og vensla. (5 stig)

Skýrið ítarlega hvað gerir vensl samhverf og andsamhverf og nefnið dæmi. Skýrið einnig muninn á falli og vensli og gefið gott sýnidæmi um muninn.

### Svar:

### A

Þegar vensl eru samhverf, þá þýðir það að ef eitt par er í venslinu, þá er gagnstæða parið líka í því:

 $$(a, b) \in R \implies (b, a) \in R \text{ fyrir öll } (a, b) \in R$$

Þegar vensl eru andsamhverf, þá þýðir það að ef a tengist b og b tengist a, þá þarf a og b að vera sama gildið, a = b

 Til dæmis er mengið:
 
 $$A = \{(1, 2, 3)\}$$ 
 
 og vensli:
 
 $$R = \{(1, 2), (2, 1), (3, 3)\}$$

 ekki andsamhverft þar sem 1 bendir á 2 og öfugt, en það er ekki sama gildi. 
 
 Tökum nú dæmi um mengi og vensl sem að eru bæði samhverf og andsamhverf

 Höfum eftirfarandi mengi:

 $$A = \{(1, 2, 3)\}$$

 og eftirfarandi vensl:

 $$R = \{(1, 1), (2, 2), (3, 3)\}$$

 Þetta er samhverft þar sem að fyrir hvert par í venslinu gildir að a = b, svo að fyrir hvert par er "andhverfa parið" alltaf til, svo það brýtur ekki reglu um samhverf pör

 Þetta er andsamhverft þar sem að það er ekkert tilvik þar sem a er ekki sama gildi og b, því er venslið bæði samhverft og andsamhverft

 ### B

Vensl á mengi A er hlutmengi af vörpunum úr AxA. Vensl getur tengt eitt gildi við annað eða sjálft sig
Til dæmis A = \{1, 2, 3\} og venslið R = {(1, 2), (1, 3)}. 
Hér tengist 1 bæði 2 og 3, getur sem sagt tengst nokkrum gildum

Fall er sérstakt vensl þar sem hvert gildi í frummenginu A tengist nákvæmlega einu gildi í myndmenginu B
Til dæmis $$\ f: A \to B$$ þar sem A = {1, 2, 3} og B = {a, b} og f = {(1, a), (2, b), (3, a)}

Þannig að sérhvert stak í mengi A, getur aðeins tengst einu staki úr myndmengi B.

Sem sagt í stuttu máli, vensl er almennt hugtak sem lýsir samböndum milli staka, þau geta tengst við eitt gildi, mörg önnur eða jafnvel sjálft sig. Fall er sérstakt vensl þar sem að hvert gildi tengist nákvæmlega einu öðru gildi í myndmengi þess.

# Liður 4 
####  Hægt er að sjá kóðann í skjalinu "Mengi og vensl - liður 4.py". 

## Útskýra hvernig eigi að keyra kóðann ykkar (og hvaða pakka þarf að setja upp, ef við á).

Fyrst þurfti að setja upp neðantalda pakka til að setja upp verkefnið á réttan hátt
pip3 install numpy - Það er sérstaklega öflugt fyrir útreikninga á fylkjum og fylkjaröðum.
pip3 install network - Það er notað til að meðhöndla og greina grafasafn og net. 
pip3 install matplotlib - Það er notað til að teikna og setja fram sjónræna framsetningu gagna.

Síðan til þess að keyra sjálft forritið þarf að skrifa: python "Mengi og vensl - liður 4.py"

#### Býr til slembifylki út frá afmælisdögum
Efst í kóðanum var búið til slembifræ með skipuninni "seed" út frá dagsetningu og 4x4 slembifylki út frá dagsetningum (afmælisdögum hópmeðlima), og voru fylkin skráð með tölunum 0 eða 1. Sett var upp fall með degi, mánuði og ári sem hægt var að setja mismunandi dagsetningar inn fyrir sem gaf út mismunandi fylki sem forritið gat lesið og ályktað hvort væri sjálfhverf, samhverf, andsamhverf eða gegnvirk. 

#### Athugar eiginleika fylkja
Eftir það var sett upp fjögur föll sem athuguðu eiginleika fylkis. 
* Sjálfhverf fylki: Hvert stak er tengt við sjált sig. Þ.e. sjálfhverf fylki hafa 1 á öllum meginás (þar sem röð og dálkur eru þau sömu, þ.e. i == j). 
Kóðinn notar listaskilgreiningu með all() sem fer í gegnum öll stök á meginás fylkisins (fylki[i][i]) og athugar hvort þau séu jöfn 1.
* Samhverf fylki: Ef stak a er tengt við stak b, þá er b tengt við a. Þ.e. Samhverf fylki eru þannig að fyrir alla i og j gildir að fylki[i][j] == fylki[j][i]. Það þýðir að fylkin eru eins og spegilmynd með tilliti til meginássins, (dálkar verða raðir). 
* Andsamhverf fylki: Ef stak a er tengt við stak b, þá tengist b ekki a. Þ.e. að fyrir öll i og j (þar sem i != j) gildir að fylki[i][j] == -fylki[j][i]. Oftast eru núll á meginásnum (þar sem i == j).
* Gegnvirk fylki: Ef stak a er tengt við b, og b er tengt við c, þá tengist stak a við c. Þ.e. Fyrir hvert par i, j þar sem bæði fylki[i][j] == 1 og fylki[j][k] == 1, verður fylki[i][k] að vera 1.

#### Prentar og teiknar niðurstöður
Því næst var búið til örvanet með networkx. 
G = nx.DiGraph() skapar tómt stefnt net.

Tvær lykkjur voru notaðar til að fara í gegnum öll stök fylkisins, þar sem fylki[i][j] == 1 gefur til kynna að það sé tengsl frá hnúti i til hnútar j. Þetta þýðir að það verður til ör (stefnt tengsl) frá i+1 til j+1.
G.add_edge(i+1, j+1) bætir þessum tengslum við í grafið.

Hnútarnir voru teiknaðir með örvum milli þeirra, þar sem hnútarnir tákna meðlimi í tengslaneti og örvarnar tákna stefnubundin tengsl milli þeirra.

pos = nx.spring_layout(G) var notað til að reikna út staðsetningu hnútanna i+1 og j+1. Það veldur því að hnútarnir dreifast á snyrtilegan hátt í rýminu með tilliti til tengslanna þeirra á milli.

### Útkoma og myndir (örvanet)

 Hér að neðan má sjá útkomu fyrir hvern afmælisdag:  

Fylkið fyrir dagsetninguna : 15-10-2002 og seed 15102002:

$$\begin{bmatrix}
0 & 0 & 0 & 0 \\
0 & 0 & 0 & 1 \\
1 & 1 & 0 & 0 \\
0 & 1 & 0 & 0
\end{bmatrix}$$


##### Eiginleikar venslanna:
Sjálfhverf: False
Samhverf: False
Andsamhverf: False
Gegnvirk: False

![Figure 1](/Figure_1.png)

Fylkið fyrir dagsetninguna 27-05-2001 og seed 27052001:
$$\begin{bmatrix}
1 & 1 & 1 & 1 \\
1 & 1 & 1 & 1 \\
0 & 1 & 1 & 0 \\
1 & 1 & 1 & 0
\end{bmatrix}$$

##### Eiginleikar venslanna:
Sjálfhverf: False
Samhverf: False
Andsamhverf: False
Gegnvirk: False

![Figure 2](/Figure_2.png)

Fylkið fyrir dagsetninguna 14-07-2003 og seed 14072003:

 $$\begin{bmatrix}
0 & 1 & 0 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 1 & 0 \\
1 & 0 & 0 & 0
\end{bmatrix}$$

##### Eiginleikar venslanna:
Sjálfhverf: False
Samhverf: False
Andsamhverf: True
Gegnvirk: False

![Figure 3](/Figure_3.png)

Fylkin lýsa nákvæmlega þeim tengingum sem eru sýndar í örvanetinu. Með því að skoða fylkin getum við séð hvaða hnútar eru tengdir í gegnum örvar í sjálfu netinu.

### Niðurstaða
Þá kemur í ljós að örvanetið er mismunandi eftir ólíkum dagsetningum þar sem þær tengdust við mismunandi örvanet. 

Með því að nota fylki til að tákna tengsl milli hnúta, er verið að sýna hvernig einstaklingar tengjast eða hafa áhrif á hver annan í neti, þar sem tengslin eru stefnubundin. 


