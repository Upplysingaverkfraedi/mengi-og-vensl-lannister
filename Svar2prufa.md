# 2. Veldismengi 
Látum $P(A)$ vera veldismengið af menginu $A$. Sýnið hvort að $P(A) \subseteq P(P(A))$ sé alltaf það sama. Rökstyðjið af hverju eða af hverju ekki

## Svar: 

### Við skulum fyrst byrja á því að skilgreina mengin okkar: 
$P(A)$ er veldismengi sem er venslað af mengi $A$ svo að stök $A$ eru öll hlutmengi mengisins $A$, $P(A)$. 
Sem dæmi ef að $A = \lbrace 1, 2, 3 \rbrace$ þá er $P(A) = \lbrace \emptyset, \lbrace 1 \rbrace, \lbrace 2 \rbrace, \lbrace 3 \rbrace, \lbrace 1,2 \rbrace, \lbrace 1,3 \rbrace, \lbrace 2,3 \rbrace, \lbrace 1,2,3 \rbrace \rbrace$.
$P(P(A))$ er veldismengi af veldismenginu $P(A)$ og inniheldur því öll hlutmengi $P(A)$.

### Næst skoðum við $P(A) \subseteq P(P(A))$: 
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
