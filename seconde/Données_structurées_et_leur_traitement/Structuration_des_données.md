### Structuration des données

#### I. Définitions 

a) Dans un carnet d'adresse, pour chaque personne, on renseigne le prénom, le nom, la ville... Il est possible de visualiser le carnet sous la forme d'un tableau :

| Prénom |	Nom | Ville |
| :---: | :---: | :---: |
| Jean | Némare | Toulouse |
| Anne | Ammare | Tour |

1) Quel est le nom de famille de Jean ? ...............

2) Dans quelle ville habite Mme Ammare ? ...............

b) Compléter les définitions ci-dessous à l'aide des mots suivants :

`ensemble de données`, `fichiers`, `tableur`, `attributs`, `CSV`, `open data`, `enregistrement`, `collection`

1) Un ................ que l'on peut représenter sur la forme d'un tableau s'appelle une ...................... Exemple : le carnet d'adresses est une collection.

2) Les intitulés des informations d'une collection s'appellent les .............. Exemple : Prénom, Nom et ville sont tous les trois des attributs.

3) Chaque ligne du tableau qui représente une collection s'appelle un ............... Exemple : Jean Némare et Anne Ammare sont des enregistrements.

4) Les collections sont aujourd'hui stockées dans des ............., il y a par exemple les fichiers texte de type ..... (pour *Coma Seperated-Values* en anglais) où les données sont séparées par des virgules.

5) Un ............ est un outil numérique permettant d'ouvrir les fichiers textes de données sous forme de tableau.

6) Les données ouvertes (ou .............. en anglais), sont des données numériques dont l'accès et l'usage sont libres. Ces données sont principalement mises à disposition par des institutions publiques.

#### II. Format de fichiers

1) Fichiers CSV

Dans le format *CSV* (*Comma-separated values*), les données sont enregistrées sous la forme d'une unique collection. Chaque ligne est un enregistrement. Les valeurs des attributs sont séparées par des ",". La première ligne est en général réservée aux noms des attributs.

Écrire ce que contiendrait le fichier `carnet_d_adresse.csv` représentant les données du carnet d'adresse :

........................................
........................................
........................................

2) Fichiers JSON

Dans le format *JSON* (*JavaScript Object Notation*), les données sont sous forme de listes avec des étiquettes. Le format JSON permet des structures plus complexes que la simple collection.

Exemple :

```python
[
  {
    "nom": "Gérard",
    "ville": "Paris"
  },
  {
    "nom": "Marie",
    "ville": "Toulouse"
  }
]
```

Dessiner le tableau de données correspondant aux données écrites d'après l'exemple ci-dessus :

#### III. Repères historiques

a) En cherchant les informations sur Internet (sur votre téléphone portable), relier ci-dessous les dates avec leur évènement.

| --------------Date---------------- | ---------------Évènement----------------- |
| :------ | ------: |
| **1956 -** | **- Premier support de stockage : cartes perforées** |
| **1970 -** | **- Open Government Initiative du président Obama**|
| **2013 -** | **- Invention du modèle relationnel**|
| **XXe siècle -** | **- Création du premier tableur, VisiCalc** |
| **1979 -** | **- Invention du disque dur** |
| **2009 -** | **- Charte du G8 pour l’ouverture des données publiques** |

#### IV. Enjeux des données ouvertes publiques

Document :

```
L'ouverture des données publiques consiste à mettre à disposition des citoyens, des chercheurs, des entreprises, les données numériques que les collectivités produisent dans leur activité quotidienne.

Ces données concernent des domaines variés :
    - informations géographiques,
    - statistiques sociales, démographiques,
    - localisation de services,
    - textes réglementaires,
    - études, mesures,
    - informations sur les transports,
    - annuaires divers, etc.

Le mouvement de l'open data a été initié dans les années 2000. La société civile, quelques gouvernements et quelques administrations ont peu à peu défini les critères caractérisant les données ouvertes.

Les données ouvertes doivent être :
    - disponibles par défaut : elles doivent être publiée sans qu'il soit besoin de le demander
    - récentes, complètes et à la source : elles doivent être disponibles dès qu'elles sont produites et sans prétraitement
    - accessibles : elles doivent être utilisables par tous les usagers potentiels
    - dans des formats standards et ouverts, avec des licences ouvertes

Actuellement, en France comme dans de nombreux pays, l'ouverture des données publiques constitue une contrainte légale.

    - 2005 : Transcription en droit français d'une directive européenne sur les conditions de réutilisation des informations du secteur public.
    - 2011 : Publication d'un décret posant le principe de la gratuité du droit à la réutilisation des documents et données publiques.
    - 2016 : Loi sur la transition énergétique qui impose la mise à disposition d'un certain nombre de données.

De nombreux avantages sont attendus du développement des données ouvertes.

Pour les citoyens et la démocratie : La participation citoyenne aux débats sociétaux nécessite une transparence des pouvoirs publics. Les administrés peuvent ainsi examiner des faits, développer des opinions et analyser les choix politiques de façon éclairée. Ils peuvent par ailleurs être force de proposition et participer au développement de solutions créatives.

Pour les pouvoirs publics : L'ouverture des données participe à l'amélioration de la qualité des services et renforce leur légitimité. Elle permet, par ailleurs, une ouverture accrue et incite à l'interopérabilité, voire à la coopération.

Pour l'économie : Les bénéfices économiques résident, non seulement dans les nouvelles solutions qui peuvent émerger de la mise à disposition des données, mais également dans l'amélioration de l'efficacité des services.
```

1) Lire le texte ci-dessus.

2) Repérer les quatre parties du texte et donner un titre à chacune d'elles.
