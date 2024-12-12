# Intel·ligència Artificial en Informàtica - ASIX

> Aquest manual explora les aplicacions i impactes de la IA en el camp de l'anàlisi de dades dins l'àmbit d'ASIX, amb propostes per abordar els reptes ambientals.

---

## 📊 Anàlisi de dades

### 📌 Aplicacions de la IA

Les aplicacions més comunes de la IA en l'anàlisi de dades inclouen:

- **Predicció de tendències**: Anàlisi de grans volums de dades per predir comportaments futurs en mercats, usuaris o processos empresarials.
- **Processament de dades massives**: Processament automàtic de Big Data per identificar patrons i correlacions.
- **Visualització de dades**: Creació d'eines interactives que permeten una comprensió millorada de dades complexes.
- **Optimització d'algoritmes**: Desenvolupament d'algoritmes més eficients per a la classificació i la regressió.

#### Exemple de comanda per al processament de dades:
```python
import pandas as pd
# Càrrega del conjunt de dades
data = pd.read_csv('dataset.csv')
# Anàlisi de les estadístiques bàsiques
data.describe()
```

### 🏢 Impacte al sector

> La IA està transformant la manera com es processen i analitzen les dades, amb impactes significatius en diversos sectors.

- **Eficàcia millorada**: Reducció del temps necessari per analitzar dades complexes i extreure conclusions.
- **Noves oportunitats de negoci**: Les empreses poden identificar noves línies de productes o serveis gràcies a una comprensió més profunda dels patrons del mercat.
- **Desplaçament laboral**: Les tasques rutinàries d'anàlisi són automatitzades, creant una necessitat de *reskilling* per als treballadors.

### 🌍 Impacte ambiental

La IA té un impacte notable sobre el medi ambient, especialment en l'àmbit de l'anàlisi de dades:

1. **Consum energètic**: Els models d'aprenentatge profund utilitzats per processar grans volums de dades poden requerir grans quantitats d'energia.
2. **Generació de residus electrònics**: L'obsolescència de maquinari utilitzat per al càlcul massiu.
3. **Ús excessiu de recursos naturals**: Per fabricar maquinari especialitzat com les GPU.


### 💡 Propostes per minimitzar els impactes ambientals

Per reduir l'impacte ecològic, proposem:

- **Optimització energètica**: Desenvolupar models IA menys intensius en energia o que utilitzin hardware més eficient.
- **Reutilització de maquinari**: Promoure la reutilització i el reciclatge de components electrònics.
- **Fonts d'energia renovable**: Alimentar els centres de dades amb energia solar, eòlica o altres fonts sostenibles.
- **Reducció de complexitat en models**: Apostar per arquitectures de xarxes neuronals més simples i igualment efectives.

#### Exemple de model optimitzat:
```python
from sklearn.ensemble import RandomForestClassifier
# Creació d'un model amb paràmetres optimitzats
model = RandomForestClassifier(n_estimators=100, max_depth=5)
model.fit(X_train, y_train)
```
 ## IA: Google Cloud AI (Anàlisi de grans volums de dades).

- Google Cloud AI ofereix eines per analitzar i treure insights de grans volums de dades, incloent-hi models de machine learning preentrenats, eines per a la creació de models personalitzats i serveis per integrar AI directament a aplicacions empresarials.

- Link: [Google Cloud AI](https://cloud.google.com/ai/generative-ai#generative-ai-on-google-cloud)

 ## IA: Tableau Einstein Analytics (Anàlisi i visualització avançada).
 
- Tableau Einstein combina funcionalitats de visualització avançada amb eines d’AI predictiva per donar suport a la presa de decisions basades en dades. Les seves característiques inclouen la predicció de tendències i l’optimització de fluxos de treball empresarials mitjançant insights accionables i generats automàticament​.

- Link: [Tableau Einstein](https://www.tableau.com/)

