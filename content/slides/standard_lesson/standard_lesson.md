---
theme: serif
controlsBackArrows: 'faded'
progress: true
enableMenu: false
transition: convex
# enableChalkboard: false
# like them? see https://unsplash.com/collections/94734566/slidev
---
<!-- .slide: data-background="https://source.unsplash.com/1920x1080/?white" -->

# Argomento lezione

## sottotitolo

<br>

<br>

<br>

**autore**: [diego fantinelli](diego.fantinelli@gmail.com) | **data**: 28/08/2021

---

# introduzione
		
- **abstract:**[^1]
  
  Lorem ipsum dolor sit amet, $t=\sqrt{1-x^2}$ consectetur adipiscing elit. 

---

### topics

$$\int \sqrt{1-x^2} \, dx$$

--

- La semplice sostituzione $t=\sqrt{1-x^2}$ non risulta adeguata; 
- è opportuno porre $x=sin t$, da cui $t=arcsin x$, con $-\dfrac{\pi}{2} \leq t \leq \dfrac{\pi}{2}$, intervallo di invertibilità della funzione $x=sin t$.
- da  $\sqrt{1-x^2}$, si ricava  $t=\sqrt{1-sin^2 t} = cos t$, poiché: $$-\dfrac{\pi}{2} \leq t \leq \dfrac{\pi}{2} \Rightarrow cos t \geq 0$$

---

# teoremi e definizioni
## *teorema*:
- Una funzione $$F(x)$$ si dice **primitiva** di una funzione $y=f(x): I \subseteq \mathbb{R} \rightarrow \mathbb{R}$, se $F(x)$ è **derivabile** nell'intervallo $$I$$ e risulta: $F ^\prime(x)=f(x)$
- **_dimostrazione:_**
	- *scrivere qui la dimostrazione*

---

# esempio

>una breve descrizione non fa mai male.  
>--marchetto da Rubbio

--


| descrizione | formula          | note       |
| ----------- | ---------------- | ---------- |
| derivata    | x^2              | no comment |
| derivata    | y=x^2 - 3x+1 | non funziona una sega, però la tabella è _cool_    |
| derivata    | $$y=x^2 - 3x+1$$ | no comment |

--

1. questa non è una formula
2. questa sì: $$f(x)=\sum_{n=0}^\infty\dfrac{f^{(n)}(a)}{n!}(x-a)^n$$

---

## *esercizio*:
- Determinare il numero di soluzioni **reali** della seguente equazione: 
 - $$x^4 + 3x^2 - 4 = 0$$

---

### _soluzione_:
- effettuaimo la sostituzione $$t=x^2$$ ottenendo un'equazione di secondo grado: $$t^2 + 3t - 4 =0$$
- le cui soluzioni sono: 
$$\begin{align}
\Delta = b^2 - 4ac = 9 + 16 = 25\\
\Rightarrow t_{1,2}&= \dfrac{-b \pm \sqrt{\Delta}}{2a}\\ &= \dfrac{-3 \pm \sqrt{5}}{2}= 1, \, 4
\end{align}$$
- a questo punto è possibile sostituire e risolvere le due equazioni di secondo grado:
	- $$x^2 = 1$$
	- $$x^2 = -4$$
- che producono due soluzioni ciascuna. 
	Poiché siamo interessati alle **soluzioni reali** dobbiamo considerare soltanto la prima equazione e pertanto le soluzioni saranno due: 
	$${x = -1}$$ e $${x=1}$$

---