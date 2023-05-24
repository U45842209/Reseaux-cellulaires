#Réseaux cellulaires

AMPS (1G) : 1980 - Voix

GSM (2G) : 1990 - Voix et Data (Message)

UMTS (3G) : 2000 - Voix et Data (Message et photo)

LTE (3~4G) : 2010 - Voix et Data (Message, photo et vidéo)

5G : 2020 - Tout est possible

6G : 2030 - ?

*cartoradio.fr*

[Atoll]: https://www.teleres.com.au/products/network-planning-design/atoll/	"Logiciel de mapping de fréquence pro"



## AMPS

Fréquence : 850Mhz

Norme analogique FDMA (Frequency Division Multiple Access)

Une antenne est composée de : Une antenne et d'un BTS (modulation, démodulation, multiplexage, etc)

## Organisation du réseau cellulaire

Utilisez plusieurs émetteurs de faible puissance (100W)

### Pourquoi pas une grande zone de service ?

- Le nombre d'utilisateur serait limité
- le mobile doit avoir une plus grande puissance exigée

10 à 50 fréquences utilisées par cellule

![Mobile Communications - GSM (Les caractéristiques de l'interface Air) -  Karim El-Khazen](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-veKAUzorJdTb21dMXpN_j8Gt5Ki7g-Jfsz0jSOT3jpV6KwC-lVaoUbQxuus7ijuVTew&usqp=CAU)

R = Rayon d'une cellule

d = Distance entre les centres des cellules adjacentes

- d = R*Racine(3)

D = Distance minimale

N = Nombre de cellule dans un motif répétitif (chaque cellule utilise une géométrie hexagonal unique)
$$
N = I²+J²+(I*J)
$$

### Capacité de cellule

Nombre d'utilisateur :
$$
n = (W/B)*(m/N)
$$
avec :

- W = largeur de bande passante
- B = bande passante nécessaire par utilisateur
- N = facteur de réutilisation spectrale

​           = nombre de cellule par cluster

- m = nombre total de cellules

### Example :

- Rayon d'une cellule = 1.6 Km
- Nb Cellule = 32
- Nb canaux = 336
- N = 7

1) Calculer la surface de couverture de chaque cellule ?

Surface = 2.6*R²

= 6.656Km²

2. Quelle est la couverture totale de cette zone ?

Surface*Nombre de cellule = 213Km²

3. Donner le nombre de canaux par cellule ?

Nb canaux/N = 48

48/Nb Cellule = 1.5 canaux par cellule

4. Quelle est la capacité totale ?

Nb Cellule*Nb Canaux par cellule

## Topologie Réseaux Cellulaire

![img](https://lafibre.info/images/3g/201210_architecture_reseau_mobile_orange.jpg)

[Topologie]: https://www.technologuepro.com/gsm/chapitre_2_GSM.htm


