# Webová aplikace pro hodnocení školních obědů

Vítejte v našem projektu, jehož cílem je **vytvořit moderní aplikaci pro hodnocení školních obědů**, která umožní studentům i zaměstnancům školy rychle a jednoduše sdělit zpětnou vazbu na kvalitu a podobu nabízených jídel.

---

## 🏆 **Cíle projektu**
1. **Umožnit přihlášení přes Office 365** (jen pro strávníky dané školy).  
2. **Zobrazit automaticky načítaný jídelníček** (např. z webu / API / CSV).  
3. **Nabídnout formulář pro hodnocení** jídla (3–5 otázek).  
4. **Zabránit opakovanému hodnocení** téhož oběda jedním uživatelem.  
5. **Umožnit zobrazení výsledků** (statistiky, průměrná hodnocení).  

---

## 🧩 **Role v projektu (SCRUM tým)**

- **Scrum Master (SM):** Matyáš Koppel  
  - Zajišťuje, aby tým měl vše potřebné k práci a odstraňuje překážky.  
  - Organizuje sprinty a dohlíží na správné používání Scrumu.  

- **Product Owner (PO):** Bruno Niubo  
  - Určuje priority, komunikuje se „zákazníkem“ (učitel WA) a se stakeholdery.  
  - Udržuje backlog a kontroluje, zda aplikace vyhovuje požadavkům.  

- **Vývojáři:**  
  - Vojtěch Mydlář  
  - Martin Rosič  
  - Ondřej Šprungl  
  - Implementace kódu, testování, nasazování a technické řešení.

---

## 🚀 **Technologie a architektura**
> Poznámka: Zde pak někdo přepište co budete používat

- **Front-end**: React / Angular / Vue (vyberte dle potřeby)  
- **Back-end**: Node.js / Express / ASP.NET / Django / …  
- **Databáze**: MySQL / PostgreSQL / MongoDB / …  
- **Autentifikace**: OAuth 2.0 / MS Graph (Office 365)  
- **Repozitář**: Git (GitHub / GitLab / Bitbucket)  
- **Správa úkolů**: Microsoft Planner / Trello / Asana  

---

## ⚙️ **Struktura projektu** (příklad)

├── frontend/ │ ├── public/ │ ├── src/ │ └── package.json ├── backend/ │ ├── src/ │ ├── tests/ │ └── package.json ├── docs/ │ └── UML_diagrams.md └── README.md

markdown
Copy
Edit

- **frontend/** – obsahuje klientskou část (UI)  
- **backend/** – obsahuje serverovou logiku (API) a případně připojení k DB  
- **docs/** – technická dokumentace (UML, příručky, specifikace)  
- **README.md** – tento soubor  

---

## 📝 **Funkce a backlog – hlavní User Stories**

1. **Autentifikace přes Office 365**  
   - Jako uživatel chci se přihlásit přes školní účet, abych mohl hodnotit obědy.

2. **Načtení a zobrazení jídelníčku**  
   - Jako uživatel chci vidět aktuální jídelníček, abych věděl, které jídlo mohu hodnotit.

3. **Formulář pro hodnocení**  
   - Jako uživatel chci vyplnit krátký dotazník, abych mohl poskytnout zpětnou vazbu na oběd.

4. **Zamezení opakovaného hodnocení**  
   - Jako uživatel mohu ohodnotit každý oběd jen jednou.

5. **Zobrazení výsledků**  
   - Jako vedení školy chci vidět statistiky hodnocení, abych mohl reagovat na kvalitu jídel.



---

## 📦 **Instalace a spuštění** 

### **1. Klonování repozitáře**
```bash
git clone https://github.com/vas-ucet/Skolni-Obedy.git
cd Skolni-Obedy
