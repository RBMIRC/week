# Semainier · Black Mountain College (1933-1957)

Le Black Mountain College semaine par semaine : https://rbmirc.github.io/week

Chaque entrée porte sa source (document de l'Asheville Art Museum avec lien vers la fiche du musée, livre et page, notice du BMC Yearbook) et sa **part déduite** : 0 % pour un fait daté par un document, davantage pour ce qui est tiré d'un livre, d'une lecture automatique ou reconstitué (emploi du temps du trimestre). La vue « Semaine » montre les 7 jours ; les options choisissent les collections affichées :

- Documents du collège (Asheville Art Museum) : bulletins de la communauté, catalogues et annonces, bulletins d'information, programmes de concerts et spectacles, cours à horaire attesté, fiches du musée en lecture automatique ;
- Témoignages : entretiens de Mary Emma Harris (Black Mountain College Project), Michael Rumaker, *Black Mountain Days* (2003) ;
- Histoires et études : Martin Duberman, *Black Mountain* (1972), dépouillé et en lecture automatique ; David Silver, *The Farm at Black Mountain College* (2024) ; 52 autres livres et études en lecture automatique, au choix titre par titre ;
- Reconstitution : emploi du temps et vie commune du trimestre, établis par l'analyse croisée des documents ;
- Faits datés au mois ou à la saison.

## Version publique

Cette version garde toutes les entrées et leurs références exactes, mais pas les extraits longs des textes cités (citations de livres, biographies, passages d'entretiens), qui appartiennent à leurs auteurs et éditeurs : ils restent consultables à la source. Retraits de cette publication :

- notes de Duberman (data.js) : 670
- extraits Chronos et Rumaker (data_chronos.js) : 1166
- phrases des livres (renvois) : 32
- biographies du BMC Yearbook : 1359
- extraits de vérification (verification.js) : 32812

## Fichiers

Publié le 2026-11-02 depuis le dépôt de travail RBMIRC/bmc-chronology (`bmc-programmes-aam/scripts/publier_semainier.py`). Ne pas modifier ici : les fichiers sont régénérés à chaque publication.

| fichier | taille |
|---|---|
| `data.js` | 7.0 Mo |
| `data_chronos.js` | 1.3 Mo |
| `data_en.js` | 5.5 Mo |
| `data_personnes.js` | 1.3 Mo |
| `data_scenario.js` | 5.4 Mo |
| `data_syntheses.js` | 8.7 Mo |
| `verification.js` | 1.1 Mo |
| `spec/*.js` (22 années, chargées à la demande) | 20.8 Mo |

Total : 51.1 Mo (servis compressés par GitHub Pages).

Bibliothèque d'affichage : Event Calendar (licence MIT), dans `lib/`.

## English

English version: https://rbmirc.github.io/week/en/ (or `?lang=en`). Sources quoted in English are never translated. Our own French texts are translated by hand into American English and checked line by line (`scripts/traduction_en.py`, guide in `semainier/i18n/GUIDE_TRADUCTION.md`): interface, collections, scoring rules, and every title, summary, and note from Duberman, the museum documents, the reconstruction, the supplements, the student records, and the other books and studies (14,082 strings, all reviewed). Machine translation is kept only as a fallback for a text added later, marked ≈ with the original French in the record; long syntheses remain in French.
