# ✈️ Aircraft Wildlife Strikes Analysis (1990–2015)

Projekt analize podataka o sudarima divljih životinja i zrakoplova između 1990. i 2015. godine.

## 📖 Opis projekta

Ovaj projekt bavi se analizom podataka o incidentima sudara divljih životinja sa zrakoplovima. Korišten je dataset koji sadrži evidenciju svih prijavljenih sudara između različitih vrsta životinja i zrakoplova u razdoblju od 1990. do 2015. godine.

Cilj projekta je:
- očistiti i pripremiti podatke za analizu,
- analizirati obrasce sudara,
- vizualizirati podatke,
- primijeniti metode grupiranja podataka,
- dobiti uvid u čimbenike koji utječu na učestalost sudara.

---

# 📊 Dataset

Korišteni dataset:
- **Aircraft Wildlife Strikes, 1990–2015**

Dataset je preuzet s Kaggle platforme:

:contentReference[oaicite:0]{index=0}

Dataset sadržava:
- 174 104 retka
- 66 atributa

Podaci uključuju:
- godinu incidenta,
- mjesec i dan,
- aerodrom,
- vrstu životinje,
- tip zrakoplova,
- podatke o šteti,
- podatke o letu i lokaciji.

---

# 🛠️ Korištene tehnologije i biblioteke

Projekt je izrađen u Pythonu koristeći Jupyter Notebook.

## Biblioteke
- pandas
- matplotlib
- seaborn
- scikit-learn
- scipy

---

# 🧹 Obrada i čišćenje podataka

Prije analize provedeno je čišćenje podataka kroz nekoliko koraka:

1. Uklanjanje stupaca s više od 50% NaN vrijednosti
2. Uklanjanje redaka koji imaju 4 ili više NaN vrijednosti
3. Popunjavanje nedostajućih vrijednosti prethodnim vrijednostima
4. Uklanjanje preostalih redaka s NaN vrijednostima

Cilj obrade bio je pripremiti kvalitetan i konzistentan skup podataka za daljnju analizu.

---

# 📈 Analiza podataka

Projekt uključuje različite vrste analize i vizualizacije podataka.

## Provedene analize

### 📅 Analiza po godinama
- usporedba broja sudara po godinama.

### 📆 Analiza po mjesecima
- prikaz sezonskih obrazaca sudara.

### 📍 Analiza po danima u tjednu
- usporedba učestalosti incidenata tijekom tjedna.

### 🛫 Aerodromi s najvećim brojem sudara
- identifikacija aerodroma s najviše prijavljenih incidenata.

### 🦅 Vrste životinja
- analiza životinja koje najčešće uzrokuju sudare.

### ✈️ Tipovi zrakoplova
- prikaz tipova zrakoplova uključenih u incidente.

---

# 🤖 Primjena strojnog učenja

U projektu su korištene metode grupiranja podataka:

## KMeans
Korišten za grupiranje podataka i prepoznavanje obrazaca među incidentima.

## DBSCAN
Korišten za detekciju gustoće i izdvajanje potencijalnih anomalija u podacima.

---

# 📂 Struktura projekta

```text
project/
│
├── Projekt_Tomislav_Juric.ipynb
└── README.md
```

---

# ▶️ Pokretanje projekta

## 1. Kloniranje repozitorija

```bash
git clone https://github.com/tomisljuric/REPOSITORY_NAME.git
```

---

## 2. Instalacija potrebnih biblioteka

```bash
pip install pandas matplotlib seaborn scikit-learn scipy
```

---

## 3. Pokretanje notebooka

Pokrenuti Jupyter Notebook:

```bash
jupyter notebook
```

Otvoriti datoteku:

```text
Projekt_Tomislav_Juric.ipynb
```

---

# 🎯 Cilj projekta

Glavni cilj projekta je:
- analiza stvarnih podataka,
- obrada i čišćenje podataka,
- vizualizacija podataka,
- primjena metoda strojnog učenja,
- stjecanje iskustva u analizi podataka i Data Science području.

---

# 📚 Područja obuhvaćena projektom

- Data Analysis
- Data Cleaning
- Data Visualization
- Machine Learning
- Clustering
- Exploratory Data Analysis (EDA)

---

# 👨‍💻 Autor

Projekt izradio:

**Tomislav Jurič**
