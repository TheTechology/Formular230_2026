# Formular 230 ANAF – Generare PDF Local (2026)

Aplicație web pentru completarea și generarea **Formularului 230 ANAF** (redirecționarea a 3,5% din impozitul pe venit), dezvoltată pentru utilizare rapidă, sigură și fără transmiterea datelor către servere externe.

Proiect realizat de **programatori voluntari ai Asociației Grupul Verde**, din **Adjud, județul Vrancea**.

---

## 🎯 Scopul proiectului

Această aplicație permite contribuabililor să:

- completeze digital formularul 230;
- semneze olograf direct în browser;
- genereze și descarce formularul completat în format **PDF**;
- utilizeze aplicația **fără cont**, **fără stocare de date** și **fără transmitere online**.

Toate operațiunile se desfășoară **local, pe dispozitivul utilizatorului**.

---

## 🔐 Confidențialitate & securitate

- Datele introduse **NU sunt salvate**;
- Datele **NU sunt trimise** către servere externe;
- Generarea PDF-ului se face exclusiv în browser;
- Aplicația respectă principiile **privacy by design**.

---

## ⚙️ Tehnologii utilizate

- **HTML5**
- **CSS3**
- **Bootstrap 5** (UI & responsive design)
- **JavaScript (Vanilla)**
- **pdf-lib** – generare PDF
- **signature_pad** – captură semnătură olografă
- **fontkit** – integrare fonturi în PDF

---

## 📁 Structura proiectului

```text
/
├── index.html
├── README.md
├── css/
│   ├── bootstrap.min.css
│   └── main.css
├── js/
│   ├── bootstrap.bundle.min.js
│   ├── pdf-lib.min.js
│   ├── signature_pad.umd.js
│   ├── fontkit.umd.min.js
│   ├── download.min.js
│   ├── validate-forms.js
│   └── main.js

