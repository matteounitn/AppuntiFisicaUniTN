# Fisica

[TOC]

## 18/02/2019

### Metodo Scientifico

> Fenomeno di interesse e sua idealizzazione, ho grandezze fisiche per descriverlo (**unità**), osservazione e misura (**incertezze**), formulazione di ipotesi, passando dal **modello alla legge fisica**.
>
> Attraverso quest'ultima (legge fisica) per descrivere e prevedere ed in caso **falsificare l'ipotesi.**

---

### Unità del sistema internazionale

#### Grandezze fisiche e la loro misurazione

#### Incertezza di misura

#### Grandezze Fondamentali

#### Sistemi di Unità di Misura

#### Sistema Internazionale

#### Cifre significative e Arrotondamenti

---

### Cinematica

La cinematica è la descrizione del moto degli oggetti, rappresentati da punti materiali.

> **Punto materiale**: Punto con delle proprietà fisiche, privandolo dell'estensione. Lecito quanto piccolo è l'oggetto.
>
> *(Più piccolo, più lecito).*

Esempio:

*Luna è un punto materiale con un rapporto 100 alla terra*.



#### Legge oraria del moto

Scelgo un **punto**, un **verso di percorrenza** e creo il movimento del punto in **UNA dimensione.**

Un punto materiale non fa spazio ne ingombro.

Posso assumere una unità di misura nella retta orientata (tipo centimetri).



![1550510794776](/home/matteo/.config/Typora/typora-user-images/1550510794776.png)



La legge oraria posso esprimerla con una **tabella**:

| $t(s)$ | $s(m)$ |
| :----: | :----: |
|   0    |   2    |
|   1    |   0    |
|   2    |   -1   |
|   3    |   1    |
|   4    |   4    |

E disegno un **GRAFICO**:

![1550510934763](/home/matteo/.config/Typora/typora-user-images/1550510934763.png)





> **Equazione oraria**: $s=s(t)$

**spazio** in funzione del **tempo**.

La legge oraria può variare in base alla funzione che ho su $s(t)$



*Esempi*

s=$A \cos(Bt)$

> Nota bene che:
>
> **NON** posso rimuovere la costante A, mentre posso rimuovere la costante B(se ad esempio la B vale 1), ma è consigliato tenerla in ogni caso. Senza A non posso dire di che cosa si tratta, di lunghezza, di tempo etc etc, quindi A deve essere **DEFINITA** ed avere una unità di misura.

> **Pulsazione**: nella **formula** **precedente** la pulsazione è $\omega=B$.





#### Velocità media

Velocità positiva![1550510163049](/home/matteo/.config/Typora/typora-user-images/1550510163049.png) 

Velocità negativa![1550511250810](/home/matteo/.config/Typora/typora-user-images/1550511250810.png)

> **Equazione:** $V_m={\Delta x\over\Delta t}$

Ovviamente ha una unità di misura

$[v]={[s]\over[t]}$

Le parentesi quadre indicano una equazione dimensionale, stiamo considerando l'uguaglianza del punto di vista delle **dimensioni**.



Abbiamo ovviamente una **unità di misura**

$udm(v)={udm(s)\over udm(t)}={m\over s}$

*può essere metri al secondo come altro(km/h...)*



> Nota che **è una differenza, non dipende dal sistema che abbiamo utilizzato**.



utilizzando il sistema di riferimento di prima (**tabella**), abbiamo:

${-2\over1}=-2{m\over s}$

$-1{m\over s}$

$2{m\over s}$

$3{m\over s}$



> **Coefficente Angolare: ** Nel grafico ho
>
> **$m={\Delta y\over\Delta x}$**





> Nota bene che **il grafico con tempo, non può avere valori che "tornano indietro nel tempo".**



#### Velocità istantanea



> Velocità nel tempo che dipende dall'istante $t$.

$\lim_{\Delta t\longrightarrow0}{\Delta x\over \Delta t}=v$

anche detta

> $\lim_{\Delta t\longrightarrow0}{\ x(t)-x_0\over t-t_0}=v(t)$ 
>
> Rapporto incrementale, quindi è la **derivata** nel grafico **spazio tempo.**

*Esempi:*



$s(t)=At \Longrightarrow v(t)={ds\over dt}=A$

Essendo t Tempo, **A sarà spazio tempo perchè mi fornisce un uguaglianza = spazio, quindi deve dare spazio.** Quindi A sarà la **Velocità**.



$v(t)=A[-\sin(\omega t)]\omega=-A\omega \sin(\omega t)$

In questo caso A è **Spazio**.



Avendo la **legge oraria della velocità**, posso ottenere la **legge oraria del moto** integrando $v(t)​$



![1550511395367](/home/matteo/.config/Typora/typora-user-images/1550511395367.png)

> $s(t)-s_0=\int^t_{t_0} d\tau v(\tau) \Longrightarrow s(t)=s_0+\int_{t_0}^t d\tau v(\tau)$

