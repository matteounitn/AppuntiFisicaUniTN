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



![1550510794776](./assets/1550510794776.png)



La legge oraria posso esprimerla con una **tabella**:

| $t(s)$ | $s(m)$ |
| :----: | :----: |
|   0    |   2    |
|   1    |   0    |
|   2    |   -1   |
|   3    |   1    |
|   4    |   4    |

E disegno un **GRAFICO**:

![1550510934763](./assets/1550510934763.png)





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

Velocità positiva![1550510163049](./assets/1550510163049.png) 

Velocità negativa![1550511250810](./assets/1550511250810.png)

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



![1550511395367](./assets/1550511395367.png)

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

![1550511703222](./assets/1550511703222.png)

> **Punti estremanti**: Punti di massimo e di minimo, punti nei quali  l'accelerazione vale ZERO, cioè la velocità è costante.





#### Integrale della velocità



> $v(t)=v_0+\int_{t_0}^t d\tau a(\tau)$



*Nota che:*

**Integrando** accelerazione, ottengo la **velocità**.

**Integrando ancora** , ottengo lo **spazio**.

**Derivando** lo spazio, ottengo la **velocità**.

**Derivando ancora** ottengo **l'accelerazione**.

![1550511505456](./assets/1550511505456.png)

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

## 22/02/2019

Ricordiamo che **l'accelerazione** è un **differenziale** della velocità

${dv\over dt}=a$

tornando all'esercizio precedente, otteniamo 

$\begin{cases} v(t)=v_0+gt \\ s(t)=v_0t+{1\over 2}gt^2 \end{cases}$



Ora nel punto in cui la velocità è zero:

$\begin{cases} v(t)=0=v_0+gt_{max} \\ s(t)=h_{max}=v_0t_{max}+{1\over 2}gt_{max}^2 \end{cases}$

![1550830324261](./assets/1550830324261.png)

Continuando:

$\begin{cases}v_0=-gt_{max} \\h_{max}=-{1\over2}gt^2_{max}\end{cases}=\begin{cases} v_0=-g\sqrt{2h_{max}\over-g}=\sqrt{|g|^2{2h_{max}\over-g}}=\sqrt{-2gh_{max}}=8,9m/s\\t_{max}=\sqrt{2h_{max}\over-g}=\sqrt{8m\over9,8m/s^2}=\sqrt{0,816}\end{cases}$

![1550830593170](./assets/1550830593170.png)

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

![1550831035270](./assets/1550831035270.png)

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
   ![Le ASSONOMETRIE – educazionetecnica.dantect.it](./assets/cartesiano.gif)

2. Cilindrico  ![Cylindrical coordinate system - Wikipedia](./assets/download.png)

3. Polare

   ![Triple integral change of variable examples - Math Insight](./assets/polare.png)





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

![1550832890549](./assets/1550832890549.png)

![1550832978953](./assets/1550832978953.png)

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

![Moto circolare uniforme](./assets/acccentripeta.png)

**Nota che**:

Se non ho una circonferenza, posso dire che **l'accelerazione ORTOGONALE** ci porta ad avere un'accelerazione centripeta verso una ipotetica circonferenza per la nostra curva:

![https://proxy.duckduckgo.com/iu/?u=http%3A%2F%2Fwww2.unipr.it%2F~basgio93%2F2004%2FXI%2Findex_files%2Fimage055.jpg&f=1](./assets/accortogonale.jpg)





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

![1551434665292](./assets/1551434665292.png)

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

![1551436719109](./assets/1551436719109.png)



$\overrightarrow{N}+\overrightarrow{P}_{perp}=0$

$P_{parall}=P\sin \alpha$

$P_{perp}=P\cos \alpha$

$\begin{cases}t:ma_t=F_t=mg\sin \alpha \\n: ma_n=F_n=0 \end{cases}$

da questo ottengo $a_t=g\sin\alpha$



Se aggiungo una fune

![1551437365748](./assets/1551437365748.png)

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



![1551865138841](./assets/1551865138841.png)



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

![1551874321218](./assets/1551874321218.png)

In questo caso

$\begin{cases}w_a=-mg{h\over3}\\w_c=-mg{2\over3}h\\w_b=0\end{cases}$

$w_b=0$ perchè ho $\Delta \overrightarrow{s}=0$



ottengo che alla fine, sommandoli è $=-mgh$.

Questo ci fa capire che la formula rimane la stessa!



#### Con Forza non costante:

Cosa succede se la **forza non è costante?**

![1551875002361](./assets/1551875002361.png)

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

![1552040339087](./assets/1552040339087.png)

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

Per fare questa cosa ho dovuto fare un trick brutalmente poco matematico: passare il $dt$ sotto al $ds$

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

![1552043047804](./assets/1552043047804.png)

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

![1552043660158](./assets/1552043660158.png)

#### Per casa

Problema del pendolo semplice: FIlo di lunghezza $l$, viene lasciato il pendolo.

$\theta<<1$

1. Analisi delle forze
2. $\theta=\theta(t)$
3. scegliere $c_1,c_2$(Sistema di coordinate a piacere)
   1. $c_1=c_1(t),  {d_{c_1}\over d_t(t)}, v_1, a_1​$
   2. $c_2=c_2(t) , {d_{c_2}\over d_t(t)}, v_2, a_2$

-----

---

## 11/03/2019

### Moto armonico

**Problema del pendolo: soluzione**

![1552471296488](./assets/1552471296488.png)



$\begin{cases}x=l\sin\theta \\y=-l\cos\theta  \end{cases}$

Dove $l $ è la lunghezza del filo.

Derivando in $d\over dt$ ottengo 

$\begin{cases} {dx(t)\over dt}=l\cos\theta {d\theta\over dt} \\{dy\over dt}=l\sin\theta {d\theta\over dt} \end{cases}$ riderivo in $d\over dt$ $\begin{cases} {d^2x\over dt^2}=l[-\sin\theta( {d\theta\over dt} )^2+\cos\theta {d^2\theta\over dt^2}]\\ {d^2y\over dt^2}=l[\cos\theta( {d\theta\over dt} )^2+\sin\theta {d^2\theta\over dt^2}]\end{cases}$

> nota bene che ${d^2x\over dt^2}\ne( {d\theta\over dt} )^2$

Ora per aiutarmi disegno un triangolo

![1552472698664](./assets/1552472698664.png)

noto che formo due angoli $\theta$ coniugati interni!

Dunque ora, mettendo $\overrightarrow{R}=\overrightarrow{P}_{parallela}$ e $\overrightarrow{P}=\overrightarrow{F}_p$

$\begin{cases} R_x=-R\cos\theta = -P\sin\theta\cos\theta \\R_y=-R\sin\theta=-P\sin^2\theta\end{cases}$

$\overrightarrow{R}=\overrightarrow{F}=m{d^2\overrightarrow{r}\over dt^2} \Rightarrow\begin{cases}R_x=m{d^2x\over dt^2}\\R_y=m{d^2y\over dt^2}\end{cases}$

Proseguendo:

$\begin{cases}\bcancel{m}\cdot(-g)\sin\theta\cos\theta=\bcancel{m}\cdot l[-\sin\theta({d\theta\over dt})^2+\cos{d^2\theta\over dt^2}]\\\bcancel{m}\cdot(-g)\sin^2\theta=\bcancel{m}\cdot l[\cos\theta({d\theta\over dt})^2+\sin{d^2\theta\over dt^2}] \end{cases}$

Ora divido per $l$ e sposto tutto a sinistra

$\begin{cases} \cos\theta{d^2\theta\over dt^2}-\sin\theta({d\theta\over dt})^2+{g\over l}\sin\theta\cos\theta=0 \\\\sin\theta{d^2\theta\over dt^2}+\cos\theta({d\theta\over dt})^2+{g\over l}\sin^2\theta=0\end{cases}$

Ricordando le *serie di taylor mcLaureen*

> $\sin\epsilon\simeq\epsilon \ \ \ \ \epsilon\longrightarrow0$
>
> $\cos\epsilon\simeq1-{\epsilon^2\over2} \ \ \ \ \epsilon\longrightarrow0$
>
> $(1+\epsilon)^\alpha \simeq 1+\alpha\epsilon  \ \ \ \ \epsilon\longrightarrow0$

Continiuamo con

$\begin{cases}\theta''-\theta(\theta')^2+{g\over l}\theta=0\\\theta\theta''+(\theta')^2+{g\over l}\theta^2=0\end{cases}$ ora moltiplico la seconda equazione per $\theta$ e ottengo $\begin{cases}\theta''-\theta(\theta')^2+{g\over l}\theta=0\\\theta^2\theta''+(\theta')^2\theta+{g\over l}\theta^3=0\end{cases}$

Effettuo una somma della prima equazione con la seconda ottenendo:

$(1+\theta^2)\theta''(1+\theta^2){g\over l}\theta=0$

$\theta"+{g\over l}\theta=0$ ma questa è una **differenziale!**

#### Equazione differenziale armonica

> $x'' + cx=0$ con $c>0$

dove a è la **pulsazione al quadrato** del moto armonico. Ottengo la 

> **Pulsazione:** $\omega=\sqrt{c}$

Come soluzioni abbiamo 

$\begin{cases}\theta(t)=A\sin(\sqrt{(c)}t+B)\\\theta''=-A\sin(\sqrt{(c)}t+B)c\end{cases}$



nell'esempio di prima otteniamo

$\begin{cases}\theta(t)=A\sin\sqrt{({g\over l})}t+B)\\\theta''=-A\sin(\sqrt{({g\over l})}t+B){g\over l}\end{cases}$

Ora **trovo A e B:**

$\begin{cases}\theta(o)=\theta_0\ (angolo\ iniziale)\\B={\pi\over2}\end{cases}$ 

quindi la soluzone è $\theta(t)=\theta_0\sin(\sqrt{{g\over l}}+{\pi\over2})=\theta_0\cos(\sqrt{g\over l}t)$.

$\blacksquare$

Da questo esercizio possiamo capire come la pulsazione fosse

$\omega=\sqrt{g\over l}$

La maggior parte delle volte $c$ della equazione precedente sarà uguale a qualcosa tipo $\alpha\over\beta^2$

Abbiamo inoltre ottenuto che il **moto armonico è periodico.**

Avendo che

> **Periodo:** $T|\omega T=2\pi\Longrightarrow T={2\pi\over \omega}$
>
> Tempo tra due riproposizioni nello stesso atto di moto, cioè stesso spazio con la stessa velocità.
>
> più pulsazioni ho più il periodo è **corto.**

Da notare che nell'esercizio del pendolo precedente **non ho considerato l'attrito, quindi ho continue oscillazioni**. Cioè il pendolo non si ferma.

> **Isocronia delle piccole oscillazioni:** Per angoli piccoli, maggiore spostamento **non significa** maggiore periodo.

### Forza Elastica

> **Forza di richiamo(o Elastica):** $\overrightarrow{F}=-k\overrightarrow{x}$

#### Esercizio: Calcolo molla con piccole contrazioni

$m=10kg$

$k=10^3 N/m$

$T=?$

$F=ma$

$-kx=m{d^2x\over dt^2}$

Ottengo

$x''+{k\over m}x=0$

che è l'equazione armonica!

quindi ora ottengo la pulsazione $\omega^2={k\over m} \Rightarrow \omega=\sqrt{k\over m}$

$T={2\pi\over\omega}=\sqrt{m\over k}=0,635$

**Periodo**

$W_{AB}=\int^0_x-ky(-dy)=-{1\over2}kx^2$

*Il meno è presente perchè vado da $x$ a zero.*

Noto che questo integrale è $\int^B_A\overrightarrow{F}\cdot d\overrightarrow{s}=\int^x_0 kxdx={1\over2}kx^2=-Ep$

#### Esercizio: Ciclista

Un ciclista va a 25 km/h

La potenza che produce è $ P=150w$

