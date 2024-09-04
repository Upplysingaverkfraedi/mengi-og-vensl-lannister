# 1. Mengjafræði 
Látum A og B vera hlutmengi alsherjarmengisins U. Notið skilgreiningar á mengjahugtökum og þekktar umritunarreglur til að sýna að:

## a. Sýnið að sniðmengi $A \cap B$ má skrifa sem:

$$
        A \cap B = A \setminus(A \setminus B)
$$
### Svar: 
Byrjum á því að skilgreina sniðmengi (∩) og mismengi (∖): 
Sniðmengi $A \cap B$ er samansett af öllum gildum sem tilheyra bæði hlutmengis A og B. 
        $A \cap B = \{x \in U \mid x \in A \text{ og } x \in B\}$
        
Mismengi tveggja mengja A og B er mengi þeirra staka sem eru í A en ekki í B.
        $A \setminus B = \{x \in U \mid x \in A, x \notin B\}$

Næst skoðum við mengið $A \setminus (A \setminus B)$: Þetta mengi er úr öllum þeim stökum sem tilheyra A en ekki mismenginu $(A∖B)$.
Mengið $(A∖B)$ er úr gildum hlutmengisins A en ekki B. 
Því getum við sagt að mengið $A \setminus (A \setminus B)$ er samansett af öllum gildunum sem eru í A og í B sem jafngildir sniðmenginu $A \cap B$. 


## b. Sýnið að sammengi $(A \cup B)$ má skrifa með hjálp mismunamengja:

$$
        A \cup B = (A \setminus B) \cup B
$$
### Svar: 
Sammengi $A \cup B$ er mengi allra þeirra staka sem tilheyra hlutmengis A, B eða þeim báðum. 
        $A \cup B = \{x \in U \mid x \in A \text{ eða } x \in B\}$

Eins og í lið a. þá er mengið $(A∖B)$ úr stökum hlutmengisins sem er í A en ekki í B. 
$(A \setminus B) \cup B$ er því mengi stakana sem eru annaðhvort í $A∖B$ eða B. 
Því er jafngilt því að segja $A \cup B$ og $(A \setminus B) \cup B$. 
