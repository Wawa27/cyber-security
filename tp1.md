# Étape 1 : Effectuez des recherches sur les cyberattaques de haut niveau.

### Faille de sécurité chez Home Depot

En septembre 2014, Home Depot subit une attaque pour cause d'un logiciel malveillant intégré dans les systèmes de
paiements, qui a pour cause plus de 53 millions d'adresses mails volés ainsi que 56 millions de cartes de crédit.

Sources:

- [Bsi group](https://www.bsigroup.com/LocalFiles/en-US/Case-Studies/bsi-lessons-learned-home-depot.pdf)
- [Bank info security](https://www.bankinfosecurity.com/examining-home-depot-breach-a-7339)

### Faille ciblant les cartes bancaires Target

Similaire à l'attaque visant Home Depot, 120 millions de données personnelles ou bancaires ont été dérobées de Target
par un logiciel malveillant visant des caisses enregistreuses entre le 27 novembre et le 15 décembre.

Sources:

- [Le monde informatique](https://www.lemondeinformatique.fr/actualites/lire-110-millions-clients-de-target-braques-par-un-malware-56253.html)
- [Bank info security](https://www.bankinfosecurity.com/target-breach-what-happened-a-6312)

### Virus Stuxnet

En 2010, un ver informatique qui aurait été conçu par la NSA (et l'unité israélienne 8200) afin de s'attaquer aux
centrifugeuses iraniennes d'enrichissement d'uranium, a été découvert, le ver aurait affecté 45 000 systèmes
informatiques. Ce ver serait composé de 4 attaques zero day mais aussi grâce au ver Conficker, il vise un certain type
de système utilisant les logiciels SCADA, WinCC ou PCS 7, développé par Siemens.

Sources:

- [Wikipedia](https://fr.wikipedia.org/wiki/Stuxnet)
- [France 24](https://www.france24.com/fr/20141121-stuxnet-virus-patient-zero-kaspersky-lab-iran-enquete-nucleaire-foolad)

### Attaque de Sony Pictures Entertainment

Un groupe d’hackers, nommé Gardiens de la paix (Guardians of Peace), ont volé, en fin novembre 2014, une grosse quantité
d'informations provenant du réseau de Sony. Les gardiens de la paix ont menacé avec les informations volées Sony
d'annuler le film comédie The Interview, une comédie à propos de 2 américains assassinant le leader de la Corée du Nord,
Kim Jong Un.

Sources:

- [Vox](https://www.vox.com/2015/1/20/18089084/sony-hack-north-korea)
- [Wikipedia](https://fr.wikipedia.org/wiki/Piratage_de_Sony_Pictures_Entertainment)

# Étape 2 : Faites l'analyse à l'écrit d'une cyberattaque (Virus Stuxnet)

### a. Qui étaient les victimes de l'attaque ?

La cible des créateurs du ver était l'état iranien, néanmoins, le ver a été trouvé sur plusieurs systèmes dans d'autres
pays comme l'Allemagne, la france, l'Inde, et l'Indonésie.

### b. Quels outils et technologies ont-ils été utilisés lors de l'attaque ?

Le ver a été conçu en plusieurs langages de programmation différents, comme notamment le C, ou le C++.

### c. Quand l'attaque a-t-elle eu lieu sur le réseau ?

Le virus est probablement inoculé par la mise à jour d'un virus déjà installé sur les ordinateurs cibles ; il contamine
ensuite d’autres ordinateurs WinCC du réseau à l’aide d’autres exploits.

### d. Quels systèmes ont-ils été ciblés ?

Le ver comportent 3 différentes couches qui attaquent 3 systèmes différents :

- L'OS Windows
- Les logiciels Siemens: PCS 7, Win CC, et STEP7
- Un ou plusieurs automates programmables industriels (API) Siemens S7

### e. Quel était le mobile des hackers au cours de cette attaque ? Quel était leur but ?

Le mobile ou le but des hackers ne sont pas avérés, il y a eu néanmoins plusieurs suppositions, notamment celle de
Symantec et de Langner Communications, qui affirme que le ver visait les systèmes de contrôle des turbines à vapeur,
(ceux utilisées à la centrale nucléaire de Bouchehr)

### f. Quelles ont été les conséquences de l'attaque ? (données volées, rançon, systèmes endommagés, etc.)

Les conséquences du ver est la dégradation des centrifugeuses de la centrales nucléaires, ainsi qu'à des explosions. La
Russie a déclaré que ce projet aurait pu aboutir à une catastrophe plus grande que celle de Tchernobyl.
