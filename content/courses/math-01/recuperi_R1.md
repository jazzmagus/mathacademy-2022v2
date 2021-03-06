---
title: Recuperi classi prime
linktitle: Classi prime | recuperi
toc: true
type: docs
date: "2021-09-09T00:00:00+01:00"
draft: false
slides: recuperi_R1
diagram: true
menu:
  math-01:
    parent: 
    weight: 

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 80
---

{{< toc >}}
<!-- {{< toc hide_on="xl" >}} -->

> ☆ **scadenza**: 30 settembre 2021

![ex1_img](../majong_01.png)

---

## Conoscenze

- Proprietà degli insiemi numerici $\mathbb{N}, \mathbb{Z}, \mathbb{Q}, \mathbb{R}$ e consapevolezza della necessità degli ampliamenti da $\mathbb{N}$ a $\mathbb{Z}$, da $\mathbb{Z}$ a $\mathbb{Q}$, da $\mathbb{Q}$ a $\mathbb{R}$.
Rappresentazione degli insiemi numericisu una retta orientata.
- Definizioni e proprietà delle quattro operazioni e delle potenze nei quattro insiemi numerici.

- `Divisibilità` in $\mathbb{N}$ e `numeri primi`;
 `mcm` e `MCD` di due o più numeri naturali.

- Concetto di `numero relativo` e di `valore assoluto`; *regola dei segni*.

- **Numeri razionali**: frazioni e rappresentazione decimale.
 Notazione `esponenziale` e notazione `scientifica` di un numero: ordine di grandezza.
 **Proporzioni** e **percentuali**.

- **Numeri irrazionali** e loro rappresentazione decimale.
 Concetto di `approssimazione` ed `errore` di un’approssimazione.

---

## Abilità

- Eseguire i calcoli con i numeri degli insiemi numerici  $\mathbb{N}$, $\mathbb{Z}$ e $\mathbb{Q}$
- Scomporre un numero naturale in fattoriprimi e calcolare il `mcm` e il `MCD` tra due o più numeri naturali.
Trasformare la scrittura di un numero naturale dalla base $10$ alla base $b$ e viceversa.
- Trasformare una frazione in numero decimale e viceversa;
scrivere un numero decimale finito in notazione scientifica e determinarne l’`ordine di grandezza`.
- Risolvere problemi su **proporzioni** e **percentuali**.
Calcolare l’errore relativo di un’approssimazione conoscendo l’errore assoluto e viceversa e determinare il valore abbreviato e quello arrotondato di un numero decimale.

---

## competenze

- Utilizzare le tecniche e le procedure del calcolo aritmetico ed algebrico, rappresentandole anche sottoforma grafica.
- Analizzare dati e interpretarli sviluppando deduzioni e ragionamenti sugli stessi anche con l’ausilio dirappresentazioni grafiche, usando consapevolmente gli strumenti di calcolo e le potenzialità offerte da applicazioni specifiche di tipo informatico.

{{< youtube cCJU5By_b8U>}}
## L’insieme dei numeri naturali

<!-- {{< figure src="../majong_01.png" caption="A caption" numbered="true" >}} -->

> Numeri, continuamente numeri: il numero dei giri, il numero della macchina, il distacco, il tempo trascorso, il tempo che manca, il numero sulla maglia, il punteggio...
>
> - Servono veramente tutti questi numeri?
> - Sono essenziali o se ne potrebbe fare a meno?

### 1. numeri naturali e loro ordinamento

- come si rappresentano gli insiemi numerici?

$$ \mathbb{N} = \\{ 0; 1; 2; 3; \dots \\} $$

>**osservazione**: l'inserimento dello `zero` nell'insieme $\mathbb{N}$ è ancor oggi una questione controversa, tanto che, a volte, si rende necessario distinguere i due *diversi* insiemi $\mathbb{N}$ in:

- $\mathbb{N}$: insieme dei numeri naturali, compreso lo `zero` (regalatoci dagli indiani...)

- $\mathbb{N^*}$: insieme dei numeri naturali, escluso lo `zero`

Nascono comunque dall'attività dell'uomo del `contare`, per questo vengono detti **naturali**.

## proprietà dell’insieme $N$

- L’insieme dei numeri naturali è `infinito`.
- Ogni numero naturale ha un `successivo`.
- Ogni numero naturale, eccetto lo zero, ha un `precedente`.
- Lo `zero` è l’elemento `minimo` dell’insieme dei numeri naturali.
- L’insieme dei numeri naturali `non` ha un elemento `massimo`