Attrito $=?$ (Calcola l'attrito che colpisce il ciclista)

$v=25km/h={25\over3,6}m/s=6,9m/s$

$P={dw\over dt}=\overrightarrow{F}{d\overrightarrow{s}\over dt}$ Qui ho dovuto fare un trick poco matematico, **spostando il $dt$** sotto il $d\overrightarrow{s}$

$P_a=\overrightarrow{F}_a\cdot \overrightarrow{v}=-Av$

Sappiamo che $P_c=-P_a$

Abbiamo dunque che 

$P_c=Av$

$A={P_c\over v}=21,6 N\simeq 2Kg$ cioè è come se spingesse circa $2kg$

---

---

## 12/03/2019

#### Esercizio:Massa puntiforme che fa un cerchio


$m=50g=50\cdot10^{-3}kg$

$\theta=?$

$tensionefilo=?$

$l=0,5m$

$f={1\over T}={1\over4}s^{-1}$

$\omega=2\pi f ={2\pi\over2}rad/s$

![1552471296488](./assets/1552471296488.png)

L'asse $z$ entra nella lavagna.

![1552643396358](./assets/1552643396358.png)

$m\omega^2R=F_c$

${R\over l}=\sin\theta$

$\theta=\arcsin({R\over l})$

$\omega^2 l\bcancel{\sin \theta}=g {\bcancel{\sin\theta}\over\cos\theta}$

$\theta=\arccos({g\over \omega^2 l})=\arccos({\bcancel{0,8}\over {\bcancel{\pi}^2\over 4}{1\over2}})$

La velocità angolare è troppo bassa per permettere all'oggetto di muoversi, quindi non ho un $\theta$

$0\le {g\over\omega^2l}\le 1$

$\omega^2\le{g\over l}|\omega\ge 4.5 rad/s$

$\lim_{w\to\infty} \theta(\omega)={\pi\over2}$

Per far arrivare ${g\over\omega^2l}$ a zero, avendo $g$ ed $ l$ che sono costanti, posso solo lavorare con $\omega$. Quindi per far si che sia zero, devo applicare il limite qui sopra con omega che va ad infinito.



#### Esercizio: Giro della morte

*nonleggoidatiallalavagna*

#### Esercizio: Terra

Ho la terra, con un raggio $R$ , una forza gravitazionale e $\theta$ è l'angolo che voglio calcolare per capire qual è il punto di distacco (e opzionalmente il punto di landing.)





### Termodinamica

> **Atomi**: Costituenti minimi della materia che conosciamo, sistemi aggregati composti da un nucleo e sistemi orbitali(elettroni) che gravitano attorno questo nucleo.


Gli atomi sono a **carica neutra**, quindi se gli elettroni hanno carica **negativa**, i protoni la hanno **positiva** e contraria agli elettroni(somma =0).

**Raggio** **nucleo** è dell'ordine alla $10^{-15}m$

**atomo**= $10^{-10}m$

**molecole**= $10^{-8}m$

**Nucleo**= Composto di nucleoni

**Elettroni**: non riusciamo a calcolarne il raggio, troppo piccolo.

>**Costante di avogadro:**  $N_a=6,022 \cdot 10^{23}$

Quanti atomi ho?

>**MOLE**: Quantità di sostanza che contiene esattamente un numero di avogadro di componenti. misuratasi in $mol$.

> $1 mol=$ quantità di sostanza contenuta in $m=A$ grammi dell'elemento, dove $A$ è il **peso atomico**.

**Esempio**:
Avendo un Idrogeno, ho una A=1, cioè una mole di $^1H$ è la quantità di quanta sostanza in 1g di H

mentre

Avendo un Carbonio, ho una A=12, cioè una mole di $^{12}C$ è la quantità di quanta sostanza in 12g di C

Avendo $H_2O$, ho una $A_{effettiva}=18$ cioè $1mol$ di $H_20$ è la quantità di sostanza in 18g di $H_20$

Stati della materia:

* **Solido**: Conservo volume e massa;
* **Liquido**: Ho un volume proprio ma non ho forma, assume quella del recipiente;
* **Gassoso**: Non ho un volume, non ho una forma, si espande prendendo tutto lo spazio disponibile.

#### Energia interna

> In un sistema gassoso, le molecole sono in costante movimento, avendo energia cinetica. Grazie a questa presenza di  l'energia cinetica possiamo dire che il sistema ha una **energia interna** $E_{interna}=U$

#### Gas Ideale

Un gas che ha :

* Le molecole che non interagiscono tra di loro;
* Le particelle non sono interagenti anche con il recipiente;
* Il moto delle particelle è assolutamente casuale.

è definito **gas ideale.**


**Q:Cosa succede quando una particella tocca la parte del contenitore? **

*A: Rimbalza*

Il rimbalzo è calcolabile : $i$= iniziale; $f$=finale.

$\overrightarrow{p}_i=p_x \hat{x}+p_y\hat{y}$

$\overrightarrow{p}_{f}=-p_x\hat{x}+p_y\hat{y}$

$\Delta\overrightarrow{P}=\overrightarrow{P}_f-\overrightarrow{P}_i=-2p_i\hat{x}$


*Ma con il rimbalzo, non perdo energia?* No perchè è **perfettamente elastico** quindi non ho una perdita di energia, mentre in una pallina elastica ho una componente NON elastica che assorbe.


**Q: Quante particelle ho in una zona gassosa che urtano il contenitore?**

*A:*

$N?$ 

$N_u$ numero di urti nel tempo $\Delta t$

$\mathcal{N}_u=N$ 

Attenzione, questo $\mathcal{N}_u$ vuol dire la quantità di urti in un determinato istante di tempo! 

Quindi è uguale al numero di particelle nel volume.

tutto ciò che ho dentro a quel contenitore sta urtando la parete in velocità $v_x$.

Se il gas è perfetto ed ideale, le particelle che urtano sono $N$.

$N=v\cdot n$ dove $n$ è la **densità di volumica**($[n]=[{1\over L^3}]$).

Quindi otteniamo che

${N\over\Delta t}={nSL\over\Delta t}={nSv_x\bcancel{\Delta t}\over\bcancel{\Delta t}}=nSv_x$

$nSv_x\Delta t$ è il numero di urti che ho. 

In $\Delta t$ , ottengo che il numero di urti nella quantità di tempo è $nSv_x$.


*Avendo tutte la stessa velocità $v_x$ abbiamo che tutte andranno ad urtare la parete allo stesso momento, quindi ottengo la formula qui sopra.*

Tutte urtano l'oggetto perchè il nostro è un esperimento deterministico, muovendosi orizzontalmente, tutte che partono dalla stessa linea toccano allo stesso momento.

**Se ho particelle molto veloci, avrò più urti nel tempo.**

**Q:Ognuna di queste particelle, che impulso trasferisce alla parete?**

*A:*

$\Delta\mathcal{P}_x=\mathcal{N}_y\Delta p=n S v_x \Delta t(-2mv_x)$


dove l'ultima parte equivale a $-2nS\Delta t mv_x^2$

Ora noto che ho 

$F_x={\Delta\mathcal{P}_x\over\Delta t}=2nSmv_x^2$

**Osservo che**: Per ognuna delle pareti che considero, devo considerare tutte le particelle che hanno il rispettivo $v_x$ ma che vanno nella direzione giusta(con il segno giusto).

**Osservo che**: Posso considerare la velocità globale della particella, non ho la $v_x$ e $v_y$. Da $v_x$ devo passare a $v$.

**Osservo che**: $v_x$ è il valor medio delle v, cioè ammetto che ho delle variazioni.

Quindi passo da $v^2_x\to v^2$ attraverso il valor medio di $v$ cioè $<v_x^2>$

Ottengo che

$v^2=-nSm<v_x^2>$

$<v^2>=<v_x^2+v_y^2+v_z^2>=<v_x^2>+<v_y^2>+\dots$

Poichè ho scelto io il sistema di riferimento: $mv_x^2={1\over3}<v^2>$


$F_x={\Delta\mathcal{P}_x\over\Delta t}=2nSmv_x^2=-{N\over V}S{1\over3}<mv^2>$

>Ottenendo la formula della **pressione**:
>
$P={F\over S}=+{N\over V}{1\over 3}<mv^2>$


Quindi la pressione P nel nostro volume V è 

$PV=N {2\over 3}<{1\over2}mv^2>$

dove $<{1\over2}mv^2>$ è **energia cinetica media.**

----

---

## 22/03/2019

### Pressione

$[P]=[{F\over S}]$ dove F è **forza** e **S** è superf. misurata in $1Pa$ cioè **Pascal**

Quindi la definizione è

> $P={dF\over dS}$

Sotto ad un determinato valore, le variazioni di superficie sono nulle.

Abbiamo che:

$1 bar=10^5 Pa$

$1 atm= 1,015 bar= 1,015\cdot 10^5 Pa$

In millimetri di mercurio

$1 mmHg | 1 atm=760mmHg$

Facendo un po' di esperimenti ottieniamo che
>$PV=costante\ T$ 
>
>questo vale solo per gas molto rarefatti e poco reagenti(gas **ideali**) con **T misurata in Kelvin**.
>
>Se misurata in C o F non vale.

$costante \ = Rn$ dove $R$ è **indipendente dal gas considerato** e $n$ è **il numero di moli, la quantità di gas.**

Ricordando che $PV=nRT$

$[R]=[{PV\over nTe}]=[{F_{L^2}\cdot L^3 \over QTe}]=[{F\cdot L \over Q T_e}]=[{E\over QT_e}]$

Esempio:

*Ho 13 moli di azoto liquido, a quanti atomi ho?*

Che sia liquido o meno poco ci interessa.

$N=n\cdot N_a$ dove $N_a$ è il numero di avogadro e $n$ è il numero di moli.

otteniamo $nR=N{R\over N_a}=NK_b$

dove $K_b$ è la costante di boltzman.

#### Costante di Boltzman
>$K_b={R\over N_a}={8,314 J/\cancel{mol}K)\over 6,022\cdot 10^{23} K/\cancel{mol}}=1,38\cdot 10^{-23}J/K$

ottenendo che

#### Equazione di stato di gas perfetti
> $PV=nRT \longrightarrow PV=NK_bT$
>

Noto che la prima equazione la ottengo **sperimentalmente** mentre la seconda la ottengo **misurando.**

ora noto che $\begin{cases}PV={2\over3}N<E_k> \\ PV=NK_bT\end{cases} \to K_bT={2\over3}<E_k> $ e
$<E_k>={3\over2}K_bT=3\cdot{1\over2}K_bT$


**Il singolo componente del mio gas ha tre gradi di libertà in questo caso.**

Ora ottengo che

#### Energia interna media in un gas perfetto monoatomico

$U=E_i=^{monoatomico} N<E_k>$ con 

> $u={U\over N}=^{n.a.}<E_k>$

#### Equipartizione dell'energia cinetica
> $u=L {K_bT\over 2}$ dove $L$ è il **numero di gradi di libertà**.

Vediamo dunque che dipende solo da $T$ temperatura e dal numero di gradi di libertà.

#### Esercizio moli

$L=3$

$n=3mol$

$V_i=831,4l$

$P=3 atm$

Trasformazione isobarica

$V_f=2V_i$

$T_i,T_f,U_i,U_f=?$


$PV=nRT$

$T={PV\over nR}\to T_i={P_iV_i\over nR}={3\cdot1,015\cdot10^5Pa\cdot 8,314\cdot10^2\cdot10^{-3}m^3\over 3mol 8,314 {J\over mol\cdot K}}=10150 K$


$P={nRT\over V}\to {\cancel{nR}T_i\over V_i}={\cancel{nR}T_f\over V_f}\to {T_i\over V_i}={T_f\over 2V_i}\to T_f=2T_i=20300K$

Calcolando 

$U={3\over2}nRT$

$U_f=2U_i$ ed $U_i$ me lo calcolo.

#### Esercizio
$PV=cost\ t+A$

![1553252748837](./assets/1553252748837.png)

Noto che la temperatura minimia possibile non dipende dal gas.

Adatto una scala diversa, spostando la $y$ dove ho lo **zero assoluto**

> **Zero assoluto**: Zero kelvin sotto il quale non ha più senso parlare di termodinamica.
>
> $0K=-273,16 $ celsius

![1553253061397](./assets/1553253061397.png)

### Principi della termodinamica
Ho un ambiente che chiamo universo e un sistema con un energia interna $U$. Come avviene lo scambio di energia?

Ricordiamo **che quando si scalda, aumenta l'energia interna**.

Posso avere degli scambi di:

1. $W$ Lavoro:
   1. Ordinato;
   2. Coerente;
   3. Organizzato.
2. $Q$ Calore 
   1. Disordinato;
   2. Incoerente;
   3. Disorganizzato.
##### Esempio dei pistoni
Ho un pistone, con dentro un gas, ha una forza esterna che spinge dentro e fuori il pistone.

*Man mano che spingo, la pressione sarà maggiore, quindi la forza da applicare è maggiore. Questo aspetto lo trascuriamo, la forza applicata è sempre la stessa.*

$W=\overrightarrow{F}_{ext}\cdot\Delta\overrightarrow{x}=F\Delta x>0$

Posso assumere che il lavoro esterno si tramuti tutto in variazione di energia interna:

