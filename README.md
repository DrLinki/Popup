# Popup

## À faire
L'activation et la désactivation de la Popup se font grâce à des lien HTML/CSS :
* **lien_activation_popup**
* **lien_desactivation_popup**

Le but est de remplacer ça par du JavaScript.
Pour se faire, il faudra modifier le CSS en remplaçant **:target** par une autre classe CSS qui se rajoutée à la popup lorsque l'on cliquera sur le bouton **Ouvrir Popup**, et enlevée/supprimée lorsque l'on cliquera sur **Fermer Popup**.

Il faudra ensuite créer 2 fonctions JavaScript :
* **ouvrirPopup()**
* **fermerPopup()**