Per indicare che due numeri $a$ e $b$ sono uguali, useremo il simbolo $=$ e scriveremo: $$a=b$$ leggendo «*$a$ è uguale a $b$*»;

- la precedente **relazione** è `bidirezionale`, cioè deve intendersi nelle due direzioni, *sempre*.

Il termine a **sinistra** dell'uguale viene chiamato **primo membro**, mentre quello a **destra** si indica con **secondo membro**.

>ad esempio: $$17=17$$

La relazione di **uguaglianza** tra due numeri naturali gode delle seguenti proprietà:

- **riflessiva**: ogni numero è uguale a se stesso: $a=a$;
- **simmetrica**: se $a=b$ allora $b=a$;
- **transitiva**: se $a=b$ e $b=c$ allora $a=c$.

- I numeri naturali hanno un `ordine`, cioè, dati due numeri naturali, diversi tra loro, è sempre possibile confrontarli stabilendo tra essi una relazione di **disuguaglianza**:
  - se nella successione dei numeri naturali un numero $a$ precede un numero $b$, si dice che $a$ è **minore** di $b$ e si scrive: $$a<b$$
  - se invece $a$ segue $b$, si dice che $a$ è **maggiore** di $b$ e si scrive: $$a>b$$
- per indicare le relazioni d'ordine vengono utilizzati anche i simboli di **disuguaglianza**:
  - **maggiore o uguale**: si indica con il simbolo "$\geq$": $$a \geq b$$
    - **minire o uguale**: si indica con il simbolo "$\leq$": $$a \leq b$$
  >es.: proprietà transitiva della **disuguaglianza**:
  >
  >- se $a \leq b$ e $b \leq c$, allora $a \leq c$
  >
- I numeri naturali possono essere facilmente **rappresentati** graficamente attraverso una **semiretta orientata**

![semiretta numeri naturali](../semiretta_naturali.svg)

## Le quattro operazioni aritmetiche con i numeri naturali

### 2. addizione e sue proprietà

>**definizione**: la **somma** di due numeri naturali è quel numero naturale che si ottiene contando di seguito al primo tutte le unità del secondo.

1. proprietà **commutativa**:
   - cambiando l'**ordine** degli addendi il risultato non cambia: $$a+b=b+a$$
2. proprietà **associativa**:
   - la somma di tre numeri non cambia se a due addendi consecutivi si sostituisce la loro somma: $$(a+b)+c=a+(b+c)$$
3. Esiste l'**elemento neutro** dell’addizione:
   - è il `numero zero`. Ciò significa che sommando *zero* a qualsiasi numero si ottiene il numero dato

---

### 3. sottrazione e sue proprietà

- è un’operazione che si esegue tra due numeri, considerati nell’ordine, il primo detto `minuendo` e il secondo `sottraendo`. Il risultato della sottrazione si chiama `differenza`.

>**definizione**: la **differenza** tra due numeri naturali è quel numero naturale, se esiste, che addizionato al `sottraendo` dà come somma il `minuendo`.
>
>- esempio: $5-2=3$ perché $5=3+2$

- casi particolari:
- La sottrazione $4-6$ non si può eseguire in $\mathbb{N}$ perché non esiste alcun numero naturale che, sommato a $6$, dia $4$.
- La sottrazione, nell’insieme dei numeri naturali, si può eseguire solo se il minuendo è **maggiore** o **uguale** al sottraendo: $$a-b=c \rightarrow a= b+c$$ con $$a\geq c$$

- La sottrazione gode della proprietà `invariantiva`: se si somma o si sottrae uno stesso numero sia al minuendo sia al sottraendo, la differenza non cambia: $$(a-b)=(a+c)-(b+c)$$
  - Grazie alla proprietà invariantiva possiamo eseguire rapidamente alcune sottrazioni: $$(198-48)=(198+2)-(48+2)=200-50=150$$

- La sottrazione **non** gode della proprietà **commutativa**: $7- 5 =2$, ma $5-7$ non è calcolabile in $\mathbb{N}$ e non ammette elemento neutro: $2- 0 =2$, ma $0-2$ non si può eseguire in $\mathbb{N}$.
- La sottrazione **non** gode neppure della proprietà **associativa**.
  - Ad esempio per calcolare $15-4-2$ è necessario eseguire le sottrazioni `nell’ordine` indicato: $$\underbrace{(15-4)}_{11}-2=9$$

---

### 4. moltiplicazione e sue proprietà