quindi

$s(t)=s_0+\int^t_{t_0}\bar{v}d\tau=s_0+\bar{v}(t-t_0)$

Avendo una velocità costante ottengo

$s(t_0)=s_0+\bar{v}(t_0-t_0)=s_0$



#### Accelerazione



> **Variazione** della velocità nel tempo o **Derivata** della velocità nel tempo
>
> $\lim_{\Delta t\longrightarrow0}{\ v(t)-v(t_0)\over t-t_0}=a(t_0)$ 

> **Protip**: Controllo di avere consistenza dimensionale
>
> $[a]={[v]\over[t]}={[s]\over[t][t]}=[s/t^2]$



##### Accelerazione Gravitazionale 



> L**'accelerazione gravitazionale** è pari a
>
> $g=9,8055{m\over s^2}$

![1550511703222](/home/matteo/.config/Typora/typora-user-images/1550511703222.png)

> **Punti estremanti**: Punti di massimo e di minimo, punti nei quali  l'accelerazione vale ZERO, cioè la velocità è costante.





#### Integrale della velocità



> $v(t)=v_0+\int_{t_0}^t d\tau a(\tau)$



*Nota che:*

**Integrando** accelerazione, ottengo la **velocità**.

**Integrando ancora** , ottengo lo **spazio**.

**Derivando** lo spazio, ottengo la **velocità**.

**Derivando ancora** ottengo **l'accelerazione**.

![1550511505456](/home/matteo/.config/Typora/typora-user-images/1550511505456.png)

> **Protip**:
>
> $F={-G\cdot m\cdot M\over r^2}={-m\cdot g\cdot r}$
>
> l'accelerazione gravitazionale è **diversa** in base a dove mi trovo nella terra, ma di poco, quindi la **assumo** come **definita prima**.

#### Esercizio

**Protip**: Io posso piazzare il mio asse delle $x$, cioè s(t) come mi pare e piace, quindi posso ottenere una $g$ **negativa**, per avere una accelerazione **positiva**.

> Un tipo tira un sasso in aria
>
> DATI:
>
> $v_0=?$
>
> $h=4,0 m$



$s_0=0, t_0=0$

$a=+g (g=-9,81 m/s^2)$

$v(t)=v_0 >0 + \int ^t _0 d\tau a(\tau)=v_0+\int ^t _0 d\tau g=v_0+gt$

dove g è ovviamente l'accelerazione gravitazionale.

$s(t)=s_0+\int_{t0}^t d\tau v(\tau)=\int_0^t d\tau (v_0+g\tau)=v_0t+g{t^2\over2}$

---

---

### 22/02/2019

Ricordiamo che **l'accelerazione** è un **differenziale** della velocità

${dv\over dt}=a$

tornando all'esercizio precedente, otteniamo 

$\begin{cases} v(t)=v_0+gt \\ s(t)=v_0t+{1\over 2}gt^2 \end{cases}$



Ora nel punto in cui la velocità è zero:

$\begin{cases} v(t)=0=v_0+gt_{max} \\ s(t)=h_{max}=v_0t_{max}+{1\over 2}gt_{max}^2 \end{cases}$

![1550830324261](1550830324261.png)

Continuando:

$\begin{cases}v_0=-gt_{max} \\h_{max}=-{1\over2}gt^2_{max}\end{cases}=\begin{cases} v_0=-g\sqrt{2h_{max}\over-g}=\sqrt{|g|^2{2h_{max}\over-g}}=\sqrt{-2gh_{max}}=8,9m/s\\t_{max}=\sqrt{2h_{max}\over-g}=\sqrt{8m\over9,8m/s^2}=\sqrt{0,816}\end{cases}$

![1550830593170](1550830593170.png)

#### Esercizio: Doppio lancio vericale

Vengono lanciati due sassi

> **DATI**: 
>
> $v_0=8,0 m/s$
>
> $a=g=-9,8055m/s^2$
>
> $s_0=0m$
>
> $t_{0A}=0s$
>
> $t_{0B}=$Arbitrario

Si incontrano per $s>0$?

Se aspetto che il primo sasso vada a terra, **no.**

![1550831035270](1550831035270.png)

Come possiamo vedere, la possibilità che si incontrino è **nell'intersezione delle due parabole.**

1. **Primo Caso/Modo:** $t_{0B}>t_{LA}=2t_{max}=2\sqrt{-2h_{max}\over g}$

   se ho che lo lancio dopo il landing dell'altro.

