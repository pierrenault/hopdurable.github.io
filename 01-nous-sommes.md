---
title: Nous sommes
layout: main
---
## Association de préfiguration  

Hop!Durable est aujourd'hui une [association](http://www.journal-officiel.gouv.fr/publications/assoc/pdf/2016/0040/JOAFE_PDF_Unitaire_20160040_00728.pdf) de préfiguration.  
L'objet : la promotion et le développement d’une culture de l’aménagement durable à l’échelle du bassin rhonalpin.  

Elle est organisée selon un **Directoire collégial** regroupant 4 collèges :

 - Membres actifs  
 - Membres entreprises  
 - Membres institutions  
 - Membres scientifiques  

Réunir au sein de sa gouvernance les acteurs de l'aménagement durable (publics, parapublics, privés) traduit notre volonté d'inscrire Hop!Durable au coeur d'une **coopération de territoire efficace** - portée par et pour ses acteurs - qui impulse et porte une dynamique sur la durée.  

L’équipe à plein temps est composée de 3 membres actifs bénévoles.
Nous recherchons une quatrième personne Artisan - designer - concepteur.

<a href="offre-artisan-designer.html" class="button">Nous rejoindre</a>

## Ils nous accompagnent  

{% for partners in site.data.partners %}
<div class="clearfix">
  <img class="left" src="{{ partners.logo }}" alt="{{ partners.name }}" style="max-width: 20%;margin-right: 1rem;">
  <div class="clearfix" style="overflow:hidden">
  <h3>{{ partners.name }}</h3>
  {{ partners.motivation }}
  </div>
</div>
{% endfor %}
