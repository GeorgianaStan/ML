# Proiectul #1: Antrenează și compară algoritmi clasici de ML

Alegeți un set de date, antrenați cel puțin 2 modele de ML și arătați, cu cifre, care merge mai bine și de ce. Puteți coda cu agenți AI, dar nota se dă pe ce înțelegeți și puteți explica.

## Calendar

| Etapă | Dată |
|---|---|
| Primiți tema | Sep 26, 2026 |
| Urcați proiectul pe GitHub | Oct 10, 2026 |
| Primiți feedback și eventuale corecturi | până pe Oct 17, 2026 |
| Prezentare (max. 5 minute) | Oct 19, 2026 |

## Setul de date

**Setul dat:** Telco Customer Churn (Kaggle). Preziceți dacă un client părăsește operatorul de telefonie: 7.043 de clienți, din care ~26% pleacă.

**Sau vă alegeți voi setul:** tabelar (CSV), cu o coloană clară de prezis, între ~1.000 și ~100.000 de rânduri, dintr-o sursă publică. Nu Titanic, Iris sau Mall Customers.

Recomandări:

| Set de date | Tip | Ce preziceți |
|---|---|---|
| Medical Cost Personal (`insurance.csv`, Kaggle) | Regresie | Costul asigurării medicale |
| Pima Indians Diabetes (Kaggle) | Clasificare | Dacă pacientul are diabet |
| Wine Quality (UCI) | Regresie sau clasificare | Nota de calitate a vinului |
| California Housing (`sklearn`) | Regresie | Prețul mediu al caselor dintr-o zonă |
| Adult Income (UCI) | Clasificare | Dacă venitul trece de 50K pe an |

**Setul ales și ce prezic:**

## Ce aveți de făcut

Fiecare pas are o întrebare. Răspunsurile le scrieți în README, cu cuvintele voastre, fără AI.

### 1. Explorați datele
Dimensiune, valori lipsă, distribuția coloanei de prezis, 3 grafice cu câte o propoziție despre ce se vede.

> **Întrebare:** E clasificare sau regresie? Ce greșeală a modelului ar costa mai mult în realitate?

**Răspuns:**

### 2. Pregătiți datele
Împărțire train/test, valori lipsă, coloane text transformate în numere, scalare dacă e nevoie.

> **Întrebare:** De ce împărțim datele înainte de scalare?

**Răspuns:**

### 3. Baseline
`DummyClassifier` sau `DummyRegressor`.

> **Întrebare:** Ce scor are un model care nu știe nimic?

**Răspuns:**

### 4. Antrenați cel puțin 2 modele
Din cele făcute la curs: regresie liniară sau logistică, arbore de decizie, Random Forest, XGBoost, SVM.

> **Întrebare:** Care a ieșit mai bine și de ce credeți că s-a întâmplat asta?

**Răspuns:**

### 5. Evaluați pe setul de test
La clasificare: matrice de confuzie, precision, recall, F1. La regresie: MAE, RMSE, R².

> **Întrebare:** De ce ați ales metrica principală pe care ați ales-o?

**Răspuns:**

### 6. Concluzie
Ce model recomandați, cât de mult bate baseline-ul și o limitare a analizei.

**Răspuns:**

---

Deasupra fiecărei celule de cod importante puneți o celulă text scrisă de voi: ce faceți și de ce, în 1-2 propoziții.

**Opțional, pentru bonus:** mai mult de 2 modele, `GridSearchCV`, importanța coloanelor (feature importance), clustering cu k-Means.

## Lucrul cu AI

- Cereți agentului un pas pe rând, nu tot proiectul odată.
- Cereți-i să vă explice codul, nu doar să-l scrie.
- Nu păstrați cod pe care nu-l puteți explica.

În README scrieți și 3 rânduri: ce ați cerut agentului, ce ați schimbat din ce v-a dat și o greșeală de-a lui pe care ați prins-o.

**Ce am cerut agentului:**

**Ce am schimbat din ce mi-a dat:**

**O greșeală de-a lui pe care am prins-o:**

## Cum puneți proiectul pe GitHub

Dacă știți deja git, puteți face commit și push direct. Dacă nu l-ați mai folosit, varianta ușoară e să lucrați în Colab și să urcați fișierele prin upload:

1. Intrați pe github.com → **Sign up**. Completați e-mailul, o parolă și un username, apoi confirmați contul cu codul primit pe e-mail.
2. După logare, apăsați **+** (dreapta sus) → **New repository**. Nume: `proiect-1-ml`, lăsați-l **Public**, bifați **Add a README file**, apoi **Create repository**.
3. În Colab: **File → Download → Download .ipynb**.
4. În repository: **Add file → Upload files**, trageți fișierul `.ipynb` (și CSV-ul, dacă are sub 25 MB), apoi **Commit changes**.
5. Deschideți `README.md` → iconița creion (**Edit**) → scrieți README-ul → **Commit changes**.
6. Copiați linkul repository-ului din bara browserului și trimiteți-l.

Dacă modificați notebook-ul după upload, repetați pașii 3-4; fișierul vechi se înlocuiește.

## Predare și notare

Până pe **Oct 10, 2026** trimiteți linkul repository-ului GitHub, care conține:

- notebook-ul (`.ipynb`), care rulează de sus până jos;
- `README.md`, de maximum o pagină: setul de date ales și ce preziceți, răspunsurile scurte la cele 6 întrebări, modelul recomandat și cele 3 rânduri despre AI.

Până pe **Oct 17, 2026** primiți feedback și, dacă e cazul, corecturi de făcut; le urcați în același repository înainte de prezentare. Pe **Oct 19, 2026** prezentați proiectul în maximum 5 minute și răspundeți la 2-3 întrebări despre codul vostru.

| Criteriu | Puncte |
|---|---|
| Explorare și pregătirea datelor (pașii 1-2) | 20 |
| Baseline și cele 2 modele (pașii 3-4) | 20 |
| Evaluare și concluzie (pașii 5-6) | 20 |
| README: răspunsurile la întrebări și nota despre AI | 20 |
| Prezentarea și întrebările | 20 |
| **Total** | **100** |

Nota = punctajul / 10. Bonusul poate aduce până la 10 puncte în plus, fără a depăși 100. Dacă notebook-ul nu rulează, pierdeți 10 puncte.