2. **Secondo Caso/Modo**:
   $\begin{cases}s(t)=v_{0A}(t-t_{0A})+{1\over2}g(t-t_{0A})^2 \\s(t)=v_{0B}(t-t_{0B})+{1\over2}g(t-t_{0B})^2\end{cases}$ ottengo $\cancel{v_0t+{1\over2}gt^2}=v_0(\cancel{t}-t_{0B})+{1\over2}g(\cancel{t}-t_{0B})^2$

   **Ottengo** dunque che

   $0=-v_0\ t_{0B}+{1\over2}gt^2_{0B}-gt_{0B}$

   **arrivando** a $t$

   $t={{1\over2}gt^2_{0B}-v_0t_{0B}\over gt_{0B}}={t_{0B}\over2}-{v_0\over g}$



### Grandezze vettoriali

$s\longrightarrow\overrightarrow{s}$

$v\longrightarrow\overrightarrow{v}$

$a\longrightarrow\overrightarrow{a}$



Ci sono diversi tipi di **assi**

1. **Cartesiano**
   ![Le ASSONOMETRIE – educazionetecnica.dantect.it](cartesiano.gif)

2. Cilindrico (Cyl) ![Cylindrical coordinate system - Wikipedia](download.png)

3. Polare

   ![Triple integral change of variable examples - Math Insight](polare.png)





Formule (le quali non ho idea a cosa si riferiscano)



$ s\longrightarrow \Delta\overrightarrow{s}=\Delta\overrightarrow{r}=\bigg(\begin{smallmatrix}\Delta x\\\Delta y\\\Delta z\end{smallmatrix}\bigg)=\Delta x \ \hat x + \Delta y \ \hat y + \Delta z \ \hat z$



$\overrightarrow{v}_M={\Delta\overrightarrow{s}\over\Delta t}=\Bigg(\begin{smallmatrix}{\Delta x\over\Delta t}\\{\Delta y\over\Delta t}\\{\Delta z\over\Delta t}\end{smallmatrix}\Bigg)=\bigg(\begin{smallmatrix}{v_x}\\{v_y}\\{v_z}\end{smallmatrix}\bigg)= v_x \ \hat x + v_y \ \hat y + v_z \ \hat z$





#### Velocità istantanea in più dimensioni

> $\overrightarrow{v}(t)=\lim_{t'\longrightarrow t} {\overrightarrow{s}(t')-\overrightarrow{s}(t)\over t'-t}$

Al cambio di dimensioni posso avere valori in più.

La velocità, in ogni caso, **è sempre tangenziale alla direzione**.

#### Accelerazione in più dimensioni

> $\overrightarrow{a}(t)=\lim_{t'\longrightarrow t} {\overrightarrow{v}(t')-\overrightarrow{v}(t)\over t'-t}$

Prima avevo solo una variazione di velocità, qui invece ci dice che l'accelerazione c'è se la velocità in un certo istante è **diversa** dalla velocità in un altro istante. Ciò **non implica** che i vue valori siano diversi. In **matematichese**:

$\overrightarrow{a}=\overrightarrow{0} \Rightarrow \overrightarrow{v}(t')\ne\overrightarrow{v}(t)\nRightarrow v(t')\ne v(t)$

Possiamo avere

1. Moto rettilineo uniforme **(MRV)**
2. Moto rettilineo uniforme vario **(MRVA)**
3. Moto non rettilineo uniforme **(MNRV)**
4. Moto non rettilineo non uniforme **(MNRNV)**

![1550832890549](1550832890549.png)

![1550832978953](1550832978953.png)

### Moto circolare uniforme

> Ha **velocità costante**, con traiettoria **circonferenza**.

$\begin{cases}x=r\cos\phi \\y=r\sin\phi\end{cases}$

per trovare le coordinate.



> $r(t)=\cos t=R \Rightarrow s=R\phi$

*Perchè R=s_phi.... ?* boh(dubbio)



*Ogni punto della velocità è tangente alla circonferenza*(incerto)



La velocità è il prodotto della **velocità angolare per il raggio**.

> **Velocità:** 
>
> $v={ds\over dt}={d(R\phi)\over dt}=R\ {dy\over dt}= \omega R$

$\omega$ è la **pulsazione**, cioè la **velocità angolare.**

> **L'accelerazione**:
>
> $a={dv\over dt}=R\ {d\omega\over dt}=\alpha R$

L'accelerazione è **diretta verso il centro**, cioè **accelerazione** **centripeta.**

Accelerazione centripeta in un moto non circolare = **accelerazione normale**.

È normale moto, perpendicolare.

![Moto circolare uniforme](acccentripeta.png)

**Nota che**:

Se non ho una circonferenza, posso dire che **l'accelerazione ORTOGONALE** ci porta ad avere un'accelerazione centripeta verso una ipotetica circonferenza per la nostra curva:

