# JPM Finance - Startup Profit Analyse (Dansk Version)

## Beskrivelse
Dette repository indeholder en komplet machine learning analyse af startup profit baseret på R&D-udgifter, markedsføringsudgifter og administrative omkostninger. Hele analysen er udført på dansk med danske forklaringer og sammenfatninger.

## Hovedresultater
- **Model Performance:** R² = 92,6% (meget høj nøjagtighed)
- **Vigtigste faktor:** R&D-investeringer giver 38 kr profit per investeret krone
- **Markedsføring:** Moderat positiv effekt - 3,2 kr profit per krone
- **Administrative omkostninger:** NEGATIV effekt - reducerer profit med 1,1 kr per krone

## Indhold
- `JPM_Finance_Startup_Linear_Regression.ipynb` - Komplet dansk analyse med lineær regression
- **Avancerede udvidelser implementeret:**
  - OneHotEncoder for State variable (geografisk analyse)
  - Ridge/Lasso Regularization sammenligning
  - Learning Curves for bias-variance analyse
  - Bootstrap Prediction Intervals for usikkerhedskvantificering

## Teknisk Stack
- **Python** - Hovedprogrammeringssprog
- **Scikit-learn** - Machine learning bibliotek
- **Pandas** - Data manipulation og analyse
- **Matplotlib** - Data visualisering
- **NumPy** - Numeriske beregninger
- **Jupyter Notebook** - Interaktivt analyse miljø

## Vigtigste Fund og Anbefalinger

### For Investorer:
- Prioriter startups med høje R&D-budgetter
- Vær forsigtig med virksomheder der bruger for meget på administration
- Geografisk placering (US states) har ingen betydning for profit

### For Startup-Grundlæggere:
- Maksimer R&D-investeringer (38x ROI)
- Hold administrative omkostninger minimale
- Marketing er vigtigt men sekundært til innovation

### Tekniske Erkendelser:
- Simple lineær regression er tilstrækkelig (komplekse modeller tilføjer ikke værdi)
- Prediction usikkerhed: ±9.000 kr per estimat
- Dataset på 50 samples er adequat for pålidelige resultater

## Model Begrænsninger
- Baseret på kun amerikanske startups
- Ignorerer kvalitative faktorer (team, marked, timing)
- Lineær antagelser kan være for simple for visse use cases

## Næste Skridt
1. Udvide datasæt med internationale startups
2. Inkludere kvalitative variabler
3. Test ikke-lineære modeller
4. Validere på tværs af forskellige sektorer

## Forfatter
**Jonas** - Data Science og Machine Learning Analyse

---
*Hele analysen er udført på dansk for at sikre klarhed og forståelighed for danske interessenter og samarbejdspartnere.*