$W_{ext}=\Delta U$ cioè $U_i\to_{W_{ext}}U_f\Delta U=U_f-U_i=W_{ext}$

Questo funziona perchè non ho altri scambi di energia di questo gas con l'esterno.

#### Calore

Se metto un oggetto al sole si "scalda". Ma non ho lavoro, perchè **non ho spostamento**.

Quindo ho un trasferimento di energia **senza lavoro**. Questo è chiamato **CALORE**.

----

----

## 25/03/2019

#### Esercizio pistone
$\overrightarrow{F}_{tot}=\overrightarrow{0}$

$\overrightarrow{F}_{ext}+\overrightarrow{F}_{int}=0$

${\overrightarrow{F}_{ext}\over A}={\overrightarrow{F}_{int}\over A}\Rightarrow P_{ext}=P_{int}$

![1553768816547](./assets/1553768816547.png)

$\overrightarrow{F}_{ext}\cdot\Delta\overrightarrow{x}=F\Delta x= W_{ext}>0$

$W_{ext}=\Delta U=U_1-U_i>0$

La forza esterna va sempre pensata come la forza che **comprime/tenta di comprimere il gas**. Il volume si espande per un $\Delta x$, lentamente, la forza esterna prova a contrastarlo.

Il lavoro esterno, per questo motivo, sarà dunque **negativo**.

$\overrightarrow{F}_{ext}\cdot \Delta\overrightarrow{x}=-F\Delta x=W_{ext}<0$

$W_{ext}=\Delta U= U_f- U_i<0$

Assumiamo sempre che le due forze siano uguali e opposte

$W_{ext}=-W_{gas}$

Ottengo che

> $\Delta U_{gas}=-W_{gas}$

La variazione dell'energia interna è **uguale al lavoro COMPIUTO  dal sistema!**

cioè più generale 

> $\Delta U=-W$
> 
> Convenzionalmente diciamo che:
>
> * $W>0$  componente del sistema, sistema che fornisce la variazione;
> 
> * $W<0$ Sistema che si **oppone** alla variazione.
> 


Ricordiamo che $U_{int}$ è *qualcosachenonhocapito* della temperatura.

I componenti sono $Na\cdot$ molecole.

Quando definisco devo avere il grado di **disordine**.

#### Esercizio ruota bicicletta
$r_{ext}=25cm$

$r_{int}=23cm$

Tubolare

Ho un uomo con $m=100kg$

1. Calcolare il volume del tubo
2. Calcolare pressione all'interno quando l'uomo sale
3. Assumo che per gonfiare la ruota ho fatto 100 colpi di pompa dove, ad ogni colpo, mette $V^{20*C}=240cm^3$, a che temperatura ho la ruota quando sale?
4. Calcolare il lavoro per gonfiare la gomma.

#### Scatola con gas dentro
Ho una scatola con gas dentro

* Espongo la scatola al sole, ho **radiazione luminosa**.
* **Non** conto una ipotetica riflessione.
* Fornisco energia all'oggetto, il volume non cambia.
* Ho $T_{gas}$ e $T_{ext}$(temperatura recipiente)

Se aspetto abbastanza ho un trasferimento di energià tra $T_{ext}$ e $T_{gas}$ tale che 

>$\Delta T+T_{ext}=T_{gas}$ 
>

Dove $\Delta T$ è la variazione di temperatura provocata dalle radiazioni.

>Ho un trasferimento di energia senza **lavoro meccanico**.
>

#### Calore
**Calore:** $\Delta U = Q$ 

Variazione di energia **senza lavoro meccanico**.

con:
* $Q>0$ se è ricevuto dal sistema
* $Q<0$ se è sottratto dal sistema.


Ricordiamo che noi trattiamo **sistemi in equilibrio**, quindi il contenitore e il gas all'interno raggiungono la stessa temperatura (aspettando abbastanza).

#### Primo principio della termodinamica
>$\Delta U=Q-W$
>
>Variazione di energia interna= Calore - Lavoro

##### Conduzione

![1553776317730](./assets/1553776317730.png)


Atomi che "vibrano",  percepibile da tutti gli atomi vicini. Aumentando la vibrazione avrò un aumento della vibrazione indotta. 

Per conduzione: Sposto energia con calore. 

La sua vibrazione **è l'energia media**, crea un'onda di calore.

La vibrazione viene trasmessa agli atomi vicini in modo "ammortizzato", cioè più debole, che a loro volta trasmetteranno ai loro vicini in modo più debole ancora, fino a quando sarà impercettibile. Questa vibrazione è il calore.

##### Convezione

Ho un fluido, con una zona del fluido più calda, spostandolo ad una zona più fredda il calore si "dissipa". 

Per esempio: in un sistema di raffreddamento a liquido, il liquido passa da freddo a caldo perchè viene fatto passare in zone dove il motore ha bisogno di rilasciare calore. Il calore viene passato al liquido, che viene fatto circolare fino a raggiungere una zona aperta all'ambiente, nel quale disperde il calore che aveva ottenuto tornando freddo.

##### Irraggiamento

A colpire il mio sistema è la **radiazione elettromagnetica**, cioè **energia pura**.

L'energia non viene "riflessa", viene assorbita facendo in modo che l'oggetto vibri e si scaldi.

>**Riflessione:** Un fotone entra, l'atomo si eccita e si diseccita subito, rispedendo lo stesso fotone(dove in realtà è vierso ma potente uguale).
>

*Curiosità: Un corpo nero ha temperatura costante($\simeq 2.7 K$).*

##### Sistema Isolato

Sistema che non scambia **calore**, ne **lavoro** con il sistema esterno. 

Il sistema è definito **chiuso** se ho inoltre una assenza di scambio di materia.

#### Esempio sistema isolato

Ho un sistema isolato con un pendolo dentro.


Se torno dopo anni avendo dato una spinta al pendolo e ho del gas dentro, il pendolo sarà fermo(attrito).
avendo $U_i$ come energia interna iniziale e $U_f$ energia interna finale:

$\begin{cases} Q=0 \\ W=0 \end{cases}  \Delta U=0 \Longrightarrow U_f= U_i$
ma quindi otteniamo che	

$\begin{cases}U_i=U_i^{pendolo}+U_i^{gas}\\U_f= \bcancel{U_f^{pendolo}}+U_f^{gas}\end{cases}$

abbiamo che $ \bcancel{U_f^{pendolo}}$ perchè $U_f^{pendolo}=0$ visto che il pendolo è **fermo** a fine esperimento.

Otteniamo dunque:

> $U_f^{gas}= U_i^{pendolo}+U_i^{gas} \\ U_f^{gas}-U_i^{gas}=\Delta U^{gas}=U_i^{pendolo} \\ \text{Con}\ \Delta T ^{gas}>0 \text{e } T_f^{gas}>T_i ^{gas}$

Ottengo delle osservazioni importanti:

1.  $U$ finale del gas è la $U$ iniziale del pendolo $+$ la $U$ finale del gas.
2.  $U$ del pendolo iniziale è dunque $\Delta U_{gas}$.
3.  *Se vario la temperatura il pendolo non si muove, perchè il gas si scalda in modo disordinato, non solo da un lato.*
4.  Il disordine è presente.

#### Trasformazioni

##### Trasformazione isocora

$\Delta V=0 \Rightarrow W=0$ (volume non varia, non ho un lavoro che ci agisce)

$\Delta U=Q$ 

##### Trasformazione adiabatica

$Q=0$ (calore non varia)

$\Delta U=-W$

##### Trasformazione isotermica

$\Delta T=0 \Rightarrow \Delta U=0 \iff Q=W $ con $Q>0, W>0$ (temperatura non cambia)

#### Capacità termica

Avendo un gas

$\Delta Q= \mathfrak{c} \ \ \ \Delta T \Longrightarrow \mathfrak{c}=^{def}$ Capacità termica $=$ 

$dQ\over dT$ 

>Quindi La capacità termica è  **il variare del calore in relazione alla variazione di temperatura**
>($\mathfrak{c} = {dQ\over dT}$ )
>

Come **unità di misura** ha  $\mathfrak{c} ={1J \over 1K}​$

*Un buon piumino ha una **alta capacità termica**, mentre un fondo di pentola ha una **bassa capacità termica***.

Affermiamo anche che

>Più massa $=$ Maggiore capacità termica. 

#### Calore specifico
Di due tipi:

1. **Calore specifico (per quantità di massa)**$= c = {\mathfrak{c}\over m}= {1\over m}\cdot {dQ\over dT } $
   
   *Unità di misura*$={J\over Kg \cdot K}$
2. **Calore specifico (Molare)**$= c={\mathfrak{c}\over n}={1\over n}\cdot {dQ\over dT} $
   
   *Unità di misura*$={J\over mol\cdot K}$

#### Esperimento di Joule

![Risultati immagini per esperimento di joule](./assets/01-termodinamica-mulinello-joule.png)

$W=mgh$

$W_{h_2O}=0$

$\Delta U=Q$ (1 principio termodinamica)

$p=1 atm \ \ \ 14,5 ^{\circ}\mathrm{c}\to 15,5 ^{\circ}\mathrm{c}$ 

Devo applicare un lavoro $W_G=4,186 KJ$

Otteniamo dunque il valore di una **kilocaloria (Kcal)**che

> $1 cal= 4,186J$
> 


$C_{H_2O}$ liquido$= {1Kcal\over 1Kg\cdot 1K}=4,186 {KJ\over KgK}$

Ricordiamo che

$\Delta T=1K=\Delta T= 1^{\circ}\mathrm{c}$
##### Esempio pozzanghera