![https://proxy.duckduckgo.com/iu/?u=http%3A%2F%2Fwww2.unipr.it%2F~basgio93%2F2004%2FXI%2Findex_files%2Fimage055.jpg&f=1](accortogonale.jpg)





$v_x={dx\over dt}=R{d\cos \phi\over dt}=-R\sin \phi {d\phi\over dt}$

$v_y={dy\over dt}=R{d\sin \phi\over dt}=R\cos \phi {d\phi\over dt}$



**Quindi ottengo che**

> $v=\sqrt{v_x^2+v_y^2}=R{d\phi\over dt}=R\omega$

con le **accelerazioni** 

$a_x={dv_x\over dt}=-R[{\cos \phi({d\phi\over dt})^2}+\sin \phi \xcancel{({d^2\phi\over dt^2})}]$

$a_y={dv_y\over dt}=R[{-\sin \phi({d\phi\over dt})^2}+\cos \phi \xcancel{({d^2\phi\over dt^2})}]$

> **Nota bene**: ${d^2\phi\over dt^2}={d\over dt}[{d\phi\over dt}]$
>
> dove $[{dy\over dt}]$=$\omega$ è costante, quindi la derivata di una costante è **zero**.



## 25/02/2019

$\omega=\cos t$

> **Velocità angolare:** $v=\omega r$



#### esercizio palla di cannone

Calcolo della traiettoria di un oggetto sparato con un cannone.



Il cannone è posizionato su $(0,0)$.

$x_0=0$ 	$v_{0x}=v_0\cos\phi$

$y_0=0$		$v_{0y}=v_0\sin\phi$

$\overrightarrow{v}_0=v_{0x} \hat{x}+v_{0y} \hat{y} \iff v_o, \phi$

$\begin{cases} x(t)=x_0+v_{0x}t\\ y(t)=y_0+v_{0y}t+{1\over2}at^2\end{cases} \begin{cases} x=v_{0x}t\\ y=v_{0y}t-{1\over2}gt^2\end{cases} \begin{cases} t={x\over v_{0x}}\\ y={v_{0y}\over v_{0x}}x-{1\over2v_{0x}}gx^2\end{cases}$

ottenendo

$x=-{b\over a}= \tan\phi {2v_{0x}^2\over g}={2v_{0x}v_{0y}\over g}$ 

Sottolineo che ho sostituito $y=\tan\phi x -{g\over 2V_{0x}^2}x^2=bx+ax^2$





La componente **perpendicolare** cambia la direzione del moto.

**Nota**

Non posso dopo un po' continuare a derivare perchè ottengo

$\overrightarrow{F}=c\cdot \overrightarrow{a}$

derivando rimarrebbe solo $c$.



### Inzerzia

#### Primo principio di inerzia:

$\overrightarrow{v}=\overrightarrow{0}$

$\overrightarrow{v}=\overrightarrow{costante}$

> Un corpo rimane in moto rettilineo uniforme fino a quando una forza esterna ne cambia e ferma la quiete del moto.

**Sistema di riferimento inerziale**: Sistema di sistemi di riferimento tra i quali, per passare tra di essi attraverso una **velocità costante**.

> **Molto importante:** Se sono sopra un oggetto movente non posso affermare se si sta muovendo, perchè mi sto muovendo con esso.

#### Secondo principio di inerzia:

##### Esperimenti carrelli

*IMMAGINE che non trovo*

avendo due carrelli che si tirano tra loro con una molla di mezzo cosa succede?

Beh se i carrelli sono uguali, ho i $\Delta v1=\Delta v2$

altrimenti, se carrello 2 è 2 volte la **massa** del carrello 1 ottengo $\Delta v1=2\Delta v2$

idem se vale 3 ottengo $\Delta v1=3\Delta v2$

da qui otteniamo che 

> $\overrightarrow{F}=m\cdot \overrightarrow{a}$

Sull'es di prima ottengo

$\overrightarrow{p}=m\cdot \overrightarrow{v}$



Forza è la variazione della quantità di moto per l'unità di tempo.

La forza è l'interazione.

per l'esercizio di prima, con$ v1$ con stessa massa di $v2$ abbiamo

${d\overrightarrow{p}_1\over dt}=-{d\overrightarrow{p}_2\over dt}$

dove $\overrightarrow{F}_1={d\overrightarrow{p}_1\over dt}$ $\overrightarrow{F}_2={d\overrightarrow{p}_2\over dt}$



OTTENENDO

$\overrightarrow{F}_1=-\overrightarrow{F}_2$

$\overrightarrow{F}={d\overrightarrow{p}\over dt}={{d\over dt}(m\overrightarrow{v}_2)}={dm\over dt}\overrightarrow{v}+m {d\overrightarrow{v}\over dt}$

Noi sappiamo che $a= {d\overrightarrow{v}\over dt}$



quindi abbiamo la **seconda legge della termodinamica**

>$\overrightarrow{F}={d\overrightarrow{p}\over dt}$ 
>
>cioè $\overrightarrow{F}= m\cdot \overrightarrow{a}+ {dm\over dt}\overrightarrow{v}$
>
>**LA MAGGIOR PARTE DELLE VOLTE** ${dm\over dt}\overrightarrow{v}$ SI PUÒ **IGNORARE** PERCHÈ È NULLO, vale se abbiamo tipo un razzo mandato nello spazio.

Unità di misura: **NEWTON** =km/h

$\overrightarrow{F}={d\overrightarrow{p}\over dt}$ 

${d\overrightarrow{p}}={\overrightarrow{F}}{dt}$

per calcolare la 

**forza media** dobbiamo avere l'impulso.

> **Impulso**: $\Delta \overrightarrow{p}=\int^t_{t_0}\overrightarrow{F}(\tau)d\tau$



Avendo poi

> **Forza media**: $\overrightarrow{\bar{F}}={\Delta\overrightarrow{p}\over\Delta t}$



#### Esercizio pallina da tennis

Ho una pallina da tennis, la tiro contro il muro che succede?

$m=150g$ di pallina

$v=36 km/h=10m/s$

otteniamo

$\xcancel{\overrightarrow{p}_i=1,5kg\ {m\over s}}$ è sbagliato!



**Non ho un vettore dall'altra parte!** devo mettere $\hat{x}$

$\overrightarrow{p}_i=1,5kg\ {m\over s}\cdot \hat{x}$

ottenendo

$\begin{cases} \overrightarrow{p}_i=1,5kg\ {m\over s}\cdot \hat{x} \\ \overrightarrow{p}_i=-1,5kg\ {m\over s}\cdot \hat{x} \end{cases}$



il professore dovrà fornirmi in quanto tempo si stretcha. ($\Delta t$)



> **Principio di sovrapposizione:**
>
> Gli effetti delle forze sono equivalenti alla sovrapposizione degli effetti delle forze (_somma_)
>
> $\overrightarrow{F}_{tot}=m \overrightarrow{a}_{tot}$





$\overrightarrow{s}(t)=\overrightarrow{s}_0+\int^t_{t_0} d\tau \overrightarrow{v}_0(\tau)+\int^t_{t_0} d\tau+\int^\tau_{t_0} du {\overrightarrow{F}(u)\over m}\bcancel{(du-du)}$



**in ordine di forza crescente:**

1. Forza di gravità

2. Forza debole

3. Forza elettromagnetica

4. Forza Forte

----

----

## 01/03/2019

### Forza di gravità

![1551434665292](1551434665292.png)

La massa descrive **quanto intensamente** sento la gravità.

> **Forza che 1 esercita su 2:** $\overrightarrow{F}_{1\rightarrow2}=-G{m_1m_2\over r^2_{12}}\hat{r}_{12}$



dove G è la costante di **gravitazione universale**

$G=6,67\cdot 10^{-11} {N\cdot m^2\over kg^2}$

La massa $m_1 $ è influenzata dalla massa $m_2$ e viceversa. 

La gravità si propaga alla velocità della luce, ma non è istantanea, però per noi abbiamo velocità infinita.

> Nota sulla elettricità:
>
> $\overrightarrow{F}=Kel{g1g2\over r^2_{12}}\hat{r}_{12}$ dove $Kel={1\over4\pi\epsilon_0}$



### Forza Peso

Forza con la quale descrivo il fenomeno della caduta dei gravi sulla superfice terrestre.

*Ho un palazzo alto 100 metri, butto un sasso.*

$\overrightarrow{F}=-G{Mm\over r^2}\hat{r}$ dove $M$ è la massa della terra, $m$ è la massa del sasso.($\overrightarrow{P}=-m\overrightarrow{g}$)

> **Teorema della forza centrale:** Posso assumere che la massa sia concentrata al centro dell'oggetto, poichè le forze applicate vanno al centro.

$\overrightarrow{F}=-G{M_Tm\over (R_t+h)^2}=-{GM_T\over R_T^2(1+{h\over R_T})}m$

ora so che

$(1+\epsilon)^\alpha=1+\alpha\epsilon$ con $\epsilon<<1$

quindi

${1\over1+e}=1-\epsilon$

So che 

$-{GM_T\over R_T^2}(1+2{h\over R_T})m=-{GM_T\over R_T^2}$ perchè $(1+2{h\over R_T})$ è dell'ordine di $10^{-5}$

$\overrightarrow{g}=G{M_T\over R_T^2}\hat{R_T}$





**La gravità della luna è un sesto della gravità della terra**

la massa è collegata in qualche modo a ciò?

**NO**.





#### Piano inclinato

![1551436719109](1551436719109.png)



$\overrightarrow{N}+\overrightarrow{P}_{perp}=0$

$P_{parall}=P\sin \alpha$

$P_{perp}=P\cos \alpha$

$\begin{cases}t:ma_t=F_t=mg\sin \alpha \\n: ma_n=F_n=0 \end{cases}$

da questo ottengo $a_t=g\sin\alpha$



Se aggiungo una fune

![1551437365748](1551437365748.png)

ottengo che ho una forza $T$ che sommata a $P_t $ è $=0$

quindi ottengo 

$\overrightarrow{P}+\overrightarrow{N}+\overrightarrow{T}=\overrightarrow{0}$





Importante:

$\overrightarrow{F}_c=m\overrightarrow{a}_c\ne\overrightarrow{0}$



Con la forza centripeta, posso immaginarmi come una fune che è collegata al centro della circonferenza.

Dunque il carico di rottura sale quadraticamente:

$F_c=-m\omega^2R=-G{mM\over R^2}$

otteniamo che 

> **Terza legge di Keplero**
>
> $\omega^2={GM\over R^3}\Longrightarrow_{w={2\pi\over T^2}} {R^3\over T^2}={GM\over4\pi^2}$ dove questa è **costante**.



### Forza di attrito

Forza di **reazione vincolare**.

$\overrightarrow{F}_a| \overrightarrow{F}_t+\overrightarrow{F}_A=\overrightarrow{0}$

##### L'attrito statico 

dipende da quanto l'oggetto "preme". Ovviamente dipende dalla forza peso, che è uguale e opposta a $N$. Quindi uso N

> **Nota bene che:**
>
> $\overrightarrow{F}_a\le \overrightarrow{F}_{a,max}=\mu_S|\overrightarrow{N}|\hat{t}$
>
> Questo esiste sempre. $\mu_S$ è il **coefficente di attrito statico**.



##### Attrito dinamico

> $\overrightarrow{F}_{AD}=\mu_C|\overrightarrow{N}|\hat{t}\longrightarrow \overrightarrow{F}_{AD}=-\mu_C|\overrightarrow{N}|\hat{v}$



Disco rotante:

Velocità $\omega$, ho la corona inglese sopra, forza di attrito$ \mu s=0,3$ qual è il massimo a cui posso far girare prima che se ne vada?

## 04/03/2019

*spiegazione disco rotante che ho perso*



### Esercizio: Macchina che frena(senza ABS)

Ho una macchina che frena

$t_{f}=$tempo frenata$=?$

$s_f=$spazio frenata$=?$

$\mu s$

$\overrightarrow{F}=-\overrightarrow{F}_a=m\overrightarrow{a}$

$-\mu_cN=m{dv\over dt}$

$-\mu_cN(t-t_0)=m(v(t)-v_0)$

$-\mu_c\bcancel{m}g(t_f-t_0)=m(v_t-v_0)$ dove $mg=N$ e $v_t=0$

ottengo:

$\mu_cgt_f=v_0$



Concludendo

$t_f={v_0\over\mu_cg}\Longrightarrow s_f={1\over2}at_f^2={1\over2}(-\mu_cg){v_0^2\over(\mu_cg)^2}=-{1\over2}{v_0^2\over \mu_cg}$

la posso calcolare integrando

$-\mu_cN{(t-t_0)^2\over2}=m[(s(t)-s_0)-v_0(t-t_0)]$

ottenendo

$-\mu g{t_f^2\over2}=s_f-v_0t_f$

### Esempio della carrucola



![1551865138841](1551865138841.png)



Ho due carrucole, attaccate ad una ruota.

Supponendo che la corda **non si estende**:

1. Si muovono a velocità uguali;
2. Le variazioni di velocità sono uguali.

Posso dunque supporre che $\overrightarrow{a}=\overrightarrow{a}_1=\overrightarrow{a}_2$

$\begin{cases}m_1\overrightarrow{a}=\overrightarrow{P}_1+T\\m_2\overrightarrow{a}=\overrightarrow{P}_2+T\end{cases}\Longrightarrow\begin{cases}m_1\overrightarrow{a}=\overrightarrow{P}_1-T\\m_2(-\overrightarrow{a})=\overrightarrow{P}_2-T\end{cases}\Longrightarrow \begin{cases}m_1\overrightarrow{a}=m_1g-T\\m_2\overrightarrow{a}=T-m_2g\end{cases}$

Otteniamo:

$(m_1+m_2)a=(m_1-m_2)g\Longrightarrow a={m_1-m_2\over m1+m2}g$

Osservo che 

Se le due masse sono uguali, $m_1-m_2=0$ non si muovono! l'accelerazione è nulla!

Se una delle due forze è zero otteniamo "g", quindi ottengo $\overrightarrow{a}=\pm g$ cioè uno dei due cade.



### Lavoro

Ad una massa, tipo un treno che va per dei binari:

1. Applico forza parallela **concorde**, posso affermare che sono **avvantaggiato dal moto**;
2. Applico forza parallela **discorde**(che ha il senso opposto). Posso affermare che sono **svantaggiato dal moto**.
3. Forza perpendicolare (applicata ad esempio in "giù") non sono avvantaggiato ne svantaggiato dal moto.

Voglio dunque ottenere una forza che dipende da:

1. Per quanto tempo la applico;
2. Come la applico(1,2,3)

> **Lavoro**: Prodotto scalare forza con spostamento.

$w=\overrightarrow{F} \Delta\overrightarrow{s}=\cos(\Theta_{F_1\Delta s})$

cioè 

$[w]=[FL]=M{L\over T^2}L]=[m {L^2\over T^2}]$