>**definizione**: **prodotto** di due numeri naturali
>
>- è la somma di tanti addendi uguali al primo fattore quante sono le unità indicate dal secondo: $$a \cdot b= \underbrace{a+a+a+ \ldots + a}_{b \\; \text{addendi}}$$

1. proprietà **commutativa**: il prodotto tra due o più fattori non cambia se cambia il loro `ordine`: $$a \cdot b = b \cdot a$$
1. proprietà **associativa**: il prodotto di tre numeri non cambia se a due fattori consecutivi si sostituisce il loro prodotto: $$(a \cdot b)\cdot c= a \cdot (b \cdot c)$$
1. proprietà **distributiva**:
   - della moltiplicazione rispetto alla addizione: $$a \cdot (b+c)= a \cdot b + a \cdot c$$
   - della moltiplicazione rispetto alla sottrazione: $$a \cdot (b-c)= a \cdot b - a \cdot c$$
1. raccoglimento a `fattor comune`: si ottiene leggendo nell'altro verso la proprietà distributiva: se in una somma **tutti** gli addendi hanno un `fattore` in comune, esso può essere `raccolto` e `moltiplicato` per la somma degli altri termini; allo stesso modo per la differenza:
$$\underbrace{3 \cdot 7 + 3 \cdot 5}\_{21+15=36} = \underbrace{3 \cdot (7+5)}\_{3 \cdot 12 = 36} \qquad \underbrace{8 \cdot 12-8 \cdot 9}\_{96-72=24}=\underbrace{8 \cdot(12-9)}\_{8 \cdot 3=24}$$
1. esistenza dell'elemento `neutro`: moltiplicando qualsiasi numero per `uno` si ottiene il numero dato
1. esistenza dell'`elemento annullatore`: moltiplicando qualsiasi numero per `zero` si ottiene `zero`
1. **Legge di annullamento del prodotto**: se il prodotto tra due o più fattori è `zero` allora almeno uno dei fattori è `zero`

---

### 5. divisione e sue proprietà

>Il `quoziente` tra due numeri naturali, dei quali il secondo diverso da `zero`, è quel numero naturale, se esiste, che moltiplicato per il `divisore` dà il `dividendo`:
>
>- $a : b=c$, con $b \neq 0$, $\underbrace{\Longrightarrow}_{\text{implica}} a=b \cdot c$
>
>se la divisione si può eseguire in $\mathbb{N}$, allora si dice che $a$ è **divisibile** per $b$ o anche che $b$ è **multiplo** di $a$.
>
>- Ad esempio $24$ è divisibile per $6$  e $24$ è multiplo di $6$
>- La divisione $19:5$ non può essere eseguita in $\mathbb{N}$, poiché non esiste alcun numero naturale che, moltiplicato per $5$, dia $19$.
>
>**ATTENZIONE**:
>
>- Non è invece possibile eseguire la divisione di un numero naturale e lo `zero`, poiché il risultato dovrebbe essere un numero che, moltiplicato per `zero` dia il numero iniziale, ma qualsiasi numero moltiplicato per `zero` restituisce `zero`, che rappresenta infatti l'elemento **annullatore** della moltiplicazione.
>- La divisione $0:0$ invece ha infiniti risultati, poiché esistono infiniti numeri che moltiplicati per`zero` danno come risultato `zero`.
>- La divisione per `zero` quindi **non è mai definita**

- **casi particolari**:

| in generale            | esempio | osservazioni|
| ---------------------- | ------- |---|
| $a:1=a$                | $6:1=6$ |$1$ può essere considerato l'*elemento neutro* della divisione|
| $a:a=1$, con $a \neq 0$               | $6:6=1$ | se *dividendo* e *divisore*, entrambi $\in \mathbb{N}$ sono uguali, il risultato della divisione è l'**unità**
| $0:a=0$, se $a \neq 0$ | $0:6=0$ |lo $0$ al **dividendo** può essere considerato l'*elemento annullatore* della divisione|

`Q: Qual è la differenza tra divisione e quoziente?`

### proprietà invariantiva della divisione

- se si moltiplicano o si dividono sia il dividendo sia il divisore per uno stesso numero - diverso da zero -, il quoziente non cambia:

  - $a:b=(a \cdot c):(b \cdot c)$
  - **esempio**:
$$65:5=(65 \cdot 2):(5 \cdot 2)=130:10=13$$

  - $a:b=(a : c):(b : c)$

  - **esempio**:
$$72:12=(72 : 2):(12 : 2)=36:6=6$$


