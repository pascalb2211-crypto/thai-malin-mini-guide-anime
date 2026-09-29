Version test HTML : 20 pages navigables, sommaire, favoris, PDF/impression, checklist mémorisée, liens utiles et zones prévues pour les interactions. Les visuels 2-20 sont temporairement extraits de la planche maître ; ils seront remplacés par les 20 fichiers HD individuels sans modifier le HTML.

Pages 1, 2 et 3 : images HD finales intégrées (WebP, 1024x1536, ~400 Ko chacune), avec zones cliquables posées dessus (11 sur la page 1, 5 sur la page 2, 6 sur la page 3). Pages 4-20 : toujours des extraits provisoires en attendant les HD.
Toutes les images du guide sont en WebP + miniatures légères assets/thumbs/ (~10 Ko chacune, ne se rechargent qu'une fois).
Zones cliquables : bloc HOTSPOTS dans index.html (x,y,w,h en % + destination href/page/panel). Mode placement à la souris : ouvrir index.html?edit=1.

Page 4 (Visa & Entrée en Thaïlande) intégrée : image HD portrait 1024x1536, 6 zones cliquables sur les cartes numérotées (Passeport/Preuves→checklist, TDAC→site officiel, Visa→France Diplomatie, Assurance→SafetyWing, Autres informations→Liens utiles).

Page 5 intégrée : ton fichier porte le titre « À l'arrivée en Thaïlande » — j'ai mis à jour le titre de la page 5 dans le sommaire en conséquence (il portait l'ancien placeholder « Vols & Réservations »). 6 zones cliquables : Contrôle d'immigration→page Visa (4), Bagages→page Valise (9), Douane→France Diplomatie, Transport→page Se déplacer (11), Argent→page Mon argent (8), SIM/Internet→page eSIM (7).

Page 6 intégrée : titre réel « Où aller en Thaïlande ? » (mis à jour, remplace l'ancien placeholder « Assurance voyage »). 6 zones cliquables (les 6 régions) → toutes vers la page Itinéraires recommandés (15).

Page 7 intégrée : titre réel « Itinéraires conseillés » (remplace l'ancien placeholder « eSIM & Internet »). 6 zones cliquables : les 5 durées → page Où aller (6), Thématiques → page Excursions (19).
⚠️ Le lien « Carte SIM/Internet » de la page 5 pointait vers la page 7 en pensant y trouver du contenu eSIM plus tard — corrigé vers le panneau Liens utiles, car la page 7 est maintenant les Itinéraires.

Page 8 intégrée : titre réel « Conseils pratiques pour un séjour réussi » (remplace l'ancien placeholder « Mon argent en Thaïlande »). 6 zones cliquables : Meilleure période → Liens utiles, Budget → Liens utiles, Transports → page Se déplacer (11), Hébergement → page Se loger (12), Santé et sécurité → SafetyWing (assurance voyage), Étiquette et culture → page Culture & Traditions (17).
⚠️ Le titre de la page 8 (« Conseils pratiques pour un séjour réussi ») est très proche de celui de la page 16 (« Conseils pratiques au quotidien ») — à vérifier lors du point sur le plan final pour éviter un doublon de sujet.

Page 9 intégrée : titre réel « À ne pas manquer en Thaïlande » (remplace l'ancien placeholder « Ma valise »). 6 zones cliquables : Temples & culture → page Visiter les incontournables (14), Plages & îles → page Où aller (6), Gastronomie → page Manger en Thaïlande (13), Nature & aventure → page Excursions (19), Marchés & shopping → page Shopping & Souvenirs (18), Bien-être & détente → Liens utiles.
⚠️ Autre doublon potentiel à surveiller : le sujet de la page 9 (« À ne pas manquer ») recoupe fortement celui prévu pour la page 14 (« Visiter les incontournables »).

Page 10 intégrée : titre réel « Le petit plus pour un séjour parfait » (remplace l'ancien placeholder « Arrivée en Thaïlande »).
⚠️ Cette page recoupe fortement la page 8 sur 3 des 6 cartes (Climat/Meilleure période, Argent/Budget, Santé et sécurité — contenus quasi identiques). Sur demande de Pascal : ces 3 cartes redondantes pointent vers la page 8 au lieu de dupliquer l'info. Seules les 3 cartes vraiment nouvelles ont un lien propre : Applications utiles → Liens utiles, Respect et culture → page Culture & Traditions (17), Au quotidien → Liens utiles.

Page 11 intégrée : titre réel « Astuces et bons plans » (remplace l'ancien placeholder « Se déplacer en Thaïlande »).
⚠️ Cette page reprenait à 100% du contenu déjà couvert par les pages 8 et 10 (eSIM/apps déjà vues 2 fois, argent, transport, coutumes, petits plus). Sur demande de Pascal : aucune carte n'a de contenu propre, les 6 hotspots redirigent vers la page 8 ou 10 correspondante (Internet/téléphone→10, Change et paiements→10, Se déplacer malin→8, Applications indispensables→10, Respecter les coutumes→8, Petits plus→10).
⚠️ Corrections en cascade liées à la disparition de la page « Se déplacer en Thaïlande » (qui n'existe plus en tant que page dédiée) :
  - Page 5, carte « Moyens de transport » : pointait vers la page 11 en anticipant une page transport dédiée → corrigé vers le panneau Liens utiles.
  - Page 5, carte « Récupération des bagages » : pointait vers la page 9 en anticipant du contenu bagages qui n'y est jamais arrivé (page 9 = « À ne pas manquer ») → corrigé vers le panneau Checklist.
  - Page 8, carte « Transports » : pointait vers la page 11 en anticipant la même page transport dédiée → corrigé vers le panneau Liens utiles.

Page 12 intégrée : titre réel « En résumé — Tout pour un séjour réussi » (récap volontaire, remplace l'ancien placeholder « Se loger »). 6 zones cliquables : Les indispensables → Checklist, Le budget → page 8, Se déplacer facilement → Liens utiles, Où dormir ? → page 8, Santé et sécurité → page 8, Profiter pleinement → Liens utiles.
⚠️ Comme pour « Se déplacer », le sujet « Se loger » n'a plus de page dédiée dans le plan actuel (le placeholder a été remplacé par ce récap). Corrigé en cascade : la carte « Hébergement » de la page 8 pointait vers la page 12 en anticipant cette page dédiée → repointée vers le panneau Liens utiles.

Page 13 intégrée : titre réel « Les erreurs à éviter » (choisi par Pascal parmi 2 visuels proposés ; remplace l'ancien placeholder « Manger en Thaïlande »). 6 zones cliquables : Arnaques courantes → Liens utiles, Nourriture et eau → Liens utiles, Climat et saison → page 8, Règles et culture → page 17, Santé et sécurité → page 8, Déplacements → Liens utiles.
⚠️ Troisième sujet fantôme : « Manger en Thaïlande » n'a plus de page dédiée (comme Se déplacer et Se loger avant lui). Corrigé en cascade : 3 hotspots qui pointaient vers la page 13 en anticipant du contenu gastronomie (« Gastronomie » et « Cuisine délicieuse » sur la page 1, « La gastronomie thaïlandaise » sur la page 9) → tous repointés vers le panneau Liens utiles.

Page 14 intégrée : titre réel « Les petits plus pour une expérience inoubliable » (remplace l'ancien placeholder « Visiter les incontournables »). Sur demande de Pascal, cartes redondantes liées vers leur source plutôt que dupliquées : Activités selon vos envies → page 9, Souvenirs à rapporter → page 18 (Shopping & Souvenirs), Itinéraires sur mesure → page 7 (Itinéraires conseillés). Cartes propres restantes → Liens utiles : Expériences à vivre, Bonnes adresses, Mot de la fin.
⚠️ Corrections en cascade liées à la disparition du sujet « Visiter les incontournables / Temples » : la carte « Temples majestueux » de la page 1 et « Les temples et la culture » de la page 9 pointaient vers la page 14 en anticipant une page dédiée aux temples → toutes deux repointées vers la page Culture & Traditions (17), plus pertinente.

📌 Réservé pour la page 20 : le visuel « Derniers conseils et mot de la fin » (reçu comme "page 15") a été mis de côté dans _reserved/page-20-source-derniers-conseils.png. C'est clairement une page de clôture de guide (carte "Merci et bon voyage !") — elle sera intégrée en page 20 une fois qu'on aura les vraies pages 15-19. Sa carte "Les choses à éviter" recoupera la page 13 quand elle sera intégrée.

📌 Deuxième visuel de clôture reçu (envoyé comme "page 16") : « À bientôt en Thaïlande ! » — réservé sans décision dans _reserved/page-20-source-a-bientot.png, en attendant les vraies pages 16-19. À trancher avec Pascal : celui-ci remplace le premier réservé, ou les deux se suivent en pages 19/20.

📌 Troisième visuel réservé (envoyé comme "page 17") : « Après la Thaïlande... et pourquoi pas la suite ? » — autres destinations Asie (Bali, Vietnam, Laos, Cambodge, Singapour...). Hors-sujet par rapport à « Culture & Traditions » attendu en page 17, et de nombreux hotspots (pages 1,8,9,10,11,13,14) pointent déjà vers la page 17 en anticipant du contenu Culture/Étiquette. Réservé dans _reserved/page-source-apres-thailande-autres-destinations.png, probablement une page de fin de guide (proche des 2 visuels de clôture déjà en réserve). La vraie page 17 « Culture & Traditions » reste à recevoir.

⏳ EN ATTENTE DE RÉGÉNÉRATION (non intégrées) :
- Page 18 « Conseils pratiques pour un voyage réussi ! » — erreur factuelle : indique 60 jours sans visa au lieu de 30 (règle en vigueur depuis le 15/09/2026). Sauvegardée dans _pending/page-18-visa-60jours-conseils-pratiques.png.
- Page 19 « Astuces et bons plans pour un séjour au top ! » — bug visuel sur le logo « Réunion Malin » (le M s'affiche comme un Λ). Sauvegardée dans _pending/page-19-logo-glitch-astuces-bons-plans.png.
Les deux recoupent aussi fortement les pages 8/10/11/12 déjà intégrées et ne correspondent pas aux sujets placeholder attendus (Shopping & Souvenirs / Excursions).

Page 20 intégrée : titre réel « Prêt pour l'aventure ? » (remplace l'ancien placeholder « Numéros utiles & SOS »). C'est la vraie page de clôture (badge "20", "Merci d'avoir lu ce mini-guide !"). 6 zones cliquables : Check-list → panneau Checklist, Adoptez le bon état d'esprit / Voyagez responsable / Immortalisez vos souvenirs → Liens utiles, Rejoignez la communauté → thaimalin.fr, Et maintenant à vous ! → retour page 1 (relance le guide).
⚠️ Quatrième sujet fantôme : « Numéros utiles & SOS » (numéros d'urgence) n'a plus de page dédiée dans le plan actuel.
⚠️ Cette vraie page 20 change la donne pour les 3 visuels de clôture mis en réserve plus tôt (Derniers conseils/mot de la fin, À bientôt en Thaïlande, Après la Thaïlande/autres destinations) : ils ne sont probablement plus nécessaires puisqu'on a maintenant la vraie fin du guide. À confirmer avec Pascal.

Page 15 intégrée : « Itinéraires recommandés » — contenu enfin conforme au sujet attendu. 5 zones cliquables (7/10/15/21/30 jours) → Liens utiles.

Page 17 intégrée : « Culture & Traditions » — enfin le bon sujet, tous les liens posés depuis les pages 1, 8, 9, 10, 11, 13, 14 pointent maintenant vers du contenu pertinent. 6 zones cliquables : Art/artisanat → page 18 (Shopping & Souvenirs), les 5 autres → Liens utiles.

Page 18 intégrée : titre réel « Formalités & Entrée en Thaïlande » (visa 30 jours correct, mentionne explicitement la suppression de l'exemption 60 jours — remplace le placeholder « Shopping & Souvenirs »). Sur demande de Pascal, cartes redondantes avec les pages 3/4 liées plutôt que dupliquées : Exemption de visa → page 4, Passeport et documents → page 3, TDAC obligatoire → page 3, Assurance voyage → page 4. Cartes nouvelles : Billet de sortie/retour → Checklist, Séjour de plus de 30 jours → Liens utiles.
⚠️ Cinquième sujet fantôme : « Shopping & Souvenirs » n'a plus de page dédiée. Corrigé en cascade : 4 hotspots qui pointaient vers la page 18 en anticipant du contenu shopping (page 1 ×2, page 9, page 14) → tous repointés vers le panneau Liens utiles.

Page 16 intégrée : « Conseils pratiques au quotidien » (visa 30 jours correct). Sur demande de Pascal, cartes redondantes liées vers leur source : Formalités et documents → page 18, Argent et paiements → page 10, Se loger malin → page 8, Communication et internet → page 10. Cartes gardant leur propre lien : Se déplacer facilement → Liens utiles, Santé/sécurité/bien-être → Liens utiles (contient les numéros d'urgence 191/1669, qui comblent en partie le sujet « Numéros utiles & SOS » disparu plus tôt).

Page 19 intégrée : « Excursions & Activités » — enfin le bon sujet, logo « Réunion Malin » correctement rendu cette fois. 6 zones cliquables : Culture et découverte locale → page 17, les 5 autres → Liens utiles.

🎉 GUIDE COMPLET : 20/20 pages réelles intégrées, testées et vérifiées (dimensions, texte, hotspots, alignement pixel-perfect, zéro erreur JS/réseau sur l'ensemble des 20 pages).

Note : les dossiers _reserved/ et _pending/ contiennent des visuels reçus en trop ou obsolètes pendant la construction (3 visuels de clôture redondants avec la page 20, remplacés par les vraies pages 18/19 corrigées). Ils ne sont pas utilisés par le site et peuvent être supprimés sans impact.