Con **unità di misura** pari a $1N\cdot 1m$

> La formula di prima **VALE SOLO SE UNIFORME SU** $\Delta\overrightarrow{s}$

#### Esempio: Lancio sasso in aria

> Lancio in aria

$w_{grav}=\overrightarrow{F}\cdot \Delta\overrightarrow{s}=$



$\begin{cases}\overrightarrow{F}=-mg\cdot\hat{z}\\\Delta\overrightarrow{s}=h\hat{z}\end{cases}=\overrightarrow{F}\cdot\Delta\overrightarrow{s}=-mgh$



$w_{grav}=-mgh$

cioè la gravità oppone.

> Il sasso torna giù



$w_{grav}=\overrightarrow{F}\cdot \Delta\overrightarrow{s}=$

$\overrightarrow{F}=-mg\hat{z}$

$\Delta\overrightarrow{s}=-h\hat{z}$

ottengo 

$w_{grav}=mgh$ 

cioè la gravità aiuta.

> Caso dove il sasso viene lanciato+ il sasso torna giù

$\overrightarrow{F}=-mg$

$\Delta\overrightarrow{s}=\overrightarrow{0}$ quindi **zero**.



> Caso dove fa dei giri strani

![1551874321218](1551874321218.png)

In questo caso

$\begin{cases}w_a=-mg{h\over3}\\w_c=-mg{2\over3}h\\w_b=0\end{cases}$

