---
format: 1920x1080
duration: 40s
message: "Tout votre cycle achat, de la demande au paiement, dans un seul outil, sans connexion internet."
arc: Désordre → Réponse → Cycle → Meilleure offre → Contrôle → Hors ligne → Au-delà des achats → CTA
audience: "Directions achats d'entreprises en Côte d'Ivoire"
mode: collaborative
music: corporate modern tech, confident steady pulse, clean piano and light drums, premium, no vocals
tempo: 100 BPM — chevauchement ≈ un demi-temps (0,3 s) entre scènes
vertical: 1080x1920 par recadrage animé (même timeline, caméra recentrée sur la zone utile)
---

<!--
Décor commun à toutes les scènes : fond #0A2140, grille discrète qui dérive en diagonale,
fines lignes de flux DA → BC → Livraison → Paiement (motif récurrent), accent unique #5FB8D8.
Les écrans de l'application sont des captures réelles (données de démo) posées dans un cadre
tablette plat ; tous les montants sont masqués (barres grises) — règle « pas de prix à l'écran ».
Composants 21st.dev reproduits à la main (mécanique seulement).
-->

## Frame 1 — Le désordre

- scene: Des éléments épars s'empilent en désordre (e-mail « DA urgente », fichier « devis_v3_final.xlsx », bon papier scanné, message « Tu as relancé le fournisseur ? ») ; la pile penche, sature, se fige ; la question s'écrit en grand, accent sur « commande ».
- voiceover: "Des demandes d'achat dans les e-mails, des devis dans Excel, des bons de commande sur papier… et toujours la même question : où en est ma commande ?"
- duration: 9.5s
- poster: 8.5s
- transition_in: cut
- status: animated
- src: compositions/frames/s01.html
- type: hook
- persuasion: Pain validation (miroir du quotidien de l'acheteur)
- beat: overwhelm → tension
- blueprint: kinetic-type-beats
- components: Animated List (reproduit) — cartes qui tombent et s'empilent, rotation croissante
- asset_candidates:

narrativeRole: faire reconnaître au directeur achats son propre désordre — chaque élément de la pile est un canal réel cité par la voix (e-mail, tableur, papier, relance).
keyMessage: le suivi des achats est éparpillé ; personne ne sait où en est la commande.

## Frame 2 — Meridian Access

- scene: Le symbole se construit (flèche tracée, trois barres qui montent), « Meridian Access » lettre par lettre ; « Tout votre cycle achat. Un seul outil. » avec reflet sur « un seul » ; tablette qui se redresse (rotateX 20° → 0) et fait défiler l'accueil de l'application ; sortie en whip.
- voiceover: "Meridian Access réunit tout votre cycle achat dans un seul outil."
- duration: 5s
- poster: 3.8s
- transition_in: cut
- status: outline
- src: compositions/frames/s02.html
- type: product_intro
- persuasion: Negative contrast (désordre → un seul outil)
- beat: relief + clarity
- blueprint: logo-assemble-lockup
- components: Container Scroll Animation (reproduit) ; Text Rotate / reflet (reproduit)
- asset_candidates: assets/screens/00-accueil.png — accueil de l'application, tuiles des modules ; logo SVG « ma-logo » — symbole flèche + 3 barres

narrativeRole: la promesse arrive au 2e temps (reverse iceberg) — la marque et la valeur ensemble.
keyMessage: un seul outil pour tout le cycle achat. Vignette PNG de la vidéo tirée de cette scène.

## Frame 3 — Le cycle

- scene: Frise horizontale de 5 cards — Demande d'achat → Comparatif → Bon de commande → Livraison → Paiement ; un faisceau parcourt la frise au rythme de la voix, chaque card s'allume et montre un mini-écran réel ; la caméra suit le faisceau de gauche à droite.
- voiceover: "De la demande d'achat au paiement, chaque étape est tracée."
- duration: 5s
- poster: 4s
- transition_in: push-slide LEFT
- status: outline
- src: compositions/frames/s03.html
- type: key_feature
- persuasion: Show-don't-tell proof (le parcours complet, écran par écran)
- beat: clarity + control
- blueprint: spatial-pan-stations
- components: Animated Beam (reproduit)
- asset_candidates: assets/screens/01-liste-DA.png — liste des DA ; assets/screens/02-comparatif-meilleure-offre.png — comparatif ; assets/screens/03c-liste-BC.png — liste des BC ; assets/screens/04-suivi-livraisons.png — livraisons ; assets/screens/05-echeancier-paiements.png — paiements

narrativeRole: installer le motif DA → BC → Livraison → Paiement qui relie toute la vidéo.
keyMessage: chaque étape du cycle est tracée dans le même outil.

## Frame 4 — La meilleure offre

- scene: Tableau comparatif (3 fournisseurs fictifs) qui se remplit ligne par ligne, la colonne « Retenu / mieux-disant » s'illumine (Border Beam) ; puis des cases se cochent ligne par ligne et seules les lignes cochées glissent vers le bon de commande (commande partielle) ; mot qui change « Comparez. Choisissez. Commandez. »
- voiceover: "Comparez vos fournisseurs, la meilleure offre ressort d'elle-même. Commandez tout, ou seulement les lignes validées."
- duration: 7s
- poster: 5.5s
- transition_in: crossfade
- status: outline
- src: compositions/frames/s04.html
- type: key_feature
- persuasion: Feature-to-benefit translation (le comparatif désigne la meilleure offre ; on commande ligne par ligne)
- beat: confidence + control
- blueprint: cursor-ui-demo
- components: Border Beam, Tilt Card + Spotlight, Word Rotate (reproduits)
- asset_candidates: assets/screens/02-comparatif-meilleure-offre.png — comparatif avec colonne « Retenu » ; assets/screens/03a-commande-partielle-selection.png — une ligne décochée, « Commander la sélection (3) » ; assets/screens/03b-bon-de-commande-lignes-retenues.png — BC partiel « 3 articles sur 4 »

narrativeRole: la preuve centrale pour un acheteur — la décision fournisseur et la commande partielle, deux fonctions réelles.
keyMessage: la meilleure offre ressort d'elle-même ; on ne commande que ce qui est validé.

## Frame 5 — Le contrôle

- scene: Liste de statuts qui tombent toutes les ~0,4 s — « Livraison reçue », « Facture reçue — échéance calculée », « Paiement à prévoir », « Reçu comptant imprimé » ; à droite un échéancier dont les dates se placent sur une frise. Aucun montant.
- voiceover: "Livraisons, factures, échéances : vous savez qui payer, et quand."
- duration: 5s
- poster: 4s
- transition_in: crossfade
- status: outline
- src: compositions/frames/s05.html
- type: benefits
- persuasion: Rule of three (livraisons, factures, échéances) → peace of mind
- beat: control + peace of mind
- blueprint: grid-card-assemble
- components: Animated List, Number Ticker (sur compteurs de documents uniquement)
- asset_candidates: assets/screens/04-suivi-livraisons.png — suivi des réceptions ; assets/screens/05-echeancier-paiements.png — échéances 7/15/30 jours ; assets/screens/06b-recu-achat-comptant.png — reçu de dépense caisse

narrativeRole: transformer les fonctions aval (réception, facture, échéance, comptant) en un bénéfice simple.
keyMessage: vous savez qui payer, et quand.

## Frame 6 — Hors ligne & sécurité

- scene: Une clé USB stylisée s'insère, icône Wi-Fi barrée, l'application s'ouvre quand même ; puis Société A (bleu) et Société B (vert) côte à côte, séparées par une ligne infranchissable ; card à Border Beam « Vos données restent chez vous. »
- voiceover: "Pas besoin d'internet. Vos données restent chez vous, et chaque société a son espace séparé."
- duration: 6s
- poster: 5s
- transition_in: zoom-through
- status: outline
- src: compositions/frames/s06.html
- type: benefits
- persuasion: Risk reversal (pas de dépendance au réseau, données sur le poste)
- beat: trust + peace of mind
- blueprint: kinetic-type-beats
- components: Border Beam (reproduit)
- asset_candidates: assets/screens/07c-choix-societe.png — choix Société A / Société B ; assets/screens/07a-vue-multi-societes.png — vue consolidée ; assets/screens/07b-espace-societe-B.png — espace Société B

narrativeRole: l'atout différenciant (fichier unique, hors ligne, multi-sociétés isolées) remplace le témoignage.
keyMessage: sans internet, vos données chez vous, chaque société isolée.

## Frame 7 — Au-delà des achats

- scene: Bento de 4 cellules qui arrivent en vol — Stock (physique vs théorique), Ventes & comptoir (ticket 80 mm), Comptabilité (journaux), Flotte & immobilisations (validé : remplace « Tableau de bord DG » pour coller à la voix) ; la caméra plonge dans chaque cellule quand la voix la cite, recule sur « Toute votre gestion, au même endroit. »
- voiceover: "Et quand vous êtes prêts : stock, ventes, comptabilité, flotte. Toute votre gestion, au même endroit."
- duration: 6.5s
- poster: 6s
- transition_in: crossfade
- status: outline
- src: compositions/frames/s07.html
- type: benefits
- persuasion: Future pacing (la version Gestion Commerciale quand l'entreprise est prête)
- beat: aspiration
- blueprint: camera-journey
- components: Bento Grid + Spotlight Card (reproduits)
- asset_candidates:

narrativeRole: ouvrir sur la version Gestion Commerciale sans détourner du message achats.
keyMessage: toute la gestion, au même endroit, quand vous serez prêts.

Pas de capture disponible pour ces modules (l'application fournie est la version Achats) : cellules en
interface stylisée, libellés seuls, sans aucun chiffre.

## Frame 8 — Appel à l'action

- scene: « Vos achats méritent mieux qu'un tableur. » au-dessus de la tablette qui fait défiler Meridian Access ; bouton « Demander une démo » (shimmer) : clic → loader → coche ; fin : logo, « Meridian Access », baseline « ERP Achats & Gestion Commerciale », +225 01 40 35 21 55 (téléphone & WhatsApp), bande qui défile « Demandes d'achat · Comparatifs · Bons de commande · Livraisons · Paiements · Stock · Ventes · Comptabilité ».
- voiceover: "Vos achats méritent mieux qu'un tableur. Demandez votre démonstration gratuite."
- duration: 7.5s
- poster: 6.8s
- transition_in: blur-crossfade
- status: outline
- src: compositions/frames/s08.html
- type: cta
- persuasion: Negative contrast (tableur) → Risk reversal (démonstration gratuite)
- beat: motivation → urgency-to-act
- blueprint: logo-assemble-lockup
- components: Container Scroll Animation, Shimmer Button, Logo Marquee (reproduits)
- asset_candidates: assets/screens/00-accueil.png — accueil pour la tablette ; assets/screens/08-tableau-de-bord.png — tableau de bord ; logo SVG « ma-logo »

narrativeRole: convertir — une action simple, un contact local.
keyMessage: demandez votre démonstration gratuite, +225 01 40 35 21 55.
