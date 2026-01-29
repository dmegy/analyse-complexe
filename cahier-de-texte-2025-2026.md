# analyse-complexe 2025-2026 : Cahier de texte

Cahier de texte de l'année 2025-2026, séance par séance.

<!-- Macros KaTeX / MathJax : -->

$\newcommand\C{\mathbb{C}}\renewcommand{\R}{\mathbb R}$

---

+++ Cours du 2025-01-20 +++

---

## CHAPITRE I : Fonctions holomorphes

### 1) Fonctions de $\C$ vers $\C$

a) Notations : cercle unité, disques, demi-plan etc. $\Omega_\alpha := \mathbb C\setminus e^{i\alpha}\mathbb{R}_-$ Oublié : $\Gamma(z_0,r)$ pour les cercles.

b) Fonctions d'une variable complexe : identifications, fonctions réelle associée

c) Topologie, limites : limite en un point. Exemple de fonction "simple" qui n'a pas de limite en zéro ($|z|/z$). Limite en l'infini, sphère de Riemann, dessin de la projection stéréographique.

d) Comparaison locale : petits o, grands O, équivalents. Oublié : fonction C^\infty qui n'a pas de DL "en z" en zéro.

e) Coordonnées polaires, décomposition polaire, argument à valeurs dans $\R/2\pi\Z$. Autres déterminations de l'argument. Détermination principale de l'argument $\operatorname{Arg}_0$. Notations interdites. Déterminations du logarithme sur le plan privé d'une coupure.

### 2) Holomorphie

a) Définition avec le taux d'accroissement, formes équivalentes avec un DL d'ordre un "en h" ( ou "en $z-z_0$").
Pas fait d'exemples !

b) Similitudes, matrices réelles 2x2 $\C$-linéaires.

c) Lien entre $\C$-dérivabilité et différentiabilité.

Pas encore prononcé "Cauchy-Riemann", pas fait d'exemples de fonctions holomorphes ni de contre-exemples.

---

+++ Cours du 2025-01-27 +++

---

Nombre complexe dérivé. Holomorphie sur un ouvert, notation $\mathcal{O}(U)$ pour la $\C$-algèbre des fonctions holomorphes sur l'ouvert $U$. Fonction dérivée d'une fonction holomorphe. Règles de dérivation : règles usuelles. (Dérivée d'une composée faite en CM, le reste à faire soi-même.)

Exemples : $\C$-dérivabilité de $z\mapsto z^n$. Exponentielle complexe : plus tard, avec les conditions de Cauchy-Riemann, section suivante. Log complexe : encore après, en polaires.

Biholomorphismes, exemples, petits exos à faire.

### 3) Cauchy-RIemann, Compléments calcul diff, similitudes directes etc.

Rappels/compléments sur les fonctions $\R$-linéaires de $\C$ dans $\C$. Décomposition comme somme de partie $\C$-linéaire et partie $\C$-antilinéaire, ou encore : décomposition comme somme d'une similitude directe et d'une similitude indirecte. Notation omise en CM mais utilisé dans la feuille de TD : $M = M^+ + M^-$ pour une matrice, $\phi = \phi^+ + \phi^-$ pour une application. Avertissement : notations non standard, dans les livres de géométrie complexe niveau (M1 ou ) M2, ça sera $f = f^{1,0}+f^{0,1}$.

Conditions de Cauchy-Riemann.

Diverses reformulations des conditions de Cauchy-Riemann.

### 4) Opérateurs de Wirtinger ($\frac{\partial}{\partial z}$ et $\frac{\partial}{\partial \overline z}$).

- Idée générale et cahier des charges partiel: on veut entre autres $\frac{\partial}{\partial z}(z)=1$, $\frac{\partial}{\partial z}(\overline z)=0$ et $\frac{\partial}{\partial \overline z}(z)=0$, $\frac{\partial}{\partial \overline z}(\overline z)=1$.
- Définitions mauvaises (bien que pouvant sembler naturelles).
- Définition
- Vérification du cahier des charges, exemples fondamentaux. Règles de dérivation de base (somme, produit) admises. Preuve de la règle de dérivation d'une composée en utilisant la décomposition $Df = Df^+ + Df^-$.
- Reformulation : $\frac{\partial f}{\partial z}$ et $\frac{\partial f}{\partial \overline z}$ sont les (nombres complexes correspondant aux) parties $\C$-linéaires et $\C$-antilinéaires de $Df$.

> Pas vu en cours mais fait en TD et remarque fondamentale : une matrice $\begin{pmatrix}a & -b \\b & a\end{pmatrix}$ est nulle ou inversible, auquel cas l'inverse est également une similitude directe. La somme et le produit de deux matrices de cette forme est toujours de cette forme. Reformulation : les matrices de la forme $\begin{pmatrix}a & -b \\b & a\end{pmatrix}$ forment une sous-$\R$-algèbre de $M_2(\R)$. Cette sous-$\R$-algèbre est isomorhe à $(\C,+,\times)$. Dans certains ouvrages, ceci est la _définition_ de $\C$.)

Reformulation des conditions de Cauchy-Riemann en un point comme $\frac{\partial f}{\partial \overline z}(z_0) = 0$.

---

+++ Cours du 2025-02-03 +++

---

## Chapitre II : intégration curviligne

### 1) Intégrale de fonctions de variable réelle à valeurs complexes

définition, Chasles, inégalité triangulaire etc.

### 2) Chemins du plan

### 3) Formes différentielles

### 4) Intégration de formes différentielles. Primitives

### 5) Théorème de Goursat, théorème intégral de Cauchy
