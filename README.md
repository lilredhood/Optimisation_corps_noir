# Optimisation_corps_noir
Projet d'optimisation de l'émittance monochromatique maximale d'un corps noir.

On se propose d'étudier l'énergie rayonnante d'un corps noir dans un intervalle d'émission $[\lambda, \lambda + d\lambda]$. On l'appelle aussi émittance monochromatique maximale du corps noir (en $Wb/m^2$) et elle est donnée par la loi de Planck : \\
$M(\lambda) = \dfrac{2 \pi h C_0^2}{n^2\lambda^5}. \dfrac{1}{\exp\big(\frac{h C_0}{n k T \lambda}\big) - 1}$ \\

où : 

*   $C_0$ est la vitesse de la lumière dans le vide. ($m.s^{-1}$).
* $h$ : constante de Planck ($J.s$).
* $k$ : constante de Boltzmann ($J.K^{-1}$).
* $\lambda$ : longueur d'onde ($m$).
* $T$ : température absolue de la surface du corps noir ($K$).
* $n$ : indice de réfraction du milieu (ici le vide).

On souhaite trouver la valeur $\lambda^*$ qui maximise l'émittance monochromatique pour une température de surface $T$ donnée. Pour s'y faire, la méthode de la section dorée sera utilisée (https://en.wikipedia.org/wiki/Golden-section_search).

De plus, dans ce projet, les lois de Wien seront vérifiés :
* $\lambda^* T = A$
* $M(\lambda^*) = B.T^5$. 
