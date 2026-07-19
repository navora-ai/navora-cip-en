# NAVORA CIP — Clinical Intelligence (Mockup)

Statischer Demo-Build der NAVORA CIP (Clinical Intelligence Platform) Oberfläche.

**Live:** https://navora-cip-en.vercel.app  
_Öffentlich per Link erreichbar (Vercel Authentication deaktiviert); per `noindex` + `robots.txt` von Suchmaschinen ausgeschlossen._

## Was das ist
Interaktives UI-Mockup zur Veranschaulichung der CIP-Ansichten (Case Command Center, Lab Intelligence, Multisystem Map, Timeline u. a.). Alle dargestellten Patientendaten sind **synthetisch** und dienen ausschließlich der Demonstration. Kein Diagnosesystem und keine medizinische Anwendung — „for clinical review" only.

## Technik
Statischer Vite-Build: `index.html` plus gehashte JS-/CSS-Assets im Repo-Root. Kein Build-Schritt nötig (Vercel-Preset „Other", Root `./`).

## Deployment
Über Vercel, git-verbunden mit diesem Repo. Jeder Push auf `main` löst automatisch ein neues Deployment aus.