$w_b=0$ perchè ho $\Delta \overrightarrow{s}=0$



ottengo che alla fine, sommandoli è $=-mgh$.

Questo ci fa capire che la formula rimane la stessa!



#### Con Forza non costante:

Cosa succede se la **forza non è costante?**

![1551875002361](1551875002361.png)

dunque questo grafico, con curva che chiameremo AB

$\overrightarrow{AB}=\sum^N_{i=1} d\overrightarrow{s}n \longrightarrow_{n\to\infty} \int^B_A \overrightarrow{F}\cdot d\overrightarrow{s}$

Quindi la vera definizione di lavoro è:

> **Lavoro:** $W_{A\to B}=\int^B_A \overrightarrow{F}\cdot d\overrightarrow{s}$

### Potenza

##### Potenza istantanea

Lavoro che compie nel tempo: $dw\over dt$

##### Potenza media

Totale del lavoro nell'intervallo di tempo: $w_{tot}\over\Delta t$

----

---

## 08/03/2019

### Forza conservativa

$W_{a\to a}=0$

Cioè $\oint=\overrightarrow{F}\cdot d\overrightarrow{s}$

> **Teorema**: $\oint^B_A\overrightarrow{F}\cdot d\overrightarrow{s}$ non dipende dal percorso $A\to B$

