# Reels « Israël-Palestine, qu'en pensent les Français ? » (26/11/2026)

**Sujet SENSIBLE** : validation de Salah ou d'Enis, Reel par Reel, avant toute programmation.

## Comment ils sont faits
- Modèle : le Reel « Les médias neutres, ça existe pas ».
- Format 1080x1920, tiré des rushs 4K propres. La caméra suit la parole : cadrage sur Salah quand il pose la question, sur l'invité quand il répond.
- Habillage : encadré bleu #003FB0, texte blanc italique gras, mots exacts entre guillemets, placé sous les visages. Logo bleu transparent en haut à droite. Pas de sous-titres.
- Fin : carte « L'épisode complet est sur YouTube » avec la miniature et le titre « Israël-Palestine, qu'en pensent les Français ? », en fondu de 0,3 s.
- Coupes : toujours en fin de phrase. Chaque début et chaque fin ont été réécoutés avec Whisper large-v3.
- Outils :
  - `outils/reel-suit-parole.py` lit le fichier `reels.json` (tours de parole et cadrages relevés à l'œil).
  - `outils/calque-encadre.js` fait l'encadré.
  - `outils/fin-youtube.js` fait la carte de fin.
  - `outils/couverture-reel.js` fait les couvertures (style grille, étiquette MICRO-TROTTOIR).

## Ordre de publication conseillé
Conseil de l'agent pr-communications-manager :
- commencer par les Reels consensuels, qui installent la série ;
- alterner les points de vue, jamais plus de deux Reels du même côté d'affilée ;
- garder les plus clivants pour la fin.

| # | Fichier | Personne | Durée | Encadré / titre de couverture (mots exacts) |
|---|---|---|---|---|
| 1 | r16-seul-droit-saimer | dame au manteau rouge (228) | 50 s | « On n'a qu'un seul droit, de s'aimer » |
| 2 | r20-inhumanite | dame de 78 ans (209) | 28 s | « On ne va pas recommencer ces histoires d'inhumanité » |
| 3 | r08-diplomate | jeune homme (230) | 42 s | « C'est un travail de diplomate » |
| 4 | r13-guerres-servent-a-rien | homme à capuche (229) | 48 s | « Les guerres, ça ne sert à rien » |
| 5 | r01-montreal | jeune femme au foulard (231) | 57 s | « Pour moi, c'est pas du tout religieux » |
| 6 | r24-chacun-sa-religion | dame de 78 ans (209) | 55 s | « Chacun fait sa religion » |
| 7 | r12-envie-dy-croire | jeune homme (230) | 59 s | « J'ai envie d'y croire » |
| 8 | r07-espoir-vaincra | jeune femme au keffieh (213) | 31 s | « L'espoir vaincra » |
| 9 | r09-france-genocide | jeune homme (230) | 52 s | encadré : « Elle a mis du temps à dire que c'est un génocide » ; couverture : « Mettre une pression ou du moins un holà à Israël » |
| 10 | r21-vive-israel | dame de 78 ans (209) | ~53 s | « Moi je dis Vive Israël » |
| 11 | r02-buzz | jeune femme au foulard (231) | 44 s | « Il faut faire le buzz pour être entendu » |
| 12 | r15-titans | homme à capuche (229) | 61 s | « C'est mauvais dans les deux côtés » (moment léger, L'Attaque des Titans) |
| 13 | r23-eilat | dame de 78 ans (209) | 29 s | « Personne ne leur dit rien » |
| 14 | r05-liberation | jeune femme au keffieh (213) | 48 s | « Je suis pour la libération de la Palestine » |
| 15 | r17-choisissons-lamour | dame au manteau rouge (228) | 48 s | « Choisissons l'amour » |
| 16 | r22-une-guerre | dame de 78 ans (209) | 22 s | « C'est une guerre » |
| 17 | r18-enfants | homme au bonnet (225) | 63 s | « Il y a des enfants qui sont en train de mourir » |
| 18 | r06-france-complice | jeune femme au keffieh (213) | 68 s | « La France est complice de ces crimes-là » |
| 19 | r04-crime-humanite | jeune femme au foulard (231) | 58 s | « Crime contre l'humanité » |
| 20 | r14-que-la-paix | homme à capuche (229) | 41 s | « On ne veut que la paix » |

## Précautions (avis de pr-communications-manager)
- **Légende de chaque Reel** : « Micro-trottoir, propos des passants, ils n'engagent pas Jeunesse Média », suivie du lien vers la vidéo longue. Pas de hashtags militants (#FreePalestine…).
- **Le mot « génocide »** n'apparaît que dans la bouche des passants, entre guillemets. Jamais dans nos titres ni nos légendes.
- **Reel 19 (r04)** : elle évoque des violences sexuelles par des militaires israéliens. C'est son propos : aucun titre ni aucune légende ne reprend l'accusation.
- **Reel 20 (r14)** : il dit « je n'ai rien contre les juifs, c'est plus les sionistes ». La phrase reste entière, l'encadré porte sur la paix.
- **Reels 10 et 16 (r21, r22)** : commentaires vifs à prévoir, modération active.

## Passages écartés volontairement
- 225 : « ici c'est les sionistes qui contrôlent », « un sioniste derrière Macron », « les mecs du Mossad ». Complotisme : risque de suppression par Meta et TikTok. ⚠️ C'est aussi l'accroche de la vidéo longue : à revoir avec Enis avant sa publication.
- 225 : comparaison avec Hitler.
- 225 : les vidéos de maisons chrétiennes, non vérifiées.
- 209 : accusations nominatives contre Mélenchon.
- 224 : probablement mineur.
- 213 : question de Salah très orientée (« pourquoi ils se permettent de faire des génocides »).
- 209 : passages hors sujet (casseurs, « les Africains », immigration).
- Doublons retirés : les autorités internationales et leurs intérêts économiques (231), l'intérêt d'Israël et les médias (230).
