![](/links/Eracom_Typotheque_Graphics_v4_alt_2.jpg)

<style>
/* Collapsible H1-style drawers (kramdown / GitHub Pages) */
/* Hide empty TOC anchors like <a id="-terminologie"></a> to avoid extra whitespace */
  a[id]:not([href]) {
    display: block !important;
    height: 0 !important;
    overflow: hidden !important;
    margin: 0 !important;
    padding: 0 !important;
  }
details.drawer {
  margin: 0 0 1.5rem 0;
}

details.drawer > summary {
  list-style: none;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: space-between;

  /* Mimic markdown H1 */
  font-size: 2em;
  font-weight: 600;
  line-height: 1.25;
  margin-top: 24px;
  margin-bottom: 0px;
  padding-bottom: 0.3em;
  border-bottom: 1px solid #eaecef;
}

/* Hide native marker */
details.drawer > summary::-webkit-details-marker { display: none; }
details.drawer > summary::marker { content: ""; }

/* Custom right-aligned triangle */
details.drawer > summary::after {
  content: "▸";
  flex: 0 0 auto;
  margin-left: 1rem;
  transform: rotate(0deg);
  transition: transform 160ms ease;
}

details.drawer[open] > summary::after {
  transform: rotate(90deg);
}
</style>
<script>
(function () {
  function openDrawerFromHash() {
    var hash = window.location.hash;
    if (!hash || hash.length < 2) return;

    var id = decodeURIComponent(hash.slice(1));
    var target = document.getElementById(id);
    if (!target) return;

    // Find the drawer to open: either the next <details> after an anchor,
    // or the closest <details> ancestor if the target is inside.
    var details = null;
    if (target.tagName && target.tagName.toLowerCase() === 'a') {
      var next = target.nextElementSibling;
      if (next && next.tagName && next.tagName.toLowerCase() === 'details') details = next;
    }
    if (!details) details = target.closest ? target.closest('details.drawer') : null;
    if (!details) return;

    // Close all drawers, then open the target one
    document.querySelectorAll('details.drawer').forEach(function (d) {
      d.removeAttribute('open');
    });
    details.setAttribute('open', '');

    // Scroll to the drawer header
    var summary = details.querySelector('summary');
    if (summary && summary.scrollIntoView) {
      requestAnimationFrame(function () {
        summary.scrollIntoView({ block: 'start' });
      });
    }
  }

  window.addEventListener('hashchange', openDrawerFromHash);
  window.addEventListener('DOMContentLoaded', openDrawerFromHash);
})();
</script>

<!-- # 📋 Table des matières

