SKY SPLASH – GitHub-Pages-Paket (zum Teilen & Testen)
=====================================================

WICHTIG: Diese Dateien müssen DIREKT im Repo-Stamm liegen
(also NICHT in einem Unterordner). index.html muss ganz oben sein.

DATEIEN (alle in den Repo-Stamm legen):
  index.html, sw.js, manifest.webmanifest, netlify.toml,
  icon-192.png, icon-512.png, apple-touch-icon.png, favicon-32.png

-------------------------------------------------------------------
GITHUB PAGES – SCHRITT FÜR SCHRITT
-------------------------------------------------------------------
1. Lege ein PUBLIC Repository an (z.B. "sky-splash").
2. Lade ALLE oben genannten Dateien in den STAMM des Repos hoch
   (Add file -> Upload files -> die Dateien aus diesem ZIP, NICHT den Ordner).
   -> Danach muss "index.html" in der Dateiliste GANZ OBEN sichtbar sein.
3. Settings -> Pages:
      Source: "Deploy from a branch"
      Branch: main      Ordner: / (root)      -> Save
4. 1-2 Minuten warten. Oben erscheint:
      "Your site is live at https://DEINNAME.github.io/sky-splash/"
5. Diesen Link an Freunde schicken. Fertig.

ALS APP INSTALLIEREN (Freunde):
  Android/Chrome: Menü (⋮) -> "App installieren"
  iPhone/Safari:  Teilen -> "Zum Home-Bildschirm"

-------------------------------------------------------------------
NOCH EINFACHER: Netlify
-------------------------------------------------------------------
https://app.netlify.com/drop öffnen und diese Dateien (oder den
entpackten Ordner) hineinziehen -> sofort ein fertiger Link.

-------------------------------------------------------------------
HINWEISE
-------------------------------------------------------------------
- Für echten Release im Code  const UNLOCK_ALL = true;  auf  false  setzen.
- Bei Updates in sw.js  'skysplash-v1'  auf  'skysplash-v2'  erhöhen,
  damit Freunde die neue Version sehen (sonst lädt der Cache die alte).
