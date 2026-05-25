# DM-LAB-7---Galerie-de-Stars-RecyclerView-Animations-et-Filtrage

Objectif
L’objectif de ce TP est de créer une application Android complète permettant d’afficher une galerie de stars (personnalités célèbres) sous forme de liste avec images circulaires, notes, filtrage par nom, et animations d’introduction.
L’apprenant découvrira :
le RecyclerView et le pattern ViewHolder,
la gestion des adapters personnalisés,
les animations dans Android,
l’utilisation de Glide pour le chargement d’images distantes,
la mise en œuvre d’un filtrage dynamique via une barre de recherche (SearchView).

Étape 1 — Structure du projet
Créer un projet Android nommé StarsGallery.
Créer les packages suivants :
beans → contient la classe Star
dao → contient l’interface générique IDao
service → contient la classe StarService
adapter → contient la classe StarAdapter
ui → contient les activités SplashActivity et ListActivity
Dans le dossier res/drawable, ajouter une image star.png (ou utiliser l’icône par défaut du projet).

![Import OVA](https://github.com/user-attachments/assets/d7e69f22-0e53-4bea-a1e9-805e4c42c2ca)

---

Étape 2 — Écran de démarrage animé (SplashActivity)

![Import OVA](https://github.com/user-attachments/assets/617faefe-6abd-4b04-933d-92c93b358980)

---

Étape 3 — Modèle de données (Classe Star)

Étape 4 — Interface DAO Générique

![Import OVA](https://github.com/user-attachments/assets/3fcef9d9-ef06-4db4-a574-2b8061f278ab)


