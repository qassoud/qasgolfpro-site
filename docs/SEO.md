# QasGolfPro SEO — 4 octobre 2026

## Audit avant intervention
- Site statique bilingue, six pages HTML, production liée à main.
- Référence de retour arrière : 4b38aa02669198c68dd17b6daba5c2c25b142f39 ; déploiement dpl_A82bYNLR2BfhMMy3h4B73cx2eMnh.
- Accueil HTTP 200 ; URL inexistante HTTP 404.
- robots.txt et sitemap.xml HTTP 404.
- Canonical et alternates FR/EN déjà présents.
- Absence de données structurées et de métadonnées Open Graph/Twitter.
- Pages GPS : absence de H1 et de meta description.
- Captures PNG lourdes, dimensions HTML et chargement différé absents.
- Plusieurs textes décrivaient la mise en page plutôt que l’usage de l’application.

## Modifications
- Titres et descriptions uniques sur les six pages ; canonical conservées ; ajout x-default réciproque.
- Open Graph et Twitter Cards avec images existantes du produit.
- JSON-LD WebSite, WebPage, MobileApplication ; BreadcrumbList sur les exemples GPS.
- Aucun avis, note, prix ou classement inventé. Le balisage ne garantit pas de résultat enrichi.
- H1 sur chaque page, contenu FR/EN reformulé, FAQ visible avec accordéons natifs.
- robots.txt autorisant l’exploration et indiquant le sitemap ; sitemap XML de six URL canoniques avec alternates.
- Redirection permanente /index.html vers / ; les liens internes pointent vers /.
- Captures PNG conservées ; variantes WebP à dimensions identiques, poids cumulé réduit de 88 % (8 168 799 à 980 582 octets).
- Images dimensionnées, chargement différé hors du premier écran ; vidéos à la demande, fichiers vidéo inchangés ; brochure différée.
- Lien d’évitement et titre de l’iframe PDF.

## Search Console : étape nécessitant le compte propriétaire
L’accès Google n’est pas encore authentifié dans cette session. Aucune propriété vérifiée ni demande d’indexation ne doit être présumée.
1. Ouvrir https://search.google.com/search-console ; sélectionner ou ajouter la propriété de type Préfixe de l’URL : https://qasgolfpro.vercel.app/.
2. Si nécessaire, utiliser la balise HTML de validation fournie par Google dans le head de index.html, ou le fichier HTML exact fourni par Google à la racine. Ne pas inventer de code de validation.
3. Après publication de la preuve, valider la propriété.
4. Soumettre https://qasgolfpro.vercel.app/sitemap.xml dans Sitemaps.
5. Inspecter / et /en.html, lancer le test en direct puis demander l’indexation.
6. Contrôler Pages, Performances, Core Web Vitals et les éventuelles erreurs de données structurées.
Ne pas utiliser l’Indexing API pour ces pages ordinaires ni l’ancien endpoint de ping des sitemaps.

## Cibles et mesure
Priorité : QasGolfPro / Qas Golf Pro ; application golf iPhone ; carte de score golf iPhone ; statistiques golf ; GPS golf iPhone. Anglais : QasGolfPro, golf scorecard app iPhone, golf statistics app, satellite golf GPS.
Les requêtes génériques sont concurrentielles. Aucune position Top 5 ne peut être garantie, et aucune mesure de position initiale n’est disponible sans Search Console.
Après indexation : comparer les périodes de 28 jours, séparer marque et hors marque, FR et EN, pays et appareils. Suivre impressions, clics, CTR, position moyenne et URL indexées. Mesurer les conversions App Store via les outils Apple si souhaité ; aucun traqueur ajouté par cette intervention.
À 30 jours : corriger les exclusions d’indexation et ajuster les titres des pages ayant des impressions mais peu de clics.
À 60–90 jours : créer des guides originaux utiles à partir des questions réelles des golfeurs, avec captures et exemples vérifiés ; obtenir des liens éditoriaux de clubs et partenaires pertinents. Éviter le bourrage de mots-clés, les pages artificielles et les achats de liens.

## Sources officielles
- https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap
- https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl
- https://developers.google.com/search/help/crawling-index-faq

## Contrôles avant publication
Syntaxe JSON/JSON-LD et XML, six titres et descriptions uniques, H1 unique, canonicals/hreflang, existence des ressources locales, ancres, scripts de navigation et sources vidéo inchangés. Vérification visuelle et HTTP à effectuer sur le déploiement avant de déclarer l’intervention terminée. Aucun score PageSpeed ni Core Web Vitals de terrain n’a été mesuré.
