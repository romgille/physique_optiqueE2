
---
title: Interférences à deux ondes
author: Romain Gille
geometry : margin=1in
date: 17/02/2016
...

\newpage

# Cohérence de la lumière

Le phénomène d'interférence entre deux sources lumineuses nécessite que les
  longueurs d'ondes qui interfèrent soient identiques mais également que les
  sources soient ponctuelles.

  Ces deux impératifs sont reliés respectivement aux notions de cohérence
  temporelle et de cohérence spatiale. La nécessité d'avoir des sources à la
  même fréquence, se confronte à l'impossibilité d'avoir une source parfaitement
  monochromatique.

## Caractère scalaire de l'émission lumineuse

Les sources émettent de la lumière par suite de la désexcitation d'atomes, au
  préalable soumis à une excitation électrique, thermique ou lumineuse.

L'atome excité devient un dipôle oscillant dont la charge négative est
  l'électron, atome qui en se désexcitant émet une onde électromagnétique.

L'énergie rayonnée est fournie par l'énergie mécanique de l'oscillateur qui
  s'ammortit du fait de l'émission lumineuse, émission qui cesse lorsque l'atome
  arrête de vibrer.

Lorsque l'atome est désexcité, il l'est avec la même fréquence d'oscillation
  $\nu_0$ et le même module du champ électrique $E_0$. En revanche, la phase
  initiale du mouvement est aléatoire, c'est à dire sans relation avec celle du
  mouvement précédent.