**Dimostrazione:**

Ho due semimetà $I$ e $II$

$\oint_{II}\overrightarrow{F}\cdot d\overrightarrow{s}=0$

$I\oint^B_A\overrightarrow{F}\cdot d\overrightarrow{s}+II\oint^A_B\overrightarrow{F}\cdot d\overrightarrow{s}=0$

$I\oint^B_A\overrightarrow{F}\cdot d\overrightarrow{s}=-II\oint^A_B\overrightarrow{F}\cdot d\overrightarrow{s}=II\oint^A_B\overrightarrow{F}\cdot d\overrightarrow{s}\Longrightarrow wI_{a\to b}=wII_{a\to b}$

 $\blacksquare .$

### Forza Non conservativa

> Una forza non conservativa è la **forza di attrito.**

**Esempio**:

Ho un oggetto sul quale ho una forza esercitata

per andare da A a B quanto lavoro applica la forza d'attrito?

$W^{(A)}_{A\to B}=\int_A^B \overrightarrow{F}\cdot d\overrightarrow{s}=\overrightarrow{F}_A\cdot \int_A^B  d\overrightarrow{s}=F_a \times \bar{AB}\cos\alpha_{\overrightarrow{F}_A,\overrightarrow{AB}}$

Otteniamo che questa formula è $=-\mu_dmgd=W^{(A)}_{B\to A }$

ci permette di dire che $\Longrightarrow W^{(A)}_{A\to A}=-2\mu_dmgd$ dove $A\to A$ mi significa qualcosa che va da un punto, fa un percorso non nullo e torna dove era.



#### Scelta origine del sistema di riferimento

![1552040339087](1552040339087.png)

Ho un asse cartesiano.

$W_{O\to B}=\int_O^B\overrightarrow{F}d\overrightarrow{s}=f(\overrightarrow{B})$

