# 📋 Cheatsheet — Ranges exploitantes Baki (All in Team)

> Générée depuis `ranges_baki_all_in_team.json` (la source de vérité reste l'app).
> But : retenir **l'idée** de chaque range et ses frontières — le drill grave le reste.

## Lecture des cases
- **Case bicolore (split)** : pas une fréquence — un choix selon le profil (relanceur serré → couleur pleine, relanceur/table large → triangle).
- **Triangle seul** (défense) : *optionnel* — fold par défaut, prends l'option si les conditions s'y prêtent (stacks profonds pour set-mine, adversaire qui abandonne trop pour raise/fold).
- **Contour blanc [6BB]** : sizing 6 blindes.

## 🌍 Règles universelles
1. **AA-KK = toujours l'action max** : 4bet/call en attaque, limp/reraise sur aggro early, raise/5bet all-in en défense. *Unique exception : SB vs 3bb vs 10 % → seul AA part all-in (KK et AKs = raise/call).*
2. **A5s-A2s = la famille caméléon, jamais fold** : limp/reraise (passive), limp puis 4bet-bluff (aggro dès HJ, surtout A5s), limp/call (blinds), raise/fold 4bet (défense). *Si tu hésites sur un petit as assorti → c'est ta main de bluff.*
3. **Petites paires = set-mine** : limp/call en attaque, call (souvent triangle = optionnel) en défense vs 3bb. Face à un gros sizing (6bb), elles disparaissent.
4. **Suited connectors (JTs→54s) = limp/call** en attaque passive, call en défense BB — jamais des opens en early.
5. Plus la position/le % villain augmente → les mains **montent en grade** (fold→limp→open→[6BB]→4bet). Une range n'est jamais réinventée, elle glisse.

---

## ⚔️ Attaque — Table Passive
**Idée : on limp énormément, on n'open presque rien, et l'open grossit d'un cran par position.**

- **UTG n'open que 10 mains (~4 %)** : TT+, AK, AQs-AJs, KQs. Tout le reste limp ou fold.
- Paires 99-22 : limp/call partout (99-88 passent à l'open dès MP).
- **L'escalier des promotions** (ce qui devient open à chaque cran) :
  - UTG1 : `AQo`
  - UTG2 : `ATs KJs`
  - MP : `KTs QJs AJo KQo` (+ 99-88 → open/call)
  - **HJ : le tournant 🎯** — tous les limp/fold deviennent *« open OU limp »* (le vol s'active)
  - CO : `77-66, K9s QTs ATo KJo QJo` sortent des splits en open pur
  - BTN : `A9s-A2s` opens (les petits as [6BB]), et **QQ rejoint le 4bet/call** (QQ+ au lieu de KK+)

## 🔥 Attaque — Table Aggro
**Idée : UTG→MP on n'open JAMAIS — on tend des pièges. Dès HJ, jeu « normal » mais plus serré que vs passive.**

- UTG→MP : **les monstres limpent pour reraise** (JJ+, AQs, AK) ; TT + broadways assortis (AJs ATs, KQs KJs, QJs) = limp/call ; A5s-A2s = limp/call-ou-reraise.
- Range early minuscule (17-26 mains) : *vs table aggro, serre-toi et laisse-les s'entretuer.*
- **HJ : la bascule** — open classique ; QQ-TT AK = open/call + 4bet/call [6BB] ; **A5s-A4s = le 4bet-bluff attitré**.
- CO/BTN : élargissement rapide (K5s+/Q8s+ au CO) ; paires moyennes en open/call (88-55 au CO, 77-33 au BTN).

## 🛡️ Défense (position libre · SB · BB)
**Idée : le % du relanceur dicte tout ; le sizing 3bb/6bb règle les calls spéculatifs ; le triangle = optionnel.**

- **vs 10 %** : le noyau = QQ+/AK (KK+ AKs all-in), AQs/KQs en call, + set-mine optionnel des paires vs 3bb. C'est tout.
- **vs 20 %** : un cran de plus — JJ/TT, AJs/KJs/QJs en call ; **QQ et AQs montent en raise/call 4bet**.
- **vs 40 %** : large et agressif — QQ+/AK all-in ; presque toutes les mains jouables prennent un côté **raise/fold 4bet** (relance, jette si 4bet).
- **3bb → 6bb** : coupe les mains marginales… *sauf vs 40 % en position libre : la range reste identique.* En blinds vs 6bb d'un 40 % : **JJ-88 = all-in-ou-fold**.
- **La BB défend ~2× plus large que la SB** (tu closes avec la cote) : vs 3bb, la BB call *toutes* les paires et *tous* les suited connectors, même contre un 10 %.

## 🕶️ RFI en Blinds (SB & BB)
**Idée : une seule range de « vraies mains » pour les deux blinds — seul le sizing change.**

- Raise : **99+, ATs+, KJs+, QJs, AQo+** (KTs JTs, AJo-ATo, KQo en raise/fold) ; QQ+ = 4bet/call ; A5s-A2s = limp/call.
- Depuis **SB : sizing [6BB]** ; depuis BB : sizing normal.
- Tout le reste : limp/fold (la BB complète avec l'intégralité des poubelles).

---

## 🎯 Méthode (30 s)
1. Lis la section d'une catégorie. 2. Drill **« Catégorie — positions mélangées »** dessus. 3. Termine par « Tout mélangé ». 4. Ne reviens ici que pour les lignes qui t'ont piégé.