Donc le champ électrique prend toutes les orientations possibles dans le plan
  perpendiculaire à la direction de propagation sur une durée suffisante pour
  l'observation ou la détection du rayonnement
  (durée très supérieure à la durée d'oscillation du dipôle).

\newpage

## Intensité spectrale

$$I(\nu) = \dfrac{dI}{d\nu} \text{ avec } \nu \text{ : fréquence}$$

### Distribution lorentzienne

$$I(\nu) = \dfrac{A}{1 + 4 \pi^2 \tau_c^2 (\nu - \nu_0)^2}$$
$$\nu_0 \text{ : fréquence centrale d'oscillation}$$
$$\tau_c \text{ : temps de cohérence}$$

La largeur totale à mi hauteur définie comme étant la largeur de bande
$\Delta \nu_{1/2}$ est telle que l'intensité spectrale $I(\nu) \geq
\dfrac{A}{2}$

$$\Delta \nu_{1/2} = \dfrac{1}{\pi \tau_c}$$

Cette forme de distribution est attribuée aux collisions entre atomes de la
  source, collisions dues à l'agitation thermique. Elle est reliée à la durée
  de l'émission de l'onde entre deux chocs.

### Distribution hertzienne

Cette forme de distribution est attribuée à l'effet Doppler, c'est à dire la
  variation de fréquence de l'onde émise par les atomes de la source du fait
  de leur mouvement.

## Cohérence temporelle

Le mouvement oscillant des atomes excités s'amortissant, le profil du champ
électrique de l'onde émise est de la forme suivante :

$$E(t) = E_0 \exp{(\frac{-t}{\tau_0})} \cos(2\pi\nu_0 t)$$

Notation complexe :

$$E(t) = E_0 \exp{(\frac{-t}{\tau_0})} \exp{(j2\pi\nu_0 t)}$$

$\tau_c$ représente la durée caractéristique du mouvement oscillatoire de
  l'atome pendant laquelle l'amplitude du champ électrique s'amortit d'un
  facteur $e$ et s'appelle le temps de cohérence.

L'ensemble des vibrations d'allure sinusoïdale durant cet intervalle de temps
  s'appelle le train d'onde. Le temps de cohérence correspond à la durée moyenne
  du train d'onde.

\newpage

### Transformée de Fourier pour passer de $E(t) \text { à } E(\nu)$

$$E(\nu) = \int_{-\infty}^{+\infty} E(t) \exp{(-i 2 \pi \mu t)} dt$$
$$E(\nu) = \int_{0}^{+\infty} E(t) \exp{(-i 2 \pi \mu t)} dt$$

\centering
\fbox{
  $E(\nu) = \dfrac{E_0}{i 2 \pi (\nu - \nu_0) + \frac{1}{\tau_c}}$
}
\fbox{
  $I(\nu) = \dfrac{n E_0^2 \tau_c^2}{4\pi^2 \tau_c^2(\nu - \nu_0^2) + 1}$
}

\raggedright
La largeur de bande $\Delta\nu_{1/2}$ étant inversement proportionnelle à
  $\tau_c$, l'existence d'une raie monochromatique idéale supposerait que les
  atomes oscillent durant une durée infinie et sans amortissement.

On définie la longueur de tolérance temporelle $L_c$ comme $L_c = c \tau_c$.

$L_c$ est la longueur moyenne du train d'onde.

Pour un système interférenciel à deux ondes, si la différence de marche $\delta$
  en un point $M$, entre des rayons 1 et 2 issus des sources, est supérieure à
  $L_c$, alors il n'y a plus d'interférence. Autrement dit, si $\delta > L_c$ la
  différence de phase est aléatoire.

Les trains d'onde ne se superposent plus la majorité du temps quand la
  différence de marche entre les rayons est trop grande.


   |$\lambda (nm)$ | $\tau_c (s)$ | $L_c (m)$ |
   |----------------|--------------|-----------|
   | lampe à vapeur de Hg | $546 nm$ | $10^{-12}$ | $0.3 mm$ |
   | laser He / Ne | $632 nm$ | $0.7 \times 10^{-9}$ | $0.2$|
   | laser He / Ne (stabilisé) |$632.8 nm$ | $10^{-6}$ | $300m$|

## Cohérence spatiale

La cohérence spatiale représente la capacité de chacun des points du front
  d'onde à être dans le même état vibratoire. La dimension dans le plan d'onde
  pour laquelle les trains d'ondes sont en phase s'appelle la largeur de
  cohérence spatiale $l_s$.

Si la source est trop étendue, elle présente des ondes incohérentes entre elles.
  La source étendue peut être vue comme un ensemble de sources ponctuelles
  chacune susceptible de produire son propre système d'interférence.

Si la variation de $\delta$ pour les différentes sources ponctuelles est
  perturbée, cela peut brouiller les interférences comme nous le verrons avec
  les fentes d'Young.

\newpage

# Interférences lumineuses

Considérons deux ondes monochromatiques, polarisées rectilignement, issus de
  deux sources $S_1$ et $S_2$ ponctuelles. Les ondes sont sphériques, synchrones
  (elles ont même $\omega \text{ ou } f$), les champs électriques instantanés
  en notation complexe en un point $M$ de l'espace s'écrivent de la façon
  suivante :

\centering
\fbox{
  $\overrightarrow{E_1} = \dfrac{C_1}{r_1} \exp{j(\omega t + kr_1 + \phi_1)} \overrightarrow{u_1}$
}

\fbox{
  $\overrightarrow{E_2} = \dfrac{C_2}{r_2} \exp{j(\omega t + kr_2 + \phi_2)} \overrightarrow{u_2}$
}

\raggedright
Les $C$ sont des constantes.
Les $\phi$ sont les phases instantanées à l'origine des temps et de l'espace,
c'est-à-dire, aux sources $S_1$ et $S_2$ à l'instant d'émission des trains
d'ondes.

Pour simplifier la notation, nous posons : $\Phi = kr + \phi$, la phase à
l'origine des temps.
Ainsi que $A = \dfrac{C}{r}$, les amplitudes à l'origine des signaux.

$$\overrightarrow{E_1} = A_1 \exp{(j \Phi_1)} \exp{(j \omega t)}
  \overrightarrow{u_1}$$
$$\overrightarrow{E_2} = A_2 \exp{(j \Phi_2)} \exp{(j \omega t)}
  \overrightarrow{u_2}$$
$$\overrightarrow{E} = (A_1 \exp{(j \Phi_1)} \overrightarrow{u_1} +
  A_2 \exp{(j \Phi_2)} \overrightarrow{u_2}) \exp{(j\omega t)}$$
$$I = n E E^*\text{ (conjugué) }$$
$$I = n \overrightarrow E \overrightarrow{E^*} = n (\overrightarrow{E_1} +
  \overrightarrow{E_2})(\overrightarrow{E^*_1} + \overrightarrow{E^*_2})
  \text{  on considère n = 1}$$
$$I = [A_1 \exp{(j \Phi_1)} \overrightarrow{u_1} + A_2 \exp{(j \Phi_2)}
  \overrightarrow{u_2}] . [A_1 \exp{(-j \Phi_1)} \overrightarrow{u_1} +
  A_2 \exp{(-j \Phi_2)} \overrightarrow{u_2}]$$
$$I = A^2_1 + A^2_2 + A_1 A_2 \exp{(j(\Phi_1 - \Phi_2))} \overrightarrow{u_1} .
  \overrightarrow{u_2} + A_2 A_1 \exp{(j(\Phi_2 - \Phi_1))}
  \overrightarrow{u_2} . \overrightarrow{u_1}$$
$$I_1 = E_1 E^*_1 = A^2_1$$
$$I_2 = E_2 E^*_2 = A^2_2$$
$$I = I_1 + I_2 + \sqrt{I_1 I_2} \cos{(\Theta)} [\exp{(j(\Phi_1 - \Phi_2))} +
\exp{(j(\Phi_2 - \Phi_1))}]$$

**Relation trigonométrique :** $\exp{(ja)} + \exp{(-ja)} = 2 \cos{a}$

$$I = I_1 + I_2 + 2 \sqrt{I_1 I_2} \cos{(\Phi_1 - \Phi_2)} \cos{(\Theta)}$$
$$I = I_1 + I_2 + 2 \sqrt{I_1 I_2} \cos{(\Theta)} \cos{(kr_1 + \phi_1 - kr_2 -
\phi_2)}$$
$$I = I_1 + I_2 + 2 \sqrt{I_1 I_2} \cos{(\Theta)} \cos{(k(r_1 - r_2) +
(\phi_1 - \phi_2))}$$

\newpage

Pendant la durée nécessaire à l'observation ou à la détection des trains d'ondes
au point $M$, les champs $\overrightarrow{E_1}$ et $\overrightarrow{E_2}$
prennent toutes les orientations possibles.
En effet, le champ électrique a une orientation fixe pour un train d'onde mais
le temps de détection ou d'observation est bien supérieur à la durée d'un train
d'onde.

Le terme en $\cos{(\Phi_1 - \Phi_2)}$ du champ électrique résultant
$\overrightarrow{E}$ prend toutes les valeurs possibles entre $-1$ et $+1$ car
$(\Phi_1 - \Phi_2)$ présente un déphasage aléatoire d'où une valeur moyenne
nulle. L'intensité lumineuse moyenne en $M$ durant le temps d'observation ou de
détection est donc

\centering
\fbox{
  $I_{moy} = I_{1 moy} + I_{2 moy}$
}

\raggedright L'intensité résultant de la superposition des deux ondes n'est alors que la somme de leurs intensités. On dit alors que les sources sont **incohérentes**. Si les sources présentent un déphasage $(\phi_1 - \phi_2)$ entre les trains d'ondes constants au cours du temps (donc si les sources sont cohérentes) mais également si les champs instantanés $\overrightarrow{E_1}$ et $\overrightarrow{E_2}$ qui varient au cours du temps forment un angle constant entre eux ($\cos{\Theta}$ est une constante) et différent de $\dfrac{\pi}{2}$, alors il y a interférence. $I_{moy} = I_{1 moy} + I_{2 moy} + 2 \sqrt{I_{1 moy} I_{2 moy}} \cos{(\Theta)} \cos{(k(r_1 - r_2) + (\phi_1 - \phi_2))}$ s'appelle le terme d'interférence. On a donc une distribution spatiale de l'intensité indépendante du temps et telle que l'ensemble des points d'égale intensité correspond à $(r_1 - r_2) = \text{ constante}$. Les surfaces ainsi définies sont des **hyperboloïdes**. L'intersection de ces surfaces avec un plan d'observation défini la figure d'interférences avec des franges brillantes correspondantes aux maxima d'intensité et des franges sombres correspondantes aux minima d'intensité. L'intersection des hyperboloïdes avec un plan perpendiculaire à l'axe $(S_1 S_2)$ donne un système de franges circulaires. Leurs intersections avec des plans parallèles à $(S_1 S_2)$ donne des hyperboles qui s'approximent par des portions de droites dans la zone d'observation des interférences. Les interférences entre deux ondes sont possibles si : * elles ont mêmes $\omega \text{ ou } f$ * leur différence de phase instantanée ($\phi_1 - \phi_2$) à l'émission des trains d'ondes reste constante dans le temps $\Rightarrow$ les ondes sont donc cohérentes temporellement (leurs trains d'onde se superposent au point $M$). * leurs champs électriques instantanés bien que prenant toutes les orientations possibles sur une durée suffisante pour l'observation ou la détection font entre eux un angle constant et différent de $\dfrac{\pi}{2}$. La première condition est difficile à obtenir. Les deux suivantes sont impossibles à obtenir si les sources $S_1 \text{ et } S_2$ sont indépendantes. Le phénomène d'interférence n'est donc possible que si les sources $S_1 \text{ et } S_2$ dérivent de la même source primaire. On parle alors de cohérence mutuelle des deux sources. Compte tenue du fait que $(r_1 - r_2)$ est faible dans la zone d'obtention des interférences et que les sources $S_1 \text{ et } S_2$ dérivent de la même source primaire alors $C_1 = C_2$ et donc l'intensité lumineuse moyenne entre les deux ondes est négligeable.

\centering
\fbox{
  $I_{1 moy} = I_{2 moy} = I_{0 moy}$
}

\raggedright
De plus, comme $r_1 \approx r_2$, le point $M$ est suffisamment loin des sources
pour que l'angle $\Theta$ entre les champs électriques instantanés soient
faibles, donc $\cos{(\Theta)} = 1$.

On prend $I = I_{moy}$.

$$I = 2 I_0 + 2 I_0 \cos{(\Phi_1 - \Phi_2)} =
2I_0 (1 + \cos{(\Phi_1 - \Phi_2)})$$

**Relation trigonométrique :** $1 + \cos{(2a)} = 2 \cos^2{(a)}$

\centering
\fbox{
  $I = 4 I_0 \cos^2{(\dfrac{\Phi_1 - \Phi_2}{2})}$
}

\raggedright
\newpage

**On va poser :** $\Phi = \Phi_1 - \Phi_2$

$\Phi$ est une grandeur indépendante du temps donc stationnaire. Compte tenu du
fait que $\phi_1 - \phi_2 = 0$ (car les sources sont mutuellement cohérentes)
on a :
$$\Phi = \dfrac{2\pi}{\lambda}(r_1 - r_2)$$
$$\Phi = \dfrac{2\pi}{\lambda_n}n(r_1 - r_2) \text { avec } \lambda_n =
\lambda_0$$

\centering
\fbox{
  $\Phi = \dfrac{2\pi}{\lambda_0}\delta \text{ avec }\delta
  \text{ : la différence de marche}$
}

\raggedright
Les extrema d'intensité obtenus pour
$I_1 = I_2 = I_0$ est donc $I_{min(r_1 - r_2)} = 0$ et $I_{max} = 4 I_0$

On définit l'ordre d'interférence
$p = \dfrac{\delta}{\lambda_0} = \dfrac{\Phi}{2\pi}$ les points d'égale
intensité lumineuse correspondent donc à $p = \text{constante}$.

De plus $I = I_{max}$ pour $p$ entier et $I = I_{min}$ pour $p$ demi entier.

Le contraste (ou module de la visibilité) des franges d'interférence est défini
par

\centering
\fbox{
  $\gamma = \dfrac{I_{max} - I_{min}}{I_{max} + I_{min}}$
}

\raggedright

# Conclusion

Pour qu'il y ait interférence dans une zone de l'espace, il faut que la longueur
de cohérence temporelle $L_c$ et que la largeur de cohérence spatiale $l_s$
soit suffisante.

Or deux sources lumineuses indépendantes présentent entre
elles des trains d'ondes qui arrivent en un point $M$ avec une différence de
phase aléatoire et l'orientation du champ électrique instantanée de chacune
est également aléatoire. Les sources sont alors incohérentes.
On obtient une intensité lumineuse moyenne en ce point ($M$) qui est la somme
des intensités lumineuses moyenne de chaque onde. Dans ce cas, l'intensité
lumineuse est uniforme puisqu'elle ne présente pas de distribution spatiale
telle qu'on l'obtient avec un phénomène d'interférence.

Pour obtenir des interférences, il faut que les deux sources dérivent de la
même source primaire pour supprimer le caractère aléatoire relatif de
l'émission de train d'ondes entre deux sources indépendantes.

**Les sources sont alors mutuellement cohérentes.**

Pour obtenir des sources mutuellement cohérentes à partir d'une même source
primaire, on peut réaliser une division spatiale de l'onde primaire, c'est la
**division du front d'onde**, on peut également réaliser une division des trains
d'ondes, c'est la **division d'amplitude.**
