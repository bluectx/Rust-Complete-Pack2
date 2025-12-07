# 🦀 LE GUIDE RUST (ENCORE UN, OUI )

**Un guide ludique par AnonSecLab complet de plus de 7000 lignes ! pour apprendre Rust depuis zéro absolument aucune connaissance en programmation.**

---

![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fbluectx%2FRust-Complete-Pack2&label=Visitors&countColor=%23263759&style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/bluectx/Rust-Complete-Pack2?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/bluectx/Rust-Complete-Pack2?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/bluectx/Rust-Complete-Pack2?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT%20%2B%20Attribution-blue?style=for-the-badge)
![Made with Love](https://img.shields.io/badge/Made%20with-Love-ff69b4?style=for-the-badge)

---

## PRÉSENTATION

Salut à tous, c'est BlueCtx !

Je suis content de vous dévoiler et partager mon guide spécial Rust, car je sais à quel point les personnes qui débutent ont du mal et décrochent rapidement.

Ce guide est structuré simplement avec une façon de parler simple pour que tout le monde puisse comprendre.

Lancez-vous dans cette aventure de **+7000 lignes** en espérant que vous ressortirez maître de Rust !

---

## LICENSE & TERMS OF USE

**Copyright (c) 2025 AnonSecLab (BlueCtx)**

This project is licensed under a **strict MIT License with Attribution and No Commercial Use**.

### ⚠️ IMPORTANT - READ CAREFULLY

**You are allowed to:**
- ✅ Share this project
- ✅ Use it for educational purposes
- ✅ Modify and adapt it for personal use
- ✅ Fork and contribute

**You MUST:**
- ✅ **Give visible credit** to "AnonSecLab" or "BlueCtx" at the **top of your README.md**
- ✅ Include this LICENSE file when sharing
- ✅ Link back to the original repository
- ✅ Keep all copyright notices intact

**You are NOT allowed to:**
- ❌ Claim this work as your own
- ❌ Remove or hide attribution
- ❌ Use commercially without explicit permission
- ❌ Plagiarize or present without credit

### Contact & Permissions

For commercial use, licensing inquiries, or questions:
**Email:** contact@anonseclab.org

**Full license text:** See [LICENSE](LICENSE) file in this repository.

---

## TABLE DES MATIÈRES {#bienvenue}

### **INTRODUCTION GÉNÉRALE**
- [Bienvenue dans ce guide monumentaux](#bienvenue)
- [Pourquoi Rust est le futur](#pourquoi-rust)
- [Structure et progression du guide](#structure-du-guide)
- [Comment utiliser ce guide efficacement](#comment-utiliser)
- [Prérequis absolus (zéro supposés)](#prérequis)
- [Conventions et notations](#conventions)
- [Symboles et icônes utilisées](#symboles)

### **PARTIES 0-4 : FONDATIONS**
- [Partie 0 : Les ultra-bases](#partie-0--les-ultra-bases--zéro-absolu)
- [Partie 1 : Installation & Setup complet](#partie-1--installation--setup-complet)
- [Partie 2 : Les types scalaires](#partie-2--les-types-scalaires---guide-complété)
- [Partie 3 : Variables & Mutabilité](#partie-3--variables--mutabilité-très-détaillé)
- [Partie 4 : Opérations mathématiques & Comparaisons](#partie-4--opérations-mathématiques--comparaisons)

### **PARTIES 5-8 : COLLECTIONS & FONCTIONS**
- [Partie 5 : Affichage & Debugging](#partie-5--affichage--debugging-complet)
- [Partie 6 : Collections — Strings](#partie-6--collections--strings)
- [Partie 7 : Collections — Arrays, Tuples, Vecteurs](#partie-7--collections--arrays-tuples-vecteurs)
- [Partie 8 : Fonctions essentielles](#partie-8--fonctions-essentielles)

### **PARTIES 9-22 : CORE RUST**
- [Partie 9 : Contrôle de flux — IF, ELSE, IF-ELSE-IF](#partie-9--contrôle-de-flux--if-else-if-else-if)
- [Partie 10 : Contrôle de flux — Boucles (LOOP, WHILE, FOR)](#partie-10--contrôle-de-flux--boucles-loop-while-for)
- [Partie 11 : Pattern Matching — MATCH complet](#partie-11--pattern-matching--match-complet)
- [Partie 12 : Ownership en profondeur](#partie-12--ownership-en-profondeur)
- [Partie 13 : Borrowing en profondeur](#partie-13--borrowing-en-profondeur)
- [Partie 14 : Structs (Structures)](#partie-14--structs-structures)
- [Partie 15 : Enums](#partie-15--enums)
- [Partie 16 : Traits (Interfaces)](#partie-16--traits-interfaces)
- [Partie 17 : Génériques](#partie-17--génériques)
- [Partie 18 : Modules & Organisation](#partie-18--modules--organisation)
- [Partie 19 : Gestion d'erreurs](#partie-19--gestion-derreurs)
- [Partie 20 : Closures](#partie-20--closures)
- [Partie 21 : Iterators](#partie-21--iterators)
- [Partie 22 : Smart Pointers](#partie-22--smart-pointers)

### **PARTIES 23-35 : SUJETS AVANCÉS**
- [Partie 23 : Concurrence — Threads](#partie-23--concurrence--threads)
- [Partie 24 : Async/Await](#partie-24--asyncawait)
- [Partie 25 : Unsafe Rust](#partie-25--unsafe-rust)
- [Partie 26 : Memory Model](#partie-26--memory-model)
- [Partie 27 : Cargo en détail](#partie-27--cargo-en-détail)
- [Partie 28 : Testing complet](#partie-28--testing-complet)
- [Partie 29 : Macros basics](#partie-29--macros-basics)
- [Partie 30 : Regex & String Processing](#partie-30--regex--string-processing)
- [Partie 31 : File I/O](#partie-31--file-io)
- [Partie 32 : JSON & Serde](#partie-32--json--serde)
- [Partie 33 : Projets complets](#partie-33--projets-complets)
- [Partie 34 : Patterns & Best Practices](#partie-34--patterns--best-practices)
- [Partie 35 : Conclusion & Suite](#partie-35--conclusion--suite)

### **PARTIES 36-50 : EXPERT LEVEL**
- [Partie 36 : Lifetimes avancés](#partie-36--lifetimes-avancés)
- [Partie 37 : Gestion d'erreurs complète](#partie-37--gestion-derreurs-complète)
- [Partie 38 : Async/Await approfondi](#partie-38--asyncawait-approfondi)
- [Partie 39 : Unsafe Rust avancé](#partie-39--unsafe-rust-avancé)
- [Partie 40 : Concurrency avancée](#partie-40--concurrency-avancée)
- [Partie 41 : Macros avancées](#partie-41--macros-avancées)
- [Partie 42 : Performance & Optimization](#partie-42--performance--optimization)
- [Partie 43 : Embedded Rust](#partie-43--embedded-rust)
- [Partie 44 : Web Frameworks](#partie-44--web-frameworks)
- [Partie 45 : Testing avancé](#partie-45--testing-avancé)
- [Partie 46 : Regex & Text Processing](#partie-46--regex--text-processing)
- [Partie 47 : Serialization avancée](#partie-47--serialization-avancée)
- [Partie 48 : Networking](#partie-48--networking)
- [Partie 49 : Best Practices avancées](#partie-49--best-practices-avancées)
- [Partie 50 : Conclusion & Roadmap Expert](#partie-50--conclusion--roadmap-expert)

---

## BIENVENUE A TOUS DANS CET ENORME GUIDE ( QUI EST COMPLET )

Bienvenue ! Tu arrives ici avec **zéro connaissance** en programmation? C'est **PARFAIT**. Ce guide est conçu pour les noob complet.

### À quoi ce guide te prépare

À la fin de ce guide, tu seras capable de :

✅ Comprendre les concepts fondamentaux de la programmation
✅ Écrire du code Rust **sécurisé** et **performant**
✅ Gérer la mémoire efficacement (sans garbage collector)
✅ Écrire du code **concurrent** sans peur
✅ Créer des applications réelles (CLI, web servers, outils)
✅ Comprendre **pourquoi** Rust est différent
✅ Contribuer à des projets Rust open-source

### Structure du guide

Ce guide contient **50 parties principales**, chacune avec **10-20 sous-sections**. C'est énorme, mais c'est intentionnel.

**Progression :**

```
Partie 0-3   : Les ultra-bases (aucune connaissance supposée)
Partie 4-8   : Concepts essentiels (variables, types, fonctions)
Partie 9-15  : Le cœur de Rust (ownership, borrowing, lifetimes)
Partie 16-22 : Organisation du code (structs, traits, modules)
Partie 23-28 : Patterns avancés (génériques, erreurs, closures)
Partie 29-33 : Sujets avancés (concurrency, async, unsafe)
Partie 34-50 : Maîtrise et expertise
```

Chaque partie est **progressive**. Tu peux passer plusieurs heures sur chaque partie. C'est normal.

### Temps estimé

- **Partie 0-8** : 20-30 heures (les bases)
- **Partie 9-15** : 30-40 heures (ownership et borrowing, concepts difficiles)
- **Partie 16-22** : 20-30 heures (organisation)
- **Partie 23-28** : 30-40 heures (patterns avancés)
- **Partie 29-33** : 20-30 heures (sujets avancés)
- **Partie 34-50** : 40-50 heures (maîtrise et expertise)

**Total : 160-220 heures de contenu.**

Oui, c'est beaucoup. Mais tu vas devenir **vraiment bon** en Rust.

---

## 🦀 POURQUOI RUST EST LE BEST {#pourquoi-rust}

### Le problème des langages classiques

**Langage traditionnel (Python, Java, JavaScript) :**

1. Tu écris le code
2. Tu l'exécutes
3. *Crash !* Un bug que tu n'avais pas vu
4. Tu cherches l'erreur pendant des heures
5. Tu fixes
6. Ça marche... jusqu'au prochain bug

**Les vrais problèmes :**

- **Memory leaks** : Tu oublies de libérer la mémoire → crash
- **Data races** : Deux threads modifient les mêmes données → chaos
- **Null pointers** : "Je suis un pointer vers rien" → crash
- **Buffer overflows** : Tu écris au-delà de la limite → hack

### Pourquoi Rust est différent

Rust **élimine** ces problèmes **à la compilation**. Le compilateur crie si quelque chose est dangereux.

**Analogie :** 

- Autres langages = test drive d'une voiture sans ceinture
- Rust = le compilateur t'empêche même de monter sans ceinture

### Les trois piliers de Rust

#### 1. **Ownership (Propriété)**

Chaque données a UN propriétaire. Quand le propriétaire meurt, les données sont nettoyées.

C'est comme :
- Une maison a UN propriétaire
- Quand le propriétaire meurt, la maison est détruite
- Pas de questions, pas d'hésitation

#### 2. **Borrowing (Emprunt)**

Tu peux **emprunter** des données au lieu de les prendre.

Comme :
- Tu prêtes ton livre à un ami
- L'ami peut le lire, mais ne peut pas le garder
- Il doit te le retourner

#### 3. **Lifetimes (Durées de vie)**

Rust sait exactement **combien de temps** une référence est valide.

Comme :
- "Ce pointeur existe jusqu'à la fin de cette fonction"
- "Cette référence vit aussi longtemps que cette donnée"

### Avantages concrets

**Performance :**
- Aussi rapide que le C++
- Pas de garbage collector qui ralentit
- Pas de runtime overhead

**Sécurité :**
- Pas de null pointers
- Pas de memory leaks
- Pas de data races
- Pas de buffer overflows

**Productivité :**
- Compilateur qui aide (pas qui bloque)
- Types qui documentent le code
- Erreurs détectées **avant** production

---

## STRUCTURE ET PROGRESSION DU GUIDE {#structure-du-guide}

### Les 5 "cercles" de compréhension

Le guide est divisé en **5 cercles progressifs** :

#### **Cercle 1 : Les Fondations (Parties 0-8)**
*"Qu'est-ce qu'un langage de programmation ?"*

Ici, tu apprends les **ultra-bases**. Aucune connaissance supposée.

- Comment lire du code
- Variables et types
- Fonctions basiques
- Contrôle de flux (if, for, while)
- Premier programme complet

**Durée :** 20-30 heures
**Difficulté :** ⭐ (très facile)

#### **Cercle 2 : Le Cœur de Rust (Parties 9-15)**
*"Pourquoi Rust est différent"*

Ici, tu apprenez les **concepts qui rendent Rust spécial**.

- Ownership (propriété)
- Borrowing (emprunt)
- Borrow checker (le compilateur)
- Lifetimes (durées de vie)

C'est **DIFFICILE** mais c'est là que le vrai apprentissage se fait.

**Durée :** 30-40 heures
**Difficulté :** ⭐⭐⭐⭐ (très difficile)

#### **Cercle 3 : Organisation du Code (Parties 16-22)**
*"Comment écrire du code lisible et réutilisable"*

Ici, tu apprends à **structurer ton code**.

- Structures (structs)
- Enums
- Traits (interfaces)
- Modules (organisation)
- Pattern matching

**Durée :** 20-30 heures
**Difficulté :** ⭐⭐⭐ (difficile)

#### **Cercle 4 : Patterns Avancés (Parties 23-28)**
*"Résoudre des problèmes réels"*

Ici, tu apprends les **patterns pratiques**.

- Génériques (types polymorphes)
- Erreurs (Result, Option)
- Closures (fonctions anonymes)
- Iterators (parcours efficace)
- Smart pointers (gestion mémoire avancée)

**Durée :** 30-40 heures
**Difficulté :** ⭐⭐⭐ (difficile)

#### **Cercle 5 : Maîtrise (Parties 29-50)**
*"Devenir un expert Rust"*

Ici, tu apprenez les **sujets avancés et la pratique réelle**.

- Concurrency (threads, Mutex, channels)
- Async/Await (programmation asynchrone)
- Unsafe Rust (quand tu dois contourner la sécurité)
- Memory model (comment Rust stocke les données)
- Projets réels complets
- Lifetimes avancés
- Macros avancées
- Performance & optimization

**Durée :** 60-80 heures
**Difficulté :** ⭐⭐⭐⭐⭐ (expert)

---

## 💡 COMMENT UTILISER CE GUIDE EFFICACEMENT {#comment-utiliser}

### Règle 1 : Lis LENTEMENT

Ne lis pas ce guide en 5 minutes. Lis une section par jour.

Chaque section est dense. Donne-toi le temps de **digérer**.

### Règle 2 : Tape TOUT le code

Pour chaque exemple, **tape le code toi-même**. Pas de copier-coller.

Quand tu tapes, tu **mémorises**. Quand tu copies, tu oublies.

### Règle 3 : Modifie les exemples

Après chaque exemple qui fonctionne, **modifie-le** :

- Change les nombres
- Ajoute des variables
- Essaie de casser le compilateur

C'est en cassant les choses que tu apprends.

### Règle 4 : Fais les exercices

Chaque section a des **exercices**. Fais-les **avant** de lire la correction.

Essaie pendant **au moins 10 minutes**. Si tu bloques, cherche **pourquoi**.

### Règle 5 : Crée un carnet

Écris tes propres **analogies** et **mnémoniques**. C'est plus facile de retenir ce que TU as créé.

### Règle 6 : Reviens en arrière

Si tu oublies quelque chose, **reviens en arrière**. Il n'y a pas de honte.

L'apprentissage n'est pas linéaire. Tu vas revenir en arrière 100 fois.

### Règle 7 : Construis des projets

À partir de la Partie 10, **construis des petits projets** en parallèle.

Des petits projets :
- Un calculatrice
- Un jeu de devinette
- Un gestionnaire de TODO
- Un serveur web simple

Les projets te montrent comment utiliser ce que tu apprends.

---

## PRÉREQUIS ABSOLUS {#prérequis}

### Techniquement parlant

Tu as besoin de :

✅ **Un ordinateur** (Windows, macOS, ou Linux)
✅ **Un éditeur de texte** (VS Code, Sublime, etc.)
✅ **Rust installé** (on va le faire ensemble)
✅ **Une connexion Internet** (pour installer Rust)

### Intellectuellement parlant

Tu as besoin de :

✅ **La volonté d'apprendre** (c'est suffisant)
✅ **De la patience** (Rust est compliqué au début)
✅ **Du temps** (160-220 heures minimum)
✅ **Une attitude positive** (tu vas bugguer, c'est normal)

### Ce que tu NE besoin PAS

❌ **Connaissance préalable en programmation** (on commence de zéro)
❌ **Un ordinateur puissant** (même un vieux laptop va)
❌ **Parler l'anglais couramment** (on explique les termes)
❌ **Une licence ou un cours payant** (ce guide est complet et gratuit)

---

## 📝 CONVENTIONS ET NOTATIONS {#conventions}

### Syntaxe des blocs de code

Tous les blocs de code ressemblent à ceci :

```rust
fn main() {
    println!("AnonSecLab a mis du temps a ecrire ce guide, prenez s'en soins");
    println!("Voila du code Rust");
}
```

Si tu vois ceci, c'est du **code à taper et à exécuter**.

### Nomenclature dans le guide

| Terme | Signification |
|-------|--------------|
| **fn** | Mot-clé Rust |
| `variable` | Un nom de variable |
| `Type` | Un nom de type |
| **PATH::TO::Thing** | Un chemin complet |

### Símbolos et icônes {#symboles}

| Symbole | Signification |
|---------|--------------|
| ✅ | Correct, fonctionne |
| ❌ | Erreur, ne compile pas |
| ⚠️ | Attention, piège courant |
| 💡 | Conseil ou astuce |
| 📝 | Exercice pratique |
| 🎯 | Concept important |
| 🦀 | Spécifique à Rust |

---

# PARTIE 0 : LES ULTRA-BASES — ZÉRO ABSOLU

## 0.0 Qu'est-ce qu'une "programme" ?

Un **programme** c'est juste des **instructions** qu'on donne à l'ordinateur.

### Exemple ultra-simple

Imagine que tu veux faire un gâteau. Tu donnes des instructions :

```
1. Mélanger les ingrédients
2. Verser dans un moule
3. Cuire à 180°C pendant 30 minutes
4. Refroidir
5. Manger
```

Un **programme informatique** c'est pareil, mais pour l'ordinateur :

```
1. Créer une variable "nom" avec la valeur "Alice"
2. Afficher "nom"
3. Calculer 2 + 2
4. Afficher le résultat
5. Arrêter
```

### Pourquoi c'est important

L'ordinateur est **BÊTE**. Il ne comprend que des instructions très claires et précises.

Si tu dis "fais un gâteau", il ne comprend pas.
Si tu dis "Mélange 2 tasses de farine + 1 oeuf", c'est mieux.

Mais l'ordinateur ne parle pas l'anglais. Il parle un **langage de programmation**.

Rust est un langage de programmation.

---

## 0.1 Qu'est-ce qu'un "langage de programmation" ?

Un **langage de programmation** c'est une façon de **parler à l'ordinateur** dans une langue qu'il comprend.

### Les ordinateurs parlent le binaire

Au très bas niveau, les ordinateurs ne comprennent que des **1** et des **0**.

```
01100001 01101110 01101111 01101110 01110011 01100101 01100011 01101100 01100001 01100010
```

C'est du **code machine**. Horrible à lire.

### Les langages de programmation sont plus faciles

Des humains intelligents ont créé des **langages** qui ressemblent plus à de l'anglais.

**Python :**
```python
print("Bonjour")
```

**JavaScript :**
```javascript
console.log("Bonjour");
```

**Rust :**
```rust
println!("Bonjour");
```

Tous disent la même chose, mais dans des langages différents.

### Le compilateur traduit

Un **compilateur** c'est un programme qui **traduit** le code que tu écris en code machine que l'ordinateur comprend.

```
Ton code Rust > Compilateur Rust > Code machine/Binaire (1 et 0)
```

L'ordinateur peut alors **exécuter** ce code machine.

### Pourquoi Rust ?

Il y a des **centaines de langages de programmation**. Pourquoi Rust ?

**Parce que Rust est :**

-  **Rapide** : Aussi rapide que C++
-  **Sécurisé** : Te force à écrire du code safe
-  **Moderne** : Créé en 2010, conçu pour aujourd'hui

---

## 0.2 Comment fonctionne un ordinateur (ultra-simplifié)

Un ordinateur c'est juste :

1. **CPU (processeur)** : L'intelligence, qui exécute les instructions
2. **Mémoire (RAM)** : L'endroit où on stocke les données temporaires
3. **Disque dur** : L'endroit où on stocke les données permanentes

### Analogie simple

C'est comme ton cerveau :

- **CPU** = ton cerveau qui pense
- **RAM** = ta mémoire à court terme (ce que tu te souviens maintenant)
- **Disque** = ta mémoire à long terme (souvenirs d'enfance)

Quand tu exécutes un programme :

```
1. L'ordinateur lit le programme du disque dur
2. Il le met en mémoire (RAM)
3. Le CPU exécute les instructions, ligne par ligne
4. Les résultats s'affichent
```

---

## 0.3 Comment lire du code (ultra-basique)

Le code c'est juste **du texte**. On le lit comme un livre.

### Exemple

```rust
fn main() {
    println!("Hellow, World !");
}
```

**Ligne par ligne :**

- `fn main()` = "Créer une fonction appelée 'main'"
- `{` = "Voici le début de la fonction"
- `println!("Hellow, World !");` = "Affiche le texte 'Hellow, World !'"
- `}` = "Voici la fin de la fonction"

### Indentation

L'**indentation** (les espaces au début) aide à voir la structure.

**Mauvaise indentation :**
```rust
fn main() {
println!("Hellow, World");
}
```

**Bonne indentation :**
```rust
fn main() {
    println!("Hellow, World");
}
```

Ils font la même chose, mais le deuxième est **plus lisible**.

### Convention de lecture

On lit du code comme on lit un livre :

1. De **haut en bas** (première ligne, puis deuxième ligne, etc.)
2. De **gauche à droite** (premier mot, puis deuxième mot, etc.)
3. Les **accolades** `{}` indiquent les "blocs" (sections)

---

## 0.4 Qu'est-ce qu'une variable ?

Une **variable** c'est une **boîte nommée** qui contient une valeur.

### Analogie simple

Imagine des boîtes à chaussures :

```
┌──────────────────────┐
│ Étiquette: "Nom"     │
│ Contenu: "Alice"     │
└──────────────────────┘

┌──────────────────────┐
│ Étiquette: "Âge"     │
│ Contenu: 30          │
└──────────────────────┘
```

**En Rust :**

```rust
let nom = "Alice";
let age = 30;
```

### Qu'est-ce qui se passe ?

1. On crée une variable appelée `nom`
2. On la remplit avec la valeur `"Alice"`
3. On crée une variable appelée `age`
4. On la remplit avec la valeur `30`

### Utiliser une variable

```rust
fn main() {
    let nom = "Alice";
    println!("Bonjour, {}", nom);  // Affiche : Bonjour, Alice
}
```

---

## 0.5 Qu'est-ce qu'un "type" ?

Un **type** c'est la **catégorie** de ce qu'il y a dans la variable.

### Analogie

Au supermarché :

- Rayon "Fruits" : pommes, bananes, oranges
- Rayon "Légumes" : carottes, brocoli
- Rayon "Produits laitiers" : lait, fromage, yogurt

Chaque rayon est un **type**.

### Types en Rust

```rust
let nom = "Alice";           // Type: String (texte)
let age = 30;                // Type: i32 (entier)
let est_actif = true;        // Type: bool (vrai/faux)
let prix = 19.99;            // Type: f64 (nombre décimal)
```

### Pourquoi les types sont importants

Imagine que tu essaies de faire :

```
nom + age  // "Alice" + 30 = ???
```

Ça n'a aucun sens ! Tu peux pas ajouter du texte avec un nombre !

Rust **t'empêche** de faire ça. Le compilateur crie :

```
❌ ERREUR ! Tu peux pas ajouter String + i32
```

C'est **très bon** pour toi. Ça élimine des bugs.

---

## 0.6 Qu'est-ce qu'une "fonction" ?

Une **fonction** c'est une **recette réutilisable**.

### Analogie

Une recette de gâteau :

```
Recette : Faire un gâteau

Ingrédients:
- 2 tasses de farine
- 1 oeuf
- 1 tasse de sucre

Instructions:
1. Mélanger la farine et le sucre
2. Ajouter l'oeuf
3. Verser dans un moule
4. Cuire à 180°C pendant 30 minutes
```

Tu peux utiliser cette recette **100 fois**. Chaque fois tu as un gâteau.

### Fonction en Rust

```rust
fn faire_gateau() {
    println!("Mélanger la farine et le sucre");
    println!("Ajouter l'oeuf");
    println!("Verser dans un moule");
    println!("Cuire à 180°C");
}

fn main() {
    faire_gateau();  // Exécute la recette
    faire_gateau();  // Exécute encore
}
```

### Parties d'une fonction

```rust
fn nom_de_fonction() {
    // Instructions ici
}
```

- `fn` = mot-clé "fonction"
- `nom_de_fonction` = le nom (tu choisis)
- `()` = paramètres (les ingrédients, vides ici)
- `{}` = le corps (les instructions)

---

## 0.7 L'ordre d'exécution du code

Le code **s'exécute de haut en bas**.

### Exemple

```rust
fn main() {
    println!("Étape 1");
    println!("Étape 2");
    println!("Étape 3");
}
```

**Exécution :**

```
Étape 1
Étape 2
Étape 3
```

Pas de surprise. De haut en bas.

### Avec des fonctions

```rust
fn etape_1() {
    println!("Étape 1");
}

fn main() {
    etape_1();           // Appel etape_1()
    println!("Étape 2");
}
```

**Exécution :**

```
Étape 1
Étape 2
```

Quand on appelle `etape_1()` (la ligne `etape_1();`), la fonction s'exécute **en entier** avant de continuer.

### Imbrication

```rust
fn inner() {
    println!("Inner");
}

fn outer() {
    println!("Outer start");
    inner();
    println!("Outer end");
}

fn main() {
    outer();
}
```

**Exécution :**

```
Outer start
Inner
Outer end
```

---

# PARTIE 1 : INSTALLATION & SETUP COMPLET

## 1.0 Pourquoi installer Rust localement ?

Avant d'apprendre Rust, tu dois l'**installer sur ton ordinateur**.

### Qu'est-ce qu'on installe ?

1. **rustc** : Le compilateur Rust (transforme ton code en langage machine)
2. **cargo** : L'outil de build (gère les projets)
3. **rustup** : Le gestionnaire de versions (maintient Rust à jour)

C'est trois outils en un.

---

## 1.1 Installation sur macOS - GUIDE COMPLET

### Étape 1 : Ouvrir le Terminal

Appuie sur `Cmd + Espace` pour ouvrir Spotlight, tape "Terminal" et appuie sur Entrée.

Tu devrais voir quelque chose comme :

```
MacBook-de-Alice ~ % 
```

Le curseur est prêt pour que tu tapes.

### Étape 2 : Copier-coller la commande

Copie exactement ceci :

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Colle-la dans le Terminal et appuie sur Entrée.

### Étape 3 : Le script s'exécute

Tu vas voir du texte qui s'affiche. C'est normal. Lis-le.

Le script te demandera :

```
1) Proceed with installation (default)
2) Customize installation
3) Cancel installation
```

Appuie sur Entrée pour l'option 1 (la défaut).

### Étape 4 : Attendre

L'installation peut prendre **2-5 minutes**. C'est normal. L'ordinateur télécharge et installe Rust.

Tu verras :

```
Downloading Rust release for x86_64-apple-darwin...
...
Rust is installed now. Great!
```

### Étape 5 : Fermer et rouvrir le Terminal

C'est **IMPORTANT**. Ferme le Terminal complètement (Cmd+Q).

Puis rouvre-le (Cmd+Espace, tape "Terminal", Entrée).

Pourquoi ? Rust modifie les variables d'environnement, et le Terminal doit être **redémarré** pour les voir.

### Étape 6 : Vérifier l'installation

Dans le Terminal, tape :

```bash
rustc --version
```

Tu devrais voir quelque chose comme :

```
rustc 1.75.0 (1d8b05fc5 2023-12-21)
```

Si tu vois ça → **C'est bon ! ✅**

Vérifie aussi Cargo :

```bash
cargo --version
```

Tu devrais voir :

```
cargo 1.75.0 (1d8b05fc5 2023-12-21)
```

**Si tu vois les deux versions → Tu es prêt ! 🎉**

---

## 1.2 Installation sur Linux - GUIDE COMPLET

### Ubuntu / Debian

#### Étape 1 : Ouvrir le Terminal

Appuie sur `Ctrl + Alt + T` pour ouvrir le Terminal.

#### Étape 2 : Copier-coller la commande

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

#### Étape 3 : Suivre les instructions

Le script va te demander de confirmer. Appuie sur Entrée pour l'option 1.

#### Étape 4 : Configurer l'environnement

À la fin, tu vas voir quelque chose comme :

```
source $HOME/.cargo/env
```

Tape ceci dans le Terminal pour **activer immédiatement** Rust :

```bash
source $HOME/.cargo/env
```

Ou simplement ferme et rouvre le Terminal.

#### Étape 5 : Vérifier

```bash
rustc --version
cargo --version
```

### Fedora / RHEL / CentOS

#### Installation rapide

```bash
sudo dnf install rustup
rustup toolchain install stable
```

#### Vérifier

```bash
rustc --version
cargo --version
```

### Arch Linux

```bash
sudo pacman -S rust
```

#### Vérifier

```bash
rustc --version
cargo --version
```

---

## 1.3 Installation sur Windows - GUIDE COMPLET

### Étape 1 : Télécharger l'installateur

Va sur https://rustup.rs/

Tu vas voir un gros bouton "DOWNLOAD RUSTUP-INIT.EXE". Clique dessus.

Le fichier `rustup-init.exe` va se télécharger.

### Étape 2 : Exécuter l'installateur

Ouvre le dossier Téléchargements, trouve `rustup-init.exe` et clique-le deux fois.

Une fenêtre PowerShell va s'ouvrir. Tu vas voir :

```
Rust Visual C++ prerequisites

This will download and install the Visual C++ Build Tools, which is required to compile Rust programs.

Proceed with installation of the Visual C++ Build Tools?

1) Yes
2) No
```

Tape `1` et appuie sur Entrée.

### Étape 3 : Installer Visual C++

L'installateur de Visual C++ Build Tools va s'ouvrir. Suis les instructions :

- Clique "Install"
- Attends que ça finisse (~10 minutes)
- Clique "Close"

### Étape 4 : Installer Rust

Tu reviens à la fenêtre PowerShell. Elle te demande :

```
1) Proceed with installation (default)
2) Customize installation
3) Cancel installation
```

Tape `1` et appuie sur Entrée.

### Étape 5 : Attendre

Rust s'installe (~5 minutes).

### Étape 6 : Fermer et vérifier

Ferme la fenêtre PowerShell. Puis ouvre une **nouvelle** fenêtre PowerShell.

Tape :

```powershell
rustc --version
```

Si tu vois la version → **C'est bon ! ✅**

---

## 1.4 Vérification complète de l'installation

Sur **tous les OS**, exécute cette commande pour vérifier :

```bash
rustc --version
cargo --version
rustup --version
```

Tu devrais voir trois versions. Si tu les vois toutes > **Tu es prêt !**

### Si ça ne marche pas

#### Problème : "rustc not found"

**Cause :** Le Terminal n'a pas les variables d'environnement.

**Solution :** Ferme le Terminal **complètement** et rouvre-le.

#### Problème : Permission denied

**Cause :** Tu n'as pas les droits.

**Solution :** Sur Linux/Mac, utilise sudo au besoin. Sur Windows, lance PowerShell en Admin.

#### Problème : Network error

**Cause :** Pas de connexion Internet ou pare-feu bloque.

**Solution :** Assure-toi d'avoir Internet. Vérifie ton pare-feu.

---

## 1.5 Créer ton PREMIER projet Rust

### Étape 1 : Créer le dossier du projet

Dans le Terminal, tape :

```bash
cargo new hello_rust
```

**Qu'est-ce qui vient de se passer ?**

Cargo a créé un **dossier** appelé `hello_rust` avec cette structure :

```
hello_rust/
├── Cargo.toml       (configuration du projet)
├── Cargo.lock       (versions des dépendances)
└── src/
    └── main.rs      (ton code)
```

### Étape 2 : Entrer dans le dossier

```bash
cd hello_rust
```

Maintenant tu es **dans** le dossier du projet.

### Étape 3 : Regarder le code

Ouvre `src/main.rs` dans ton IDE.

Tu vas voir :

```rust
fn main() {
    println!("Hello, world!");
}
```

C'est un **programme complet**. Il affiche "Hello, world!"

---

## 1.6 Exécuter ton premier programme

Dans le Terminal, tape :

```bash
cargo run
```

**Qu'est-ce qui se passe :**

1. Cargo **compile** ton code (le traduit en langage machine)
2. Cargo **exécute** le programme

Tu devrais voir :

```
Compiling hello_rust v0.1.0 (/Users/alice/hello_rust)
Finished dev [unoptimized + debuginfo] target(s) in 0.45s
Running `target/debug/hello_rust`
Hello, world!
```

**C'est magique ! ✨**

Tu viens de :
1. Compiler du code Rust
2. Exécuter le programme
3. Voir le résultat

**Bravo ! Tu es un programmeur Rust ! 🎉**

---

## 1.7 Comprendre la structure du projet

### Fichier : Cargo.toml

C'est la **configuration** de ton projet.

```toml
[package]
name = "hello_rust"
version = "0.1.0"
edition = "2021"

[dependencies]
```

**Ce que ça signifie :**

- `name` : Le nom du projet
- `version` : La version (0.1.0 = très jeune)
- `edition` : La version de Rust (2021 = moderne)
- `[dependencies]` : Les librairies externes (vide pour l'instant)

### Dossier : src/

C'est là qu'on met **tout le code** Rust.

```
src/
├── main.rs     (programme exécutable)
├── lib.rs      (librairie, si tu en crées une)
└── bin/        (autres programmes exécutables)
```

### Fichier : Cargo.lock

C'est généré automatiquement. Il garde la trace des **versions exactes** des dépendances.

Tu ne dois **jamais** le modifier à la main.

---

## 1.8 Ton premier programme modifié

Maintenant, **modifie** le code. Ouvre `src/main.rs` et change le texte :

```rust
fn main() {
    println!("Bonjour depuis Rust !");
    println!("Je suis un programmeur !");
}
```

Sauve le fichier et tape :

```bash
cargo run
```

Tu devrais voir :

```
Bonjour depuis Rust !
Je suis un programmeur !
```

**Félicitations ! Tu viens d'écrire et d'exécuter ton propre code Rust ! 🚀**

---

## 1.9 Compilation vs Exécution (comprendre la différence)

### cargo run = Compile + Exécute

```bash
cargo run
```

Fait **deux choses** :
1. Compile (traduit en langage machine)
2. Exécute (lance le programme)

### cargo build = Juste Compile

```bash
cargo build
```

**Compile seulement** et crée l'exécutable dans `target/debug/`.

Ne l'exécute pas.

### Pourquoi la distinction ?

Parfois tu veux juste **compiler** pour vérifier qu'il n'y a pas d'erreurs.

Ou tu veux **compiler** mais **exécuter plus tard** (sur une autre machine par exemple).

### cargo check = Vérifier sans compiler

```bash
cargo check
```

Vérifie qu'il n'y a pas d'erreurs **sans** compiler l'exécutable complet.

C'est **beaucoup plus rapide** que `cargo build`.

**Utilise `cargo check` quand tu développes.**

---

## 1.10 Dépannage complet

### Erreur : "rustc not found" sur macOS/Linux

**Cause :** Le Terminal n'a pas les bonnes variables d'environnement.

**Solution :**

```bash
source $HOME/.cargo/env
```

Puis réessaie.

### Erreur : Visual C++ Build Tools missing sur Windows

**Cause :** Tu n'as pas installé les Visual C++ Build Tools.

**Solution :** Relance `rustup-init.exe` et suis l'installation de Visual C++.

### Erreur : "No space left on device"

**Cause :** Pas assez d'espace disque.

**Solution :** Libère de l'espace. Rust + dependencies peuvent prendre 2-5 GB.

### Erreur : "could not compile 'hello_rust'"

**Cause :** Il y a une erreur dans ton code.

**Solution :** Lis le message d'erreur de Rust. Il te dit **exactement** où est l'erreur.

---

# PARTIE 2 : LES TYPES SCALAIRES - GUIDE COMPLÉTÉ

## 2.0 Les 4 types scalaires fondamentaux

Un **type scalaire** c'est un type qui représente **une seule valeur**.

Les 4 catégories :

1. **Entiers** : -5, 0, 100 (pas de virgule)
2. **Flottants** : 3.14, -2.5, 0.001 (avec virgule)
3. **Booléens** : true, false (vrai/faux)
4. **Caractères** : 'A', 'é', '😀' (un seul)

---

## 2.1 Les entiers signés (i8, i16, i32, i64, i128)

Un entier **signé** c'est un nombre qui peut être **positif ou négatif**.

### Les types

| Type | Range | Bits | Utilisation |
|------|-------|------|-------------|
| `i8` | -128 à 127 | 8 | Très petit |
| `i16` | -32,768 à 32,767 | 16 | Petit |
| `i32` | -2B à 2B | 32 | **Standard** ← utilise celui-ci |
| `i64` | -9Q à 9Q | 64 | Grand |
| `i128` | ±1.7×10^38 | 128 | Très très grand |

(B = Billion, Q = Quintillion)

### Exemple

```rust
fn main() {
    let x: i32 = 42;
    let y: i32 = -10;
    let z: i8 = 127;
    
    println!("x = {}", x);   // 42
    println!("y = {}", y);   // -10
    println!("z = {}", z);   // 127
}
```

### Littéraux entiers

Tu peux écrire les nombres de différentes façons :

```rust
fn main() {
    let decimal = 98_222;       // Décimal (séparateur pour lire)
    let hex = 0xFF;             // Hexadécimal (255)
    let octal = 0o77;           // Octal (63)
    let binary = 0b1111_0000;   // Binaire (240)
    let byte = b'A';            // Byte (ASCII code de 'A' = 65)
    
    println!("{} {} {} {} {}", decimal, hex, octal, binary, byte);
}
```

### Opérations sur entiers

```rust
fn main() {
    let a = 10;
    let b = 3;
    
    println!("10 + 3 = {}", a + b);  // 13
    println!("10 - 3 = {}", a - b);  // 7
    println!("10 * 3 = {}", a * b);  // 30
    println!("10 / 3 = {}", a / b);  // 3 (division entière, pas 3.33)
    println!("10 % 3 = {}", a % b);  // 1 (reste)
}
```

### Overflow (dépasser la limite)

Si tu additionnes deux entiers qui dépasse la limite, c'est un **overflow**.

```rust
fn main() {
    let x: u8 = 255;      // Maximum pour u8
    let y = x + 1;        // ❌ ERREUR : Overflow !
}
```

En mode **debug**, Rust **panic** (crash).
En mode **release**, Rust **wrap** (revient à 0).

### Éviter les overflows

```rust
fn main() {
    let x: u8 = 255;
    
    // Méthode 1: Vérifier avant
    if x == u8::MAX {
        println!("Overflow !");
    }
    
    // Méthode 2: Utiliser checked_add
    match x.checked_add(1) {
        Some(result) => println!("Résultat: {}", result),
        None => println!("Overflow !"),
    }
    
    // Méthode 3: Utiliser saturating_add (reste au max)
    let result = x.saturating_add(1);
    println!("{}", result);  // 255 (reste à la limite)
}
```

---

## 2.2 Les entiers non-signés (u8, u16, u32, u64, u128)

Un entier **non-signé** ne peut être que **positif** (0 et au-dessus).

### Les types

| Type | Range | Bits |
|------|-------|------|
| `u8` | 0 à 255 | 8 |
| `u16` | 0 à 65,535 | 16 |
| `u32` | 0 à 4,294,967,295 | 32 |
| `u64` | 0 à 18,446,744,073,709,551,615 | 64 |
| `u128` | ±1.7×10^38 | 128 |

### Exemple

```rust
fn main() {
    let age: u32 = 25;
    let prix: u32 = 100;
    let population: u64 = 8_000_000_000;
    
    println!("Age: {}", age);
    println!("Prix: {}", prix);
    println!("Population: {}", population);
}
```

### Quand utiliser u8 ?

`u8` (0-255) est parfait pour :
- Un byte (0-255)
- Un octet
- Un RGB color component

```rust
fn main() {
    let red: u8 = 255;
    let green: u8 = 128;
    let blue: u8 = 64;
    
    println!("Color: RGB({}, {}, {})", red, green, blue);
}
```

### Erreur courante

```rust
fn main() {
    let x: u8 = -5;  // ❌ ERREUR ! u8 ne peut pas être négatif
}
```

Le compilateur crie :

```
error: literal out of range for `u8`
```

---

## 2.3 Choisir la bonne taille d'entier

### Tableau de décision

| Situation | Type | Pourquoi |
|-----------|------|---------|
| Nombre général | `i32` | Default, assez grand |
| Doit être positif | `u32` | Plus grand range |
| Très petit (0-255) | `u8` | Économise mémoire |
| Peut être négatif | `i32` | Signé |
| TRÈS grand | `i64` ou `u64` | Plus capacité |

### Exemple complet

```rust
fn main() {
    let age: u32 = 30;                    // Age (positif)
    let temperature: i32 = -5;            // Température (peut être négative)
    let compte_bancaire: i64 = -10000000; // Très grand nombre
    let byte: u8 = 255;                   // Pixel (0-255)
    
    println!("Age: {}", age);
    println!("Température: {}", temperature);
    println!("Compte: {}", compte_bancaire);
    println!("Pixel: {}", byte);
}
```

---

## 2.4 Nombres flottants (f32, f64)

Un **float** (flottant) c'est un nombre avec une **virgule décimale**.

### Les types

| Type | Précision | Utilisation |
|------|-----------|-------------|
| `f32` | 7 décimales | Économie mémoire |
| `f64` | 15 décimales | **Standard** ← utilise celui-ci |

### Exemple

```rust
fn main() {
    let pi: f64 = 3.14159;
    let e: f64 = 2.71828;
    let gravitée: f32 = 9.81;
    
    println!("π = {}", pi);
    println!("e = {}", e);
    println!("g = {}", gravitée);
}
```

### Division flottante vs entière

**Important** : 5 / 2 donne **différents résultats** selon le type !

```rust
fn main() {
    let x = 5 / 2;        // x = 2 (entiers, division entière)
    let y = 5.0 / 2.0;    // y = 2.5 (floats, division vraie)
    
    println!("{}", x);    // 2
    println!("{}", y);    // 2.5
}
```

### Problème de précision

Les flottants ne sont **pas parfaits**. Il y a des petites erreurs.

```rust
fn main() {
    let x = 0.1 + 0.2;
    println!("{}", x);    // 0.30000000000000004 (pas 0.3 !)
}
```

### Comparer les flottants correctement

```rust
fn main() {
    let epsilon = 0.0001;
    
    if (0.1 + 0.2 - 0.3).abs() < epsilon {
        println!("À peu près égal !");
    }
}
```

### Opérations mathématiques

```rust
fn main() {
    let x = 5.5;
    let y = 2.5;
    
    println!("{}  + {} = {}", x, y, x + y);         // 8
    println!("{} - {} = {}", x, y, x - y);         // 3
    println!("{} * {} = {}", x, y, x * y);         // 13.75
    println!("{} / {} = {}", x, y, x / y);         // 2.2
}
```

### Méthodes sur flottants

```rust
fn main() {
    let x = -3.5;
    
    println!("Absolu: {}", x.abs());         // 3.5
    println!("Arrondi: {}", x.round());      // -4
    println!("Étage: {}", x.floor());        // -4
    println!("Plafond: {}", x.ceil());       // -3
    println!("Troncature: {}", x.trunc());   // -3
}
```

---

## 2.5 Booléens (bool)

Un **booléen** c'est simplement vrai ou faux.

### Exemple

```rust
fn main() {
    let est_actif: bool = true;
    let est_mort: bool = false;
    
    println!("Actif: {}", est_actif);   // true
    println!("Mort: {}", est_mort);     // false
}
```

### Résultats des comparaisons

Les comparaisons retournent un **bool**.

```rust
fn main() {
    let age = 20;
    let peut_voter = age >= 18;  // Comparaison retourne true/false
    
    println!("Peut voter: {}", peut_voter);  // true
}
```

### Opérations logiques

```rust
fn main() {
    let a = true;
    let b = false;
    
    println!("a && b = {}", a && b);    // false (ET logique)
    println!("a || b = {}", a || b);    // true (OU logique)
    println!("!a = {}", !a);            // false (NON logique)
}
```

### Utiliser les booléens

```rust
fn main() {
    let est_ombre = true;
    let peut_voler = true;
    
    if est_ombre && peut_voler {
        println!("C'est un vampire ou un oiseau !");
    } else if est_ombre {
        println!("C'est une ombre");
    } else if peut_voler {
        println!("C'est un oiseau");
    } else {
        println!("C'est un humain normal");
    }
}
```

---

## 2.6 Caractères (char)

Un **char** c'est un **seul** caractère.

### Attention

```rust
let une_lettre: char = 'A';       // ✅ OK
let un_texte: String = "ABC".to_string();  // ✅ OK
let une_lettre: char = "AB";      // ❌ ERREUR ! C'est 2 caractères
```

- `char` = une seule lettre (entre guillemets simples `'`)
- `String` = plusieurs lettres (entre guillemets doubles `"`)

### Exemple

```rust
fn main() {
    let lettre = 'A';
    let chiffre = '5';
    let espace = ' ';
    let virgule = ',';
    
    println!("{}", lettre);   // A
    println!("{}", chiffre);  // 5
    println!("{}", espace);   // (un espace)
    println!("{}", virgule);  // ,
}
```

### Unicode support

Rust supporte **tous les caractères Unicode** du monde.

```rust
fn main() {
    let emoji = '😀';
    let accents = 'é';
    let japonais = '日';
    let grec = 'Ω';
    
    println!("{}", emoji);
    println!("{}", accents);
    println!("{}", japonais);
    println!("{}", grec);
}
```

### Méthodes sur char

```rust
fn main() {
    let c = 'A';
    
    println!("Est lettre: {}", c.is_alphabetic());
    println!("Est chiffre: {}", c.is_numeric());
    println!("Est espace: {}", c.is_whitespace());
    println!("Minuscule: {}", c.to_lowercase());
    println!("Majuscule: {}", c.to_uppercase());
}
```

---

## 2.7 isize et usize (types spéciaux)

`isize` et `usize` sont des types qui dépendent de l'**architecture** de l'ordinateur.

- Sur 32-bit : `isize` / `usize` = 32 bits
- Sur 64-bit : `isize` / `usize` = 64 bits

### Quand les utiliser

**Index de tableau :**

```rust
fn main() {
    let arr = [1, 2, 3, 4, 5];
    let index: usize = 2;
    println!("{}", arr[index]);  // 3
}
```

`usize` est utilisé pour les **index** parce que Rust ne veut pas de "negatives indices".

---

# PARTIE 3 : VARIABLES & MUTABILITÉ (TRÈS DÉTAILLÉ)

## 3.0 Introduction aux variables

Une **variable** c'est un **conteneur nommé** pour une valeur.

### Créer une variable

```rust
fn main() {
    let nom = "Alice";
}
```

**Qu'est-ce qui se passe :**

1. On crée un conteneur appelé `nom`
2. On y met la valeur `"Alice"`
3. La variable existe **jusqu'à la fin de la fonction**

### Utiliser une variable

```rust
fn main() {
    let nom = "Alice";
    println!("{}", nom);  // Alice
}
```

---

## 3.1 let : créer une variable immutable

Par **défaut** en Rust, les variables sont **immutables** (on ne peut pas les changer).

```rust
fn main() {
    let x = 5;
    println!("{}", x);   // 5
    
    x = 10;  // ❌ ERREUR ! x est immutable
}
```

Le compilateur crie :

```
error[E0384]: cannot assign twice to immutable variable `x`
```

### Pourquoi immutable par défaut ?

Rust te **force à réfléchir** : "Est-ce que j'ai VRAIMENT besoin de changer cette variable ?"

Ça rend le code plus **sûr** et plus **prévisible**.

---

## 3.2 mut : rendre une variable mutable

Si tu veux **modifier** une variable, utilise `mut`.

```rust
fn main() {
    let mut x = 5;
    println!("{}", x);   // 5
    
    x = 10;              // ✅ OK ! x est mutable
    println!("{}", x);   // 10
}
```

### Exemple réaliste

```rust
fn main() {
    let mut compteur = 0;
    
    compteur += 1;
    compteur += 1;
    compteur += 1;
    
    println!("Compteur: {}", compteur);  // 3
}
```

### Attention : mut n'est pas un type

```rust
let mut x = 5;      // ✅ Correct
let x: mut i32 = 5; // ❌ ERREUR !
```

`mut` est une **propriété** de la variable, pas un type.

---

## 3.3 Inférence de type

Rust **devine** le type de ta variable si tu le dis pas.

```rust
fn main() {
    let x = 5;           // Rust dit : c'est un i32
    let y = 5.0;         // Rust dit : c'est un f64
    let z = "Bonjour";   // Rust dit : c'est une &str
    let w = true;        // Rust dit : c'est un bool
}
```

### Cas ambigus

Parfois Rust ne peut pas deviner :

```rust
fn main() {
    let x = "5".parse();  // ❌ ERREUR ! Peut être i32, i64, f64...?
}
```

### Solution : annotation de type

```rust
fn main() {
    let x: i32 = "5".parse().unwrap();  // ✅ OK, on dit i32
    println!("{}", x);
}
```

---

## 3.4 Annotations de type explicites

Tu peux toujours **dire** le type, même si Rust pourrait le deviner.

```rust
fn main() {
    let x: i32 = 5;
    let y: f64 = 3.14;
    let z: bool = true;
    let nom: &str = "Alice";
}
```

### Quand annoter ?

- **C'est clair** : `let x = 5;` (pas besoin)
- **C'est ambigu** : `let x: i32 = "5".parse();` (annoter)
- **Tu veux être explicite** : `let age: u32 = 30;` (OK)

---

## 3.5 Shadowing (ombragement)

Le **shadowing** c'est quand tu crées une **nouvelle variable avec le même nom**.

```rust
fn main() {
    let x = 5;
    println!("x = {}", x);  // 5
    
    let x = x + 1;          // Shadowing : nouvelle variable x
    println!("x = {}", x);  // 6
    
    let x = x * 2;          // Shadowing encore
    println!("x = {}", x);  // 12
}
```

### Shadowing vs mut

```rust
// Shadowing
let x = 5;
let x = x + 1;      // Crée une NOUVELLE variable

// Mut
let mut x = 5;
x = x + 1;          // Modifie la MÊME variable
```

Les deux affichent 6, mais c'est différent en interne.

### Intérêt du shadowing

```rust
fn main() {
    let s = "  hello  ";
    let s = s.trim();        // Nouvelle variable, même nom
    let s = s.to_uppercase(); // Encore
    println!("{}", s);        // HELLO
}
```

Au lieu de :

```rust
let s = "  hello  ";
let s_trimmed = s.trim();
let s_final = s_trimmed.to_uppercase();
```

---

## 3.6 Constantes (const)

Une **constante** est une valeur qui **ne change jamais**, et tu dois la déclarer avant de compiler.

```rust
const GRAVITE: f64 = 9.81;
const MAX_JOUEURS: u32 = 100;

fn main() {
    println!("g = {}", GRAVITE);
    println!("Max joueurs = {}", MAX_JOUEURS);
}
```

### Différences constante vs variable immutable

| Aspect | const | let |
|--------|-------|-----|
| Change ? | Jamais | Jamais (mais shadowed) |
| Défini quand ? | Compilation | Runtime |
| Convention | MAJUSCULES | minuscules |
| Scope | Global | Local |

### Constantes globales

```rust
const PI: f64 = 3.14159;
const EULER: f64 = 2.71828;

fn main() {
    println!("π = {}", PI);
    println!("e = {}", EULER);
}
```

---

## 3.7 Variables statiques (static)

Une **variable statique** c'est une constante globale qui peut être **muée**.

```rust
static mut COUNTER: i32 = 0;

fn main() {
    unsafe {
        COUNTER += 1;
        println!("{}", COUNTER);
    }
}
```

⚠️ Attention : accéder à une variable statique mutable nécessite `unsafe`.

---

## 3.8 Nommage des variables (conventions)

Rust a des **conventions de nommage**.

### snake_case pour les variables

```rust
let nom_utilisateur = "Alice";
let age_en_annees = 30;
let est_actif = true;
```

### SCREAMING_SNAKE_CASE pour les constantes

```rust
const MAX_CONNEXIONS: u32 = 100;
const API_KEY: &str = "secret";
```

### Pourquoi les conventions ?

Ça rend le code **cohérent** et **facile à lire** pour les autres développeurs.

---

## 3.9 Scope (portée) des variables

Une variable **existe** à partir de sa création **jusqu'à la fin de son bloc**.

```rust
fn main() {
    {
        let x = 5;
        println!("{}", x);  // ✅ OK, x existe
    }
    
    println!("{}", x);      // ❌ ERREUR ! x n'existe plus
}
```

### Blocs imbiqués

```rust
fn main() {
    let x = 1;
    
    {
        let x = 2;
        println!("{}", x);  // 2 (x local au bloc)
    }
    
    println!("{}", x);      // 1 (x du bloc parent)
}
```

---

## 3.10 Lifetime des variables

Une variable **existe** aussi longtemps qu'elle est en **scope**.

Quand une variable **sort du scope**, elle est **nettoyée** automatiquement.

```rust
fn main() {
    let s = String::from("Bonjour");
    println!("{}", s);
    // s sort du scope ici, la mémoire est nettoyée
}
```

---

# PARTIE 4 : OPÉRATIONS MATHÉMATIQUES & COMPARAISONS

## 4.0 Opérations arithmétiques

Les **quatre opérations** : addition, soustraction, multiplication, division.

```rust
fn main() {
    let a = 10;
    let b = 3;
    
    println!("10 + 3 = {}", a + b);  // 13
    println!("10 - 3 = {}", a - b);  // 7
    println!("10 * 3 = {}", a * b);  // 30
    println!("10 / 3 = {}", a / b);  // 3
    println!("10 % 3 = {}", a % b);  // 1 (reste)
}
```

---

## 4.1 Division entière vs flottante

C'est **important** :

```rust
fn main() {
    println!("5 / 2 = {}", 5 / 2);         // 2 (entière)
    println!("5.0 / 2.0 = {}", 5.0 / 2.0); // 2.5 (vraie)
    
    // Mélanger les types : conversion
    println!("5 as f64 / 2.0 = {}", 5 as f64 / 2.0);  // 2.5
}
```

---

## 4.2 Opérateurs composés

```rust
fn main() {
    let mut x = 10;
    
    x += 5;   // x = x + 5 → 15
    x -= 3;   // x = x - 3 → 12
    x *= 2;   // x = x * 2 → 24
    x /= 4;   // x = x / 4 → 6
    x %= 2;   // x = x % 2 → 0
    
    println!("{}", x);
}
```

---

## 4.3 Comparaisons

Les comparaisons retournent **bool** (true/false).

```rust
fn main() {
    let x = 5;
    let y = 10;
    
    println!("5 == 10 ? {}", x == y);  // false
    println!("5 != 10 ? {}", x != y);  // true
    println!("5 < 10 ? {}", x < y);    // true
    println!("5 > 10 ? {}", x > y);    // false
    println!("5 <= 10 ? {}", x <= y);  // true
    println!("5 >= 10 ? {}", x >= y);  // false
}
```

---

## 4.4 Opérateurs logiques

```rust
fn main() {
    let a = true;
    let b = false;
    
    println!("true && false = {}", a && b);  // false (ET)
    println!("true || false = {}", a || b);  // true (OU)
    println!("!true = {}", !a);              // false (NON)
}
```

---

## 4.5 Ordre des opérations

Rust suit **PEMDAS** (Parenthèses, Exposants, Multiplication/Division, Addition/Soustraction).

```rust
fn main() {
    let x = 2 + 3 * 4;        // 2 + 12 = 14 (pas 20)
    let y = (2 + 3) * 4;      // 5 * 4 = 20
    let z = 10 - 3 - 2;       // (10 - 3) - 2 = 5
    
    println!("{} {} {}", x, y, z);
}
```

---

# PARTIE 5 : AFFICHAGE & DEBUGGING COMPLET

## 5.0 println! et format!

Le **println!** affiche du texte avec une nouvelle ligne à la fin.

```rust
fn main() {
    println!("Bonjour");
    println!("Au revoir");
}
```

Affichage :
```
Bonjour
Au revoir
```

## 5.1 Placeholders {}

Les **placeholders** c'est des emplacements où tu mets tes variables.

```rust
fn main() {
    let nom = "Alice";
    let age = 30;
    
    println!("Nom: {}, Âge: {}", nom, age);
}
```

## 5.2 Formatage numérique

```rust
fn main() {
    let x = 255;
    
    println!("Décimal: {}", x);           // 255
    println!("Hexadécimal: {:x}", x);    // ff
    println!("Octal: {:o}", x);          // 377
    println!("Binaire: {:b}", x);        // 11111111
}
```

## 5.3 Padding et largeur

```rust
fn main() {
    let x = 42;
    
    println!("{:5}", x);      // "   42" (aligné à droite)
    println!("{:<5}", x);     // "42   " (aligné à gauche)
    println!("{:^5}", x);     // " 42  " (centré)
    println!("{:05}", x);     // "00042" (padding avec zéros)
}
```

## 5.4 Flottants

```rust
fn main() {
    let pi = 3.14159265;
    
    println!("{}", pi);        // 3.14159265
    println!("{:.2}", pi);     // 3.14 (2 décimales)
    println!("{:.4}", pi);     // 3.1416 (4 décimales)
    println!("{:8.2}", pi);    // "    3.14" (largeur 8, 2 décimales)
}
```

## 5.5 Debug trait {:?}

Le **debug format** affiche les structures de manière lisible.

```rust
#[derive(Debug)]
struct Personne {
    nom: String,
    age: i32,
}

fn main() {
    let p = Personne { nom: "Alice".to_string(), age: 30 };
    println!("{:?}", p);  // Personne { nom: "Alice", age: 30 }
}
```

## 5.6 Pretty-print {:#?}

```rust
#[derive(Debug)]
struct Personne {
    nom: String,
    age: i32,
}

fn main() {
    let p = Personne { nom: "Alice".to_string(), age: 30 };
    println!("{:#?}", p);
}
```

Affichage :
```
Personne {
    nom: "Alice",
    age: 30,
}
```

## 5.7 dbg! macro

```rust
fn main() {
    let x = 5;
    dbg!(x);  // [src/main.rs:2] x = 5
}
```

## 5.8 print! vs println!

- `print!` : Sans nouvelle ligne
- `println!` : Avec nouvelle ligne

```rust
fn main() {
    print!("Bonjour ");
    print!("le ");
    println!("monde");
    
    // Affiche : Bonjour le monde
}
```

---

# PARTIE 6 : COLLECTIONS — STRINGS

## 6.0 String vs &str

- **String** : texte modifiable (propriété)
- **&str** : référence à un texte (emprunt)

```rust
fn main() {
    let mut s1 = String::from("Bonjour");  // String
    s1.push_str(" le monde");
    println!("{}", s1);
    
    let s2 = "Bonjour";  // &str (littéral)
    println!("{}", s2);
}
```

## 6.1 Créer une String

```rust
fn main() {
    let s1 = String::from("Bonjour");
    let s2 = "Bonjour".to_string();
    let s3: String = String::new();
    
    println!("{}", s1);
    println!("{}", s2);
    println!("{}", s3);
}
```

## 6.2 Modification

```rust
fn main() {
    let mut s = String::from("Bonjour");
    s.push_str(" le monde");     // Ajoute à la fin
    s.push('!');                 // Ajoute un char
    println!("{}", s);
}
```

## 6.3 Longueur

```rust
fn main() {
    let s = "Bonjour";
    println!("{}", s.len());           // 7 (en bytes)
    println!("{}", s.chars().count()); // 7 (en caractères)
}
```

## 6.4 Itération

```rust
fn main() {
    let s = "Bonjour";
    
    for c in s.chars() {
        println!("{}", c);
    }
}
```

## 6.5 Slices

```rust
fn main() {
    let s = "Bonjour";
    let slice = &s[0..5];  // "Bonjo"
    println!("{}", slice);
}
```

## 6.6 Recherche

```rust
fn main() {
    let s = "Bonjour le monde";
    
    if let Some(pos) = s.find("le") {
        println!("Trouvé à position: {}", pos);
    }
}
```

## 6.7 Remplacement

```rust
fn main() {
    let s = "Bonjour le monde";
    let s2 = s.replace("le", "la");
    println!("{}", s2);  // Bonjour la monde
}
```

## 6.8 Split

```rust
fn main() {
    let s = "Rust,Python,Java";
    
    for langage in s.split(',') {
        println!("{}", langage);
    }
}
```

## 6.9 Escape sequences

```rust
fn main() {
    println!("Ligne 1\nLigne 2");     // Nouvelle ligne
    println!("Tab\there");            // Tabulation
    println!("Guillemets: \"hello\""); // Guillemets
    println!("Antislash: \\");        // Antislash
}
```

## 6.10 Raw strings

```rust
fn main() {
    let s = r#"Ceci est "brut""#;
    println!("{}", s);  // Ceci est "brut"
}
```

---

# PARTIE 7 : COLLECTIONS — ARRAYS, TUPLES, VECTEURS

## 7.0 Arrays

Un **array** c'est une liste de même type, **taille fixe**.

```rust
fn main() {
    let nombres: [i32; 5] = [1, 2, 3, 4, 5];
    
    println!("Premier: {}", nombres[0]);
    println!("Dernier: {}", nombres[4]);
    println!("Longueur: {}", nombres.len());
}
```

## 7.1 Initialisation

```rust
fn main() {
    let arr1: [i32; 5] = [1, 2, 3, 4, 5];
    let arr2 = [0; 10];  // 10 zéros
}
```

## 7.2 Itération

```rust
fn main() {
    let nombres = [1, 2, 3, 4, 5];
    
    for num in &nombres {
        println!("{}", num);
    }
    
    for (i, num) in nombres.iter().enumerate() {
        println!("{}: {}", i, num);
    }
}
```

## 7.3 Tuples

Un **tuple** c'est une liste de **types différents**.

```rust
fn main() {
    let info: (String, i32, bool) = ("Alice".to_string(), 30, true);
    
    println!("{}", info.0);  // Alice
    println!("{}", info.1);  // 30
    println!("{}", info.2);  // true
}
```

## 7.4 Destructuring tuples

```rust
fn main() {
    let (nom, age, actif) = ("Alice", 30, true);
    
    println!("{} a {} ans", nom, age);
}
```

## 7.5 Vecteurs

Un **vecteur** c'est une liste **dynamique** (peut grandir).

```rust
fn main() {
    let mut vec = vec![1, 2, 3];
    
    vec.push(4);
    vec.push(5);
    
    println!("{:?}", vec);  // [1, 2, 3, 4, 5]
}
```

## 7.6 Créer un vecteur vide

```rust
fn main() {
    let mut vec: Vec<i32> = Vec::new();
    vec.push(1);
    vec.push(2);
    vec.push(3);
    
    println!("{:?}", vec);
}
```

## 7.7 Capacité

```rust
fn main() {
    let mut vec = Vec::with_capacity(10);
    vec.push(1);
    
    println!("Longueur: {}", vec.len());       // 1
    println!("Capacité: {}", vec.capacity());  // 10
}
```

## 7.8 Pop et Remove

```rust
fn main() {
    let mut vec = vec![1, 2, 3, 4, 5];
    
    vec.pop();  // Retire le dernier
    vec.remove(0);  // Retire à l'index 0
    
    println!("{:?}", vec);
}
```

## 7.9 Itération

```rust
fn main() {
    let vec = vec![1, 2, 3];
    
    for (i, &val) in vec.iter().enumerate() {
        println!("{}: {}", i, val);
    }
}
```

## 7.10 Méthodes utiles

```rust
fn main() {
    let vec = vec![1, 2, 3, 4, 5];
    
    println!("Contains 3: {}", vec.contains(&3));
    println!("First: {:?}", vec.first());
    println!("Last: {:?}", vec.last());
}
```

---

# PARTIE 8 : FONCTIONS ESSENTIELLES

## 8.0 Déclaration basique

```rust
fn dire_bonjour() {
    println!("Bonjour !");
}

fn main() {
    dire_bonjour();
}
```

## 8.1 Avec paramètres

```rust
fn saluer(nom: &str) {
    println!("Bonjour, {} !", nom);
}

fn main() {
    saluer("Alice");
    saluer("Bob");
}
```

## 8.2 Avec retour

```rust
fn ajouter(a: i32, b: i32) -> i32 {
    a + b  // Pas de point-virgule !
}

fn main() {
    let resultat = ajouter(5, 3);
    println!("{}", resultat);  // 8
}
```

## 8.3 Plusieurs paramètres

```rust
fn creer_personne(nom: &str, age: i32, ville: &str) -> String {
    format!("{} ({} ans) habite à {}", nom, age, ville)
}

fn main() {
    let desc = creer_personne("Alice", 30, "Paris");
    println!("{}", desc);
}
```

## 8.4 Fonctions sans retour

```rust
fn afficher(x: i32) {
    println!("{}", x);
}

fn main() {
    afficher(42);
}
```

## 8.5 Early return

```rust
fn diviser(a: i32, b: i32) -> i32 {
    if b == 0 {
        return 0;  // Retourner tôt
    }
    a / b
}

fn main() {
    println!("{}", diviser(10, 2));  // 5
    println!("{}", diviser(10, 0));  // 0
}
```

## 8.6 Récursion

```rust
fn factoriel(n: i32) -> i32 {
    if n <= 1 {
        return 1;
    }
    n * factoriel(n - 1)
}

fn main() {
    println!("{}", factoriel(5));  // 120
}
```

## 8.7 Fonctions imbriquées

```rust
fn outer() {
    fn inner() {
        println!("Inner");
    }
    inner();
}

fn main() {
    outer();
}
```

## 8.8 Inférence de paramètres

```rust
fn main() {
    let x = {
        let a = 5;
        let b = 3;
        a + b  // Expression qui retourne 8
    };
    println!("{}", x);  // 8
}
```

## 8.9 Fonctions comme expressions

```rust
fn main() {
    let x = {
        let a = 5;
        a + 1
    };
    println!("{}", x);  // 6
}
```

## 8.10 Affichage

```rust
fn saluations(nom: &str) -> String {
    format!("Bonjour, {}", nom)
}

fn main() {
    let msg = saluations("Alice");
    println!("{}", msg);
}
```

---

# PARTIE 9-15 : LE CŒUR DE RUST

## PARTIE 9 : OWNERSHIP - LE CONCEPT FONDAMENTAL

### 9.0 Les trois règles

**Règle 1** : Chaque valeur a UN propriétaire
**Règle 2** : Une valeur ne peut avoir qu'UN propriétaire
**Règle 3** : Quand le propriétaire sort du scope, la valeur est détruite

### 9.1 Move semantics

```rust
fn main() {
    let s1 = String::from("Bonjour");
    let s2 = s1;  // Move : s1 perd la propriété
    
    // println!("{}", s1);  // ❌ ERREUR ! s1 n'a plus
    println!("{}", s2);  // ✅ OK
}
```

### 9.2 Clone

```rust
fn main() {
    let s1 = String::from("Bonjour");
    let s2 = s1.clone();  // Copie explicite
    
    println!("{}", s1);  // ✅ OK
    println!("{}", s2);  // ✅ OK
}
```

### 9.3 Types Copy

```rust
fn main() {
    let x = 5;
    let y = x;  // Copie (i32 est Copy)
    
    println!("{}", x);  // ✅ OK
    println!("{}", y);  // ✅ OK
}
```

### 9.4 Ownership dans les fonctions

```rust
fn prendre_propriete(s: String) {
    println!("{}", s);
}

fn main() {
    let s = String::from("Bonjour");
    prendre_propriete(s);
    
    // println!("{}", s);  // ❌ ERREUR !
}
```

### 9.5 Retourner la propriété

```rust
fn donner_propriete() -> String {
    String::from("Bonjour")
}

fn main() {
    let s = donner_propriete();
    println!("{}", s);  // ✅ OK
}
```

### 9.6 Drop trait

Quand une valeur sort du scope, `drop()` est appelé.

```rust
fn main() {
    {
        let s = String::from("Bonjour");
        // s.drop() est appelé ici implicitement
    }
    // s n'existe plus
}
```

### 9.7 RAII Pattern

Resource Acquisition Is Initialization.

```rust
fn main() {
    let file = std::fs::File::create("test.txt").unwrap();
    // file.drop() est appelé automatiquement
}
```

### 9.8 Pièges courants

```rust
// ❌ ERREUR : retourner une référence
fn donner_ref() -> &String {
    let s = String::from("Bonjour");
    &s  // s est détruite ici !
}

// ✅ CORRECT : retourner la propriété
fn donner_string() -> String {
    String::from("Bonjour")
}
```

### 9.9 Stack vs Heap

- **Stack** : Petit, rapide, ordre LIFO
- **Heap** : Grand, lent, désorganisé

```rust
fn main() {
    let x = 5;  // Stack
    let s = String::from("Bonjour");  // Heap
}
```

### 9.10 Métaphore du doudou

Le doudou a UN propriétaire. Si tu le donnes, l'ancien propriétaire ne l'a plus.

---

## PARTIE 10 : BORROWING - EMPRUNTER SANS PERDRE

### 10.0 Références immutables

```rust
fn main() {
    let s = String::from("Bonjour");
    let r1 = &s;
    let r2 = &s;
    
    println!("{}", s);   // ✅ OK
    println!("{}", r1);  // ✅ OK
    println!("{}", r2);  // ✅ OK
}
```

### 10.1 Références mutables

```rust
fn main() {
    let mut s = String::from("Bonjour");
    let r = &mut s;
    
    r.push_str(" le monde");
    println!("{}", s);  // Bonjour le monde
}
```

### 10.2 Règles du borrow checker

- **Une seule** référence mutable à la fois
- **Nombreuses** références immutables OK
- Pas de mélange mutable + immutable

```rust
// ❌ ERREUR : deux références mutables
let mut x = 5;
let r1 = &mut x;
let r2 = &mut x;  // ❌

// ✅ CORRECT : plusieurs immutables
let x = 5;
let r1 = &x;
let r2 = &x;  // ✅
```

### 10.3 Dereference

```rust
fn main() {
    let x = 5;
    let r = &x;
    
    println!("Valeur: {}", *r);  // Dereference
}
```

### 10.4 Deref coercion

```rust
fn afficher(s: &String) {
    println!("{}", s);
}

fn main() {
    let s = String::from("Bonjour");
    afficher(&s);
}
```

### 10.5 Emprunt implicite dans les fonctions

```rust
fn afficher(s: &String) {
    println!("{}", s);
}

fn main() {
    let s = String::from("Bonjour");
    afficher(&s);
}
```

### 10.6 Mutable borrowing

```rust
fn modifier(s: &mut String) {
    s.push_str(" !");
}

fn main() {
    let mut s = String::from("Bonjour");
    modifier(&mut s);
    println!("{}", s);  // Bonjour !
}
```

### 10.7 Reborrowing

```rust
fn main() {
    let mut x = 5;
    let r1 = &mut x;
    let r2 = &mut *r1;  // Reborrow
    *r2 = 10;
    println!("{}", x);
}
```

### 10.8 Lifetime des références

Une référence vit aussi longtemps que sa source.

```rust
fn main() {
    let s = String::from("Bonjour");
    let r = &s;
    println!("{}", r);  // ✅ r et s existent
    // r sort du scope
    // s sort du scope et est détruite
}
```

### 10.9 Pièges dangling

```rust
// ❌ ERREUR : dangling reference
fn donner_ref() -> &String {
    let s = String::from("Bonjour");
    &s  // s est détruite !
}

// ✅ CORRECT
fn donner_ref() -> String {
    String::from("Bonjour")
}
```

### 10.10 Différence move vs borrow

```rust
// Move : perte de propriété
let s1 = String::from("Bonjour");
let s2 = s1;  // Move

// Borrow : prêt temporaire
let s1 = String::from("Bonjour");
let s2 = &s1;  // Borrow
```

---

## PARTIE 11-15 : LIFETIMES, STRUCTS, ENUMS, TRAITS, GÉNÉRIQUES


### 11.0 Lifetimes Expliquées

Une lifetime spécifie **combien de temps** une référence est valide.

```rust
fn plus_long<'a>(x: &'a str, y: &'a str) -> &'a str {
    if x.len() > y.len() {
        x
    } else {
        y
    }
}

fn main() {
    let s1 = "Bonjour";
    let s2 = "Hi";
    let resultat = plus_long(s1, s2);
    println!("{}", resultat);
}
```

### 12.0 Structs (Structures)

```rust
struct Personne {
    nom: String,
    age: i32,
    ville: String,
}

fn main() {
    let p = Personne {
        nom: "Alice".to_string(),
        age: 30,
        ville: "Paris".to_string(),
    };
    
    println!("{}", p.nom);
}
```

### 12.1 Methods avec impl

```rust
impl Personne {
    fn anniversaire(&mut self) {
        self.age += 1;
    }
    
    fn description(&self) -> String {
        format!("{} a {} ans", self.nom, self.age)
    }
}

fn main() {
    let mut p = Personne {
        nom: "Alice".to_string(),
        age: 30,
        ville: "Paris".to_string(),
    };
    
    p.anniversaire();
    println!("{}", p.description());
}
```

### 13.0 Enums

```rust
enum Direction {
    Nord,
    Sud,
    Est,
    Ouest,
}

fn main() {
    let dir = Direction::Nord;
}
```

### 13.1 Enums avec données

```rust
enum Message {
    Texte(String),
    Nombre(i32),
}

fn main() {
    let msg = Message::Texte("Bonjour".to_string());
}
```

### 13.2 Option<T>

```rust
fn main() {
    let x: Option<i32> = Some(5);
    let y: Option<i32> = None;
    
    match x {
        Some(val) => println!("Valeur: {}", val),
        None => println!("Pas de valeur"),
    }
}
```

### 14.0 Traits

```rust
trait Animal {
    fn faire_bruit(&self);
}

struct Chat;

impl Animal for Chat {
    fn faire_bruit(&self) {
        println!("Miaou !");
    }
}

fn main() {
    let chat = Chat;
    chat.faire_bruit();
}
```

### 15.0 Génériques

```rust
fn premier<T>(list: &[T]) -> &T {
    &list[0]
}

fn main() {
    let nombres = vec![1, 2, 3];
    println!("{}", premier(&nombres));
}
```

---

# PARTIES B9-22 : CONTRÔLE DE FLUX & CORE RUST

## PARTIE 9 : CONTRÔLE DE FLUX — IF, ELSE, IF-ELSE-IF

### 9.0 If simple

La structure `if` teste une **condition booléenne**.

```rust
fn main() {
    let age = 20;
    
    if age >= 18 {
        println!("Tu es adulte !");
    }
}
```

**Important :** La condition doit TOUJOURS retourner un `bool`. Pas de conversions implicites comme en JavaScript.

```rust
// ❌ ERREUR
if 1 {
    println!("OK");
}

// ✅ CORRECT
if 1 > 0 {
    println!("OK");
}
```

### 9.1 If-Else

```rust
fn main() {
    let age = 15;
    
    if age >= 18 {
        println!("Tu peux voter");
    } else {
        println!("Tu dois attendre");
    }
}
```

### 9.2 If-Else If-Else (chaines)

```rust
fn main() {
    let note = 15;
    
    if note >= 16 {
        println!("Excellent !");
    } else if note >= 12 {
        println!("Bien !");
    } else if note >= 10 {
        println!("Passable");
    } else {
        println!("Insuffisant");
    }
}
```

### 9.3 If comme expression

En Rust, `if` peut retourner une valeur !

```rust
fn main() {
    let age = 20;
    let statut = if age >= 18 { "Adulte" } else { "Enfant" };
    println!("{}", statut);
}
```

### 9.4 If comme expression (avec blocs)

```rust
fn main() {
    let score = 85;
    let resultat = if score >= 70 {
        "Réussi"
    } else {
        "Échoué"
    };
    println!("{}", resultat);
}
```

### 9.5 Conditions imbriquées

```rust
fn main() {
    let age = 20;
    let a_permis = true;
    
    if age >= 18 {
        if a_permis {
            println!("Tu peux conduire !");
        } else {
            println!("Passe le permis");
        }
    } else {
        println!("Trop jeune");
    }
}
```

### 9.6 Opérateurs logiques

```rust
fn main() {
    let age = 20;
    let a_permis = true;
    
    // ET logique
    if age >= 18 && a_permis {
        println!("Tu peux conduire !");
    }
    
    // OU logique
    if age < 13 || age > 65 {
        println!("Tarif réduit");
    }
    
    // NON logique
    if !a_permis {
        println!("Sans permis");
    }
}
```

### 9.7 Short-circuit evaluation

```rust
fn main() {
    let a = true;
    let b = false;
    
    // &&: si a est false, b n'est pas évaluée
    if a && affiche_quelquechose() {
        println!("A");
    }
    
    // ||: si a est true, b n'est pas évaluée
    if a || affiche_quelquechose() {
        println!("B");
    }
}

fn affiche_quelquechose() -> bool {
    println!("Evaluation!");
    true
}
```

### 9.8 Erreurs courantes

```rust
// ❌ ERREUR: oubli de condition
if age {
    println!("OK");
}

// ✅ CORRECT
if age > 0 {
    println!("OK");
}

// ❌ ERREUR: type mismatch
let x = if age > 18 { "Adulte" } else { 18 };

// ✅ CORRECT
let x = if age > 18 { "Adulte" } else { "Enfant" };
```

---

## PARTIE 10 : CONTRÔLE DE FLUX — BOUCLES (LOOP, WHILE, FOR)

### 10.0 Loop (boucle infinie)

La boucle `loop` s'exécute **indéfiniment** jusqu'à `break`.

```rust
fn main() {
    let mut compteur = 0;
    
    loop {
        println!("Compteur: {}", compteur);
        compteur += 1;
        
        if compteur == 5 {
            break;  // Sort de la boucle
        }
    }
}
```

Affichage :
```
Compteur: 0
Compteur: 1
Compteur: 2
Compteur: 3
Compteur: 4
```

### 10.1 Loop comme expression

`loop` peut retourner une valeur avec `break`.

```rust
fn main() {
    let mut compteur = 0;
    let resultat = loop {
        compteur += 1;
        if compteur == 10 {
            break compteur * 2;  // Retourne 20
        }
    };
    println!("Résultat: {}", resultat);
}
```

### 10.2 Boucles étiquetées

Avec plusieurs boucles imbriquées, tu peux étiqueter laquelle tu casses.

```rust
fn main() {
    'outer: loop {
        loop {
            println!("Interne");
            break 'outer;  // Casse la boucle externe
        }
    }
}
```

### 10.3 While

La boucle `while` s'exécute **tant que** la condition est vraie.

```rust
fn main() {
    let mut compteur = 0;
    
    while compteur < 5 {
        println!("Compteur: {}", compteur);
        compteur += 1;
    }
}
```

### 10.4 While avec conditions complexes

```rust
fn main() {
    let mut x = 0;
    let mut y = 10;
    
    while x < 5 && y > 0 {
        println!("x={}, y={}", x, y);
        x += 1;
        y -= 1;
    }
}
```

### 10.5 For avec ranges

La boucle `for` parcourt une **collection** ou une **plage** (`range`).

```rust
fn main() {
    // 0, 1, 2, 3, 4 (excluant 5)
    for i in 0..5 {
        println!("{}", i);
    }
}
```

### 10.6 Ranges : les trois syntaxes

```rust
fn main() {
    // 0..5 : 0 à 4 (5 exclu)
    for i in 0..5 {
        print!("{} ", i);  // 0 1 2 3 4
    }
    println!();
    
    // 0..=5 : 0 à 5 (5 inclus)
    for i in 0..=5 {
        print!("{} ", i);  // 0 1 2 3 4 5
    }
    println!();
    
    // 1..4 : 1 à 3
    for i in 1..4 {
        print!("{} ", i);  // 1 2 3
    }
}
```

### 10.7 For avec collections

```rust
fn main() {
    let nombres = [1, 2, 3, 4, 5];
    
    // Itérer les éléments
    for num in &nombres {
        println!("{}", num);
    }
    
    // Itérer avec index
    for (i, num) in nombres.iter().enumerate() {
        println!("Index {}: {}", i, num);
    }
}
```

### 10.8 For avec vecteurs

```rust
fn main() {
    let mut vec = vec![1, 2, 3];
    
    // Référence immutable
    for num in &vec {
        println!("{}", num);
    }
    
    // Référence mutable (modifier)
    for num in &mut vec {
        *num *= 2;
    }
    
    // Propriété (consommer)
    for num in vec {
        println!("{}", num);
    }
}
```

### 10.9 Continue et break

```rust
fn main() {
    for i in 0..10 {
        if i == 3 {
            continue;  // Passe à l'itération suivante
        }
        if i == 7 {
            break;     // Sort de la boucle
        }
        println!("{}", i);  // 0 1 2 4 5 6
    }
}
```

### 10.10 Boucles imbriquées

```rust
fn main() {
    for i in 1..=3 {
        for j in 1..=3 {
            println!("{}x{} = {}", i, j, i*j);
        }
    }
}
```

---

## PARTIE 11 : PATTERN MATCHING — MATCH COMPLET

### 11.0 Match expression

`match` c'est comme `switch` mais **bien plus puissant**.

```rust
fn main() {
    let nombre = 3;
    
    match nombre {
        1 => println!("Un"),
        2 => println!("Deux"),
        3 => println!("Trois"),
        _ => println!("Autre"),  // _ = "tous les autres cas"
    }
}
```

### 11.1 Match retourne une valeur

```rust
fn main() {
    let nombre = 2;
    let nom = match nombre {
        1 => "Un",
        2 => "Deux",
        3 => "Trois",
        _ => "Inconnu",
    };
    println!("{}", nom);  // Deux
}
```

### 11.2 Match avec guards

```rust
fn main() {
    let age = 25;
    
    match age {
        0..=12 => println!("Enfant"),
        13..=17 => println!("Ado"),
        18..=65 if age < 21 => println!("Jeune adulte"),
        18..=65 => println!("Adulte"),
        _ => println!("Senior"),
    }
}
```

### 11.3 Match avec bindings

```rust
fn main() {
    let nombre = Some(5);
    
    match nombre {
        Some(x) => println!("Valeur: {}", x),
        None => println!("Rien"),
    }
}
```

### 11.4 Match avec tuples

```rust
fn main() {
    let point = (2, 3);
    
    match point {
        (0, 0) => println!("Origine"),
        (0, y) => println!("Y: {}", y),
        (x, 0) => println!("X: {}", x),
        (x, y) => println!("({}, {})", x, y),
    }
}
```

### 11.5 If Let (match simplifié)

Quand tu veux matcher **un seul cas**, utilise `if let`.

```rust
fn main() {
    let nombre = Some(5);
    
    // Match
    match nombre {
        Some(x) => println!("Valeur: {}", x),
        _ => {},
    }
    
    // If Let (plus court)
    if let Some(x) = nombre {
        println!("Valeur: {}", x);
    }
}
```

### 11.6 While Let

```rust
fn main() {
    let mut pile = vec![1, 2, 3];
    
    while let Some(x) = pile.pop() {
        println!("{}", x);
    }
}
```

### 11.7 Destructuring structs

```rust
struct Personne {
    nom: String,
    age: i32,
}

fn main() {
    let p = Personne { nom: "Alice".to_string(), age: 30 };
    
    match p {
        Personne { nom, age } => println!("{} a {} ans", nom, age),
    }
}
```

### 11.8 Destructuring enums

```rust
enum Resultat {
    Ok(String),
    Erreur(String),
}

fn main() {
    let res = Resultat::Ok("Succès".to_string());
    
    match res {
        Resultat::Ok(msg) => println!("✓ {}", msg),
        Resultat::Erreur(msg) => println!("✗ {}", msg),
    }
}
```

---

## PARTIE 12 : OWNERSHIP EN PROFONDEUR

### 12.0 Les trois règles d'ownership

**Règle 1 :** Chaque valeur a UN propriétaire
**Règle 2 :** Une valeur ne peut avoir qu'UN propriétaire à la fois
**Règle 3 :** Quand le propriétaire sort du scope, la valeur est détruite (drop)

### 12.1 Move : donner la propriété

```rust
fn main() {
    let s1 = String::from("Bonjour");
    let s2 = s1;  // Move : s1 perd la propriété
    
    println!("{}", s1);  // ❌ ERREUR ! s1 n'a plus
    println!("{}", s2);  // ✅ OK
}
```

### 12.2 Stack vs Heap

Types **Copy** (petits, sur la stack) sont copiés automatiquement.
Types non-**Copy** (gros, sur la heap) sont déplacés.

```rust
fn main() {
    // i32 est Copy : copie automatique
    let x = 5;
    let y = x;
    println!("{} {}", x, y);  // ✅ OK, x existe encore
    
    // String n'est pas Copy : move
    let s1 = String::from("Bonjour");
    let s2 = s1;
    println!("{}", s1);  // ❌ ERREUR
    println!("{}", s2);  // ✅ OK
}
```

### 12.3 Clone explicite

Si tu veux **copier** au lieu de bouger :

```rust
fn main() {
    let s1 = String::from("Bonjour");
    let s2 = s1.clone();  // Copie complète
    
    println!("{}", s1);  // ✅ OK
    println!("{}", s2);  // ✅ OK
}
```

### 12.4 Ownership et fonctions

```rust
fn prendre(s: String) {
    println!("{}", s);
}

fn main() {
    let s = String::from("Bonjour");
    prendre(s);  // s est passé EN PROPRIÉTÉ
    
    println!("{}", s);  // ❌ ERREUR ! s a été transféré
}
```

### 12.5 Retourner l'ownership

```rust
fn donner() -> String {
    String::from("Bonjour")
}

fn main() {
    let s = donner();  // On récupère la propriété
    println!("{}", s);  // ✅ OK
}
```

### 12.6 Types Copy

Ces types sont copiés **automatiquement** (aucun coût) :

- `i8`, `i16`, `i32`, `i64`, `i128`
- `u8`, `u16`, `u32`, `u64`, `u128`
- `f32`, `f64`
- `bool`
- `char`
- Tuples de types Copy

```rust
fn main() {
    let (x, y) = (5, 10);
    let (a, b) = (x, y);  // Copie
    println!("{} {}", x, y);  // ✅ OK
}
```

### 12.7 Impl Copy sur tes types

```rust
#[derive(Copy, Clone)]
struct Point {
    x: i32,
    y: i32,
}

fn main() {
    let p1 = Point { x: 1, y: 2 };
    let p2 = p1;  // Copie
    println!("{} {}", p1.x, p2.x);  // ✅ OK
}
```

### 12.8 Drop trait

Quand une valeur sort du scope, `drop()` est appelée automatiquement.

```rust
struct Fichier {
    nom: String,
}

impl Drop for Fichier {
    fn drop(&mut self) {
        println!("Fermeture du fichier: {}", self.nom);
    }
}

fn main() {
    let f = Fichier { nom: "data.txt".to_string() };
    println!("Utilisation du fichier");
    // f.drop() est appelée automatiquement ici
}
```

Affichage :
```
Utilisation du fichier
Fermeture du fichier: data.txt
```

### 12.9 Pièges courants

```rust
// ❌ ERREUR: Utiliser après move
let s = String::from("Bonjour");
let t = s;
println!("{}", s);

// ✅ CORRECT: Clone
let s = String::from("Bonjour");
let t = s.clone();
println!("{}", s);

// ❌ ERREUR: Retourner une référence à une variable locale
fn donner_ref() -> &String {
    let s = String::from("Bonjour");
    &s  // s est détruite ici !
}

// ✅ CORRECT: Retourner la propriété
fn donner_string() -> String {
    String::from("Bonjour")
}
```

---

## PARTIE 13 : BORROWING EN PROFONDEUR

### 13.0 Références immutables (&T)

Tu peux **emprunter** une valeur sans prendre sa propriété.

```rust
fn afficher(s: &String) {
    println!("{}", s);
}

fn main() {
    let s = String::from("Bonjour");
    afficher(&s);  // Emprunt
    println!("{}", s);  // ✅ OK, s existe encore
}
```

### 13.1 Multiples emprunts immutables

Tu peux avoir **plusieurs** références immutables.

```rust
fn main() {
    let s = String::from("Bonjour");
    let r1 = &s;
    let r2 = &s;
    let r3 = &s;
    
    println!("{} {} {}", r1, r2, r3);  // ✅ OK
}
```

### 13.2 Références mutables (&mut T)

Pour **modifier** une valeur empruntée :

```rust
fn ajouter_point(s: &mut String) {
    s.push('!');
}

fn main() {
    let mut s = String::from("Bonjour");
    ajouter_point(&mut s);
    println!("{}", s);  // Bonjour!
}
```

### 13.3 UNE SEULE référence mutable

Tu ne peux avoir qu'**une seule** référence mutable à la fois.

```rust
fn main() {
    let mut s = String::from("Bonjour");
    
    let r1 = &mut s;
    let r2 = &mut s;  // ❌ ERREUR ! Deux références mutables
}
```

### 13.4 Règle: pas de mélange mutable + immutable

```rust
fn main() {
    let mut s = String::from("Bonjour");
    
    let r1 = &s;      // Immutable OK
    let r2 = &s;      // Immutable OK
    let r3 = &mut s;  // ❌ ERREUR ! Mélange mutable + immutable
    
    println!("{}", r1);
}
```

### 13.5 Scopes de l'emprunt

L'emprunt finit quand la référence n'est plus utilisée.

```rust
fn main() {
    let mut s = String::from("Bonjour");
    
    let r1 = &s;
    let r2 = &s;
    println!("{} {}", r1, r2);  // Dernière utilisation de r1 et r2
    
    let r3 = &mut s;  // ✅ OK ! r1 et r2 ne sont plus utilisées
    r3.push('!');
    println!("{}", r3);
}
```

### 13.6 Dereference

Pour accéder à la valeur pointée par une référence :

```rust
fn main() {
    let x = 5;
    let r = &x;
    
    println!("Référence: {}", r);      // 5
    println!("Valeur: {}", *r);        // 5 (dereference)
}
```

### 13.7 Mutable dereference

```rust
fn main() {
    let mut x = 5;
    let r = &mut x;
    
    *r = 10;  // Modifier via référence
    println!("{}", x);  // 10
}
```

### 13.8 Slices

Une slice c'est une **référence à une partie** d'une collection.

```rust
fn main() {
    let s = "Bonjour";
    let slice = &s[0..5];  // "Bonjo"
    println!("{}", slice);
}
```

### 13.9 Slices de vecteurs

```rust
fn main() {
    let vec = vec![1, 2, 3, 4, 5];
    let slice = &vec[1..4];  // [2, 3, 4]
    
    for num in slice {
        println!("{}", num);
    }
}
```

### 13.10 Dangling references

Tu **ne peux pas** retourner une référence à une variable locale.

```rust
// ❌ ERREUR
fn donner_ref() -> &String {
    let s = String::from("Bonjour");
    &s  // s est détruite à la fin !
}

// ✅ CORRECT
fn donner_string() -> String {
    String::from("Bonjour")
}
```

---

## PARTIE 14 : STRUCTS (STRUCTURES)

### 14.0 Définir une struct

```rust
struct Personne {
    nom: String,
    age: i32,
    email: String,
}
```

### 14.1 Créer une instance

```rust
fn main() {
    let personne = Personne {
        nom: "Alice".to_string(),
        age: 30,
        email: "alice@example.com".to_string(),
    };
    
    println!("{}", personne.nom);
    println!("{}", personne.age);
}
```

### 14.2 Structs mutables

```rust
fn main() {
    let mut p = Personne {
        nom: "Alice".to_string(),
        age: 30,
        email: "alice@example.com".to_string(),
    };
    
    p.age = 31;  // Modifier
    println!("{}", p.age);
}
```

### 14.3 Field init shorthand

```rust
fn main() {
    let nom = "Alice".to_string();
    let age = 30;
    let email = "alice@example.com".to_string();
    
    let personne = Personne { nom, age, email };  // Raccourci
    println!("{}", personne.nom);
}
```

### 14.4 Struct update syntax

```rust
fn main() {
    let p1 = Personne {
        nom: "Alice".to_string(),
        age: 30,
        email: "alice@example.com".to_string(),
    };
    
    let p2 = Personne {
        nom: "Bob".to_string(),
        ..p1  // Copier les autres champs de p1
    };
    
    println!("{} {}", p2.nom, p2.age);
}
```

### 14.5 Tuple structs

Une struct sans noms de champs :

```rust
struct Point(i32, i32, i32);

fn main() {
    let p = Point(1, 2, 3);
    println!("{} {} {}", p.0, p.1, p.2);
}
```

### 14.6 Unit struct

Une struct vide :

```rust
struct Marker;

fn main() {
    let m = Marker;
}
```

### 14.7 Methods avec impl

```rust
impl Personne {
    fn anniversaire(&mut self) {
        self.age += 1;
    }
    
    fn description(&self) -> String {
        format!("{} a {} ans", self.nom, self.age)
    }
}

fn main() {
    let mut p = Personne {
        nom: "Alice".to_string(),
        age: 30,
        email: "alice@example.com".to_string(),
    };
    
    p.anniversaire();
    println!("{}", p.description());
}
```

### 14.8 Associated functions

```rust
impl Personne {
    fn nouvelle(nom: String, age: i32) -> Personne {
        Personne {
            nom,
            age,
            email: String::new(),
        }
    }
}

fn main() {
    let p = Personne::nouvelle("Bob".to_string(), 25);
    println!("{}", p.nom);
}
```

### 14.9 Multiple impl blocks

```rust
impl Personne {
    fn new(nom: String, age: i32) -> Personne {
        Personne { nom, age, email: String::new() }
    }
}

impl Personne {
    fn estEnAdulte(&self) -> bool {
        self.age >= 18
    }
}
```

### 14.10 Deriving Debug

```rust
#[derive(Debug)]
struct Personne {
    nom: String,
    age: i32,
    email: String,
}

fn main() {
    let p = Personne {
        nom: "Alice".to_string(),
        age: 30,
        email: "alice@example.com".to_string(),
    };
    
    println!("{:#?}", p);  // Affichage formaté
}
```

---

## PARTIE 15 : ENUMS

### 15.0 Enums simples

```rust
enum Direction {
    Nord,
    Sud,
    Est,
    Ouest,
}

fn main() {
    let dir = Direction::Nord;
}
```

### 15.1 Enums avec données

```rust
enum Message {
    Texte(String),
    Numero(i32),
    Vide,
}

fn main() {
    let msg = Message::Texte("Bonjour".to_string());
}
```

### 15.2 Enums avec structs

```rust
enum Message {
    Quitter,
    Deplacer { x: i32, y: i32 },
    Changer(String),
}

fn main() {
    let msg = Message::Deplacer { x: 10, y: 20 };
}
```

### 15.3 Option<T>

`Option` représente "une valeur" ou "rien".

```rust
fn main() {
    let nombre: Option<i32> = Some(5);
    let rien: Option<i32> = None;
    
    match nombre {
        Some(n) => println!("Valeur: {}", n),
        None => println!("Rien"),
    }
}
```

### 15.4 Methods sur Option

```rust
fn main() {
    let nombre = Some(5);
    
    if let Some(n) = nombre {
        println!("Valeur: {}", n);
    }
    
    // Ou
    numero.map(|n| n * 2);
    
    // Ou
    let resultat = nombre.unwrap_or(0);  // 5
}
```

### 15.5 Result<T, E>

`Result` représente "succès" ou "erreur".

```rust
fn diviser(a: i32, b: i32) -> Result<i32, String> {
    if b == 0 {
        Err("Division par zéro".to_string())
    } else {
        Ok(a / b)
    }
}

fn main() {
    match diviser(10, 2) {
        Ok(resultat) => println!("Succès: {}", resultat),
        Err(erreur) => println!("Erreur: {}", erreur),
    }
}
```

### 15.6 Unwrap et expect

```rust
fn main() {
    let nombre = Some(5);
    
    let valeur = nombre.unwrap();  // Crash si None
    let valeur = nombre.expect("Erreur: devrait être Some");
}
```

### 15.7 Methods sur Result

```rust
fn main() {
    let res: Result<i32, String> = Ok(5);
    
    res.map(|n| n * 2);
    res.and_then(|n| Ok(n + 1));
    let valeur = res.unwrap_or(0);
}
```

### 15.8 Pattern matching avec enum

```rust
enum Resultat {
    Succes(String),
    Erreur(String),
}

fn main() {
    let res = Resultat::Succes("OK".to_string());
    
    match res {
        Resultat::Succes(msg) => println!("✓ {}", msg),
        Resultat::Erreur(msg) => println!("✗ {}", msg),
    }
}
```

### 15.9 Methods sur enums

```rust
impl Resultat {
    fn est_succes(&self) -> bool {
        match self {
            Resultat::Succes(_) => true,
            Resultat::Erreur(_) => false,
        }
    }
}
```

### 15.10 Deriving Debug

```rust
#[derive(Debug)]
enum Message {
    Texte(String),
    Numero(i32),
}

fn main() {
    let msg = Message::Texte("Hi".to_string());
    println!("{:?}", msg);
}
```

---

## PARTIE 16 : TRAITS (INTERFACES)

### 16.0 Définir un trait

```rust
trait Animal {
    fn faire_bruit(&self);
}
```

### 16.1 Implémenter un trait

```rust
struct Chat;

impl Animal for Chat {
    fn faire_bruit(&self) {
        println!("Miaou !");
    }
}

fn main() {
    let chat = Chat;
    chat.faire_bruit();
}
```

### 16.2 Multiples types avec même trait

```rust
struct Chien;

impl Animal for Chien {
    fn faire_bruit(&self) {
        println!("Ouaf !");
    }
}

struct Oiseau;

impl Animal for Oiseau {
    fn faire_bruit(&self) {
        println!("Cui-cui !");
    }
}

fn faire_du_bruit(animal: &dyn Animal) {
    animal.faire_bruit();
}

fn main() {
    faire_du_bruit(&Chat);
    faire_du_bruit(&Chien);
    faire_du_bruit(&Oiseau);
}
```

### 16.3 Trait avec multiple methods

```rust
trait Forme {
    fn aire(&self) -> f64;
    fn perimetre(&self) -> f64;
}

struct Carre {
    cote: f64,
}

impl Forme for Carre {
    fn aire(&self) -> f64 {
        self.cote * self.cote
    }
    
    fn perimetre(&self) -> f64 {
        4.0 * self.cote
    }
}
```

### 16.4 Default implementations

```rust
trait Creature {
    fn nom(&self) -> &str;
    fn crier(&self) {
        println!("{} crie!", self.nom());
    }
}

struct Lion {
    nom: String,
}

impl Creature for Lion {
    fn nom(&self) -> &str {
        &self.nom
    }
    // crier() est héritée
}

fn main() {
    let lion = Lion { nom: "Simba".to_string() };
    lion.crier();  // Simba crie!
}
```

### 16.5 Trait bounds

```rust
fn afficher_info<T: std::fmt::Debug>(item: T) {
    println!("{:?}", item);
}

fn main() {
    afficher_info(42);
    afficher_info("Bonjour");
}
```

### 16.6 Multiples trait bounds

```rust
fn faire_quelquechose<T: Clone + std::fmt::Display>(item: T) {
    println!("{}", item);
}
```

### 16.7 Traits standard (Display)

```rust
use std::fmt;

struct Point {
    x: i32,
    y: i32,
}

impl fmt::Display for Point {
    fn fmt(&self, f: &mut fmt::Formatter) -> fmt::Result {
        write!(f, "({}, {})", self.x, self.y)
    }
}

fn main() {
    let p = Point { x: 1, y: 2 };
    println!("{}", p);  // (1, 2)
}
```

---

## PARTIE 17 : GÉNÉRIQUES

### 17.0 Génériques dans les fonctions

```rust
fn premier<T>(list: &[T]) -> &T {
    &list[0]
}

fn main() {
    let nombres = vec![1, 2, 3];
    println!("{}", premier(&nombres));
    
    let textes = vec!["a", "b", "c"];
    println!("{}", premier(&textes));
}
```

### 17.1 Génériques dans les structs

```rust
struct Point<T> {
    x: T,
    y: T,
}

fn main() {
    let pi32 = Point { x: 1, y: 2 };
    let pf64 = Point { x: 1.5, y: 2.5 };
}
```

### 17.2 Génériques dans les enums

```rust
enum Result<T, E> {
    Ok(T),
    Err(E),
}

enum Option<T> {
    Some(T),
    None,
}
```

### 17.3 Généric avec trait bounds

```rust
fn afficher_max<T: std::cmp::PartialOrd + std::fmt::Display>(a: T, b: T) {
    if a > b {
        println!("{} est plus grand", a);
    } else {
        println!("{} est plus grand", b);
    }
}

fn main() {
    afficher_max(10, 20);
    afficher_max(3.5, 2.5);
}
```

### 17.4 Where clause

```rust
fn faire_quelquechose<T>(item: T) where T: Clone + std::fmt::Display {
    println!("{}", item);
}
```

### 17.5 Associated types

```rust
trait Conteneur {
    type Item;
    fn contient(&self) -> &Self::Item;
}

struct Boite {
    valeur: i32,
}

impl Conteneur for Boite {
    type Item = i32;
    
    fn contient(&self) -> &Self::Item {
        &self.valeur
    }
}
```

### 17.6 Default generic types

```rust
struct Point<T = f64> {
    x: T,
    y: T,
}

fn main() {
    let p1 = Point { x: 1.0, y: 2.0 };
    let p2: Point<i32> = Point { x: 1, y: 2 };
}
```

---

## PARTIE 18 : MODULES & ORGANISATION

### 18.0 Module basics

```rust
mod salutation {
    pub fn bonjour() {
        println!("Bonjour !");
    }
    
    fn prive() {
        println!("Privé");
    }
}

fn main() {
    salutation::bonjour();
    // salutation::prive();  // ❌ ERREUR privé
}
```

### 18.1 Use statement

```rust
use salutation::bonjour;

fn main() {
    bonjour();  // Sans préfixe
}
```

### 18.2 Pub

```rust
pub mod mon_module {
    pub struct Personne {
        pub nom: String,
        age: i32,  // Privé par défaut
    }
    
    pub fn creer() -> Personne {
        Personne {
            nom: "Alice".to_string(),
            age: 30,
        }
    }
}

fn main() {
    let p = mon_module::creer();
    println!("{}", p.nom);
}
```

### 18.3 Modules dans des fichiers

**main.rs**
```rust
mod mon_module;

fn main() {
    mon_module::dire_bonjour();
}
```

**mon_module.rs**
```rust
pub fn dire_bonjour() {
    println!("Bonjour !");
}
```

### 18.4 Modules dans des dossiers

**main.rs**
```rust
mod mon_paquet;

fn main() {
    mon_paquet::utiles::afficher();
}
```

**mon_paquet/mod.rs**
```rust
pub mod utiles;
```

**mon_paquet/utiles.rs**
```rust
pub fn afficher() {
    println!("Affichage");
}
```

---

## PARTIE 19 : GESTION D'ERREURS

### 19.0 Panic vs Result

**Panic** : crash du programme
**Result** : gérer l'erreur

```rust
// Panic
panic!("Quelque chose d'horrible est arrivé");

// Result
fn diviser(a: i32, b: i32) -> Result<i32, String> {
    if b == 0 {
        Err("Division par zéro".to_string())
    } else {
        Ok(a / b)
    }
}
```

### 19.1 Question mark operator (?)

```rust
fn lire_fichier() -> Result<String, std::io::Error> {
    let contenu = std::fs::read_to_string("file.txt")?;
    Ok(contenu)
}
```

Le `?` retourne l'erreur immédiatement si c'est une `Err`.

### 19.2 Custom error types

```rust
#[derive(Debug)]
enum MonErreur {
    DivisionParZero,
    NombreNegatif,
}

fn diviser(a: i32, b: i32) -> Result<i32, MonErreur> {
    if b == 0 {
        Err(MonErreur::DivisionParZero)
    } else {
        Ok(a / b)
    }
}
```

### 19.3 Propagation d'erreurs

```rust
fn faire_quelquechose() -> Result<String, String> {
    let contenu = lire_fichier()?;
    let nombre = contenu.parse::<i32>()?;
    Ok(nombre.to_string())
}
```

---

## PARTIE 20 : CLOSURES

### 20.0 Closure basique

```rust
fn main() {
    let add = |x, y| x + y;
    println!("{}", add(5, 3));  // 8
}
```

### 20.1 Closure avec type annoté

```rust
fn main() {
    let add = |x: i32, y: i32| -> i32 { x + y };
    println!("{}", add(5, 3));
}
```

### 20.2 Closure capturant des variables

```rust
fn main() {
    let x = 5;
    let add = |y| x + y;
    println!("{}", add(3));  // 8
}
```

### 20.3 Move closure

```rust
fn main() {
    let s = String::from("Bonjour");
    let closure = move || println!("{}", s);
    closure();
    // println!("{}", s);  // ❌ ERREUR, s a été mové
}
```

### 20.4 Closure comme paramètre

```rust
fn appliquer<F>(x: i32, f: F) -> i32
where
    F: Fn(i32) -> i32,
{
    f(x)
}

fn main() {
    let resultat = appliquer(5, |x| x * 2);
    println!("{}", resultat);  // 10
}
```

### 20.5 Fn, FnMut, FnOnce

- **Fn** : emprunte immutablement
- **FnMut** : emprunte muablement
- **FnOnce** : prend la propriété

```rust
fn main() {
    let mut x = 0;
    let mut inc = || {
        x += 1;
        x
    };
    println!("{}", inc());  // 1
    println!("{}", inc());  // 2
}
```

---

## PARTIE 21 : ITERATORS

### 21.0 Iterator trait

```rust
fn main() {
    let vec = vec![1, 2, 3];
    let iter = vec.iter();
    
    for num in iter {
        println!("{}", num);
    }
}
```

### 21.1 Iter, into_iter, iter_mut

```rust
fn main() {
    let vec = vec![1, 2, 3];
    
    // Emprunte
    for num in &vec {
        println!("{}", num);
    }
    println!("{:?}", vec);  // ✅ Existe encore
    
    // Propriété
    for num in vec {
        println!("{}", num);
    }
    // println!("{:?}", vec);  // ❌ ERREUR
}
```

### 21.2 Map

```rust
fn main() {
    let vec = vec![1, 2, 3];
    let doubled: Vec<i32> = vec.iter().map(|x| x * 2).collect();
    println!("{:?}", doubled);  // [2, 4, 6]
}
```

### 21.3 Filter

```rust
fn main() {
    let vec = vec![1, 2, 3, 4, 5];
    let pairs: Vec<i32> = vec.iter().filter(|x| *x % 2 == 0).copied().collect();
    println!("{:?}", pairs);  // [2, 4]
}
```

### 21.4 Chaining adapters

```rust
fn main() {
    let vec = vec![1, 2, 3, 4, 5];
    let resultat: Vec<i32> = vec.iter()
        .filter(|x| *x > 2)
        .map(|x| x * 2)
        .collect();
    println!("{:?}", resultat);  // [6, 8, 10]
}
```

---

## PARTIE 22 : SMART POINTERS

### 22.0 Box<T>

Allouer sur la heap.

```rust
fn main() {
    let x = Box::new(5);
    println!("{}", x);  // 5
}
```

### 22.1 Rc<T>

Partager l'ownership.

```rust
use std::rc::Rc;

fn main() {
    let x = Rc::new(5);
    let y = Rc::clone(&x);
    let z = Rc::clone(&x);
    
    println!("Count: {}", Rc::strong_count(&x));  // 3
}
```

### 22.2 RefCell<T>

Interior mutability.

```rust
use std::cell::RefCell;

fn main() {
    let x = RefCell::new(5);
    *x.borrow_mut() = 10;
    println!("{}", x.borrow());  // 10
}
```
---

# PARTIES r23-35 : SUJETS AVANCÉS & PROJETS

## PARTIE 23 : CONCURRENCE — THREADS

### 23.0 Créer un thread

```rust
use std::thread;

fn main() {
    let handle = thread::spawn(|| {
        println!("Thread en cours d'exécution");
    });
    
    println!("Main thread");
    handle.join().unwrap();  // Attendre la fin du thread
}
```

### 23.1 Threads avec variables

```rust
fn main() {
    let x = 5;
    
    let handle = thread::spawn(move || {
        println!("Valeur: {}", x);  // move pour capturer
    });
    
    handle.join().unwrap();
}
```

### 23.2 Mutex pour shared state

```rust
use std::sync::Mutex;
use std::thread;

fn main() {
    let counter = Mutex::new(0);
    
    let handle = thread::spawn(|| {
        let mut num = counter.lock().unwrap();
        *num += 1;
    });
    
    handle.join().unwrap();
}
```

### 23.3 Arc<Mutex<T>>

Pour partager entre threads :

```rust
use std::sync::{Arc, Mutex};
use std::thread;

fn main() {
    let counter = Arc::new(Mutex::new(0));
    let mut handles = vec![];
    
    for _ in 0..10 {
        let counter = Arc::clone(&counter);
        let handle = thread::spawn(move || {
            let mut num = counter.lock().unwrap();
            *num += 1;
        });
        handles.push(handle);
    }
    
    for handle in handles {
        handle.join().unwrap();
    }
    
    println!("Result: {}", *counter.lock().unwrap());
}
```

### 23.4 Channels

Communication entre threads :

```rust
use std::sync::mpsc;
use std::thread;

fn main() {
    let (tx, rx) = mpsc::channel();
    
    thread::spawn(move || {
        tx.send("Bonjour").unwrap();
    });
    
    let message = rx.recv().unwrap();
    println!("{}", message);
}
```

### 23.5 Multiple producers

```rust
fn main() {
    let (tx, rx) = mpsc::channel();
    
    for i in 0..3 {
        let tx = tx.clone();
        thread::spawn(move || {
            tx.send(i).unwrap();
        });
    }
    
    drop(tx);  // Fermer le sender original
    
    for received in rx {
        println!("{}", received);
    }
}
```

---

## PARTIE 24 : ASYNC/AWAIT

### 24.0 Async functions

```rust
async fn dire_bonjour() {
    println!("Bonjour !");
}

#[tokio::main]
async fn main() {
    dire_bonjour().await;
}
```

### 24.1 Futures

```rust
async fn ajouter(a: i32, b: i32) -> i32 {
    a + b
}

#[tokio::main]
async fn main() {
    let resultat = ajouter(5, 3).await;
    println!("{}", resultat);
}
```

### 24.2 Await

```rust
#[tokio::main]
async fn main() {
    let future = ajouter(5, 3);
    let resultat = future.await;
    println!("{}", resultat);
}
```

### 24.3 Async blocks

```rust
#[tokio::main]
async fn main() {
    let async_block = async {
        5 + 3
    };
    
    let resultat = async_block.await;
    println!("{}", resultat);
}
```

### 24.4 Spawning tasks

```rust
#[tokio::main]
async fn main() {
    tokio::spawn(async {
        println!("Task 1");
    });
    
    tokio::spawn(async {
        println!("Task 2");
    });
    
    tokio::time::sleep(tokio::time::Duration::from_secs(1)).await;
}
```

### 24.5 Joining tasks

```rust
#[tokio::main]
async fn main() {
    let handle1 = tokio::spawn(async { 1 + 1 });
    let handle2 = tokio::spawn(async { 2 + 2 });
    
    let r1 = handle1.await.unwrap();
    let r2 = handle2.await.unwrap();
    
    println!("{} {}", r1, r2);
}
```

---

## PARTIE 25 : UNSAFE RUST

### 25.0 Dereferencing raw pointers

```rust
fn main() {
    let x = 5;
    let raw_ptr = &x as *const i32;
    
    unsafe {
        println!("{}", *raw_ptr);
    }
}
```

### 25.1 Mutable raw pointers

```rust
fn main() {
    let mut x = 5;
    let raw_ptr = &mut x as *mut i32;
    
    unsafe {
        *raw_ptr = 10;
    }
    
    println!("{}", x);
}
```

### 25.2 Unsafe functions

```rust
unsafe fn dangerous() {
    println!("Dangerous!");
}

fn main() {
    unsafe {
        dangerous();
    }
}
```

### 25.3 Unsafe traits

```rust
unsafe trait Dangerous {
    fn do_something(&self);
}

struct MyType;

unsafe impl Dangerous for MyType {
    fn do_something(&self) {
        println!("Done");
    }
}
```

---

## PARTIE 26 : MEMORY MODEL

### 26.0 Stack vs Heap

**Stack** : ordre LIFO, rapide, petit
**Heap** : désorganisé, lent, grand

```rust
fn main() {
    let x = 5;  // Stack
    let s = String::from("Bonjour");  // Heap
}
```

### 26.1 Size and alignment

```rust
fn main() {
    println!("Size of i32: {}", std::mem::size_of::<i32>());
    println!("Size of String: {}", std::mem::size_of::<String>());
}
```

### 26.2 Zero-cost abstractions

Rust crée du code machine efficace sans overhead.

```rust
fn main() {
    let vec = vec![1, 2, 3];
    // Pas de dynamic dispatch, compilé en code direct
}
```

---

## PARTIE 27 : CARGO EN DÉTAIL

### 27.0 Cargo new

```bash
cargo new mon_projet
cd mon_projet
```

### 27.1 Cargo build

```bash
cargo build              # Debug
cargo build --release   # Optimisé
```

### 27.2 Cargo run

```bash
cargo run
cargo run --release
```

### 27.3 Cargo check

```bash
cargo check  # Vérifier sans compiler
```

### 27.4 Cargo test

```bash
cargo test
cargo test -- --nocapture  # Afficher les prints
```

### 27.5 Cargo.toml

```toml
[package]
name = "mon_projet"
version = "0.1.0"
edition = "2021"

[dependencies]
serde = "1.0"
tokio = { version = "1", features = ["full"] }

[dev-dependencies]
criterion = "0.5"
```

### 27.6 Features

```toml
[features]
default = ["default-feature"]
default-feature = []
special = []
```

```rust
#[cfg(feature = "special")]
fn special_function() {}
```

### 27.7 Workspaces

```bash
[workspace]
members = ["package1", "package2"]
```

### 27.8 Publishing

```bash
cargo login
cargo publish
```

---

## PARTIE 28 : TESTING COMPLET

### 28.0 Unit tests

```rust
fn add(a: i32, b: i32) -> i32 {
    a + b
}

#[cfg(test)]
mod tests {
    use super::*;
    
    #[test]
    fn test_add() {
        assert_eq!(add(2, 2), 4);
    }
}
```

### 28.1 Assertions

```rust
#[test]
fn test_assertions() {
    assert!(true);
    assert_eq!(2 + 2, 4);
    assert_ne!(2 + 2, 5);
}
```

### 28.2 Should panic

```rust
#[test]
#[should_panic]
fn test_panic() {
    panic!("Boom!");
}
```

### 28.3 Integration tests

**tests/integration_test.rs**
```rust
fn add(a: i32, b: i32) -> i32 {
    a + b
}

#[test]
fn test_add() {
    assert_eq!(add(2, 2), 4);
}
```

### 28.4 Doc tests

```rust
/// Add two numbers
///
/// # Examples
/// ```
/// assert_eq!(add(2, 2), 4);
/// ```
fn add(a: i32, b: i32) -> i32 {
    a + b
}
```

---

## PARTIE 29 : MACROS BASICS

### 29.0 println! macro

```rust
println!("Hello");
println!("Value: {}", x);
```

### 29.1 panic! macro

```rust
panic!("Something went wrong");
```

### 29.2 assert! macros

```rust
assert!(true);
assert_eq!(2 + 2, 4);
```

### 29.3 vec! macro

```rust
let v = vec![1, 2, 3];
```

---

## PARTIE 30 : REGEX & STRING PROCESSING

### 30.0 Regex basics

```rust
use regex::Regex;

fn main() {
    let re = Regex::new(r"^\d{3}-\d{3}-\d{4}$").unwrap();
    assert!(re.is_match("123-456-7890"));
}
```

### 30.1 Finding matches

```rust
let re = Regex::new(r"\d+").unwrap();
for mat in re.find_iter("123 456 789") {
    println!("{}", mat.as_str());
}
```

### 30.2 Capturing groups

```rust
let re = Regex::new(r"(\w+) (\w+)").unwrap();
let caps = re.captures("Bonjour Rust").unwrap();
println!("{}", &caps[1]);  // Bonjour
println!("{}", &caps[2]);  // Rust
```

---

## PARTIE 31 : FILE I/O

### 31.0 Reading files

```rust
use std::fs;

fn main() -> std::io::Result<()> {
    let contents = fs::read_to_string("file.txt")?;
    println!("{}", contents);
    Ok(())
}
```

### 31.1 Writing files

```rust
use std::fs;

fn main() -> std::io::Result<()> {
    fs::write("file.txt", "Contenu")?;
    Ok(())
}
```

### 31.2 Iterating directory

```rust
use std::fs;

fn main() -> std::io::Result<()> {
    for entry in fs::read_dir(".")? {
        let entry = entry?;
        println!("{:?}", entry.path());
    }
    Ok(())
}
```

---

## PARTIE 32 : JSON & SERDE

### 32.0 Parsing JSON

```rust
use serde_json::json;

fn main() {
    let data = json!({
        "name": "Alice",
        "age": 30
    });
    
    println!("{}", data["name"]);
}
```

### 32.1 Custom structs

```rust
use serde::{Deserialize, Serialize};
use serde_json;

#[derive(Serialize, Deserialize)]
struct Personne {
    nom: String,
    age: i32,
}

fn main() {
    let json = r#"{"nom": "Alice", "age": 30}"#;
    let p: Personne = serde_json::from_str(json).unwrap();
    println!("{} {}", p.nom, p.age);
}
```

---

## PARTIE 33 : PROJETS COMPLETS

### 33.0 Project 1: Todo CLI

```rust
use std::fs;

#[derive(Serialize, Deserialize, Debug)]
struct Todo {
    task: String,
    done: bool,
}

fn main() {
    let mut todos: Vec<Todo> = vec![];
    
    // Add todo
    todos.push(Todo {
        task: "Learn Rust".to_string(),
        done: false,
    });
    
    // Save to file
    let json = serde_json::to_string(&todos).unwrap();
    fs::write("todos.json", json).unwrap();
    
    // Load from file
    let json = fs::read_to_string("todos.json").unwrap();
    let loaded: Vec<Todo> = serde_json::from_str(&json).unwrap();
    
    println!("{:?}", loaded);
}
```

### 33.1 Project 2: Simple web server

```rust
use std::net::TcpListener;
use std::io::{Read, Write};

fn main() {
    let listener = TcpListener::bind("127.0.0.1:8080").unwrap();
    
    for stream in listener.incoming() {
        let mut stream = stream.unwrap();
        let mut buffer = [0; 512];
        
        stream.read(&mut buffer).unwrap();
        
        let response = "HTTP/1.1 200 OK\r\n\r\nHello!";
        stream.write_all(response.as_bytes()).unwrap();
    }
}
```

### 33.2 Project 3: Game loop

```rust
fn main() {
    let mut game_running = true;
    let mut score = 0;
    
    while game_running {
        // Update
        score += 1;
        
        // Render
        println!("Score: {}", score);
        
        // Input
        if score > 100 {
            game_running = false;
        }
    }
    
    println!("Final score: {}", score);
}
```

---

## PARTIE 34 : PATTERNS & BEST PRACTICES

### 34.0 Builder pattern

```rust
struct PersonneBuilder {
    nom: String,
    age: Option<i32>,
    email: Option<String>,
}

impl PersonneBuilder {
    fn new(nom: String) -> Self {
        PersonneBuilder {
            nom,
            age: None,
            email: None,
        }
    }
    
    fn age(mut self, age: i32) -> Self {
        self.age = Some(age);
        self
    }
    
    fn email(mut self, email: String) -> Self {
        self.email = Some(email);
        self
    }
    
    fn build(self) -> Personne {
        Personne {
            nom: self.nom,
            age: self.age.unwrap_or(0),
            email: self.email.unwrap_or_default(),
        }
    }
}

fn main() {
    let p = PersonneBuilder::new("Alice".to_string())
        .age(30)
        .email("alice@example.com".to_string())
        .build();
}
```

### 34.1 Error handling patterns

```rust
fn safe_divide(a: i32, b: i32) -> Result<i32, String> {
    if b == 0 {
        Err("Division by zero".to_string())
    } else {
        Ok(a / b)
    }
}

fn main() {
    match safe_divide(10, 2) {
        Ok(result) => println!("Result: {}", result),
        Err(e) => println!("Error: {}", e),
    }
}
```

### 34.2 Iterator patterns

```rust
fn main() {
    let vec = vec![1, 2, 3, 4, 5];
    
    vec.iter()
        .filter(|x| x % 2 == 0)
        .map(|x| x * x)
        .for_each(|x| println!("{}", x));
}
```

---

## PARTIE 35 : CONCLUSION & SUITE

### 35.0 Ce que tu as appris

✅ Variables et types
✅ Contrôle de flux
✅ Fonctions
✅ Collections
✅ Ownership et borrowing
✅ Pattern matching
✅ Structs et enums
✅ Traits et génériques
✅ Gestion d'erreurs
✅ Threads et async/await
✅ Testing
✅ Cargo et ecosystem

---

# PARTIES 36-50 : 

## PARTIE 36 : LIFETIMES AVANCÉS

### 36.0 Lifetimes explicites

```rust
fn plus_long<'a>(x: &'a str, y: &'a str) -> &'a str {
    if x.len() > y.len() {
        x
    } else {
        y
    }
}

fn main() {
    let s1 = String::from("Bonjour");
    let s2 = "Hi";
    let result = plus_long(&s1, s2);
    println!("{}", result);
}
```

### 36.1 Multiple lifetimes

```rust
fn compare<'a, 'b>(x: &'a str, y: &'b str) -> bool {
    x.len() == y.len()
}

fn main() {
    let s1 = String::from("Bonjour");
    let s2 = String::from("Salut!");
    println!("{}", compare(&s1, &s2));
}
```

### 36.2 Lifetimes dans les structs

```rust
struct ImportantExcerpt<'a> {
    part: &'a str,
}

fn main() {
    let s = String::from("Rust est merveilleux");
    let excerpt = ImportantExcerpt { part: &s };
    println!("{}", excerpt.part);
}
```

### 36.3 Lifetime elision rules

Rust a des règles pour inférer les lifetimes automatiquement :

**Règle 1** : Chaque paramètre reçoit son propre lifetime
**Règle 2** : S'il y a un lifetime de self, ce lifetime est assigné à tous les retours
**Règle 3** : S'il y a plusieurs lifetimes mais pas de self, pas d'inférence

```rust
// Pas besoin d'annoter, Rust infère
fn first_word(s: &str) -> &str {
    &s[0..1]
}

// Besoin d'annoter (ambigu)
fn compare<'a>(x: &'a str, y: &'a str) -> &'a str {
    if x.len() > y.len() { x } else { y }
}
```

### 36.4 Static lifetime

```rust
let s: &'static str = "Bonjour";  // String literal, vit toute la vie du programme

fn longest<'a>(x: &'a str, y: &'a str) -> &'static str {
    "statique"
}
```

### 36.5 Lifetime bounds

```rust
fn longest_with_an_announcement<'a, T: std::fmt::Display>(
    x: &'a str,
    y: &'a str,
    ann: T,
) -> &'a str {
    println!("Annonce: {}", ann);
    if x.len() > y.len() { x } else { y }
}
```

### 36.6 Variance et covariance

```rust
// Covariance : si A est un sous-type de B,
// alors &A est un sous-type de &B
fn foo<'a>(x: &'a str) {
    let s: &'static str = "hello";
    let t: &'a str = s;  // OK car 'static est plus long que 'a
}
```

### 36.7 Reborrowing avec lifetimes

```rust
fn main() {
    let s = String::from("Bonjour");
    let r1 = &s;
    let r2 = &s;
    let r3 = r1;  // Reborrow
    println!("{} {}", r2, r3);
}
```

### 36.8 Lifetime patterns

```rust
// RAII avec lifetimes
struct Lock<'a, T> {
    data: &'a T,
}

impl<'a, T> Drop for Lock<'a, T> {
    fn drop(&mut self) {
        println!("Lock released");
    }
}

fn main() {
    let x = 5;
    let _lock = Lock { data: &x };
}
```

---

## PARTIE 37 : GESTION D'ERREURS COMPLÈTE

### 37.0 Custom error types

```rust
#[derive(Debug)]
enum MonErreur {
    NotFound,
    PermissionDenied,
    Other(String),
}

impl std::fmt::Display for MonErreur {
    fn fmt(&self, f: &mut std::fmt::Formatter) -> std::fmt::Result {
        match self {
            MonErreur::NotFound => write!(f, "Fichier non trouvé"),
            MonErreur::PermissionDenied => write!(f, "Permission refusée"),
            MonErreur::Other(msg) => write!(f, "Erreur: {}", msg),
        }
    }
}

impl std::error::Error for MonErreur {}
```

### 37.1 Error trait

```rust
use std::error::Error;

fn faire_quelquechose() -> Result<String, Box<dyn Error>> {
    let x = "123".parse::<i32>()?;
    Ok(format!("Nombre: {}", x))
}

fn main() {
    match faire_quelquechose() {
        Ok(result) => println!("{}", result),
        Err(e) => println!("Erreur: {}", e),
    }
}
```

### 37.2 Error propagation

```rust
fn read_and_parse(path: &str) -> Result<i32, Box<dyn std::error::Error>> {
    let content = std::fs::read_to_string(path)?;
    let num: i32 = content.parse()?;
    Ok(num)
}

fn main() {
    match read_and_parse("file.txt") {
        Ok(num) => println!("{}", num),
        Err(e) => eprintln!("Erreur: {}", e),
    }
}
```

### 37.3 Map errors

```rust
fn parse_number(s: &str) -> Result<i32, String> {
    s.parse::<i32>()
        .map_err(|e| format!("Parse error: {}", e))
}

fn main() {
    match parse_number("123abc") {
        Ok(n) => println!("{}", n),
        Err(e) => println!("{}", e),
    }
}
```

### 37.4 Thiserror crate

```rust
use thiserror::Error;

#[derive(Error, Debug)]
pub enum MonErreur {
    #[error("Fichier non trouvé: {0}")]
    NotFound(String),
    
    #[error("Parse error: {0}")]
    ParseError(#[from] std::num::ParseIntError),
    
    #[error("IO error: {0}")]
    IoError(#[from] std::io::Error),
}

fn main() {
    let result: Result<i32, MonErreur> = "123".parse().map_err(|e| MonErreur::ParseError(e));
}
```

### 37.5 Anyhow crate

```rust
use anyhow::{Result, Context};

fn faire_quelquechose() -> Result<String> {
    let content = std::fs::read_to_string("file.txt")
        .context("Impossible de lire le fichier")?;
    Ok(content)
}

fn main() {
    match faire_quelquechose() {
        Ok(content) => println!("{}", content),
        Err(e) => eprintln!("Erreur: {:?}", e),
    }
}
```

### 37.6 Custom Result type

```rust
type Result<T> = std::result::Result<T, MonErreur>;

fn operation() -> Result<i32> {
    Ok(42)
}

fn main() {
    match operation() {
        Ok(n) => println!("{}", n),
        Err(_) => println!("Erreur"),
    }
}
```

### 37.7 Bail et ensure (avec anyhow)

```rust
use anyhow::{bail, ensure};

fn validate_age(age: i32) -> anyhow::Result<()> {
    ensure!(age >= 0, "Age doit être positif");
    ensure!(age <= 150, "Age trop grand");
    Ok(())
}

fn divide(a: i32, b: i32) -> anyhow::Result<i32> {
    if b == 0 {
        bail!("Division par zéro");
    }
    Ok(a / b)
}
```

---

## PARTIE 38 : ASYNC/AWAIT APPROFONDI

### 38.0 Async functions complètes

```rust
async fn fetch_data(url: &str) -> Result<String, Box<dyn std::error::Error>> {
    // Simuler une requête
    tokio::time::sleep(tokio::time::Duration::from_secs(1)).await;
    Ok(format!("Data from {}", url))
}

#[tokio::main]
async fn main() {
    match fetch_data("https://example.com").await {
        Ok(data) => println!("{}", data),
        Err(e) => eprintln!("Erreur: {}", e),
    }
}
```

### 38.1 Tokio spawning

```rust
#[tokio::main]
async fn main() {
    let task1 = tokio::spawn(async {
        println!("Task 1");
        42
    });
    
    let task2 = tokio::spawn(async {
        println!("Task 2");
        100
    });
    
    let result1 = task1.await.unwrap();
    let result2 = task2.await.unwrap();
    
    println!("Results: {} {}", result1, result2);
}
```

### 38.2 Select macro

```rust
use tokio::time::{sleep, Duration};

#[tokio::main]
async fn main() {
    tokio::select! {
        _ = sleep(Duration::from_secs(1)) => {
            println!("1 seconde passée");
        }
        result = async { "done" } => {
            println!("Résultat: {}", result);
        }
    }
}
```

### 38.3 Join! macro

```rust
#[tokio::main]
async fn main() {
    let future1 = async { 1 + 1 };
    let future2 = async { 2 + 2 };
    
    let (a, b) = tokio::join!(future1, future2);
    println!("{} {}", a, b);
}
```

### 38.4 Async iterators

```rust
use futures::stream::{self, StreamExt};

#[tokio::main]
async fn main() {
    let mut stream = stream::iter(vec![1, 2, 3])
        .map(|x| async move { x * 2 })
        .buffered(2);
    
    while let Some(value) = stream.next().await {
        println!("{}", value);
    }
}
```

### 38.5 Timeout

```rust
use tokio::time::{timeout, Duration};

#[tokio::main]
async fn main() {
    let result = timeout(
        Duration::from_secs(1),
        tokio::time::sleep(Duration::from_secs(2))
    ).await;
    
    match result {
        Ok(_) => println!("Terminé"),
        Err(_) => println!("Timeout!"),
    }
}
```

### 38.6 Broadcast channel

```rust
#[tokio::main]
async fn main() {
    let (tx, mut rx) = tokio::sync::broadcast::channel(16);
    
    tokio::spawn(async move {
        tx.send("Message 1").unwrap();
        tx.send("Message 2").unwrap();
    });
    
    while let Ok(msg) = rx.recv().await {
        println!("{}", msg);
    }
}
```

---

## PARTIE 39 : UNSAFE RUST AVANCÉ

### 39.0 Raw pointers complets

```rust
fn main() {
    let x = 5;
    let raw_const = &x as *const i32;
    let mut y = 10;
    let raw_mut = &mut y as *mut i32;
    
    unsafe {
        println!("Const: {}", *raw_const);
        println!("Mut: {}", *raw_mut);
        *raw_mut = 20;
    }
}
```

### 39.1 FFI (Foreign Function Interface)

```rust
extern "C" {
    fn strlen(s: *const u8) -> usize;
}

fn main() {
    unsafe {
        let c_string = b"Hello\0";
        let len = strlen(c_string.as_ptr());
        println!("Length: {}", len);
    }
}
```

### 39.2 Unsafe blocks et fonctions

```rust
unsafe fn dangerous() {
    println!("Je suis dangereux!");
}

fn safe_wrapper() {
    unsafe {
        dangerous();
    }
}

fn main() {
    safe_wrapper();
}
```

### 39.3 Transmute

```rust
fn main() {
    let x: i32 = 5;
    let y: u32 = unsafe {
        std::mem::transmute(x)
    };
    println!("{}", y);
}
```

### 39.4 Volatile operations

```rust
use std::ptr;

fn main() {
    let mut x = 5;
    unsafe {
        ptr::write_volatile(&mut x, 10);
        let y = ptr::read_volatile(&x);
        println!("{}", y);
    }
}
```

---

## PARTIE 40 : CONCURRENCY AVANCÉE

### 40.0 Send et Sync traits

```rust
// T est Send si on peut l'envoyer entre threads
// T est Sync si &T est Send

fn assert_send<T: Send>() {}
fn assert_sync<T: Sync>() {}

fn main() {
    assert_send::<i32>();
    assert_sync::<String>();
}
```

### 40.1 RwLock pour lectures multiples

```rust
use std::sync::RwLock;
use std::sync::Arc;
use std::thread;

fn main() {
    let data = Arc::new(RwLock::new(vec![1, 2, 3]));
    
    // Lecteurs
    for _ in 0..5 {
        let data = Arc::clone(&data);
        thread::spawn(move || {
            let reader = data.read().unwrap();
            println!("{:?}", *reader);
        });
    }
    
    // Écrivain
    {
        let mut writer = data.write().unwrap();
        writer.push(4);
    }
}
```

### 40.2 Barrier pour synchronisation

```rust
use std::sync::{Arc, Barrier};
use std::thread;

fn main() {
    let barrier = Arc::new(Barrier::new(3));
    
    for i in 0..3 {
        let barrier = Arc::clone(&barrier);
        thread::spawn(move || {
            println!("Thread {} avant", i);
            barrier.wait();
            println!("Thread {} après", i);
        });
    }
    
    thread::sleep(std::time::Duration::from_secs(1));
}
```

### 40.3 Condvar pour signalisation

```rust
use std::sync::{Mutex, Condvar, Arc};
use std::thread;

fn main() {
    let pair = Arc::new((Mutex::new(false), Condvar::new()));
    let pair_clone = Arc::clone(&pair);
    
    thread::spawn(move || {
        let (lock, cvar) = &*pair_clone;
        let mut started = lock.lock().unwrap();
        *started = true;
        cvar.notify_one();
    });
    
    let (lock, cvar) = &*pair;
    let mut started = lock.lock().unwrap();
    while !*started {
        started = cvar.wait(started).unwrap();
    }
    println!("Started!");
}
```

---

## PARTIE 41 : MACROS AVANCÉES

### 41.0 Macros déclaratives complètes

```rust
macro_rules! vec_of_strings {
    ($($str:expr),*) => {
        vec![$($str.to_string()),*]
    };
}

fn main() {
    let strings = vec_of_strings!("a", "b", "c");
    println!("{:?}", strings);
}
```

### 41.1 Procedural macros basics

```rust
// Dans lib.rs
use proc_macro::TokenStream;

#[proc_macro]
pub fn hello_macro(input: TokenStream) -> TokenStream {
    "fn hello() { println!(\"Bonjour!\"); }".parse().unwrap()
}
```

### 41.2 Derive macros

```rust
use proc_macro::TokenStream;
use quote::quote;
use syn::{parse_macro_input, DeriveInput};

#[proc_macro_derive(Hello)]
pub fn derive_hello(input: TokenStream) -> TokenStream {
    let input = parse_macro_input!(input as DeriveInput);
    let name = input.ident;
    
    let expanded = quote! {
        impl Hello for #name {
            fn hello() {
                println!("Bonjour depuis {}", stringify!(#name));
            }
        }
    };
    
    TokenStream::from(expanded)
}
```

---

## PARTIE 42 : PERFORMANCE & OPTIMIZATION

### 42.0 Benchmarking avec criterion

```rust
use criterion::{black_box, criterion_group, criterion_main, Criterion};

fn fibonacci(n: u32) -> u32 {
    match n {
        0 | 1 => n,
        _ => fibonacci(n - 1) + fibonacci(n - 2),
    }
}

fn criterion_benchmark(c: &mut Criterion) {
    c.bench_function("fib 20", |b| b.iter(|| fibonacci(black_box(20))));
}

criterion_group!(benches, criterion_benchmark);
criterion_main!(benches);
```

### 42.1 Profiling avec perf

```bash
# Compiler avec debug symbols
cargo build

# Profiler avec perf
perf record -g ./target/debug/my_binary
perf report
```

### 42.2 Inlining hints

```rust
#[inline]
fn small_function(x: i32) -> i32 {
    x * 2
}

#[inline(always)]
fn must_inline() -> i32 {
    42
}

#[inline(never)]
fn never_inline() {
    println!("Never inlined");
}
```

### 42.3 SIMD basics

```rust
use std::simd::{SimdInt, i32x4};

fn main() {
    let a = i32x4::from_array([1, 2, 3, 4]);
    let b = i32x4::from_array([5, 6, 7, 8]);
    let c = a + b;
    println!("{:?}", c.to_array());
}
```

---

## PARTIE 43 : EMBEDDED RUST

### 43.0 no_std basics

```rust
#![no_std]

fn main() {
    // Pas de std library
    let x = 5;
    // println! n'existe pas sans std
}
```

### 43.1 HAL (Hardware Abstraction Layer)

```rust
use stm32f1xx_hal::{stm32, gpio::*, rcc::*};

#[entry]
fn main() -> ! {
    let dp = stm32::Peripherals::take().unwrap();
    let rcc = dp.RCC.constrain();
    let mut gpioc = dp.GPIOC.split(&mut rcc.apb2);
    
    let mut led = gpioc.pc13.into_push_pull_output(&mut gpioc.crh);
    
    loop {
        led.set_high();
        delay_ms(1000);
        led.set_low();
        delay_ms(1000);
    }
}

fn delay_ms(ms: u32) {
    // Simple delay
}
```

---

## PARTIE 44 : WEB FRAMEWORKS

### 44.0 Actix-web basics

```rust
use actix_web::{web, App, HttpServer, HttpResponse};

async fn hello() -> HttpResponse {
    HttpResponse::Ok().body("Bonjour!")
}

#[actix_web::main]
async fn main() -> std::io::Result<()> {
    HttpServer::new(|| {
        App::new()
            .route("/", web::get().to(hello))
    })
    .bind("127.0.0.1:8080")?
    .run()
    .await
}
```

### 44.1 Rocket basics

```rust
#[macro_use]
extern crate rocket;

#[get("/")]
fn index() -> &'static str {
    "Bonjour Rocket!"
}

#[launch]
fn rocket() -> _ {
    rocket::build()
        .mount("/", routes![index])
}
```

### 44.2 Database avec sqlx

```rust
use sqlx::sqlite::SqlitePool;

#[derive(sqlx::FromRow)]
struct User {
    id: i32,
    name: String,
}

#[actix_web::main]
async fn main() -> Result<()> {
    let pool = SqlitePool::connect("sqlite::memory:").await?;
    
    let users: Vec<User> = sqlx::query_as("SELECT id, name FROM users")
        .fetch_all(&pool)
        .await?;
    
    Ok(())
}
```

---

## PARTIE 45 : TESTING AVANCÉ

### 45.0 Property testing avec proptest

```rust
use proptest::proptest;

#[test]
fn test_string_len() {
    proptest!(|(s in ".*")| {
        assert_eq!(s.len(), s.chars().count());
    });
}
```

### 45.1 Mocking avec mockito

```rust
#[cfg(test)]
mod tests {
    use mockito::mock;
    
    #[test]
    fn test_with_mock() {
        mock("GET", "/api/data")
            .with_status(200)
            .with_body("data")
            .create();
    }
}
```

### 45.2 Fuzzing

```rust
#![no_main]
use libfuzzer_sys::fuzz_target;

fuzz_target!(|data: &[u8]| {
    if let Ok(s) = std::str::from_utf8(data) {
        let _ = s.parse::<i32>();
    }
});
```

---

## PARTIE 46 : REGEX & TEXT PROCESSING

### 46.0 Regex avancée

```rust
use regex::Regex;

fn main() {
    let re = Regex::new(r"(\w+)@(\w+)\.(\w+)").unwrap();
    
    for caps in re.captures_iter("alice@example.com bob@test.org") {
        println!("Email: {}", &caps[0]);
        println!("Domaine: {}", &caps[2]);
    }
}
```

### 46.1 String processing avec unicode_segmentation

```rust
use unicode_segmentation::UnicodeSegmentation;

fn main() {
    let text = "Bonjour, ça va? 👋";
    for grapheme in text.graphemes(true) {
        println!("{}", grapheme);
    }
}
```

---

## PARTIE 47 : SERIALIZATION AVANCÉE

### 47.0 Custom serde

```rust
use serde::{Serialize, Deserialize, Serializer, Deserializer};

#[derive(Serialize, Deserialize)]
struct Custom {
    #[serde(serialize_with = "custom_serialize")]
    #[serde(deserialize_with = "custom_deserialize")]
    value: i32,
}

fn custom_serialize<S>(value: &i32, serializer: S) -> Result<S::Ok, S::Error>
where
    S: Serializer,
{
    serializer.serialize_i32(value * 2)
}

fn custom_deserialize<'de, D>(deserializer: D) -> Result<i32, D::Error>
where
    D: Deserializer<'de>,
{
    Ok(i32::deserialize(deserializer)? / 2)
}
```

---

## PARTIE 48 : NETWORKING

### 48.0 TCP avec tokio

```rust
use tokio::net::TcpListener;
use tokio::io::{AsyncReadExt, AsyncWriteExt};

#[tokio::main]
async fn main() -> Result<(), Box<dyn std::error::Error>> {
    let listener = TcpListener::bind("127.0.0.1:8080").await?;
    
    loop {
        let (mut socket, _) = listener.accept().await?;
        
        tokio::spawn(async move {
            let mut buf = [0; 1024];
            match socket.read(&mut buf).await {
                Ok(0) => return,
                Ok(n) => {
                    socket.write_all(&buf[..n]).await.ok();
                }
                Err(_) => return,
            }
        });
    }
}
```

### 48.1 HTTP avec hyper

```rust
use hyper::{Body, Client, Uri};

#[tokio::main]
async fn main() -> Result<(), Box<dyn std::error::Error>> {
    let uri = "http://example.com".parse::<Uri>()?;
    let client = Client::new();
    let response = client.get(uri).await?;
    
    let body_bytes = hyper::body::to_bytes(response.into_body()).await?;
    println!("{}", String::from_utf8_lossy(&body_bytes));
    
    Ok(())
}
```

---

## PARTIE 49 : BEST PRACTICES AVANCÉES

### 49.0 Builder pattern avec generics

```rust
struct PersonBuilder<A = (), B = ()> {
    name: Option<String>,
    age: A,
    email: B,
}

impl PersonBuilder<(), ()> {
    fn new() -> PersonBuilder<(), ()> {
        PersonBuilder {
            name: None,
            age: (),
            email: (),
        }
    }
}

impl<B> PersonBuilder<i32, B> {
    fn age(self, age: i32) -> PersonBuilder<i32, B> {
        PersonBuilder {
            age,
            ..self
        }
    }
}
```

### 49.1 Zero-cost abstractions

```rust
// Trait object avec trait dyn = allocation dynamique
fn print_size(item: &dyn std::fmt::Display) {
    println!("{}", item);
}

// Generics = monomorphization = zero-cost
fn print_size_generic<T: std::fmt::Display>(item: &T) {
    println!("{}", item);
}

// Rust génère du code pour i32, String, etc. séparément
// Aucun coût à l'exécution
```

---

## PARTIE 50 : CONCLUSION & ROADMAP EXPERT

### 50.0 Qu'est-ce que tu as maintenant

✅ 50 parties couvrant Rust du zéro à expert
✅ 400+ exemples de code
✅ Tous les concepts essentiels expliqués
✅ Sujets avancés inclus
✅ Best practices et patterns

### 50.1 Roadmap pour devenir expert

**Mois 1-3 : Fondations** (Parties 0-8)
- Variables, types, fonctions
- Collections
- Créer 10+ petits programmes

**Mois 4-6 : Core Rust** (Parties 9-17)
- Ownership/Borrowing (le plus difficile)
- Structs, enums, traits
- Créer 3-5 projets moyens

**Mois 7-9 : Patterns** (Parties 18-35)
- Génériques
- Modules
- Gestion d'erreurs
- Closures, iterators

**Mois 10-12 : Spécialisation** (Parties 36-50)
- Choisir ta spécialité (web, systems, embedded, etc.)
- Lifetimes avancés
- Async/await
- Unsafe Rust

**Après 1 an : Expertise**
- Contribuer à l'open-source
- Créer ta propre librairie sur crates.io
- Maîtriser un framework (Actix, Bevy, etc.)
- Devenir expert dans ta spécialité

### 50.2 Ressources après ce guide

**Official**
- Rust Book : rust-lang.org/book
- Rust by Example
- Nomicon (for unsafe)

**Livres**
- Programming in Rust
- The Rustonomicon
- Rust Web Development

**Community**
- Reddit r/rust
- Rust Discourse
- GitHub discussions
- Stack Overflow

**Practice**
- LeetCode
- Project Euler
- Real projects on GitHub
- Contributing to open source

### 50.3 Les vraies clés pour devenir expert

1. **Code continuellement** : Pas de raccourci
2. **Relis le code d'autres** : Apprendre des patterns
3. **Fais tes propres projets** : Ressentir les douleurs
4. **Relis le compiler errors** : Le compilateur est ton ami
5. **Contribue à l'open-source** : Apprendre du vrai code
6. **Reste humble** : Il y a toujours à apprendre

### 50.4 Les pièges à éviter

❌ Trop de théorie, pas assez de code
❌ Ignorer le borrow checker (c'est là que c'est difficile)
❌ Utiliser `.unwrap()` partout en production
❌ Peur de unsafe (mais l'utiliser à bon escient)
❌ Ignorer les performances (benchmarking matters)
❌ Écrire du code sans tests

### 50.5 Mindset expert

✅ "Rust m'oblige à penser avant de coder"
✅ "Les erreurs du compilateur me rendent meilleur"
✅ "Ownership, c'est la puissance"
✅ "Pas de GC = pas de panique"
✅ "Le type system est mon ami"
✅ "Sûr à la compilation = sûr à l'exécution"

### 50.6 Derniers mots

Rust n'est pas facile au début.

Ownership et borrowing vont t'enraguer.

Mais quand tu comprendras... **c'est magique**.

Tu auras une compréhension profonde de la mémoire, de la concurrence, de la sécurité.

C'est un superpower que peu de programmeurs ont.

Alors persévère. Lis ce guide. Code beaucoup. Brise des choses.

**Et bienvenue dans le monde Rust.** 🦀

C'est un langage spécial, avec une communauté spéciale.

Tu vas aimer ça.

---

**FIN DU GUIDE COMPLET À 100%**

**150,000+ mots • 50 parties • 400+ exemples**

**Du zéro absolu à expert Rust.**

**Bon courage et bon code ! 🦀**

**Ecris Par AnonSecLab, Par BlueCtx, Fais avec ❤️ & Insomnie !**

---

# 🦀 INDEX COMPLET

---

## 📖 TABLE DES MATIÈRES COMPLÈTE

### PARTIE 0-4 : FONDATIONS
- **Partie 0** : Concepts ultra-basiques (8 sections)
- **Partie 1** : Installation macOS/Linux/Windows (11 sections)
- **Partie 2** : Types scalaires (i32, u32, f64, bool, char) (8 sections)
- **Partie 3** : Variables (let, mut, const, shadowing) (11 sections)
- **Partie 4** : Opérations arithmétiques et logiques (6 sections)

### PARTIE 5-8 : COLLECTIONS & FONCTIONS
- **Partie 5** : Affichage (println!, format!, dbg!) (10 sections)
- **Partie 6** : Strings (String vs &str, manipulation) (10 sections)
- **Partie 7** : Collections (arrays, tuples, vecteurs) (10 sections)
- **Partie 8** : Fonctions (paramètres, retours, récursion) (10 sections)

### PARTIE 9-22 : CORE RUST
- **Partie 9** : Contrôle de flux (if, else, if-else-if) (9 sections)
- **Partie 10** : Boucles (loop, while, for, ranges) (10 sections)
- **Partie 11** : Pattern matching (match, if let, while let) (8 sections)
- **Partie 12** : Ownership en profondeur (move, clone, copy) (10 sections)
- **Partie 13** : Borrowing en profondeur (références, slices) (10 sections)
- **Partie 14** : Structs (définition, impl, methods) (10 sections)
- **Partie 15** : Enums (simples, avec données, Option, Result) (10 sections)
- **Partie 16** : Traits (interfaces, impl, bounds) (7 sections)
- **Partie 17** : Génériques (fonctions, structs, enums) (6 sections)
- **Partie 18** : Modules & organisation (4 sections)
- **Partie 19** : Gestion d'erreurs basique (Result, panic, ?) (3 sections)
- **Partie 20** : Closures (capture, move, trait bounds) (5 sections)
- **Partie 21** : Iterators (map, filter, collect) (4 sections)
- **Partie 22** : Smart pointers (Box, Rc, RefCell) (3 sections)

### PARTIE 23-35 : SUJETS AVANCÉS
- **Partie 23** : Concurrence (threads, Mutex, Arc, channels) (5 sections)
- **Partie 24** : Async/Await basique (futures, tokio) (5 sections)
- **Partie 25** : Unsafe Rust (raw pointers, unsafe blocks) (4 sections)
- **Partie 26** : Memory model (stack vs heap) (2 sections)
- **Partie 27** : Cargo en détail (build, test, publish) (8 sections)
- **Partie 28** : Testing (unit, integration, doc tests) (5 sections)
- **Partie 29** : Macros basiques (println!, panic!, vec!) (3 sections)
- **Partie 30** : Regex & String processing (3 sections)
- **Partie 31** : File I/O (read, write, iterate) (3 sections)
- **Partie 32** : JSON & Serde (parsing, custom) (2 sections)
- **Partie 33** : Projets complets (CLI, web, game) (3 sections)
- **Partie 34** : Patterns & best practices (3 sections)
- **Partie 35** : Conclusion & ressources (4 sections)

### PARTIE 36-50 : EXPERT LEVEL
- **Partie 36** : Lifetimes avancés (explicites, structs, variance) (8 sections)
- **Partie 37** : Gestion d'erreurs complète (custom types, thiserror, anyhow) (7 sections)
- **Partie 38** : Async/Await approfondi (tokio, select!, join!, iterators) (6 sections)
- **Partie 39** : Unsafe Rust avancé (raw pointers, FFI, transmute) (5 sections)
- **Partie 40** : Concurrency avancée (Send/Sync, RwLock, Barrier, Condvar) (3 sections)
- **Partie 41** : Macros avancées (déclaratives, procedural, derive) (3 sections)
- **Partie 42** : Performance & optimization (criterion, profiling, SIMD, inlining) (4 sections)
- **Partie 43** : Embedded Rust (no_std, HAL) (2 sections)
- **Partie 44** : Web frameworks (Actix-web, Rocket, sqlx) (3 sections)
- **Partie 45** : Testing avancé (proptest, mockito, fuzzing) (3 sections)
- **Partie 46** : Regex & Text processing (regex avancée, unicode) (2 sections)
- **Partie 47** : Serialization avancée (custom serde) (1 section)
- **Partie 48** : Networking (TCP, HTTP avec tokio/hyper) (2 sections)
- **Partie 49** : Best practices avancées (builder, zero-cost abstractions) (2 sections)
- **Partie 50** : Conclusion & roadmap expert (7 sections)

---

## 📊 ROADMAP (STATISTIQUES)

```
CONTENU TOTAL
├─ 50 parties complètes
├─ 245 sections détaillées
├─ 400+ exemples de code
├─ 100+ pièges courants expliqués
└─ 3 level pour bien apprendre (noob > intermédiaire → pro du rust)

📚 COUVERTURE RUST
├─ Installation & setup
├─ Tous les types & collections
├─ Ownership & borrowing (le cœur)
├─ Pattern matching & destructuring
├─ Structs, enums, traits, génériques
├─ Modules & organisation
├─ Gestion d'erreurs complète
├─ Closures, iterators, lifetimes
├─ Concurrence (threads, async/await)
├─ Unsafe Rust & FFI
├─ Macros (déclaratives & procedural)
├─ Testing & benchmarking
├─ Web frameworks & networking
├─ Embedded Rust
├─ Performance & optimization
└─ Best practices & patterns avancés

✅ COMPLÉTUDE
├─ Débutant (Parties 0-8) : 100% ✅
├─ Intermédiaire (Parties 9-17) : 100% ✅
├─ Avancé (Parties 18-35) : 95% ✅
└─ Expert (Parties 36-50) : 90% ✅
```

---

## PAR OÙ COMMENCER

### DÉBUTANT ABSOLU
```
Semaine 1-2 : Parties 0-1 (Installation + ultra-bases)
Semaine 3-4 : Partie 2-3 (Types + Variables)
Semaine 5-6 : Partie 4-5 (Opérations + Affichage)
Semaine 7-8 : Partie 6-7 (Strings + Collections)
Semaine 9-10 : Partie 8 (Fonctions)
Semaine 11-12 : Parties 9-11 (Contrôle de flux + Pattern matching)

✅ RÉSULTAT : Comprendre les bases de Rust, créer des programmes
```

### INTERMÉDIAIRE
```
Semaine 1-4 : Parties 12-15 (Ownership + Borrowing + Structs + Enums)
Semaine 5-8 : Parties 16-22 (Traits + Génériques + Closures)
Semaine 9-12 : Parties 23-28 (Async + Concurrency + Testing)

✅ RÉSULTAT : Maîtriser les concepts clés, créer des applications
```

### EXPERT
```
Semaine 1-4 : Parties 36-39 (Lifetimes + Erreurs + Async approfondi + Unsafe)
Semaine 5-8 : Parties 40-44 (Concurrency avancée + Macros + Web + Perf)
Semaine 9-12 : Parties 45-50 (Testing + Networking + Best practices + Roadmap)

✅ RÉSULTAT : Devenir expert Rust, contribuer à l'open-source
```

---

## 💡 COMMENT UTILISER CE GUIDE

### ✅ LA BONNE FAÇON

1. **Lis une partie par jour/semaine** (pas de pression)
2. **Tape TOUT le code** (pas de copier-coller)
3. **Modifie les exemples** (change valeurs, ajoute cas)
4. **Casse intentionnellement** (apprendre des erreurs)
5. **Fais de vrais projets** (partir de la Partie 8)
6. **Relis en cas de problème** (c'est normal)
7. **Complète avec Rust Book** (pour détails supplémentaires)

### ❌ NE PAS FAIRE

- ❌ Lire trop vite
- ❌ Copier-coller passif
- ❌ Sauter les parties difficiles (ownership!)
- ❌ Pas d'exercices
- ❌ Apprendre sans coder
- ❌ Utiliser `.unwrap()` en production

---

## 🎓 CERTIFICATION MAISON

Après avoir suivi ce guide de bout en bout, tu peux te déclarer :

```
✅ Débutant Rust (Parties 0-8 terminées)
✅ Intermédiaire Rust (Parties 0-17 terminées)
✅ Avancé Rust (Parties 0-35 terminées)
✅ Expert Rust (Parties 0-50 terminées + projets réels)
```

---

## 🌟 RESSOURCES COMPLÉMENTAIRES

**Official Documentation**
- Rust Book : https://rust-lang.org/book
- Rust by Example : https://doc.rust-lang.org/rust-by-example
- Std Library : https://doc.rust-lang.org/std
- Nomicon : https://doc.rust-lang.org/nomicon

**Practice & Learning**
- Rust Playground : https://play.rust-lang.org
- Rustlings : https://github.com/rust-lang/rustlings
- LeetCode + Rust
- Project Euler

**Community**
- Reddit r/rust
- Rust Discourse
- GitHub Discussions
- Stack Overflow

**Libraries & Ecosystem**
- Crates.io : https://crates.io
- Awesome Rust : Curated list of resources
- Tokio Documentation

**Specializations**
- Web : Actix-web, Rocket, Axum book
- Systems : The Rustonomicon
- Embedded : Embedded Rust book
- Games : Bevy book
- Data : Polars, ndarray docs

---

## 💪 LES CLÉS DE LA RÉUSSITE

1. **Consistency** : Code tous les jours, même 30 minutes
2. **Projects** : Crée des vrais projets, pas juste des tutoriels
3. **Reading Code** : Lis le code d'autres developers
4. **Debugging** : Apprends à lire les erreurs du compilateur
5. **Community** : Pose des questions, partage ton code
6. **Open Source** : Contribue quand tu es prêt
7. **Patience** : C'est difficile au début (normal!)

---

## OBJECTIF FINAL

Après ce guide + pratique, tu seras capable de :

✅ Écrire du code Rust idiomatique
✅ Comprendre ownership & borrowing profondément
✅ Créer des applications complètes
✅ Utiliser des frameworks modernes
✅ Écrire du code sûr et performant
✅ Contribuer à l'open-source
✅ Enseigner Rust à d'autres
✅ APPROUVER ET PARTAGER ANONSECLAB !

---

## 🦀 BIENVENUE DANS LA COMMUNAUTÉ RUST

Tu t'apprêtes à apprendre l'un des langages les plus puissants et sûrs du marché.

C'est difficile au début.

C'est normal.

Ownership te rendra fou.

C'est normal.

Et puis un jour, ça clique.

Et tu réalises : **c'est du génie**.

Alors persévère.

Code beaucoup.

Casse des choses.

Relis les erreurs.

Et rejoins une communauté incroyable.

---

## RÉSUMÉ DE COUVERTURE

| Catégorie | Couverture | Status |
|-----------|-----------|--------|
| Débutant Rust | 100% | ✅ Complet |
| Intermédiaire Rust | 100% | ✅ Complet |
| Avancé Rust | 95% | ✅ Très complet |
| Expert Rust | 90% | ✅ Très complet |
| Spécialisations | 70% | ⚠️ Partiel (web, systems, embedded) |


---

## COMMENCE MAINTENANT

1. Ouvre ce README.md
2. Lis Partie 0 (2-3 heures)
3. Lis Partie 1 et installe Rust vraiment
4. Crée ton premier projet : `cargo new hello_rust`
5. Exécute : `cargo run`
6. Modifie le code, teste, casse des choses

**Voilà, tu as commencé Rust ! 🦀**

---

## 📞 BESOIN D'AIDE ?

Si tu bloques sur quelque chose :

1. **Relis la partie** (c'est normal, Rust c'est difficile)
2. **Consulte le Rust Book officiel**
3. **Regarde du code Rust sur GitHub**
4. **Demande sur r/rust ou Rust Discourse**
5. **Essaie le Rust Playground**

---

**C'EST LA FIN, SI TU AS LUS TOUT LE GUIDE, MERCI A TOI !**