- [Terminologie](#-terminologie)
- [Charte d’utilisation](#-charte-dutilisation)
- [Classification](#%EF%B8%8F-classification)
- [Typologie](#-typologie)
- [Formats](#-formats)
- [Licenses](#-licenses)
- [Installation](#%EF%B8%8F-installation-check-in)
- [Usage desktop](#-usage-desktop)
- [Usage web](#-usage-web)
- [Assemblage](#-assemblage)
- [Suppression](#-suppression-check-out)
- [Tags](#%EF%B8%8F-tags)
- [Catalogue](#-catalogue)
- [Sources](#-sources) -->

# ☎️ [Support](mailto:typo.eracom@eduvaud.ch)

# 🔍 [Spécimens](https://fontes.eracom.ch)

<a id="-terminologie"></a>
<details class="drawer" markdown="1">
<summary>🌐 Terminologie</summary>

|![](/links/Eracom_Typotheque_Graphics_v5_terminology.gif)                  |
|:---:|
| Terminologie |

### Typothèque
Une typothèque est une collection organisée de **polices**.
### Police
Une police désigne un **ensemble de fontes** (un dossier de fontes) qui partagent une identité commune (« le même squelette »). Une police inclut toutes les variations possibles (gras, italique, etc.) d’une même **famille** de fontes.
### Fonte
Une fonte désigne **l’ensemble des glyphes** (contenu dans un fichier) correspondant aux mêmes caractéristiques (de style) au sein d’une même police (on peut aussi parler d’un caractère). Par exemple, la police « Times », inclut notamment les fontes « Times Regular », « Times Bold », ou « Times Italic ».
### Glyphe
Un glyphe est **un signe typographique** (un symbole). Cela peut inclure non seulement les lettres et les chiffres, mais aussi les accents, les ligatures (comme « fi » ou « fl »), et d’autres symboles.
### Script
Un scripts fait référence à **un système d’écriture** (une langue) que l’on peut utiliser avec une certaine police **en fonction des glyphes** présents au sein de celle-ci (on parle alors de son « jeu de caractères »). Par exemple, une police peut prendre en charge plusieurs scripts, comme le latin, le cyrillique, l’arabe ou le chinois.

</details>

<a id="-charte-dutilisation"></a>
<details class="drawer" markdown="1">
<summary>📝 Charte</summary>
## ↪️ Téléchargez, imprimez et signez [la charte](links/Eracom_Charte_Typotheque_v2_0.pdf).
## 🔁 Envoyez un scan de la charte signée [ici](mailto:secretariat.eracom@vd.ch?subject=Charte%20Typoth&egrave;que).

![](/links/Eracom_Typotheque_Graphics_v42.jpg)

La présente charte définit **les droits et les obligations** des utilisateur.trice.s de la typothèque de l’Ecole Romande d’Arts et Communication (Eracom). Elle s’applique à l’ensemble des utilisateur.trice.s.

### 📖 Définitions
- Par la mention typothèque de l’Eracom, on entend **toutes les fontes** mises à disposition des utilisateur.trice.s. par l’Eracom.
- Une fonte est définie comme un ensemble de glyphes représentant les caractères d’un alphabet contenu dans **un fichier digital** (OTF, PS, TTF, WOFF, WOFF2, EOT, SVG, etc.).  Elle possède à la fois un **statut de design** (œuvre) et **de logiciel** (programme informatique). À ce titre, les fontes sont protégées simultanément par le **droit d’auteur** et le **droit des logiciels**.
- Par utilisateur.trice, on entend l’ensemble des membres du personnel administratif et technique, les membres du corps enseignant, les étudiant.e.s de l’école ainsi que **toute personne** à qui la Direction de l’École accorde un accès à la typothèque de l’Eracom.

### ✅ Droits
- Chaque utilisateur.trice a le droit d’utiliser les fontes de la typothèque. Toutefois, ce droit est **limité exclusivement aux projets réalisés dans le cadre académique** et n’inclut donc en aucun cas des projets personnels ou des mandats externes à l’école.

### ⛔️ Restrictions
- Le **stockage** des fontes sur des serveurs partagés tels que les serveurs de l’école, Teams, OneDrive, Dropbox, GoogleDrive, etc. est interdit.
- La **diffusion** des fontes est interdite, même au sein de l’école : par exemple se transmettre des fontes entre élèves ou collègues via courriel, messagerie instantanée, Airdrop, WeTransfer, etc.
- La **modification** des fontes est interdite : par exemple renommer une fonte, modifier ses tracés, son character-set, ses fonctionnalités opentype, son code, ou la convertir dans un autre format.
- La **copie** des fontes est interdite : par exemple copier/coller des tracés ou une quelconque partie du logiciel.

### ☝🏻 Obligations
- La **suppression** de toutes les fontes de la Typothèque par l’utilisateur.trice à la fin ou en cas d’interuption de son cursus est obligatoire.

### 🚨 Violation
Une violation des principes énoncés ci-dessus peut entraîner le **retrait de l’accès aux ressources**. En outre, les abus seront **dénoncés aux autorités** académiques et/ou administratives compétentes en vue de **sanctions disciplinaires**. Sont réservés le remboursement des frais résultant de l’utilisation abusive et de l’identification de son auteur, ainsi que l’ouverture d’éventuelles poursuites judiciaires.

![](http://eracom-typotheque.github.io/links/graphics/Eracom_Typotheque_Graphics4.jpg)

</details>

<a id="-classification"></a>
<details class="drawer" markdown="1">
<summary>🗂️ Classification</summary>

Dans le cadre des activités professionnelles des graphistes, un système de classification se révèle utile pour identifier, **sélectionner et combiner** les polices de caractères ainsi que **justifier** leur usage en fonction du contexte (sémiotique).

### Historique
La classification selon le **«principe historique»[^1]** (classification Vox adaptée) est une méthode de **classification pédagogique** des polices de caractères qui permet de répartir toutes les polices dans ordre chronologique lié à **l’histoire de l’écriture et l’évolution des technologies**.

![](/links/Eracom_Typotheque_Graphics_v47.jpg)

|![](/links/Eracom_Typotheque_Graphics_v48.jpg)                  |
|:---:|
| Classification historique |

1. **Incises**  
   *Gravure dans la pierre*
2. **Scriptes**  
   *Calligraphie (ductus)*  
   1. Onciales  
   2. Fractures  
   3. Cursives  
3. **Sérifs**  
   *Impression à caractères mobiles*  
   1. Humanes  
   2. Garaldes  
   3. Réales  
   4. Didones  
4. **Slab-Sérifs**  
   *Composition à chaud*  
   1. Mécanes  
   2. Monospaces  
6. **Sans-Sérifs**  
   *Composition à froid (photo-composition)*  
    1. Grotesques  
    2. Humanistes  
    3. Géométriques  
8. **Expressives**  
   *Composition en grands corps (aussi décoratives)*
9. **Hybrides**  
   *Variations de contrastes et de terminaisons au sein d’une même police*
10. **Non-Latines**  
   *Composition digitale (symboles: ornements (Dingbats) & mathématiques (Pi))*

[^1]: Illustration tirée du livre *Type, Sign, Symbol* de Adrian Frutiger (1980).

### Formelle
La classification selon le **«principe de forme»[^2]** (classification Kupferschmid adaptée) est une méthode de **classification fonctionnelle** des polices de caractères qui permet de répartir toutes les polices selon un système cohérent basé sur 3 paramètres.

![](/links/Eracom_Typotheque_Graphics_v49.jpg)

|![](/links/Eracom_Typotheque_Graphics_v410.jpg)                  |
|:---:|
| Classification formelle |

1. **Squelette**
   -  Dynamique  
      Plume à bec large (translation)  
      Axe diagonal + extrémités ouvertes  
      Voc. sémiotique: *convivial, ouvert, accessible, flexible, naturel, démocratique, chaleureux, accueillant, personnel, intemporel*
   -  Statique  
      Plume à bec pointu (expansion)  
      Axe vertical + extrémités fermées  
      Voc. sémiotique: *rationnel, ordonné, réservé, noble, élégant, sérieux, rigide, correct, rigoureux, autoritaire*
   -  Géométrique  
      Plume à bec rond (linéaire)  
      Construction modulaire  
      Voc. sémiotique: *géométrique, simple, technique, moderne, fonctionnel, informel, systématique, sobre, construit, épuré*
2. **Graisse**
   -  Contrasté (avec)
   -  Linéaire (sans)
3. **Enveloppe**
   -  Avec (empattements)
   -  Sans (empattement)

[^2]: Illustration tirée du livre *Le trait. Une théorie de l’écriture* de Gerrit Noordzij (2010) + ajout du principe géométrique basé sur le système de classification de Indra Kupferschmid.

|![](/links/Pair_Fonts.gif)                  |
|:---:|
| Créer des paires de fontes avec la matrice de classification |
  
### Choisir des fontes, combiner des fontes

En se basant sur la classification formelle de Indra Kupferschmid, on peut faire les remarques suivantes concernant les combinaisons:

- Les fontes du même modèle s’accordent bien
- Les fontes de modèles différents qui partagent le même contraste et les mêmes terminaisons ne s’accordent pas bien
- Les fontes de modèles différents s’accordent bien seulement si elles sont éloignées dans le tableau (plus qu’une colonne d’écart)

Ce système est un point de départ, il n’y a pas de règles absolues en matière de design. Il est nécesaire d’affiner les combinaisons en prenant en compte le contexte de votre projet, notamment les points suivants:

- la concordance des proportions (hauteur de x, hauteur des capitales)
- les hiérarchies
- les corps
- les graisses
- les styles
- les character-sets
- etc.
  
</details>

<a id="-typologie"></a>
<details class="drawer" markdown="1">
<summary>🧬 Typologie</summary>

![](/links/Eracom_Typotheque_Graphics_v45.jpg)

### Revival Classique
Cette catégorie inclut les **digitalisations des fontes classiques** de l’histoire de la typographie, qui datent d’**avant l’ère digitale**. La digitalisation fait référence au processus de conversion d’une police de caractères physique (par exemple, une police dessinée à la main ou gravée) en un format numérique. Ce processus implique la numérisation de dessins existants et leur **conversion en courbes vectorielles**, ce qui permet une mise à l’échelle sans perte de qualité.

### Revival Moderne
Cette catégorie inclut les **fontes contemporaines** qui ont été conçues **à partir du début du XXIe siècle**. Ces fontes résultent soit d’une réinterprétation d’un classique, soit d’un design original. La réinterprétation d’une police de caractères consiste à créer une nouvelle version d’une fonte existante en introduisant différentes altérations de design dans le but de l’adapter à un contexte spécifique. Cela peut inclure des modifications dans la forme des glyphes, la graisse, le contraste, l’espacement ou même le character-set.

</details>

<a id="-formats"></a>
<details class="drawer" markdown="1">
<summary>📄 Formats</summary>

|![](/links/Eracom_Typotheque_Graphics_v421.jpg)                  |
|:---:|
| Formats |

### Desktop
OTF, TTF

Les polices destinées à un usage desktop sont installées localement sur l’ordinateur d’un utilisateur et utilisées dans des logiciels comme les **applications de traitements de texte** (Word, Pages,…) et de mise en page (InDesign, Illustrator,…).

### Web
WOFF, WOFF2, EOT

Les polices destinées à un usage web sont compressées pour être utilisées directement **sur des sites internet** grâce à des langages comme le HTML et le CSS. Elles sont hébergées sur un serveur et chargées par le navigateur des utilisateurs lorsqu’ils visitent une page web.

### Variable
OTF, TTF, WOFF, WOFF2

Les polices variables sont une nouvelle technologie qui permet d’inclure **plusieurs styles (par ex., graisse, largeur, angle, etc.) dans un seul fichier de police**. Cela permet aux designers de créer des variations infinies entre des styles définis sans avoir à installer plusieurs fichiers de police distincts. Ce format de police peut être utilisé pour de la mise en page, du développement web ou encore de l’animation vidéo.

</details>

<a id="-licenses"></a>
<details class="drawer" markdown="1">
<summary>🔗 Licenses</summary>

Le type de license est toujours spécifié et précisé dans **l’EULA (End User License Agreement)**. C’est un contrat qui définit les conditions d’utilisation des police par l’utilisateur.rice final. Il précise ce que l’utilisateur est **autorisé** à faire (comme installer la police sur un nombre limité d’ordinateurs, l’utiliser pour des projets imprimés ou web) et ce qui est **interdit** (comme redistribuer, modifier, ou copier les polices).

### Propriétaire
Une licence propriétaire est un contrat qui accorde à l’utilisateur.rice le **droit d’utiliser une fonte, mais sans en posséder le code source ou les droits de modification et de redistribution**. Les restrictions sont souvent strictes: l’utilisateur.rice ne peut pas copier, modifier, ni partager le produit sans autorisation explicite.

### Libre
Une licence libre (open-source) **permet généralement à l’utilisateur.rice d’utiliser, copier, modifier et redistribuer une fonte, souvent de manière gratuite et sans restriction**. Elle garantit l’accès au code source et la liberté de l’adapter selon les besoins. Néamoins, il est toujours nécessaire d’aller vérifier ce qui est autorisé dans le contrat de license.

</details>

<a id="-installation-check-in"></a>
<details class="drawer" markdown="1">
<summary>⚙️ Installation</summary>

## ⚠️ Les fichiers sont distribués seulement lorsque l’ensemble de la classe a signé la charte.
## ⚠️ Assurez-vous de supprimer tous les fichiers sources issus d’une installation précédente.

<!-- ### Livre des polices

Afin de pouvoir utiliser les fontes de la typothèque, il est nécessaire d’installer un logiciel de gestion des fontes. Un tel outil permet notamment:
- installer des fontes disponibles pour toutes les applications
- activer et désactiver les fontes selon les besoins (pour ne pas surcharger le système)
- organiser et trier les fontes et polices selon des critères
- visualiser, examiner et comparer les fontes facilement dans le but de faire une sélection
- gérer et assurer un suivi de licences (notamment vérifier la conformité entre l’utilisation d’une fonte et sa license)
- détecter et corriger tout type de problème (par ex. fontes manquantes, fichiers de fontes corrompus, doublons, etc.)

1. Créer les 9 collections suivantes

```
1. Incises
2. Scriptes
3. Sérifs
4. Slab-Sérifs
5. Sans-Sérifs
6. Expressives
7. Hybrides
8. Non-Latines
```

2. Glisser le dossier de fontes correspondant sur chaque collection
3. Pour chaque collection, sélectionner toutes les fontes (⌘ + A) > Désactiver

|![](/links/1_Install.gif)                  |
|:---:|
| Installation |

![](/links/Eracom_Typotheque_Graphics_v43.jpg)

</details>

<a id="-usage-desktop"></a>
<details class="drawer" markdown="1">
<summary>👩🏼‍💻 Usage Desktop</summary>

### Choisir une fonte

1. Éditer le mot d’aperçu
2. Scroller à travers les différentes fontes

|![](/links/2_Preview.gif)                  |
|:---:|
| Choisir une fonte |

### Afficher les glyphes

1. Affichage en mode exemple
2. Affichage en mode échantillon > Sélectionner un glyphe

|![](/links/3_Preview_Glyphs.gif)                  |
|:---:|
| Afficher les glyphes |

### Afficher les informations

1. Dans le panneau latéral de droite, ouvrir / fermer les différents menus déroulants
   - Description
   - Langues
   - Identifiants
   - Utilisation
   - Détails

|![](/links/4_Informations.gif)                  |
|:---:|
| Afficher les informations |

### Activer une fonte

1. Choisir une fonte
2. Clic droit > Activer le style

|![](/links/5_Activate.gif)                  |
|:---:|
| Activer une fonte | -->

### Télécharger

1. Signer la charte de la [charte d’utilisation](#-charte-dutilisation)
2. Une fois votre signature validée, vous recevrez un accès OneDrive au dossier complet de la typothèque (.zip)
3. Télécharger et décompresser le dossier
4. Placer le dossier à la racine de votre dossier Eracom

### Prévisualiser

## ⬇️ Téléchargez [Font Goggles](https://fontgoggles.org).

1. Choisir un dossier de polices (contenant des fichiers fontes directement, ‼️ sans sous-dossier)
2. Glisser le dossier dans de polices Font Goggles (vous pouvez en glisser plusieurs)
3. Enregistrer le fichier de prévisualisation Font Goggles dans votre arborescence de projet

|![](/links/Font_Goggles.png)                  |
|:---:|
| Prévisualisation dans Font Goggles |

### Activer

1. Une fois la / les familles de polices sélectionnées dans Font Goggles
2. Dossier > Clic droit > Dupliquer
3. Déplacer le/les dossiers dupliqués dans le dossier *Fonts* de Adobe
4. Les polices sont immédiatement disponibles dans toutes les applications de la Suite Adobe
5. Quand vous ne les utilisez plus, supprimez simplement les dossiers de polices du dossier *Fonts* de Adobe (‼️ mais garder les originaux dans le dossier typothèque jusqu'à la fin du cursus)

```
Macintosh HD > Library > Application Support > Adobe > Fonts
```

## ➡️ Gardez un signet dans le finder de l'emplacement de ce dossier

|![](/links/Adobe_Fonts_Folder.png)                  |
|:---:|
| Dossier Fonts de Adobe |

### Informations complémentaires grâce aux tags

1. Choisir une fonte
2. Clic droit > Afficher dans le finder
3. Fichier > Afficher les informations (⌘ + I)

<!-- |![](/links/6_Tags.gif)                  |
|:---:|
| Afficher les tags d’une fonte | -->

|![](/links/7_Tags_Filter.gif)                  |
|:---:|
| Filtrer les fichiers de fontes grâce aux tags |

</details>

<a id="-usage-web"></a>
<details class="drawer" markdown="1">
<summary>🌐 Webfont</summary>

Remplacer *MyFont* par le nom de votre fichier.

### Déclarer une fonte

```
@font-face {
  font-family: 'MyFont';
  src: url('MyFont.woff2') format('woff2’);
}
```

### Utiliser une fonte

```
body {
  font-family: 'MyFont', Fallback, sans-serif;
}
```

### Fonctionnalités opentype

```
/* synthax */
.class {
  font-variant-ligatures: common-ligatures;
  -moz-font-feature-settings: "liga", "clig";
  -webkit-font-feature-settings: "liga", "clig";
  font-feature-settings: "liga", "clig";
}
```
```
/* use small-cap alternate glyphs */
.small-caps {
  font-feature-settings: "smcp" on;
}

/* convert both upper and lowercase to small caps (affects punctuation also) */
.all-small-caps {
  font-feature-settings: "c2sc", "smcp";
}

/* use zeros with a slash through them to differentiate from "O" */
.nice-zero {
  font-feature-settings: "zero";
}

/* enable historical forms */
.historical {
  font-feature-settings: "hist";
}

/* disable common ligatures, usually on by default */
.no-ligatures {
  font-feature-settings: "liga" 0;
}

/* enable tabular (monospaced) figures */
td.tabular {
  font-feature-settings: "tnum";
}

/* enable automatic fractions */
.fractions {
  font-feature-settings: "frac";
}

/* use the second available swash character */
.swash {
  font-feature-settings: "swsh" 2;
}

/* enable stylistic set 7 */
.fancy-style {
  font-family: Gabriola;
  font-feature-settings: "ss07";
}
```

### Fonctionnalités variable

```
/* synthax */
.class {
  font-variation-settings: "wght" 850, "wdth" 100, "ital" 1;
}
```

```
/* adjust the weight */
.weight {
  font-weight: 600;
}

/* adjust the width */
.width {
  font-stretch: 75%;
}

/* adjust the slant */
.slant {
  font-style: oblique 15deg;
}

/* animate font weight on hover */
.class:hover {
  transition: font-weight 0.3s ease;
  font-weight: 800; 
}
```
</details>

<a id="-assemblage"></a>
<details class="drawer" markdown="1">
<summary>📁 Assemblage</summary>

L’assemblage (InDesign, website, installation sur Figma) des fontes **n’est pas autorisé**: chaque utilisateur.rice peut ouvrir un fichier de design en **activant les polices requises dans sa propre typothèque**. En revanche, le transfert d’un fichier d’**export statique** est possible.

|![](/links/8_Package.gif)                  |
|:---:|
| Possibilités de transfert de fichiers |

</details>

<a id="-suppression-check-out"></a>
<details class="drawer" markdown="1">
<summary>🔥 Suppression</summary>

## Chaque utilisateur.rice s’engage à supprimer tous les fichiers de fontes à la fin de son cursus.

1. Aller > Se rendre au dossier
2. Copier le chemin suivant (Macintosh HD > Users > *YourName* > Bibliothèque > Fonts)

```
~/Library/Fonts
```

3. Coller le chemin > Enter
4. Supprimer toutes les fontes qui appartiennent au catalogue de la typothèque.

|![](/links/erase_fonts.gif)                  |
|:---:|
| Supprimer les fontes éracom |

![](/links/Eracom_Typotheque_Graphics_v44.jpg)

</details>

<a id="-tags"></a>
<details class="drawer" markdown="1">
<summary>🏷️ Tags</summary>

Grâce aux tags sur mac, il est possible filtrer  les fontes en fonction de critères de recherche directement dans le finder.
Sur windows, il faut se référer au tableau du catalogue ci-dessous.

| Tag         | Titre       | Valeur          |
|:---            |:---            |:---            |
| ➡️ **é_Hst** | Classification Historique[^3] | **Inc** / **Scr** / **Sér** / **Slab** / **Sans** / **Exp** / **Hyb** / **NonL** |
| ➡️ **é_ForP** | Classification Formelle Principe | **Dyn**(amique) / **Sta**(tique) / **Géo**(métrique) |
| ➡️ **é_ForC** | Classification Formelle Contraste | **Con**(trasté) / **Lin**(éaire) |
| ➡️ **é_ForT** | Classification Formelle Terminaisons | **Avec** / **Sans** |
| ➡️ **é_Typ** | Typologie | **Cla**(ssique) / **Mod**(erne) / – |
| ➡️ **é_Lic** | License | **Pro**(priétaire) / **Lib**(re) |
| ➡️ **é_Ext** | Extensions | — / **Var**(iable) | 

[^3]: **Inc**(ises) / **Scr**(iptes) / **Sér**(ifs) / **Slab**(-Sérifs) / **Sans**(-Sérifs) / **Exp**(ressives) / **Hyb**(rides) / **NonL**(atines)

</details>

<a id="-catalogue"></a>
<details class="drawer" markdown="1">
<summary>🧰 Catalogue</summary>

| Police         | é_Hst | é_ForP | é_ForC           | é_ForT        | é_Typ                 | é_Lic                 | é_Ext                 |
|:---            |:---            |:---            |:---                 |:---            |:---                     |:---                     |:---                     |
Africa | 6_Exp |||| Mod | Pro |
Agatha | 3.4_Sér_Didones | Sta | Ctr | Avec || Pro | Var
Akzidenz Grotesk Next | 5.1_Sans_Grotesques | Sta | Lin | Sans | Cla | Pro |
Alaska | 5.3_Sans_Géométriques | Géo | Lin | Sans || Pro | Var
Allegra | 5.2_Sans_Humanistes | Dyn | Lin | Sans | Mod | Pro |
Aloha | 4.2_Slab_Monos ||||| Pro | Var
Alpaga | 4.2_Slab_Monos ||||| Pro | Var
Alte Schwabacher D | 2.2_Scr_Fractures |||| Cla | Pro |
Alverata | 1_Inc |||| Mod | Pro |
Amazonia | 3.4_Sér_Didones | Sta | Ctr | Avec || Pro | Var
Angela | 6_Exp |||| Mod | Pro |
Antarctica | 5.1_Sans_Grotesques | Sta | Lin | Sans || Pro | Var
Antique Legacy | 5.1_Sans_Grotesques | Sta | Lin | Sans | Mod | Pro |
Apax | 5.3_Sans_Géométriques | Géo | Lin | Sans | Mod | Pro |
Armada | 6_Exp |||| Mod | Pro |
Arnhem | 3.3_Sér_Réales | Dyn | Ctr | Avec | Mod | Pro |
Arno | 3.1_Sér_Humanes | Dyn | Ctr | Avec | Cla | Pro |
Artex | 5.3_Sans_Géométriques | Géo | Lin | Sans || Pro | Var
Atacama | 3.2_Sér_Garaldes | Dyn | Ctr | Avec || Pro | Var
Atlantique Miami | 3.3_Sér_Réales | Dyn | Ctr | Avec || Pro | Var
Atlas Grotesk | 5.1_Sans_Grotesques | Sta | Lin | Sans | Mod | Pro |
Avant Garde Gothic | 5.3_Sans_Géométriques | Géo | Lin | Sans | Cla | Pro |
Avenir Next | 5.3_Sans_Géométriques | Géo | Lin | Sans | Cla | Pro |
Azaka | 6_Exp |||| Mod | Pro |
Azteca | 6_Exp |||| Mod | Pro |
Baikal | 5.1_Sans_Grotesques | Sta | Lin | Sans || Pro | Var
Balance | 5.2_Sans_Humanistes | Dyn | Lin | Sans | Cla | Pro |
Bodoni | 3.4_Sér_Didones | Sta | Ctr | Avec | Cla | Pro |
Bradford | 3.3_Sér_Réales | Dyn | Ctr | Avec | Mod | Pro |
Breeze Sans | 5.2_Sans_Humanistes | Dyn | Lin | Sans || Lib
Caflisch Script | 2.3_Scr_Cursives |||| Cla | Pro |
Caslon 224 | 3.3_Sér_Réales | Dyn | Ctr | Avec | Cla | Pro |
Centaur | 3.1_Sér_Humanes | Dyn | Ctr | Avec | Cla | Pro |
Chaparral | 4.1_Slab_Mécanes | Sta | Ctr | Avec | Cla | Pro |
Charter | 3.3_Sér_Réales | Dyn | Ctr | Avec | Cla | Pro |
Clarendon Graphic | 4.1_Slab_Mécanes | Sta | Ctr | Avec | Mod | Pro |
Cochin | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Cla | Pro |
Cooper Hewitt | 5.1_Sans_Grotesques | Sta | Lin | Sans || Lib
Courier | 4.2_Slab_Monos |||| Cla | Pro |
Crystal | 5.1_Sans_Grotesques | Sta | Lin | Sans || Pro | Var
Custodia | 3.3_Sér_Réales | Dyn | Ctr | Avec | Mod | Pro |
Didot Elder | 3.4_Sér_Didones | Sta | Ctr | Avec | Mod | Pro |
Didot Modern | 3.4_Sér_Didones | Sta | Ctr | Avec | Mod | Pro |
Didot | 3.4_Sér_Didones | Sta | Ctr | Avec | Cla | Pro |
Dominicale | 6_Exp |||| Mod | Pro |
Egyptienne F | 4.1_Slab_Mécanes | Sta | Ctr | Avec | Cla | Pro |
English 111 | 2.3_Scr_Cursives |||| Cla | Pro |
Estuary | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Mod | Pro |
European Pi | 8_NonL |||| Cla | Pro |
Fedra Mono | 4.2_Slab_Monos |||| Mod | Pro |
Fedra Sans | 5.2_Sans_Humanistes | Dyn | Lin | Sans | Mod | Pro |
Fedra SerifAB | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Mod | Pro |
Fedra | 7_Hyb |||| Mod | Pro |
Fira | 5.2_Sans_Humanistes | Dyn | Lin | Sans || Lib
Fleischmann | 3.3_Sér_Réales | Dyn | Ctr | Avec | Mod | Pro |
Founders Grotesk | 5.1_Sans_Grotesques | Sta | Lin | Sans | Mod | Pro |
Franklin Gothic | 5.1_Sans_Grotesques | Sta | Lin | Sans | Cla | Pro |
Fraunces | 6_Exp ||||| Lib
Frutiger | 5.2_Sans_Humanistes | Dyn | Lin | Sans | Cla | Pro |
Futura | 5.3_Sans_Géométriques | Géo | Lin | Sans | Cla | Pro |
Garamond Premier | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Cla | Pro |
Geograph | 5.3_Sans_Géométriques | Géo | Lin | Sans | Mod | Pro |
Gill Sans | 5.2_Sans_Humanistes | Dyn | Lin | Sans | Cla | Pro |
Glypha | 4.1_Slab_Mécanes | Sta | Ctr | Avec | Cla | Pro |
Goudy Text | 2.2_Scr_Fractures |||| Cla | Pro |
Gradot | 3.3_Sér_Réales | Dyn | Ctr | Avec | Mod | Pro |
Heldane | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Mod | Pro |
Helvetica Neue | 5.1_Sans_Grotesques | Sta | Lin | Sans | Cla | Pro |
Herculanum | 1_Inc |||| Cla | Pro |
Hermes | 5.3_Sans_Géométriques | Géo | Lin | Sans | Mod | Pro |
Humanistika | 2.1_Scr_Onciales |||| Cla | Pro |
IBM Plex | 7_Hyb ||||| Lib
Ibarra Real Nova | 3.3_Sér_Réales | Dyn | Ctr | Avec || Lib
Infini | 1_Inc |||| Mod | Pro |
JJannon | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Mod | Pro |
Jenson | 3.1_Sér_Humanes | Dyn | Ctr | Avec | Cla | Pro |
Johnston | 5.2_Sans_Humanistes | Dyn | Lin | Sans | Cla | Pro |
Lapture | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Mod | Pro |
Literata | 3.3_Sér_Réales | Dyn | Ctr | Avec || Lib
Lithos | 1_Inc |||| Cla | Pro |
Ludwig | 5.1_Sans_Grotesques | Sta | Lin | Sans | Mod | Pro |
Lutetia Nova | 3.1_Sér_Humanes | Dyn | Ctr | Avec | Cla | Pro |
Mathematical Pi | 8_NonL |||| Cla | Pro |
Media77 | 3.3_Sér_Réales | Dyn | Ctr | Avec | Mod | Pro |
Millionaire | 2.3_Scr_Cursives |||| Mod | Pro |
Minion | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Cla | Pro |
Moderne | 5.2_Sans_Humanistes | Dyn | Lin | Sans | Mod | Pro |
Monaako | 2.3_Scr_Cursives |||| Mod | Pro |
New Baskerville | 3.3_Sér_Réales | Dyn | Ctr | Avec | Cla | Pro |
Newsreader | 3.2_Sér_Garaldes | Dyn | Ctr | Avec || Lib
November Slab | 4.1_Slab_Mécanes | Sta | Ctr | Avec | Mod | Pro |
November | 7_Hyb |||| Mod | Pro |
NovemberL | 5.2_Sans_Humanistes | Dyn | Lin | Sans | Mod | Pro |
OCR F | 4.2_Slab_Monos |||| Cla | Pro |
Oddity | 6_Exp |||| Mod | Pro |
Omnia | 2.1_Scr_Onciales |||| Cla | Pro |
Open Sans | 5.2_Sans_Humanistes | Dyn | Lin | Sans || Lib
Palatino | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Cla | Pro |
Parmigiano Serif | 3.4_Sér_Didones | Sta | Ctr | Avec | Mod | Pro |
Pfeffer Mediaeval | 2.1_Scr_Onciales |||| Mod | Pro |
Pfeffer Simpelgotisch | 2.2_Scr_Fractures |||| Mod | Pro |
Ping | 5.2_Sans_Humanistes | Dyn | Lin | Sans | Mod | Pro |
Plain | 5.1_Sans_Grotesques | Sta | Lin | Sans | Mod | Pro |
Pompeijana | 2.1_Scr_Onciales |||| Cla | Pro |
Practice | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Mod | Pro |
Public Sans | 5.1_Sans_Grotesques | Sta | Lin | Sans || Lib
Publico Text | 3.3_Sér_Réales | Dyn | Ctr | Avec | Mod | Pro |
Red Hat | 7_Hyb ||||| Lib
Roboto | 7_Hyb ||||| Lib
Ruder Plakat | 6_Exp |||| Cla | Pro |
Serifa | 4.1_Slab_Mécanes | Sta | Ctr | Avec | Cla | Pro |
Snell Roundhand | 2.3_Scr_Cursives |||| Cla | Pro |
Source | 7_Hyb ||||| Lib
Space Mono | 4.2_Slab_Monos |||| Lib
Spectral | 3.3_Sér_Réales | Dyn | Ctr | Avec || Lib
Stardust | 6_Exp |||| Mod | Pro |
Supreme | 5.3_Sans_Géométriques | Géo | Lin | Sans | Mod | Pro |
Syntax Lapidar | 1_Inc |||| Cla | Pro |
The AntiquaB | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Mod | Pro |
The Mix Mono | 4.2_Slab_Monos |||| Mod | Pro |
The Sans | 5.2_Sans_Humanistes | Dyn | Lin | Sans | Mod | Pro |
The Serif | 4.1_Slab_Mécanes | Sta | Ctr | Avec | Mod | Pro |
Thesis | 7_Hyb |||| Mod | Pro |
Tiina | 3.2_Sér_Garaldes | Dyn | Ctr | Avec | Mod | Pro |
Times New Roman | 3.3_Sér_Réales | Dyn | Ctr | Avec | Cla | Pro |
Trajan | 1_Inc |||| Cla | Pro |
Unica77 | 5.1_Sans_Grotesques | Sta | Lin | Sans | Mod | Pro |
Univers | 5.1_Sans_Grotesques | Sta | Lin | Sans | Cla | Pro |
Walbaum Fraktur | 2.2_Scr_Fractures |||| Cla | Pro |
Walbaum | 3.4_Sér_Didones | Sta | Ctr | Avec | Cla | Pro |
Weiss Rundgotisch D | 2.2_Scr_Fractures |||| Cla | Pro |
Zapf Dingbats | 8_NonL |||| Cla | Pro
Zapfino Extra | 2.3_Scr_Cursives |||| Cla | Pro |


</details>

<a id="-sources"></a>
<details class="drawer" markdown="1">
<summary>📎 Sources</summary>

- **Christian Tännler**  
  *Supports de cours et Supports Typothèque*, 2023
- **Adrian Frutiger**  
  *Type, Sign, Symbol*, 1980
- **Karl Gerstner**  
  *Compendium for Literates, A System of Writing*, 1974
- **Gerrit Noordzij**  
  *Le trait. Une théorie de l’écriture*, 2010
- **Erik van Blokland**  
  *The Cube: practical research in theoretical models*, 2019
- **Robert Bringhurst**  
  *Principes élémentaires de la typographie: une histoire des styles*, 2023
- **Albert Jan Pool**  
  *Schriftklassifikation nach Formprinzip*, 2020
- **Indra Kupferschmid**  
  *www.kupferschrift.de*
- **Oliver Schöndorfer**  
  *www.pimpmytype.com/font-matrix*
- **Luc Devroye**  
  *www.luc.devroye.org*
- **Index Graphik**  
  *www.indexgrafik.fr*
- **Fonts In Use**  
  *www.fontsinuse.com*
- **Agrégateur de Ressources Art + Design**  
*www.ar-ad.ch/sujet/eracom*

</details>