$W_{A\to B}=W_{A\to O}+W_{O\to B}=-W_{O\to A}+W_{O\to B}$

che è uguale a 

$W_{A\to B}=f(\overrightarrow{B})-f(\overrightarrow{A})$

Ma allora facendo così ottengo che

> Il valore di $f$ è arbitrario, dipende dalla posizione di O, mentre **le differenze di $f$ sono non arbitrarie** cioè non dipendono da $O$, posso avere un'origine qualsiasi.



### Energia Potenziale

$\int_O^B\overrightarrow{F}d\overrightarrow{s}=W_{A\to B}=^{\overleftarrow{def}}-(E_p(\overrightarrow{B})-E_p(\overrightarrow{A}))$

dove $(E_p(\overrightarrow{B})-E_p(\overrightarrow{A}))=\Delta E_p=^{def}-W$

> **Energia Potenziale**: $\Delta E_p=^{def}-W$

tutto questo è possibile solo perchè il $\Delta$ **non** è **arbitrario**.

mentre l'energia potenziale è definita a meno di costante arbitraria.

### Energia Cinetica

$W_{(W>0)}=\int^B_A\overrightarrow{F}\cdot d\overrightarrow{s}=\int^B_A m{d\overrightarrow{v}\over d\overrightarrow{t}}\cdot d\overrightarrow{s}=\int^B_A md\overrightarrow{v}\cdot \overrightarrow{v}=$ caso speciale= $\int^B_Amv\ dv$

Per fare questa cosa ho dovuto fare una bestemmia matematica e passare il $dt$ sotto al $ds$

$=[m{v^2\over2}]^B_A={1\over2}mv^2_B-{1\over2}mv_A^2$

Ottengo dunque che energia cinetica

*  non richiede lavoro;
* non dipende da forze esterne;
* $W=\Delta E_K$ vale sempre;
* se c'è energia cinetica, qualcosa , una forza ci ha lavorato su.

> **Energia Cinetica**: $E_k={1\over2}uv^2$

### Bilancio energetico

Avendo

$A\to B$

$\overrightarrow{F}_{TOT}=\sum_i \overrightarrow{F}_i=\sum_i \overrightarrow{F}_i^{(Con)}+\sum_k\overrightarrow{F}_k^{{(n.c.)}}$

$W_{TOT}=\int^B_A \overrightarrow{F}_{TOT}\cdot d\overrightarrow{s}=W^{(cons)}+W^{(n.cons)}=\Delta E_k$

con $W^{(cons)}=-\Delta E_p$

dove ho che $con$ è forza **conservativa**

mentre n.c. è forza **non conservativa**.

ottengo che $-\Delta E_p+W^{n.cons.}=\Delta E_k$

Ottenendo il **Teorema generale del bilanciamento energetico**

> $\Delta E_p+\Delta E_k=W^{n.cons.}$

Alla fine gli integrali li devo usare solo con forze non conservative.

#### Varie casistiche

1. Caso: Non ho forze non conservative

   $\Delta E_p+\Delta E_k=0$

   $(E_p^f-E_p^i)+(E_k^f-E_k^i)=0$

   $(E_p^f+E_k^f)+(E_k^i+E_p^i)=0​$

   Quindi abbiamo

   $E=E_p+E_k$

   **è energia meccanica!**

   $\Delta E=W^{n. cons.}$

2. Ci sono forze non conservative

   $W^{n. cons}=\Delta E \ne 0$

### Energia Meccanica

> $E=E_p+E_k$

### Esercizi:

#### Lancio massa m in aria, a che altezza arriva?

![1552043047804](1552043047804.png)

$E=\cos t$

$E^=E_p^i+E_k^i= {\sqrt{\pi}\over e} +{1\over2}mv^{i^2}={1\over2}mv_0^2$

$E^t=E_p^t+E_k^t={\sqrt{\pi}\over e}+mgh+0=mgh$

dall'insieme di queste due otteniamo

$\bcancel{\sqrt{\pi}\over e}+gh={v_0^2\over 2}+\bcancel{\sqrt{\pi}\over e}$

$h={v_0^2\over2g}$



$\Delta E=0$

$\Delta E_k=-\Delta E_p$

*cosechenonhofattointempoaricopiare*

> Poichè le energie sono lineari, alla metà del grafico ho esattamente un'uguaglianza tra $E_P=E_k$

![1552043660158](1552043660158.png)

#### Per casa

Problema del pendolo semplice: FIlo di lunghezza $l$, viene lasciato il pendolo.

1. Analisi delle forze
2. $\theta=\theta(t)$
3. scegliere $c_1,c_2$(Sistema di coordinate a piacere)
   1. $c_1=c_1(t),  {d_{c_1}\over d_t(t)}, v_1, a_1​$
   2. $c_2=c_2(t) , {d_{c_2}\over d_t(t)}, v_2, a_2$