Ho una pozzangera quadrata con uno strato di nylon sopra(ininfluente, serve solo per evitare l'evaporazione)

sappiamo che 

$W_{sole}=700W/m^2$

La pozzanghera è lunga e larga $50cm$ e profonda $1cm$

$T_i=20^{\circ}\mathrm{c}$

$\Delta U=Q-\bcancel{W}$ (Non ho variazioni di volume, trasformazione isocora)

$\Delta t=8 hr$

$T_f=?$ 

Quale sarà la temperatura finale della pozzanghera se il sole apparisse istantaneamente(e non lentamente) per 8 ore?

$W_{sole}\Delta t=Q= mc\cdot\Delta T$ cioè  il calore immesso dal sole per irraggiamento nel tempo.


$SW_{sole}\Delta t=mc \Delta T$

*è importante ricordare che devo considerare la superficie, anche se vedremo che sarà ininfluente.*


$\Delta T={SW_{sole}\Delta t S\over mc}={W_{sole}\Delta t S\over \rho V c}={W_{sole}\Delta t \bcancel{L^2}\over \rho \bcancel{L^2} h c}$

Ora abbiamo dunque

${7\cdot10^2\cdot2,9\cdot10^4\over10^3\cdot 10^{-2}\cdot4,19\cdot10^3}K=5\cdot10^2=500K$

è dunque aumentata di 500 gradi kelvin .

Questo avviene perchè non ho considerato il **calore latente**.


#### Calore latente
$Q=\lambda m$

>$\lambda$= Calore latente.

Si misura in $J/Kg$.

$\Delta T_{Cambio\ di\ stato}=0$

*è un calore che si verifica quando abbiamo una coesistenza tra vapore e liquido, una coesistenza di due stati.*

#### Stati della materia

SOLIDO $\xrightarrow[\xleftarrow{\text{Solidificazione}}]{\text{Fusione}}$ LIQUIDO $\xrightarrow[\xleftarrow{\text{Condensazione}}]{\text{Evaporazione}}$ VAPORE



$\lambda _{SL}=3,3\cdot 10^5 J/Kg$ dove $SL$ sta per *Solido Liquido*.

$\lambda _{LV}=2,7\cdot 10^7 J/Kg$ dove $LV$ sta per*Liquido Vapore*.

#### Per casa
1. Ripetere esercizio precedente(della pozzanghera ) rimuovendo lo strato di nylon.
2. Ho $2kg$ di ghiaccio a $-10^{\circ}\mathrm{c}$ 
   3. Disegnare il grafico Temperatura/Calore (Temperatura asse $y$, Calore asse $x$)

   4. Disegnare il grafico Temperatura/ tempo (Temperatura asse $y$, tempo asse $x$)

     Aggiungendo che ${dQ\over dT}=100 cal/hr$.

----

----

## 29/03/2019

Ho un sistema e due corpi:

$m_1,c_1,T_1$

$m_2,c_2,T_2$

(c è la capacità termica)

Quando i due corpi sono a contatto ho uno **scambio di calore**.

$Q_1+Q_2=0$ perchè il calore che scambia con l'esterno è zero! $Q_{tot}=0$

Per la definizione di calore specifico, $Q_1=m_1c_1(T_f-T_1) \\Q_2=m_2c_2(T_f-T_2)$

Sommandoli, ottengo 

$Q_1+Q_2=m_1c_1(T_f-T_1)+m_2c_2(T_f-T_2) \\ \ \ \  \ \ \ 0\ \ \ \ \  \ \ =(m_1c_1+m_2c_2)T_f-(m_1c_1T_1+m_2c_2T_2)$

$T_f={m_1c_1T_1+m_2c_2T_2\over m_1c_1+m_2c_2}$

In generale

$T_f={\mathfrak{c}_1T_1+\mathfrak{c}_2T_2\over\mathfrak{c}_1+\mathfrak{c}_2}$

*Vuoto: Non ho molecole.*


#### Esercizio
$m_1=30g​$

$t_1=-15^{\circ}\mathrm{c}​$

$m_2=50g​$

$t_2=60 ^{\circ}\mathrm{c}​$

$T_e=?​$

traduciamo i dati in una forma utilizzabile

$t_{1_k}=T_1=258K​$

$t_{2_k}=T_2=333K​$

$\lambda_{H_2O}=3,3\cdot10^5 J/Kg​$

$c_{H_2O}={1kcal\over Kg\cdot K}=4,19 KJ/Kg\cdot K$

$Q_1=m_1c_1\cdot(T_f-T_1) \\ Q_2=m_2c_2\cdot(T_f-T_2)​$

sommandoli

$Q_1+Q_2=(m_1\cdot c_1+m_2\cdot c_2)\cdot T_f-(m_1\cdot c_1\cdot T_1 + m_2\cdot c_2\cdot T_2)​$

$T_f={m_1c_1T_1+m_2c_2T_2\over m_1c_1+m_2c_2}​$



$Q_{fus}=\lambda_{H_2O}\cdot m_1=10^4 J$

$Q_{ghiaccio}=m_1\cdot c_1\cdot (T_{fus}-T_1)=900J$

$Q_{Acqua}^{(max)}=m_2\cdot c_2(T_{fus}-T_2)=-1,26\cdot 10^4 J$

Il resto è un tentativo di uno studente.

Trovo il calore dell'acqua dopo che il ghiaccio si è sciolto

$Q^{res}_{H_2O}=1,7\cdot10^3 J$

$Q^{res}_{H_2O}=m_2\cdot c_2(T_*-T_{fus}=1,7\cdot10^3 J=30g\cdot 4,19 KJ/Kg\cdot K\cdot (t_*-0^{\circ}\mathrm{c})$

${1,7\cdot10^3 J Kg^{\circ}\mathrm{c}\over 50g\cdot 4,19 KJ}=t_*=0,85\cdot 10^{\circ}\mathrm{c}=8,5^{\circ}\mathrm{c}$

$Teq={m_1\cdot c_1 T_1+m_2 c_2 T_2\over m_1c_1+m_2c_2}={30g\cdot273K+50g+281,5 K\over 80 g}=278,3K=5^{\circ}\mathrm{c}$

## 01/04/2019

$\overrightarrow{F}_{ext}=\overrightarrow{0}\Rightarrow {d\overrightarrow{P}t\over dt}=\overrightarrow{0}\Rightarrow \overrightarrow{P}_{tot}=\overrightarrow{const}\Rightarrow \overrightarrow{P}_{tot}$

ottenendo

$\overrightarrow{P}_{tot}^{iniziale}=\overrightarrow{P}_{tot}^{finale}$
Quindi otteniamo che
> Se niente perturba il moto del sistema, **la quantità di moto totale si conserva**.\
> 

In altre parole
$\sum ^N_{i=1}\overrightarrow{P}_i(iniziale)=\sum ^M_{j=1}\overrightarrow{P}_i(finale)$

Noto che $N$ e $M$ non sono necessariamente uguali(non necessariamente stesso numero), vale anche per $i$ e $j$(non necessariamente stesso corpo).

### Centro di massa
>$\overrightarrow{x}_{CM}={m_1}\overrightarrow{x}_1+m_2 \overrightarrow{x}_2\over m_1+m_2$
>Punto che **meglio approssima** *l'equilibrio del sistema.*
>

In una dimensione, tolgo semplicemente i vettori.

#### Esempio Sole Terra

![1554667622045](assets/1554667622045.png)


Ho il Sole, che indicheremo con $_s$ e terra che indicheremo con $_T$

$m_s=2\cdot 10^{30}Kg$

$m_T=6\cdot 10^{24}Kg$

$d=1,5\cdot 10^{11}m​$ cioè la distanza tra la terra e il sole.

Calcolo $r$:

$r_{CM}={M_s x_s+m_T x_T\over m_s+m_T}={m_T\over m_s c_1+{m_T\over m_s}}$

Dove ${m_T\over m_s}=\epsilon \simeq 10^{-6}$

$x_T={m_T\over m_s}(1-{m_T\over m_s})$

ottenendo 

$r_{CM}=3\cdot10^{-6}\cdot1,5\cdot10^{11}m=4,5\cdot10^5m=450km$

#### Esempio raggio sole
Avendo il raggio della terra 

$R_T\simeq 6,4\cdot10^3m$

quanto sarà il raggio del sole?

$R_s=?$

Lo ottengo.

Il sole è circa $0,5^\circ$ di inclinazione rispetto alla terra, cioè $8,5 millirad$, ($1 ^\circ=17millirad$)


$d\tan{\phi\over 2}=R$

$d\cdot 4,2\cdot 10^{-3}=R$

$1,5\cdot 10^{11}\cdot 4,2\cdot 10^{-3}=R$

$6,3\cdot 10^8 m= R$

$R=630000km$ Raggio del sole.

#### Utili da sapere per esame

Se $\epsilon <<$ (molto piccolo) allora vale

* ${1+\epsilon}^{\alpha}=1+\alpha\epsilon$
* $\tan\epsilon=\sin\epsilon=\epsilon$
* $\cos\epsilon=1-{\epsilon^2\over2}$
* $\ln(1+\epsilon)=\epsilon$
* $e^\epsilon=1+\epsilon$

Praticamente limiti che tendono a zero.

#### Esempio su Aereo

Ho un aereo privato

![1554842775676](assets/1554842775676.png)

Definiamo $v_2-v_1$ come la differenza tra le due frecce.

Posso affermare che la lunghezza nella prossima immagine sarebbe equivalente se non fosse per $v_1$ che si oppone al nostro "aereo".

![1554843129553](assets/1554843129553.png)

Ora avendo $i$ che varia tra $1$ e $2$

ottengo 

$\overrightarrow{v_i}'={d\overrightarrow{x}_i\over dt}={d\over dt}(\overrightarrow{x}_i-\overrightarrow{x}_{CM})={d\overrightarrow{x}_i\over dt}-{d\overrightarrow{x}_{CM}\over dt}$
dove ${d\overrightarrow{x}_i\over dt}=\overrightarrow{v}_i$ e ${d\overrightarrow{x}_{CM}\over dt}=\overrightarrow{v}_{CM}$

Ma noto che tutto ciò è **energia cinetica**

$E_k=\sum^n_{i=1}{1\over2}m_i \overrightarrow{v}_i^2$

$E_k=\sum^n_{i=1}{1\over2}m_i \overrightarrow{v}_i^2=\sum^n_{i=1}{1\over2}m_i(\overrightarrow{v}_i-\overrightarrow{v}_{CM})^2=\sum^n_{i=1}{1\over2}m_i(\overrightarrow{v}_i^2+\overrightarrow{v}_{CM}^2-2\cdot\overrightarrow{v}_i\overrightarrow{v}_{CM})=$

$=\sum^n_{i=1}{1\over2}m_i v_i+ \sum^n_{i=1}{1\over2}m_iv_{CM}^2-(\sum^n_{i=1} m_i\overrightarrow{v}_i)\overrightarrow{v}_{CM}$

Ottenendo

$\begin{cases}E_k=\sum^n_{i=1} {1\over2} m_i \overrightarrow{v}_i^2 \\ E_k'=E_k {1\over2}Mv^2_{CM}-\overrightarrow{v}_{CM}\cdot\sum m_i\cdot \overrightarrow{v}_i\end{cases}$

>Cioè che possiamo** cambiare il sistema di riferimento senza variare il risultato**(anche se l'energia cinetica varia!)

#### La quantità di moto si conserva
$\overrightarrow{x}_{CM}=\overrightarrow{0}$

$m_1 \overrightarrow{v}_1+m_2\overrightarrow{v}_2=\overrightarrow{0}$

Ora derivo in base al tempo

$m_1\overrightarrow{v}_1+m_2\overrightarrow{v}_2=\overrightarrow{0}$
cioè $\overrightarrow{P}_1+\overrightarrow{P}_2=\overrightarrow{0}​$

Ottengo

>$\Delta \overrightarrow{P}_{tot}=\overrightarrow{0}$, cioè la **quantità di moto** si conserva nell'urto!
>

#### Esperimento barra
ho una barra, con due masse sopra all'estremità.
La barra è su un materiale che non ha attrito.

![1554885663490](assets/1554885663490.png)
Immaginiamo che la barra "scorra" verso una direzione, facendo impattare le due masse.

$x_{CM}={m_1x_1+m_2x_2\over m_1+m_2}={m_2\over m_1+m_2}={d\over 2}$

$(m_1+m_2) {d\cdot x_{CM}\over dt}=m_1\cdot{dx_1\over dt}+{m_2x_2\over dt}=$

$=m_1v_1+m_2v_2=P_1+P_2=P_{tot}=0$
ottengo che
> Se due masse impattano, **non avendo forze esterne**, il centro di massa **rimane nello stesso punto**. 
> In questo caso, il centro di massa rimane a metà della barra.

$x_{1}^{Finale}-x_{2}^{Finale}={d\over2}$


$x_{CM}^{Finale}={m_1x_1^{Finale}+m_2x_{2}^{Finale}\over m_1+m_2}={m_1x_{1}^{Finale}+m_2(x_{1}^{Finale}-{d\over2})\over m_1+m_2}=x_{CM}^{Iniziale}={m_2\over m_1+m_2}\cdot {d\over2}$

Concludendo

$(m_1+m_2)x_1^{Finale}=m_2\cdot d$

$x_1^{Finale}={m_2\over m_1+m_2}\cdot d$
#### Urto perfettamente anaelastico
> Definisco **urto perfettamente anaelastico** quando due masse, in un urto si "attaccano".
> 

**Esercizio**
Avendo un pendolo balistico

$\Delta \overrightarrow{P}_{tot}=0$ 

$\overrightarrow{P}_{iniziale}=\overrightarrow{P}_{finale}$

$m_1\overrightarrow{v}_1^{iniziale}+m_2\overrightarrow{v}_2^{iniziale}=(m_1+m_2)\cdot \overrightarrow{v}^{finale}$

$\overrightarrow{v}^{finale}={m_i \overrightarrow{v}_i^{iniziale}m_2\overrightarrow{v}_2\over m_1+m_2}\xrightarrow[{m_b}]{{v_b}}$

Più in specifico 

Ho un proiettile sparato verso un sacco di sabbia. Si comporterà come un pendolo.

![1554890396954](assets/1554890396954.png)

Il movimento sarà

![1554889980205](assets/1554889980205.png)


$M=m_s+m_b$ 

$m_bV_b+m_s\bcancel{V_s}=MV$

Il sacco essenzo fermo all'inizio abbiamo $V_s=0$

ottengo

$h=l-l\cos\phi$ dove $l$ è la lunghezza del cavo.

$Mgh={1\over2}\bcancel{M}V^2\iff V=\sqrt{2gh}$

$V=\sqrt{2gh}=\sqrt{2gl2\sin^2{\phi\over2}}=2\sin{\phi\over2}\sqrt{gl}$

Utilizzando la formula di bisezione $\sin{\phi\over2}=\pm \sqrt{1-\cos\phi\over2}$

Ottengo dunque 

$V_b={m_b+m_s\over m_b}2\sin{\phi\over2}\sqrt{gl}={m_b+m_s\over m_b}{\phi}\sqrt{gl}={m_s\over m_b} \phi\sqrt{gl}$

#### Esperienza di Joule (Espansione Libera)
Ho un contenitore:
* Pareti rigide e adiabatiche(non ho scambio di calore con l'esterno);
* Quantità di gas(moli) all'interno di un gas ideale all'interno di un comparto;
* Ho setto apribile e chiudibile tipo rubinetto.

![1554907417280](assets/1554907417280.png)

>Otteniamo che il gas si espande (espansione libera) e **non fa ne subisce lavoro!**
>Non ho scambio di calore con l'esterno!

L'energia interna del sistema non cambia per il primo principio della termodinamica.

$\begin{cases}dW=0\\dQ=0\end{cases}{ dV=0,dT=0}=U=U(t)$

Dove $dt=0$ è stato ottenuto **sperimentalmente**.

A Volume costante(isocora):

$dV=0\ \  dW=pdV=0$

$dQ=nc_vdT$ con $c_v$ calore specifico;

$dQ=dV$

ottengo
> $dU=nc_vdT\Leftarrow$ Vale sempre. 
> $\Delta U=nc_v\Delta T$

**La temperatura del gas non cambia!**
Quindi:
> $U$ dipende **solo** da $T$.


## 05/04/2019

Sospensione lezioni per prove intermedie

## 08/04/2019
#### Calore Specifico in base al processo
Abbiamo un grafico che descrive andamento di 3 gas.

![1554992324463](assets/1554992324463.png)

$\begin{cases}\Delta U=0 \\ \Delta T=0\end{cases}\Rightarrow U=U(T)$

$pV=mRT$ perchè ho un gas ideale.

Il punto A è composto da $p_A,V_A,T_A$

Il punto B è composto da $p_B,V_B,T_B$

Il punto C è composto da $p_C,V_C,T_C$

${p_A V_A\over nR}=T_A$

$p_AV_A=nRT_A$ dove $R \text{ e } T_A$ sono costanti.

$\Delta U= U_C-U_A=?$

Riprendo il calore specifico molare: $c={1\over n}{dQ\over dT}​$, 
>ho un calore specifico che dipende dal processo considerato: $c_{proc}={1\over n}[{dq\over dT}]_{proc}$

Ciò significa che una espansione **isoterma** crea un differente $c_{proc}$ di una espansione **isocora.**

$\Delta U=U_B-U_A=(U_B-U_C)+(U_C-U_A)=\Delta U_{BC}-\Delta U_{CA}$

$A\to C: dU=dQ-\xcancel{dW}$($\xcancel{dW}$ perchè isocora).

Quindi: $dV=dQ=nc_VdT$

Uso $V$ perchè ho il **volume costante**.

Ottengo

$dQ_{p_R}=nc_{p_R}dT$.

Riprendendo:

$nc_VdT\xrightarrow[{c_V=\text{costante}}]{}\Delta U_{CA}=nc_V\Delta T=nc_V(T_C-T_A)$

$C\to B:_{Isoterma} dU=\xcancel{dQ}-dW$ ma posso affermare che

$\to \Delta U_{CB}=U(T_B)-U(T_C)=0$ con $T_B$ temperatura **finale** e $T_C$ temperatura **inziale**.



> $\Delta U= \Delta U_{BC}+\Delta U_{CA}=$ $nc_V\Delta T\\nc_V(T_C-T_A)$

dunque ottengo che con i gas ideali possiamo usare ciò.

> $\Delta U$ è proporzionale a $c_V$ e **non** dipende dalle trasformazioni, **vale sempre**.

### Relazione di Mayer

ho una isobara ($p $ costante)

$dV=dQ-dW\\nc_VdT=nc_VdT-pdV$

$pV=nRT$

$d[pV]=d[nRT]$

otteniamo 
>**Differenziazione equazione di stato di gas perfetti**:$Vdp+pdV=nRdT$

Tornando a $pV=nRT$

$nRdT-\xcancel{Vdp}$($\xcancel{Vdp}$ perchè la pressione è costante!)

$=n(c_P-c_V)dT$ cioè

> **Relazione di mayer:**$c_P-c_V=R$

Continuando abbiamo che 
>$R>0\iff c_P-c_V>0 \iff c_P>c_V$ 

Per i diversi tipi di gas abbiamo:
1. **Gas Monoatomici**
$c_V={3\over2}R\Rightarrow c_P={5\over2}R$
2. **Gas Biatomici**
$c_V={5\over2}R\Rightarrow c_P={7\over2}R$
3. **Gas Poliatomici**
$c_{p}/R=a+bT+cT^2$

### Grafici p V 
Ricordiamo che una *adiabatica non ha scambio di calore con l'esterno.* $Q=0\\\Delta Q=0$

Per il primo principio della termodinamica abbiamo che:

$dV=\xcancel{dQ}-dW$

$nc_vdT=-pdV$

Ricapitolando:
* **Isocora** $V=\text{Costante}$
* **Isobara** $p=\text{Costante}$
* **Isoterma** $T=\text{Costante}$

ed una adiabatica come si comporta ?

$n(c_P-R)dT=-pdV$

$nc_PdT=nRdT-pdV$

$nRdT=pdV+Vdp$

$-Vdp=pdV-nRdT$

$nc_PdT=Vdp$

Ora unisco $nc_PdT=Vdp$ con $nc_vdT=-pdV$ ottenendo(il primo sopra il secondo sotto frazione)
${{nc_PdT\over nc_vdT}=-{Vdp\over pdV}}$

ho dunque ottenuto 

$\gamma={c_P\over c_V}={dp/p\over dV/V}>1$ cioè $-{1\over\gamma}{dp\over p}={dV\over V} \Rightarrow \int-{1\over\gamma}d[\ln p]=\int d[\ln V]$

ottengo

$-{1\over\gamma}\ln[{p_{finale}\over p_{iniziale}}]-\ln[{V_{finale}\over V_{iniziale}}]$

> $pV_{iniziale}\gamma=p_{finale}V_{finale}\gamma\to pV^{\gamma-1 }=\text{costante}$
> $Tp^{1-\gamma\over\gamma}=\text{costante}$

![1554998647285](assets/1554998647285.png)


abbiamo dunque che
* **Isocora** $V=\text{Costante}$
* **Isobara** $p=\text{Costante}$
* **Isoterma** $T=\text{Costante}$
* **Adiabatica** $pV^{\gamma }=\text{Costante}$

In tabella otteniamo

|    Tipo     |     $dU$      |     $dQ$      |     $dW$      |
| :---------: | :-----------: | :-----------: | :-----------: |
|   Isocore   |   $nc_VdT$    |   $nc_VdT$    | $\varnothing$ |
|   Isobare   |   $nc_VdT$    |   $nc_pdT$    |    $-nRdT$    |
|  Isoterme   | $\varnothing$ |     $pdV$     |     $pdV$     |
| Adiabatiche |   $nc_VdT$    | $\varnothing$ |   $-nc_VdT$   |

### Cicli Termodinamici
> Un **Ciclo Termodinamico** avviene quando lo stato **iniziale** **coincide** con lo stato **finale**.

Possiamo anche dire che($i$ per iniziale e $f$ per finale)

$U_i=U_f\Rightarrow \Delta U=0$

$p_i=p_f$

$V_i=V_f$

$T_i=T_f$

![https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQfLoqby8SJ0k7ZvveZf5wfzfKl9VplSAXxNmVSPqhiTveFxc0B](assets/images.png)

In questo esempio abbiamo l'area sottostante di colore azzurro, mentre l'area sovrastante in colore giallo.
Noi consideriamo $W_{superiore}$ come l'area sottesa della zona superiore, quindi area azzurra+area gialla.

Consideriamo $W_{inferiore}$ come l'area sottesa alla parte inferiore, quindi l'area azzurrina.
$W_{superiore}+W_{inferiore}=W$

>Per determinare il **segno di w**, ho bisogno dei segni di $W_{superiore}$ e di $W_{inferiore}$. Per vedere se è **compiuto o subito** ho bisogno del **verso di percorrenza**.

Affermiamo che 
$|W_{superiore}|>|W_{Inferiore}|$ 
$\begin{cases}W_{superiore}>0\\W_{inferiore}<0 \end{cases}$ allora $W>0​$, senso **orario**.

![1555013282548](assets/1555013282548.png)

$\begin{cases}W_{superiore}<0\\W_{inferiore}>0 \end{cases}$ allora $W<0$, senso **antiorario**.

![1555013321911](assets/1555013321911.png)

Un ciclo non compie lavoro quando ha una linea unica senza area all'interno.

![1555014027517](assets/1555014027517.png)

$\Delta U= Q-W$

$Q=W$

Tutto il lavoro che fa la da come **calore**.


#### Cliclo termico/Macchina termica
$W>0\Rightarrow Q>0$
#### Ciclo frigorifero/Macchina frigorifera
$W<0\Rightarrow Q<0$
#### Calore ceduto e calore assorbito
$Q_A=$ Somma di tutti i calori assorbiti, quindi $Q_A>0$.
$Q_C=$ Somma di tutti i calori ceduti, quindi $Q_C<0$.
#### Lavoro subito e lavoro  effettuato
$W_F=$ Somma di tutti i lavori effettuati, quindi $W_F>0$.
$W_S=$ Somma di tutti i lavori subiti, quindi $W_S<0$.

Ciò mi porta a 
> $Q=Q_A+Q_C$
> $Q=W$
> $Q_A+Q_C=W_F+W_S$
> $W=W_F+W_S$

#### Rendimento di una macchina termica
> **Il lavoro/Calore assorbito** $={W\over c_A}=\eta={Q_A+Q_C\over Q_A}=1+{Q_C\over Q_A}=1-{|Q_C|\over Q_A}$ e ciò **vale per tutte le macchine termiche.**

#### Reversibilità di una trasformazione

>Una trasformazione è reversibile se, qualsiasi sia il dettaglio, vedo una serie di **stati di equilibrio**.
Uno stato di equilibrio di esempio, per un gas ideale: $pVnRT$ per ogni punto.

#### Ciclo di Carnot

![1555015836193](assets/1555015836193.png)
$AB=T_2>T_1$
$W>0​$ perchè **orario**.

Avendo il seguente ciclo possiamo affermare che:
* $AB$ è una **espansione reversibile isoterma**;
* $BC$ è una **espansione reversibile adiabatica**;
* $CD$ è una **compressione reversibile isoterma**;
* $DA$ è una **compressione reversibile adiabatica**. 

>Sperimentalmente notiamo che $0\le \eta <1$

## 12/04/2019
Ho due sorgenti a temperature $T_2$ e $T_1$

Potrei connetterle con delle isocore, ma non lo faccio perchè avrei **scambio di calore**. Voglio che ci sia scambio di calore **nullo**, quindi utilizzo delle **adiabatiche** per collegare le due sorgenti.

Immagino di avere un pistone, rappresentato come punto $A$ che deve arrivare ad uno stato $B$

![1555059157081](assets/1555059157081.png)

Ho che

$A \xrightarrow{\Delta U=0 ,Q=W}{}B \xrightarrow{\Delta U=-W ,Q=0}C \xrightarrow{\Delta U=0 ,Q=W}D$

Nel passo $A$ abbiamo calore $Q_I$ ceduto dalla sorgente $T_2$ 

Nel passo $B$ abbiamo lavoro $W_1$ compiuto.

Nel passo $C$ abbiamo calore $Q_1$ ceduto alla sorgente $T_1$ 

Nel passo $D$ abbiamo lavoro $W_{II}$ subito.

Abbiamo che

$Q_2=nRT_2\ln({V_B\over V_A})$(questo è così perchè $Q_2=W_2=\int^B_A pdV$)

$T_2V_B^{\gamma-1}=T_1V_C^{\gamma-1}$

$W_{I}=-\Delta U_{BC}=nc_V(T_2-T_1)$

$T_2V_B^{\gamma-1}$ è associabile a $B$ mentre $T_1V_C^{\gamma-1}$ è associabile a $C$


$Q_1=nRT_1\ln({V_D\over V_C})$

$T_1 V_D^{\gamma-1}=T_2 V_A^{\gamma-1}$

$W_{II}=-\Delta U_{DA}=nc_V(T_1-T_2)$

$T_1 V_D^{\gamma-1} $ è associabile a $D$ mentre $T_2 V_A^{\gamma-1}$ è associabile a $A​$

Mi calcolo il rendimento
$\eta=1-{|Q_C|\over Q_A}=1-{Q_1\over Q_2}=1-{nRT_1\ln({V_D\over V_C})\over nRT_2\ln({V_B\over V_A})}$
con un po' di calcoli noto che i due logaritmi sono uguali.
Quindi

>$=1-{nRT_1\ln({V_D\over V_C})\over nRT_2\ln({V_B\over V_A})}=1-{\bcancel{nR}T_1\bcancel{\ln({V_D\over V_C})}\over \bcancel{nR}T_2\bcancel{\ln({V_B\over V_A})}}=1-{T_1\over T_2}$
>
>dove abbiamo che **l'inefficienza** $={T_1\over T_2}$

Di conseguenza abbiamo un'altra importante equazione

>${Q_1\over Q_2}={T_1\over T_2}\Rightarrow {Q_1\over T_1}={Q_2\over T_2}\Rightarrow  {-Q_1\over T_1}+{Q_2\over T_2}=0$

#### Rappresentazione macchina termica

Con La macchina Termica reversibile.

Il segno $W=Q_2-Q_1$ quindi lavoro ceduto, negativo.

![Risultati immagini per macchina termica](assets/images.jpg)

#### Rappresentazione macchina frigorifera

Con La macchina Frigorifera reversibile.

Il segno $W=Q_1-Q_2$ quindi lavoro ottenuto, positivo.

![img](assets/image002.gif)


>Coefficente di prestazione di macchina frigorifera(**COP**): $\xi={Q_A\over |W|}$
#### Secondo principio della termodinamica 

> **Formulazione di Clausius**:Non posso avere un processo il cui unico risultato sia trasferire calore da temperatura T ad una temperatura più calda di T. 
>

> **Formulazione di Kelvin-Plank** è impossibile realizzare un processo il cui unico risultato sia trasformare il calore in lavoro.

Le due formulazioni sono equivalenti.
Questo principio è legato allo stesso concetto del tempo.
#### Dimostrazione per assurdo
Ho macchina $\eta$ $X$ generico e $R$ reversibile.

$W=Q_2'-Q_1'$

$W=Q_2-Q_1$

$-W=-Q_2+Q_1$
Ottengo una nuova macchina

$q_1=Q_2'-Q_1'=Q_2-Q_1$

$q_2=Q_2'-Q_2=+(Q_1'-Q_1)$

Il calore che assorbo da una, è il calore che cedo dall'altra
Suppongo che questa macchina

$\eta_x>\eta_R$

${\bcancel{W}\over Q_2'}>{\bcancel{W}\Q_2}$

$Q'2<Q_2$

$q_2=Q_2'-Q_2<0$
Ma allora sto trasferimendo calore da una sorgente più fredda ad una più calda!
Viola il secondo principio nella formulazione di Clausius! **per assurdo** $\eta_x>\eta_R$ è falsa.

Quindi in teoria l'opposto è 
#### Teorema di Carnot
>$\eta_X\le\eta_R$
dove
Il minore vale se la macchina $X$ è **irreversibile,**  ($\eta=1-{Q_1\over Q_2}$) 
L'uguale vale se la macchina $X$ è **reversibile.** ($\eta=1-{T_1\over T_2}$)
(**importante tenere le temperature in KELVIN**)


>**Corollario 1** Tutte le macchine reversibili hanno lo stesso rendimento $1-{T_1\over T_2}$ se lavorano tra  le stesse temperature.

>**Corollario 2** Tutte le macchine irreversibili hanno un rendimento inferiore a  $1-{T_1\over T_2}$ .

>è Importante ricordare che un rendimento può essere solo $0\le\eta<1$.

## 15/04/2019

Ricordando il teorema di carnot dalla volta precedente abbiamo che

$1-{Q_1\over Q_2}\le 1- {T_1\over T_2}$ e ricordiamo che $Q1,Q2 >0$

Effettuando delle operazioni algebriche ottienamo:

$\bcancel{1}-{Q_1\over Q_2}\le \bcancel{1}- {T_1\over T_2}$

${Q_1\over Q_2}\ge {T_1\over T_2}$

$-{Q_1\over T_1}+{Q_2\over T_2}\le 0 \to {(-Q_1)\over T_1}+{Q_2\over T_2}\le 0$

Ora sostituisco $Q$ con $\mathcal{Q}$

$\mathcal{Q}_1=(-Q_1)\\\mathcal{Q}_2=Q_2$

${\mathcal{Q}_1\over T_1}+{\mathcal{Q}_2\over T_2}$

Cioè ho spostato i segni sui calori stessi.

Ottenendo

${\mathcal{Q}_1\over T_1}+{\mathcal{Q}_2\over T_2}+ {\mathcal{Q}_3\over T_3}+{\mathcal{Q}_4\over T_4}$

cioè

>
>**Teorema di clausius**
> $\sum^n_{i=1}{\mathcal{Q}_i\over T_i}\le 0 \to \oint_\Gamma {d\mathcal{Q}\over T}\le 0$
>
> Questo integrale viene chiamato **integrale di clausius**

Dove $\Gamma$ è la seguente area

![1555579142503](assets/1555579142503.png)
dove i due cicli non devono essere necessariamente uguali. (Li ho resi uguali per semplicità nel copia incolla grafico)
quindi
$\eta_x\le \eta_R\iff\oint {d\mathcal{Q}\over T}\le 0$

Se $\eta_x $ è reversibile

$\eta_x=\eta_R \Rightarrow \oint {d\mathcal{Q}\over T}=0$

Cioè 

> Se il ciclo è **Reversibile**, l'integrale di clausius è **nullo**.

Proseguendo con l'integrale di prima, scompongo:

$I\int^B_A {d\mathcal{Q}\over T}+II\int^A_B {d\mathcal{Q}\over T}=0\xrightarrow{Reversiblile}{}I\int^B_A {d\mathcal{Q}\over T}-II\int^B_A {d\mathcal{Q}\over T}=0$

Ottengo che 

> L'integrale non dipende dal percorso!
>
> Quindi potrei avere un percorso che va da $A$ a $B$ totalmente diverso da quello che da $B$ va ad $A$, il risultato non cambierebbe.

![img](assets/entrop24.gif)
ora ottengo
$I\int^B_A {d\mathcal{Q}\over T}=II\int^B_A {d\mathcal{Q}\over T}=III\int^B_A {d\mathcal{Q}\over T}=S_B-S_A=\Delta S$ dove $S_B$ è l'entropia

#### Entropia
>Entropia è una **funzione di stato** che :
>
>entropia$=S|\Delta S=S_B-S_A=\int^B_{A_{(Reversibile)}} {d\mathcal{Q}\over T}$ 

Facciamo finta di avere un ciclo irreversibile per colpa di $A\to B$

![1555616410243](assets/1555616410243.png)
Ottengo che $\oint dQ<0=I\int^B_A {d\mathcal{Q}\over T}+\int^A_B {d\mathcal{Q}\over T}<0$
$I\int^B_A {d\mathcal{Q}\over T}-II\int^B_A {d\mathcal{Q}\over T}<0$ cioè $I\int^B_A {d\mathcal{Q}\over T}<II\int^B_A {d\mathcal{Q}\over T}$
* La parte non reversibile è $I\int$;
* Ciò che varia è che ora ho $<$ al posto di $=$

Dunque

$\Delta S_{AB}>\int^B_A {d\mathcal{Q}\over T}$ reale irreversibile.

Ottengo dunque che

> $\int^B_A {d\mathcal{Q}\over T}\le \Delta S_{AB}$ **dove** $= \text{se reversibile}\\< \text{se irreversibile}$

Ottengo infine che
>* $\Delta S=0$ se **reversibile** $(S_A^{Finale}=S_A^{Iniziale}=0)$
>
>* $\Delta S<0 $ se **irreversibile** 



#### Esercizio di esempio

Avendo due sorgenti di calore
$T_2=380K$

$T_1=280K$

$S=100 cm^2$

$d=2,5cm$

$\Delta S_{universo}=?$(calcolare l'entropia dell'universo)

Uso la **formula di Fourier**: $Q=KS{\Delta S\over d}t$
> **Attenzione**: S sta per superficie, non entropia.

$K_{1l}=201 {J\over mSK}$

${Q|_{1Sec}}=8040J$

$Q|_{1Min}=4,824\cdot 10^5 J$

$\Delta S_u={Q\over T_1}-{Q\over T_2}=453,4 {J\over K}$



---
Tornando alla formula precedente , scritta con i diffferenziali

$dS=^{def} {d_Q\over T}$

$S_B-S_A=\int^B_A({dQ\over T})_{reversibile}>\int^B_A({dQ\over T})_{irreversibile}$

ricordando che $\oint {dQ\over T}<0$ per l'irreversibilità.

---
Quindi, sull'es di prima, l'entropia dell'universo è definita con queste tre equazioni

$\Delta S_{S1}={Q_1\over T_1}$ con $Q_1>0$ perchè la sorgente $S1$ assorbe.

$\Delta S_{S2}=-{Q_2\over T_2}$

$\Delta S=0$



ottenendo 

$\Delta S_{TOT}={Q1\over T_1}-{Q_2\over T_2}$

#### In un sistema isolato
Suppongo di avere un **sistema isolato**, cioè che non ho scambio di calore $dQ=0$

$S_B-S_A=0$

$S_B=S_A$

Quindi

>**Un sistema isolato:**
>1. Se procede per **trasformazioni reversibili** allora **l'entropia non varia**;
>2. Se procede per **trasformazioni irreversibili** allora **l'entropia aumenta**.

*L'entropia, microscopicamente è compatibile con il numero di stati macroscopici(?)*

>$S=c \ln[N]$ dove $N=$*numero di stati possibili*

Quindi l'entropia in questo caso 
>Tende ad evolvere in **stati macroscopici compatibili con stati microscopici**, cioè ho **più disordine**.

Fornendo una definizione più precisa di disordine:
> **Disordine**: Possibilità di scelta.

*Ci basta pensare ad una stanza con dei libri impilati uno sopra all'altro al centro della stanza. Successivamente avremo che i libri (usandoli) verranno spostati nei vari punti della stanza, creando disordine dallo stato iniziale i quali erano posizionati.*

### Elettromagnetismo

>**Forza di Coulomb**: $K{q_1 q_2\over d^2}$

$udm[q]=1C$

$[K]=[{F\over qq}d^2]=[{N\cdot m^2\over c^2}]=udm [K]$

Dove $K$ è una costante definita come

$K={1\over 4\pi\epsilon_0}$

avendo

>$\epsilon_0=$ costante dielettrica del vuoto = $8,85\cdot 10^{-12} {c^2\over N\cdot m^2}$

##### Paragone interessante
Forza di Newton$= \overrightarrow{F}_{1\to2}=K_G{m_1m_2\over r^2}$
Forza di Coulomb$= \overrightarrow{F}_{1\to2}={1\over 4\pi\epsilon_0}{q_1q_2\over r_{12}^2}\cdot \hat{r}_{12}$
Sono molto simili!

* Un oggetto senza massa **non è incline ad accettare interazioni** con la forza di Newton
* Un oggetto che non è carico **non è incline ad accettare interazioni** con la forza di coulomb.

Domande che sorgono:
* Perchè non posso avere masse negative?
* Perchè "d^2"?($\to$ Teorema di Gauss, il quale si applica anche alla massa). Vedremo approfonditamente nella prossima lezione.

## 19/04/2019
*parte esercizio mancante*

$\Delta S_{TOT}=\xcancel{\Delta S_{MAC}}+\Delta S_{env}=$

$\Delta S_{TOT}=\Delta S_{env}\ge 0$

$\Delta S_{TOT}=\Delta S_{env}=0={Q_1\over T_1}-{Q_2\over T_2}$

Sapendo che è Termicamente isolato ($Q_{TOT}=0$)

Tornando all'elettromagnetismo

**Cariche puntiformi**

$\overrightarrow{F}_{1\to2}={1\over 4\pi\epsilon_0}{q_1q_2\over |\overrightarrow{r}_{12}|^2}\hat{r}_{12}=-\overrightarrow{F}_{2\to1}$


$q_1=400_nC$

$q_2=100_nC$

$Q=1_nC$

$r_1=2 mm$

$r_2=1 mm$

$\overrightarrow{F}=\overrightarrow{?}$

L'inclinazione a muoversi la da la massa, non la carica. Ci manca la massa.

Supponiamo che i due punti siano fissati.
>**Principio di sovrapposizione**: Le forze elettriche sono indipendenti dall'ambiente circostante.

$\overrightarrow{F}_{1\to Q}={1\over 4\pi\epsilon_0}{400(nC)^2\over 4(\mu m)^2}\hat{r}_1=$

$={9\cdot10^9\cdot10^{-16}\over10^{-6}}N=9\cdot 10^{-1} N=0,9 N$

$\overrightarrow{F}_{2\to Q}={1\over 4\pi\epsilon_0}{100(nC)^2\over 1(\mu m)^2}\hat{r}_2=0,9 N$



![1556519535293](assets/1556519535293.png)

Come è possibile che siano entrambi $0,9N$ nonostante la differenza tra le due cariche? per la distanza.

Ridisegnando l'angolo, faccio la regola del parallelogramma tra $\overrightarrow{F}_{1\to Q}$ e $\overrightarrow{F}_{2\to Q}$ ottengo $\overrightarrow{F}$

$|\overrightarrow{F}|=\sqrt{3}\cdot 0,9N=1,55 N$

Calcoliamo il lavoro!

![1556519568713](assets/1556519568713.png)

$W=\int^B_A \overrightarrow{F}\cdot d\overrightarrow{S}={qQ\over 4\pi\epsilon_0}\int^B_A {1\over r^2}\hat{r}\cdot d\overrightarrow{S}=\lim_{N\to+\infty}{qQ\over 4\pi\epsilon_0}\sum^N_{i=1}{1\over r^2_i}\hat{r}_i\cdot d\overrightarrow{S}_i$
che è uguale a 
$\sum^N_{i=1}{1\over r^2_i}dS_i^{//}$

Ricordiamo che per il lavoro conta solo lo spostamento parallelo al raggio.
Posso immaginarmi di spostare lo spostamento parallelo su un asse.

![1556519594130](assets/1556519594130.png)



>Quindi alla fine l'integrale conta, indipendentemente dal "percorso" della funzione, tra $r_A$ e $r_B$!
>cioè
>
>${qQ\over 4\pi\epsilon_0}\int^{r_B}_{r_A} {1\over r^2}dr={qQ\over 4\pi\epsilon_0}[{1\over r_A}-{1\over r_B}]$

Conta solo lo **stato iniziale e lo stato finale**.

Otteniamo che la forza elettrica è una forza **conservativa**.

$W_{A\to B}=U_A-U_B=-\Delta U$

$U_p=U(\overrightarrow{r}_p)=U(r_p)={qQ\over 4\pi\epsilon_0}{1\over r}+C_G$

con p per punto (puntiforme)

avendo sorgente puntiforme e carica puntiforme.

$C_G$ è una costante. Facendo le differenze poi si semplifica.

##### Autoenergia
Una carica può interagire con se stessa? in quel caso il raggio sarebbe **zero!** il che sarebbe un problema!
Boh.


#### Carica di prova e campo elettrico
$\overrightarrow{F}_{TOT}=\sum^N_{i=1} {1\over 4\pi\epsilon_0}{q_1Q\over r^2_i}\hat{r}_i$

$=Q\sum^N_{i=1}{1\over 4\pi\epsilon_0}{q_1\over r_i^2}\hat{r}_i$

$\overrightarrow{E}_{TOT}={\overrightarrow{F}_{TOT}\over Q}=\sum^N_{i=1}{1\over 4\pi\epsilon_0} {q_1\over r^2_i}\hat{r}_i$

Il campo elettrico ha un corrispettivo fisico.
Un vettore associato a un punto nello spazio.
Posso avere un punto a caso e poter disegnare il campo elettrico!

![1556543372227](assets/1556543372227.png)

>**Campo elettrico**: Funzione matematica calcolabile in qualsiasi punto dello spazio, associando a questo punto un valore(vettore, tensore, scalare etc...)
>Se il campo è **vettoriale lo descrive un vettore.**


Se **scalare lo descrive un numero.**(ad esempio la temperatura!)

Posso ottenerlo senza **descrivere necessariamente le sue sorgenti.**

con i differenziali
$\overrightarrow{F}_{TOT}\xrightarrow{1/Q}{}\overrightarrow{E}_{TOT}$
$\overrightarrow{U}\xrightarrow{1/Q}{}\overrightarrow{V}|\Delta V={\Delta U\over Q}$

## 29/04/2019

$\overrightarrow{E}=^{def} {\overrightarrow{F}\over q_0}$

Con unità di misura 

$[E]=[{F \over Q}]= udm [E]={N\over C}={V\over m}$

$W_e=\int_c \overrightarrow{F}_e\cdot d\overrightarrow{l}=^{(*)}\int^B_A \overrightarrow{F}\cdot d\overrightarrow{l}=^{def} -\Delta U= - [U_B-U_A]=-q_0[V_B-V_A]$

(\*) *L'integrale lungo la curva posso farlo calcolando l'integrale agli estremi ( non è una cosa immediata)*

dove 

$-[U_B-U_A]=W_e=\int _A ^B q_0\overrightarrow{E}\cdot d\overrightarrow{l}=q_0\int_A^B \overrightarrow{E}\cdot d\overrightarrow{l}=^{def}=-q\Delta V$ **cioè differenza di potenziale**


#### Carica puntiforme

In una carica puntiforme

$\overrightarrow{F}={q_0Q\over 4\pi \epsilon_0 r}\hat{r}$

$\overrightarrow{E}={q_0Q\over 4\pi \epsilon_0 r}\hat{r}$

$V={Q\over 4\pi \epsilon_0 r}+costante$

Questa costante vale zero!

####  Energia elettrostatica delle cariche

Avendo quattro punti
$q_1, q_2, q_3, q_4$

![Risultati immagini per Energia elettrostatica delle cariche](assets/cff38e7a410f436da9cdf3b7daac7f98_A.png)

$W=-\Delta U_e|_{q_2}=-q_2\Delta V_e=-q_2[{q_1\over 4\pi \epsilon_0 r_{12}}-\xcancel{q_1\over 4\pi\epsilon_0(+\infty)}]$

Il contributo di $q_3$ verso $q_2$ è 

$W=-\Delta U_e|_{q_3}=-q_3\Delta V_e=-q_3[{q_1\over 4\pi \epsilon_0 r_{13}}-\xcancel{q_1\over 4\pi\epsilon_0(+\infty)}+\dots]$

Quindi otteniamo che è arbitrario come prendo i punti($r_{13},\ r_{12}$)

Lo posso dunque scrivere come **energia elettrostatica delle cariche**

>$U_e={1\over 2}\sum_{i\ne j} {q_iq_j\over 4\pi\epsilon_0 r_{ij}}={1\over 2}\sum_{i\ne j} q_i V_{ji}$

(l'un mezzo è li presente perchè va a formare una matrice **simmetrica**.)

#### Densità lineare

Ho un filo

>$\lambda=$ **densità lineare di carica** $={dq\over ds} \Rightarrow \lambda ds$ *(definizione differenziale, infinitesimale, ha senso in un punto dove il tratto di filo è approssimabile con una retta/segmento)*

con

$q_L=\int ^{P_0+ L}_{P_0} \lambda(s) ds$

Ho una superficie

>$\sigma=$ **densità superficiale di carica** ${dq\over d\Sigma}  \Rightarrow \sigma d\Sigma$ dove $\Sigma$ è la mia superficie con cariche.

con

$q_S=\int ^{P_0}_S \sigma(\Sigma) d\Sigma$

Avendo un volume(tre dimensioni)

>$\rho=$ **densità volumica di carica** ${dq\over d\tau} \Rightarrow \rho d\tau$ dove $\tau$ è il mio volume con cariche.

con 

$q_V=\int ^{S}_V \rho(\tau) d\tau$

<!--*IMMAGINE METRO DA SARTA(boh) SU ESEMPIO LAMBDA*-->

#### Esercizio idrogeno

Calcolo idrogeno

Ricordo che un protone è una sfera$={4\over3}\pi R^3$

$e=1,6\cdot 10^{-19} \mathcal{c}$

$R_n=10^{-15}m$

calcolo $\rho$

$\rho={dq\over d\tau}={Q\over \tau}={1e\over {4\over 3}\pi R^3}={1,6\cdot 10 ^{-20}\mathcal{c}\over 4\cdot 10^{-45} m^3}=4\cdot 10^{25}\mathcal{c}/m^3$

> Ma come fa la densità ad essere negativa? la carica può essere negativa, quindi la densità di carica può essere negativa!

Ora provo a "spalmare" la carica su tutta la superficie 

$R_a=10^{-10}m$ raggio nucleo

$\sigma={d_q\over d\Sigma}={Q\over 4\pi R^2_a}={-16\cdot 10^{-20}\mathcal{c}\over 12\cdot 10^{-20}}$

#### Passaggio al continuo (PAC)
Ho un campo elettrico formato da una serie di cariche

$\overrightarrow{E}(\overrightarrow{r}_p)=\sum^N_{i=1}{q_i\over 4\pi\epsilon_0|\overrightarrow{r}_i-\overrightarrow{r}_p|^2}=^{(\sum _i {dq_i}_{ = ds})}\int^B_A ds{\lambda\over 4\pi\epsilon_0|\overrightarrow{r}_s-\overrightarrow{r}_p|^2}\hat{r}_{SP}$


$\overrightarrow{V}(\overrightarrow{r}_p)=\sum^N_{i=1}{q_i\over 4\pi\epsilon_0|\overrightarrow{r}_i-\overrightarrow{r}_p|}=^{(\sum _i {dq_i}_{ = \rho d\tau})}\int^A d\tau{\rho\over 4\pi\epsilon_0|\overrightarrow{r}_\tau-\overrightarrow{r}_p|}$


$U_e={1\over2}\sum{i\ne j}{q_i q_j\over 4\pi\epsilon_0|\overrightarrow{r}_i-\overrightarrow{r}_j|}=\dots$

<!--*IMMAGINE PUNTINI FRECCIA PAC CON CUBO*-->

#### somma costante

$W=\Delta E_k=-\Delta U_e=-q\Delta V$

$\Delta E_k+ \Delta U_e=\Delta E_{TOT}=0$

>$\Delta[E_k+qV]=0\Rightarrow E_k+q_V= costante$ !
>

#### Esperimento di Rutherford

Degli studenti sparano delle cariche su una lamina in oro

$E_k=7MeV$ dove $MeV$ è MegaElettronVolt

$q_\alpha=+2e$

$z=76$ cioè il numero atomico dell'oro

$m_a=6,64\cdot 10^{-27} Kg$

Si sono accorti che possono succedere diverse cose

la particella $\alpha$ può passare tra gli atomi dell'oro

più mi avvicino ad un nucleo senza toccarlo più viene deviato

quando lo "colpisco" non lo tocco in realtà, perchè il campo che c'è respinge la nostra particella spedita!

![File:Scatteringrutherford.jpg](assets/Scatteringrutherford.jpg)

$7\cdot 10^6 eV=1,6\cdot 10^{-19} J$

Inizialmente $E_k^i+\xcancel{qV_i}$

$\xcancel{qV_i}$ perchè sono molto distante(quindi per le grandezze minuscole che prendiamo, con una distanza di un metro è pressochè infinita.)

Finale abbiamo $\xcancel{E_k^f}+qV_f$ 

$\xcancel{E_k^f}$ perchè l'energia cinetica alla fine è zero

Energia cinetica iniziale ${E_k^i}={1\over 2}mV_i^2=2e{z_e\over 4\pi\epsilon_0 x}$

con $x={2ze^2\over 4\pi\epsilon_0 E_k^i}=4,11\cdot 10^{-16} mz$

>**Considerazioni:** 
>
>più alta è l'energia e più posso sondare distanze.
>
più è alto un numero atomico e meno ci avviciniamo!

Se continuo ad aumentare l'energia, il bersaglio si **rompe** prima di toccarlo!

#### Esercizio anello

Ho un anello di carica, spedisco una particella tra l'anello

![1556550153039](assets/1556550153039.png)

$V(x,0,0)=?$

$\overrightarrow{E}(x,0,0)=?$

$dV={dq\over 4\pi\epsilon_0 r}={\lambda ds\over 4\pi \epsilon_0 r}$

$V=\int dV=\int _{anello} {\lambda ds\over 4\pi\epsilon_0r}={\lambda\over 4\pi\epsilon_0 r}\int ds={\lambda 2\pi R\over 4\pi\epsilon_0 r}={Q\over 4\pi\epsilon_0\sqrt{R^2+x^2}}$

con $\lambda 2\pi R=Q$

**Considerazioni finali:**

Se mi allontano tanto vedo una carica puntiforme, quindi la tratto come tale!

se $x=0 \Rightarrow {Q\over 4\pi\epsilon_0 R}$

se ${R\over x}<<1 \Rightarrow {Q\over 4\pi\epsilon_0 |x|}$

## 03/05/2019

$V_A-V_B=\int ^B_A \overrightarrow{E}\cdot d\overrightarrow{s}$

Abbiamo un **gradiente**

*Che cosa è un gradiente?*

$\overrightarrow{E}=-\overrightarrow{\nabla}V=-\begin{bmatrix} {\delta V\over \delta x}\\{\delta V\over \delta y}\\{\delta V\over \delta z}\end{bmatrix}$

con  $\overrightarrow{\nabla}$ è il gradiente, composto da derivate parziali(?)

Dove ho le derivate parziali:

$E_x= -{\delta\over \delta x}V=2V_0xy(1-z)$

$E_y= -{\delta\over \delta y}V=V_0x^2(1-z)$

$E_z= -{\delta\over \delta z}V=-V_0x^2y$

Da queste tre ho:

$\overrightarrow{E}=-\hat{r} {dV\over dr}$

#### Circuitazione 

>**Circuitazione**: $\oint q\overrightarrow{E}\cdot d\overrightarrow{s}=0$
>
>dove $q\overrightarrow{E}=\overrightarrow{F}$, ma possiamo togliere la carica $q$ perchè costante, ottenendo:
>
>$\oint \overrightarrow{E}\cdot d\overrightarrow{s}=0​$ che viene più semplicemente scritto come
>
>$\Gamma \overrightarrow{E}=0$


>**Tutti i campi conservativi hanno circuitazione zero.**
>

Coinvolgo un integrale chiuso su un dominio chiuso ma è **lineare, unidimensionale!**

#### Flusso

Immagino di avere un campo, vettoriale, che è la velocità delle particelle in un fluido.

Immagino di avere un flusso laminare controllato e che possa analizzare il vettore velocità( il campo è composto da un insieme di vettori velocità!).

Avendo un "setaccio" con il quale passiamo il nostro flusso, se è abbastanza piccolo, posso avere una ottima approssimazione di una superficie piana.

Oltretutto ho un vettore **normale** che non è necessariamente perpendicolare al nostro.

Otteniamo la **definizione di flusso**:

> $d\Phi _{d\Sigma}(\overrightarrow{v})=^{def}\overrightarrow{v}\cdot \hat{n} d\Sigma$
> 
> Quantità matematica di un campo vettoriale

Allargando la superficie il flusso aumenta.

Il segno del flusso è **arbitrario** in base al vettore **normale**.


disegno coso superfice 

$=\overrightarrow{E}\cdot\hat{n}\ d\Sigma={1\over 4\pi\epsilon_0}{q\over r^2}{\hat{r}\cdot\hat{n}}\ d\Sigma={q\over 4\pi\epsilon_0}\cos\theta {d\Sigma\over r^2}$

con $\cos\theta {d\Sigma}$ scrivibile come $d\Sigma_r$

diventando

${q\over 4\pi\epsilon_0}{d\Sigma_r\over r^2}$

Prendiamo la superficie ortogonale al vettore che stiamo valutando($\cos\theta=0$)

#### Angolo solido

Angolo portato alle tre dimensioni

Avendo un arco di circonferenza, portato ad un cilindro abbiamo

${\overparen{a}\over R}=\alpha$

cioè

${\overparen{e}\over R}={2\pi\cancel{R}\over\cancel{R} } $

ottenendo


$\Omega_{TOT}={S\over R^2}={4\pi R^2\over R^2}=4\pi$

#### Teorema delle superfici di Gauss

![1556876898769](assets/1556876898769.png)

>$\Phi_{\Sigma}(\overrightarrow{E})=\int d\Phi={q\over 4\pi \epsilon_0}=\int d\omega={q\over \cancel{4\pi} \epsilon_0}\cdot \cancel{4\pi}={q\over \epsilon_0}$
>
>cioè 
>
>$\Phi(\overrightarrow{E})={\sum_i q_i\over \epsilon_0}$

Si basa sulla definizione di interno ed esterno.

>Vale ciò solamente sulle **superfici chiuse** .

Osservazioni:
1. Il teorema non parla della superficie, posso prendere qualsiasi tipo!
2. **Non devo specificare il raggio della sfera!** (il Flusso rimane lo stesso)
3. Il teorema non dipende dalla posizione della carica.
4. I campi sono sommabili, se avessi più cariche prendo la somma delle singole cariche!

>**Il flusso del campo elettrico dipende solo dall'angolo solido!**

##### Esempio

![1556876869456](assets/1556876869456.png)

>I singoli contributi non saranno zero, il campo non è zero sulla superficie! 

##### Esercizio

Quanto vale il campo elettrico in funzione della posizione?

![1556877786492](assets/1556877786492.png)

$\overrightarrow{E}(\overrightarrow{r})=\overrightarrow{?}$

Noto che il problema è puramente radiale.

Prendo un punto P a caso, sarà a distanza $r_P$

otteniamo con il teorema di gauss

La fisica mi dice che

$\Phi_{S_D}(\overrightarrow{e})=^{phys} {q\over \epsilon_0}$

La matematica mi dice che

$\Phi(\overrightarrow{e})=E4\pi r_p^2$

ed ottengo

$E={q\over 4\pi\epsilon_0}{1\over r^2_p}$

>Ma è uguale alla carica puntiforme! Però questo non vale in un caso generico. Infatti se assumo di avere una circonferenza dentro , abbiamo tutte le cariche all'esterno. Quindi la nostra A avrà $E=0$. In specifico:

![1556878157912](assets/1556878157912.png)

La fisica mi dice che

$\Phi_{S_A}(\overrightarrow{e})=^{phys} 0$

La matematica mi dice che

$\Phi(\overrightarrow{e})=E4\pi r_A^2$

ed ottengo

$E=0$

![1556878506142](assets/1556878506142.png)

## 06/05/2019

#### Esempio uno

![1557151157410](assets/1557151157410.png)

 

$\Gamma (\overrightarrow{E})=0$

$\Phi(\overrightarrow{E})={q_{int}\over \epsilon_0}$

Come varia il campo elettrico al variare della superficie?

ho $\sigma(x,y,z)$ e $\overrightarrow{r}=(x,y,z)$

Ho che 
$\bar{AB}=\bar{CD}$

$\bar{BC}=\bar{DA}<<\bar{AB}$

$\bar{BC}=o(\bar{AB})$


come sappiamo il campo elettrico che è in un punto è la somma dei campi che esercitano in quel punto.

ottengo la circuitazione

$\Gamma_{\square} (\overrightarrow{E})=\oint_\square \overrightarrow{E}\cdot d\overrightarrow{l}= \overrightarrow{E}_2\cdot \overrightarrow{AB}+\xcancel{(\overrightarrow{E}_2 ? \overrightarrow{E}_1)\cdot \overrightarrow{BC}}+\\\overrightarrow{E}_1\cdot \overrightarrow{CD}+\xcancel{(\overrightarrow{E}_1?\overrightarrow{E}_2)\cdot \overrightarrow{DA}}$

Li cancello perchè sono infinitesimali!

ottengo

> $\Gamma (\overrightarrow{E})=0\oint \overrightarrow{E}\cdot d\overrightarrow{l}=E_{2t}-E_{1t}=0 \Rightarrow E_{2t}=E_{1t}$

cioè il campo elettrico non varia, è conservativo

#### Esempio due

Abbiamo un cilindro 

![1557152249037](assets/1557152249037.png)



$\Phi_{cyl}\overrightarrow{E}=^{math} \overrightarrow{E}_2\cdot \hat{n}_2 S+\xcancel{(\overrightarrow{E}_1?\overrightarrow{E}_2)\cdot \hat{n}_2 S_2}+\\+\overrightarrow{E}_1\hat{n}_1S=(E_{2n}-E_{1n})S$

Posso rimuovere anche qui perchè è infinitesimale.

Ottengo dunque che 

>$\Phi_{}\overrightarrow{E}={q_{int}\over \epsilon_0}\Rightarrow E_{2n}-E_{1n}={\sigma\over\epsilon_0}$
>


Campo elettrico varia di $\sigma\over\epsilon_0​$

> Unendo questi due otteniamo
>
> $\begin{cases}\Gamma (\overrightarrow{E})=0\oint \overrightarrow{E}\cdot d\overrightarrow{l}=E_{2t}-E_{1t}=0 \Rightarrow E_{2t}=E_{1t}\\ \Phi_{}\overrightarrow{E}={q_{int}\over \epsilon_0} \Rightarrow E_{2n}-E_{1n}={\sigma\over\epsilon_0}\end{cases}\Rightarrow  \ \ \ \ \ \overrightarrow{E}_2-\overrightarrow{E}_1={\sigma\over \epsilon_0}$ 
>
> con $n>\epsilon_0$

*correzione esercizio per casa che mi sono perso*

#### Campo elettrico di un piano indefinito di carica

Come fa il campo elettrico nello spazio?

$\overrightarrow{E}(\overrightarrow{r})=?$

---

**Q: Posso assumere di avere distanza infinita ?**

A: $L_P\over d$ quindi ogni punto sarebbe uguale all'altro se avessi distanza infinita.

---

Avendo una piana di carica positiva, il campo elettrico infinito sarà così

![1557153093108](assets/1557153093108.png)

> $\overrightarrow{E}_2-\overrightarrow{E}_1={\sigma\over\epsilon_0}\hat{n}_2\\ \overrightarrow{E}_2-(-\overrightarrow{E}_2)={\sigma\over\epsilon_0}\hat{n}_2\Rightarrow\overrightarrow{E}={\sigma\over2\epsilon_0}\hat{n}$

Dato che il piano è infinito, non si ha una dipendenza dalla distazna, infatti ${\infty\over d=1m}=\infty$

come ${\infty\over d=1GPa}=\infty$

#### Conduttori

>**Conduttore**: Materiale sul quale un certo tipo di  elettrone può muoversi liberamente.
>

1. Se un conduttore è neutro la somma delle cariche fa zero.
2. Se ho un conduttore all'equilibrio allora ho le cariche ferme
3. Se le cariche sono ferme, nessuna di loro subisce forze, di nessun tipo, nemmeno elettriche.

Se ho o meno le cariche all'interno non mi interessa perchè influiscono solo quelle esterne.

$\overrightarrow{E}_{int}=\overrightarrow{0}$

##### Induzione

Se ho una barra conduttore, dentro è zero e tutte le cariche sono negative all'esterno. Se una carica si depositasse all'interno, dovrebbe agire in base al campo elettrico sul bordo.


Se ho una penna bic, la carico sfregandola su una maglietta, non essendo conduttore (plastica) si piazzano tutte all'esterno!

>Appena lo avvicino alla mia barra conduttore  **induco un moto di cariche**.
>
L'**induzione** è dunque l'indurre un moto di cariche tra qualcosa a qualcos'altro.

*Le cariche negative vanno al contrario della freccia che creiamo*

##### Induzione Completa

Supponiamo di avere due conduttori

una sfera ed una sfera che la "abbraccia".

La sfera interna è carica positivamente, la sfera esterna si caricherà negativamente.

( Vedi immagine: condensatore sferico)

![File:Spherical Capacitor.svg - Wikimedia Commons](assets/download-1557154874087.png)

>Ho dunque un caso di induzione **completa** tra i conduttori, perchè TUTTE le linee di un conduttore vengono intercettate dall'altro. Tutte le linee di campo che escono da uno dei due conduttori viene intercettato dall'altro.

Se avvicinassi la sfera carica positivamente ad un conduttore, **avrò un ammasso di cariche negative dalla parte più vicina alla sfera,** perchè le linee di campo della sfera caricata positivamente.

Se avessi due linee di campo , una positiva ed una negativa, quella negativa intercetterebbe quasi tutte le linee di campo delle positive.

*Questo perchè si annullano a vicenda*.(vedi immagine: condensatore piano)

![img](assets/download.jpg)

*Non ci soffermiamo sugli effetti di bordo.*


>La superficie di un conduttore è **equipotenziale** cioè sempre costante.
>
$E=0=-{dV\over dr}\Rightarrow V=costante$

Più carica verso e più il potenziale della sfera **aumenta**.
Per il principio di **sovrapposizione** posso calcolare ogni punto di carica della sfera.

##### Capacità
> $C={Q\over V}$
> 

$udm[C]={1C\over 1V}=1F$ un farad.

Un farad è grandissimo. Infatti si utilizza spesso pico/nano/femto/micro-Farad.

>Se abbiamo un sistema in induzione completa, la capacità è data da due conduttori
>
>$C={Q\over V_2-V_1}$
>

##### Esempio

Due armature quadrate 

$S=1m^2$

$d=1mm$

$E={10KV\over m}$

$C=8,85\cdot 10^{-9} F$

Calcolare la carica delle armature.

(Si trovano in vuoto/aria).

Calcolo Q

$Q=C\Delta V$

$C$ ce lo fornisce il problema, calcolo $\Delta V=E\cdot d$

$Q=CEd=8,85\cdot 10^{-9}F\cdot 10^4\cdot 10^{-3}\mathcal{c}$

Ottenendo $Q=C\Delta V=8,9\cdot 10^{-8}\mathcal{c}$

**Osservazioni:**

1. Un condensatore mi serve per portarmi in giro energia.
2. Per caricarlo devo fare del lavoro, per colpa della differenza di potenziale.

