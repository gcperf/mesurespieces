<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <title>Calcul surface thermolaquage (tubes, limons, pièces soudées)</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    body {
      margin: 0;
      padding: 16px;
      background: #0b0b0f;
      color: #f5f5f5;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    }

    h1 {
      text-align: center;
      font-size: 1.4rem;
      margin-bottom: 10px;
    }

    .app {
      max-width: 900px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .tabs {
      display: flex;
      gap: 8px;
      margin-bottom: 4px;
    }

    .tab-btn {
      flex: 1;
      padding: 8px;
      border-radius: 999px;
      border: 1px solid #333;
      background: #15151c;
      color: #f5f5f5;
      font-size: 0.9rem;
      cursor: pointer;
    }

    .tab-btn.active {
      background: linear-gradient(135deg, #04c8ff, #00ff9c);
      color: #000;
      border-color: transparent;
      font-weight: 600;
    }

    .card {
      background: #14141b;
      border-radius: 12px;
      border: 1px solid #262636;
      padding: 12px;
    }

    label {
      font-size: 0.85rem;
      display: block;
      margin-bottom: 4px;
    }

    input, select {
      width: 100%;
      padding: 7px 9px;
      border-radius: 8px;
      border: 1px solid #3a3a4a;
      background: #0b0b11;
      color: #f5f5f5;
      box-sizing: border-box;
      margin-bottom: 8px;
      font-size: 0.9rem;
    }

    input:focus, select:focus {
      outline: none;
      border-color: #04c8ff;
    }

    .row {
      display: flex;
      gap: 8px;
      flex-wrap: wrap;
    }

    .row > div {
      flex: 1;
      min-width: 140px;
    }

    button.calc {
      width: 100%;
      padding: 9px;
      border-radius: 999px;
      border: none;
      background: linear-gradient(135deg, #04c8ff, #00ff9c);
      color: #000;
      font-weight: 600;
      cursor: pointer;
      margin-top: 4px;
    }

    button.calc:active {
      transform: scale(0.97);
    }

    .result {
      margin-top: 8px;
      padding: 8px;
      border-radius: 10px;
      border: 1px solid #333;
      background: #0d0d14;
      font-size: 0.9rem;
    }

    .small {
      font-size: 0.78rem;
      opacity: 0.8;
    }

    .badge {
      display: inline-block;
      padding: 2px 6px;
      border-radius: 999px;
      font-size: 0.7rem;
      background: #1e1e2a;
      border: 1px solid #3a3a4a;
      margin-left: 4px;
    }

    .section-title {
      font-size: 0.95rem;
      font-weight: 600;
      margin-bottom: 6px;
    }
  </style>
</head>
<body>
  <div class="app">
    <h1>Surface à thermolaquer – tubes, limons, pièces soudées</h1>

    <div class="tabs">
      <button class="tab-btn active" data-tab="simple">Forme simple</button>
      <button class="tab-btn" data-tab="limon">Limon / pièce soudée</button>
    </div>

    <!-- =========================
         ONGLET 1 : FORMES SIMPLES
         ========================= -->
    <div class="card tab-content" id="tab-simple">
      <div class="section-title">1. Forme simple</div>

      <label>Type de pièce</label>
      <select id="simpleType">
        <option value="plaque">Plaque / tôle</option>
        <option value="tubeRect">Tube carré / rectangulaire</option>
        <option value="tubeRond">Tube rond</option>
        <option value="corniereL">Cornière L</option>
        <option value="profilU">Profil U</option>
        <option value="plat">Plat (fer plat)</option>
        <option value="perimetreLibre">Profil spécial (périmètre connu)</option>
      </select>

      <!-- Bloc plaque -->
      <div id="blocSimple-plaque" class="blocSimple">
        <div class="row">
          <div>
            <label>Longueur (mm)</label>
            <input type="number" id="plaqueLongueur" placeholder="ex : 1200" />
          </div>
          <div>
            <label>Largeur (mm)</label>
            <input type="number" id="plaqueLargeur" placeholder="ex : 400" />
          </div>
        </div>
        <label>Faces à peindre</label>
        <select id="plaqueFaces">
          <option value="1">1 face</option>
          <option value="2">2 faces</option>
        </select>
      </div>

      <!-- Bloc tube rect -->
      <div id="blocSimple-tubeRect" class="blocSimple" style="display:none;">
        <div class="row">
          <div>
            <label>Largeur (mm)</label>
            <input type="number" id="tubeRectLargeur" placeholder="ex : 40" />
          </div>
          <div>
            <label>Hauteur (mm)</label>
            <input type="number" id="tubeRectHauteur" placeholder="ex : 40" />
          </div>
        </div>
        <label>Longueur du tube (mm)</label>
        <input type="number" id="tubeRectLongueur" placeholder="ex : 2000" />
        <p class="small">Surface extérieure : 2 × (L + H) × longueur.</p>
      </div>

      <!-- Bloc tube rond -->
      <div id="blocSimple-tubeRond" class="blocSimple" style="display:none;">
        <label>Diamètre extérieur (mm)</label>
        <input type="number" id="tubeRondDiametre" placeholder="ex : 60" />
        <label>Longueur du tube (mm)</label>
        <input type="number" id="tubeRondLongueur" placeholder="ex : 2000" />
        <p class="small">Surface extérieure : π × D × longueur.</p>
      </div>

      <!-- Bloc cornière L -->
      <div id="blocSimple-corniereL" class="blocSimple" style="display:none;">
        <div class="row">
          <div>
            <label>Aile 1 (mm)</label>
            <input type="number" id="corniereAile1" placeholder="ex : 40" />
          </div>
          <div>
            <label>Aile 2 (mm)</label>
            <input type="number" id="corniereAile2" placeholder="ex : 40" />
          </div>
        </div>
        <label>Épaisseur (mm)</label>
        <input type="number" id="corniereEpaisseur" placeholder="ex : 4" />
        <label>Longueur (mm)</label>
        <input type="number" id="corniereLongueur" placeholder="ex : 2000" />
        <p class="small">
          Approximatif : développé ≈ (aile1 + aile2 − épaisseur) × 2 (faces extérieures) × longueur.
        </p>
      </div>

      <!-- Bloc profil U -->
      <div id="blocSimple-profilU" class="blocSimple" style="display:none;">
        <div class="row">
          <div>
            <label>Largeur semelle (mm)</label>
            <input type="number" id="uSemelle" placeholder="ex : 80" />
          </div>
          <div>
            <label>Hauteur (mm)</label>
            <input type="number" id="uHauteur" placeholder="ex : 40" />
          </div>
        </div>
        <label>Épaisseur (mm)</label>
        <input type="number" id="uEpaisseur" placeholder="ex : 4" />
        <label>Longueur (mm)</label>
        <input type="number" id="uLongueur" placeholder="ex : 3000" />
        <p class="small">
          Approximatif : développé ≈ (semelle + 2 × hauteur) × 2 (faces extérieures) × longueur.
        </p>
      </div>

      <!-- Bloc plat -->
      <div id="blocSimple-plat" class="blocSimple" style="display:none;">
        <div class="row">
          <div>
            <label>Largeur du plat (mm)</label>
            <input type="number" id="platLargeur" placeholder="ex : 80" />
          </div>
          <div>
            <label>Épaisseur (mm)</label>
            <input type="number" id="platEpaisseur" placeholder="ex : 8" />
          </div>
        </div>
        <label>Longueur (mm)</label>
        <input type="number" id="platLongueur" placeholder="ex : 3000" />
        <p class="small">
          Surface ≈ 2 faces larges + 2 chants : 2×(largeur×longueur) + 2×(épaisseur×longueur).
        </p>
      </div>

      <!-- Bloc périmètre libre -->
      <div id="blocSimple-perimetreLibre" class="blocSimple" style="display:none;">
        <label>Périmètre développé extérieur (mm)</label>
        <input type="number" id="perimLibre" placeholder="ex : 300" />
        <label>Longueur du profil (mm)</label>
        <input type="number" id="perimLibreLongueur" placeholder="ex : 2000" />
        <p class="small">Pour profil spécial : développé × longueur.</p>
      </div>

      <div class="row">
        <div>
          <label>Quantité de pièces</label>
          <input type="number" id="simpleQuantite" value="1" min="1" />
        </div>
        <div>
          <label>Nom / référence (optionnel)</label>
          <input type="text" id="simpleRef" placeholder="ex : Garde-corps tube 40x40" />
        </div>
      </div>

      <button class="calc" id="btnCalcSimple">Calculer surface (forme simple)</button>
      <div class="result" id="resultSimple">
        Renseigne les dimensions puis clique sur “Calculer”.
      </div>
    </div>

    <!-- ================================
         ONGLET 2 : LIMON / PIÈCE SOUDÉE
         ================================ -->
    <div class="card tab-content" id="tab-limon" style="display:none;">
      <div class="section-title">2. Limon / pièce soudée avec supports de marche</div>

      <p class="small">
        Approximatif mais pratique pour devis : on calcule la surface du limon (profil continu) +
        la surface des supports de marche répétés sur toute la longueur.
      </p>

      <label>Type de limon (profil principal)</label>
      <select id="limonType">
        <option value="tubeRect">Tube carré / rectangulaire</option>
        <option value="tubeRond">Tube rond</option>
        <option value="plat">Plat</option>
        <option value="profilU">Profil U</option>
        <option value="perimetreLibre">Profil spécial (périmètre connu)</option>
      </select>

      <!-- Paramètres limon : on réutilise les mêmes logiques que formes simples -->

      <div id="blocLimon-tubeRect" class="blocLimon">
        <div class="row">
          <div>
            <label>Largeur tube (mm)</label>
            <input type="number" id="limonTubeRectLargeur" placeholder="ex : 120" />
          </div>
          <div>
            <label>Hauteur tube (mm)</label>
            <input type="number" id="limonTubeRectHauteur" placeholder="ex : 60" />
          </div>
        </div>
      </div>

      <div id="blocLimon-tubeRond" class="blocLimon" style="display:none;">
        <label>Diamètre tube (mm)</label>
        <input type="number" id="limonTubeRondDiametre" placeholder="ex : 80" />
      </div>

      <div id="blocLimon-plat" class="blocLimon" style="display:none;">
        <div class="row">
          <div>
            <label>Largeur plat (mm)</label>
            <input type="number" id="limonPlatLargeur" placeholder="ex : 200" />
          </div>
          <div>
            <label>Épaisseur (mm)</label>
            <input type="number" id="limonPlatEpaisseur" placeholder="ex : 10" />
          </div>
        </div>
      </div>

      <div id="blocLimon-profilU" class="blocLimon" style="display:none;">
        <div class="row">
          <div>
            <label>Largeur semelle U (mm)</label>
            <input type="number" id="limonUSemelle" placeholder="ex : 200" />
          </div>
          <div>
            <label>Hauteur U (mm)</label>
            <input type="number" id="limonUHauteur" placeholder="ex : 80" />
          </div>
        </div>
        <label>Épaisseur (mm)</label>
        <input type="number" id="limonUEpaisseur" placeholder="ex : 8" />
      </div>

      <div id="blocLimon-perimetreLibre" class="blocLimon" style="display:none;">
        <label>Périmètre développé du profil (mm)</label>
        <input type="number" id="limonPerimLibre" placeholder="ex : 450" />
      </div>

      <label>Longueur du limon / pièce (mm)</label>
      <input type="number" id="limonLongueur" placeholder="ex : 4000" />

      <!-- Supports de marche -->
      <div style="margin-top:8px;">
        <div class="section-title">
          Supports de marche
          <span class="badge">Optionnel, mais utile pour limons complets</span>
        </div>

        <p class="small">
          On approxime un support comme un “L” soudé : une partie verticale + une partie horizontale.
          On peint les 2 faces des plats.
        </p>

        <div class="row">
          <div>
            <label>Largeur support (mm)</label>
            <input type="number" id="supportLargeur" placeholder="ex : largeur limon ou marche, ex 200" />
          </div>
          <div>
            <label>Hauteur verticale (mm)</label>
            <input type="number" id="supportHauteur" placeholder="ex : 150" />
          </div>
        </div>

        <div class="row">
          <div>
            <label>Longueur horizontale (mm)</label>
            <input type="number" id="supportLongueur" placeholder="ex : 250" />
          </div>
          <div>
            <label>Épaisseur plat (mm)</label>
            <input type="number" id="supportEpaisseur" placeholder="ex : 8" />
          </div>
        </div>

        <div class="row">
          <div>
            <label>Nombre de marches / supports</label>
            <input type="number" id="supportNb" value="0" />
          </div>
          <div>
            <label>Quantité de limons identiques</label>
            <input type="number" id="limonQuantite" value="1" min="1" />
          </div>
        </div>
      </div>

      <button class="calc" id="btnCalcLimon">Calculer surface (limon + supports)</button>

      <div class="result" id="resultLimon">
        Renseigne les cotes du limon (et des supports si besoin), puis clique sur “Calculer”.
      </div>
    </div>
  </div>

  <script>
    // ===== Utilitaires =====
    function parseNumber(value) {
      if (!value && value !== 0) return 0;
      return parseFloat(String(value).replace(",", ".")) || 0;
    }

    function mmToM(mm) {
      return mm / 1000;
    }

    // ===== Onglets =====
    const tabButtons = document.querySelectorAll(".tab-btn");
    const tabContents = document.querySelectorAll(".tab-content");

    tabButtons.forEach((btn) => {
      btn.addEventListener("click", () => {
        const tab = btn.dataset.tab;
        tabButtons.forEach((b) => b.classList.remove("active"));
        btn.classList.add("active");

        tabContents.forEach((c) => {
          c.style.display = c.id === "tab-" + tab ? "block" : "none";
        });
      });
    });

    // ===== FORMES SIMPLES =====
    const simpleTypeSelect = document.getElementById("simpleType");
    const blocSimpleList = document.querySelectorAll(".blocSimple");

    function showSimpleBloc() {
      const val = simpleTypeSelect.value;
      blocSimpleList.forEach((b) => (b.style.display = "none"));
      const bloc = document.getElementById("blocSimple-" + val);
      if (bloc) bloc.style.display = "block";
    }

    simpleTypeSelect.addEventListener("change", showSimpleBloc);
    showSimpleBloc();

    const resultSimple = document.getElementById("resultSimple");

    document.getElementById("btnCalcSimple").addEventListener("click", () => {
      const type = simpleTypeSelect.value;
      const quantite = parseNumber(document.getElementById("simpleQuantite").value) || 1;
      const ref = document.getElementById("simpleRef").value.trim();

      let surfaceParPiece_m2 = 0;
      let details = "";

      if (type === "plaque") {
        const L = mmToM(parseNumber(document.getElementById("plaqueLongueur").value));
        const l = mmToM(parseNumber(document.getElementById("plaqueLargeur").value));
        const faces = parseInt(document.getElementById("plaqueFaces").value, 10) || 1;
        surfaceParPiece_m2 = L * l * faces;
        details = `Plaque ${faces} face(s) – L=${L.toFixed(3)} m, l=${l.toFixed(3)} m.`;
      }

      if (type === "tubeRect") {
        const larg = mmToM(parseNumber(document.getElementById("tubeRectLargeur").value));
        const haut = mmToM(parseNumber(document.getElementById("tubeRectHauteur").value));
        const long = mmToM(parseNumber(document.getElementById("tubeRectLongueur").value));
        const perim = 2 * (larg + haut);
        surfaceParPiece_m2 = perim * long;
        details = `Tube rect : ${larg.toFixed(3)}×${haut.toFixed(3)} m, L=${long.toFixed(3)} m.`;
      }

      if (type === "tubeRond") {
        const d = mmToM(parseNumber(document.getElementById("tubeRondDiametre").value));
        const L = mmToM(parseNumber(document.getElementById("tubeRondLongueur").value));
        surfaceParPiece_m2 = Math.PI * d * L;
        details = `Tube rond D=${d.toFixed(3)} m, L=${L.toFixed(3)} m.`;
      }

      if (type === "corniereL") {
        const a1 = mmToM(parseNumber(document.getElementById("corniereAile1").value));
        const a2 = mmToM(parseNumber(document.getElementById("corniereAile2").value));
        const e = mmToM(parseNumber(document.getElementById("corniereEpaisseur").value));
        const L = mmToM(parseNumber(document.getElementById("corniereLongueur").value));

        const dev_approx = (a1 + a2 - e) * 2; // 2 faces principales
        surfaceParPiece_m2 = dev_approx * L;
        details = `Cornière L ~ ailes ${a1.toFixed(3)} / ${a2.toFixed(3)} m, ép=${e.toFixed(3)} m, L=${L.toFixed(3)} m.`;
      }

      if (type === "profilU") {
        const sem = mmToM(parseNumber(document.getElementById("uSemelle").value));
        const h = mmToM(parseNumber(document.getElementById("uHauteur").value));
        const e = mmToM(parseNumber(document.getElementById("uEpaisseur").value));
        const L = mmToM(parseNumber(document.getElementById("uLongueur").value));

        const contour = sem + 2 * h; // section ouverte
        const dev_approx = contour * 2; // 2 faces
        surfaceParPiece_m2 = dev_approx * L;
        details = `Profil U ~ semelle=${sem.toFixed(3)} m, h=${h.toFixed(3)} m, L=${L.toFixed(3)} m.`;
      }

      if (type === "plat") {
        const larg = mmToM(parseNumber(document.getElementById("platLargeur").value));
        const e = mmToM(parseNumber(document.getElementById("platEpaisseur").value));
        const L = mmToM(parseNumber(document.getElementById("platLongueur").value));

        const surfFaces = 2 * (larg * L);
        const surfChants = 2 * (e * L);
        surfaceParPiece_m2 = surfFaces + surfChants;
        details = `Plat larg=${larg.toFixed(3)} m, ép=${e.toFixed(3)} m, L=${L.toFixed(3)} m.`;
      }

      if (type === "perimetreLibre") {
        const perim = mmToM(parseNumber(document.getElementById("perimLibre").value));
        const L = mmToM(parseNumber(document.getElementById("perimLibreLongueur").value));
        surfaceParPiece_m2 = perim * L;
        details = `Profil spécial périmètre=${perim.toFixed(3)} m, L=${L.toFixed(3)} m.`;
      }

      if (!surfaceParPiece_m2 || surfaceParPiece_m2 <= 0) {
        resultSimple.innerHTML = "⚠️ Vérifie les dimensions, impossible de calculer la surface.";
        return;
      }

      const total_m2 = surfaceParPiece_m2 * quantite;
      const refLine = ref ? `Pièce : <strong>${ref}</strong><br>` : "";

      resultSimple.innerHTML = `
        ${refLine}
        ${details}<br><br>
        Surface par pièce : <strong>${surfaceParPiece_m2.toFixed(3)} m²</strong><br>
        Quantité : <strong>${quantite}</strong><br>
        Surface totale : <strong>${total_m2.toFixed(3)} m²</strong>
      `;
    });

    // ===== LIMON / PIÈCE SOUDÉE =====
    const limonTypeSelect = document.getElementById("limonType");
    const blocLimonList = document.querySelectorAll(".blocLimon");
    const resultLimon = document.getElementById("resultLimon");

    function showLimonBloc() {
      const val = limonTypeSelect.value;
      blocLimonList.forEach((b) => (b.style.display = "none"));
      const bloc = document.getElementById("blocLimon-" + val);
      if (bloc) bloc.style.display = "block";
    }

    limonTypeSelect.addEventListener("change", showLimonBloc);
    showLimonBloc();

    document.getElementById("btnCalcLimon").addEventListener("click", () => {
      const type = limonTypeSelect.value;

      const L_mm = parseNumber(document.getElementById("limonLongueur").value);
      const L_m = mmToM(L_mm);
      const nbLimon = parseNumber(document.getElementById("limonQuantite").value) || 1;

      if (L_m <= 0) {
        resultLimon.innerHTML = "⚠️ Indique la longueur du limon / profil (mm).";
        return;
      }

      // --- Surface limon ---
      let surfLimon_m2 = 0;
      let descLimon = "";

      if (type === "tubeRect") {
        const larg = mmToM(parseNumber(document.getElementById("limonTubeRectLargeur").value));
        const haut = mmToM(parseNumber(document.getElementById("limonTubeRectHauteur").value));
        const perim = 2 * (larg + haut);
        surfLimon_m2 = perim * L_m;
        descLimon = `Limon tube rect ~ ${larg.toFixed(3)}×${haut.toFixed(3)} m, L=${L_m.toFixed(3)} m.`;
      }

      if (type === "tubeRond") {
        const d = mmToM(parseNumber(document.getElementById("limonTubeRondDiametre").value));
        surfLimon_m2 = Math.PI * d * L_m;
        descLimon = `Limon tube rond D=${d.toFixed(3)} m, L=${L_m.toFixed(3)} m.`;
      }

      if (type === "plat") {
        const larg = mmToM(parseNumber(document.getElementById("limonPlatLargeur").value));
        const e = mmToM(parseNumber(document.getElementById("limonPlatEpaisseur").value));
        const surfFaces = 2 * (larg * L_m);
        const surfChants = 2 * (e * L_m);
        surfLimon_m2 = surfFaces + surfChants;
        descLimon = `Limon plat larg=${larg.toFixed(3)} m, ép=${e.toFixed(3)} m, L=${L_m.toFixed(3)} m.`;
      }

      if (type === "profilU") {
        const sem = mmToM(parseNumber(document.getElementById("limonUSemelle").value));
        const h = mmToM(parseNumber(document.getElementById("limonUHauteur").value));
        const e = mmToM(parseNumber(document.getElementById("limonUEpaisseur").value));
        const contour = sem + 2 * h;
        const dev_approx = contour * 2; // 2 faces
        surfLimon_m2 = dev_approx * L_m;
        descLimon = `Limon U ~ semelle=${sem.toFixed(3)} m, h=${h.toFixed(3)} m, L=${L_m.toFixed(3)} m.`;
      }

      if (type === "perimetreLibre") {
        const perim = mmToM(parseNumber(document.getElementById("limonPerimLibre").value));
        surfLimon_m2 = perim * L_m;
        descLimon = `Limon profil spécial périmètre=${perim.toFixed(3)} m, L=${L_m.toFixed(3)} m.`;
      }

      if (!surfLimon_m2 || surfLimon_m2 <= 0) {
        resultLimon.innerHTML = "⚠️ Vérifie les dimensions du limon (profil).";
        return;
      }

      // --- Supports de marche ---
      const supportLargeur_m = mmToM(parseNumber(document.getElementById("supportLargeur").value));
      const supportHauteur_m = mmToM(parseNumber(document.getElementById("supportHauteur").value));
      const supportLongueur_m = mmToM(parseNumber(document.getElementById("supportLongueur").value));
      const supportEpaisseur_m = mmToM(parseNumber(document.getElementById("supportEpaisseur").value));
      const supportNb = parseNumber(document.getElementById("supportNb").value) || 0;

      let surfUnSupport_m2 = 0;
      let descSupport = "";

      if (supportNb > 0 && supportLargeur_m > 0 && (supportHauteur_m > 0 || supportLongueur_m > 0)) {
        // On approxime un support comme 2 plats formant un L :
        // - plat vertical : 2 faces (largeur × hauteur) + chants
        // - plat horizontal : 2 faces (largeur × longueur) + chants
        const surfVertFaces = 2 * (supportLargeur_m * supportHauteur_m);
        const surfHorizFaces = 2 * (supportLargeur_m * supportLongueur_m);
        const surfVertChants = 2 * (supportEpaisseur_m * supportHauteur_m);
        const surfHorizChants = 2 * (supportEpaisseur_m * supportLongueur_m);

        surfUnSupport_m2 = surfVertFaces + surfHorizFaces + surfVertChants + surfHorizChants;
        descSupport = `Support ~ larg=${supportLargeur_m.toFixed(3)} m, h=${supportHauteur_m.toFixed(3)} m, L=${supportLongueur_m.toFixed(3)} m.`;
      }

      const surfSupportsUnLimon_m2 = surfUnSupport_m2 * supportNb;
      const surfTotalUnLimon_m2 = surfLimon_m2 + surfSupportsUnLimon_m2;

      const surfTotalTousLimons_m2 = surfTotalUnLimon_m2 * nbLimon;

      let html = "";
      html += `<strong>Limon (1 pièce) :</strong><br>`;
      html += `${descLimon}<br>`;
      html += `Surface limon seul : <strong>${surfLimon_m2.toFixed(3)} m²</strong><br><br>`;

      if (supportNb > 0 && surfUnSupport_m2 > 0) {
        html += `<strong>Supports de marche :</strong><br>`;
        html += `${descSupport}<br>`;
        html += `Surface 1 support : ~${surfUnSupport_m2.toFixed(3)} m²<br>`;
        html += `Nombre de supports : ${supportNb}<br>`;
        html += `Surface supports / limon : <strong>${surfSupportsUnLimon_m2.toFixed(3)} m²</strong><br><br>`;
      } else {
        html += `<em>Aucun support de marche pris en compte (0 ou dimensions manquantes).</em><br><br>`;
      }

      html += `<strong>Surface totale pour 1 limon :</strong> ${surfTotalUnLimon_m2.toFixed(3)} m²<br>`;
      html += `Quantité de limons identiques : ${nbLimon}<br>`;
      html += `<strong>Surface totale (tous limons) :</strong> ${surfTotalTousLimons_m2.toFixed(3)} m²`;

      resultLimon.innerHTML = html;
    });
  </script>
</body>
</html>
