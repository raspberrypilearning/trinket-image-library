Le fichier de démarrage contient une bibliothèque d'images utiles.

Clique sur l'icône « View and Add Images » :

![Une icône ayant la forme d'une feuille de papier dont le coin supérieur droit est replié et sur laquelle figure une scène de montagne.](images/view-add-images.png)

Fais défiler la bibliothèque d'images et note le nom de fichier d'une image que tu aimerais utiliser dans ta page web :

![La bibliothèque d'images avec le fichier beetle.jpg affiché.](images/image-gallery.png)

Ajoute ton image au `<main></main>` dans `index.html` pour qu'elle apparaisse sur ta page web :

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 35
---

    <!-- Le contenu principal de la page web se trouve entre les balises principales -->
    <main>
      Lorem ipsum dolor sit amet. 
      <img src="beetle.jpg" alt="Description de l'image.">
   
    </main>

--- /code ---
