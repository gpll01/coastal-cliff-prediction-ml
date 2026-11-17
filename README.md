# Previsione della presenza di falesie costiere tramite Machine Learning

Il progetto è stato realizzato nell'ambito del corso universitario **Artificial Intelligence and Big Geo Data Management** e ha l'obiettivo di classificare le aree costiere del Cilento in base alla presenza o all'assenza di falesie, attraverso l'applicazione di algoritmi di Machine Learning a dati geospaziali.

L'attività combina analisi dei dati, modellazione predittiva e strumenti GIS, con l'obiettivo di individuare le caratteristiche del territorio maggiormente associate alla presenza di falesie.

## Obiettivi

- Analizzare le caratteristiche geomorfologiche e territoriali dell'area di studio.
- Individuare le variabili più rilevanti per la classificazione.
- Addestrare e confrontare diversi modelli di Machine Learning.
- Applicare il modello selezionato a un secondo dataset.
- Esportare i risultati per la successiva elaborazione e visualizzazione in ambiente GIS.

## Metodologia

Il progetto si è articolato in diverse fasi:

1. **Analisi e preparazione dei dati**: esplorazione del dataset e individuazione delle variabili utilizzate per la classificazione.
2. **Selezione delle feature**: utilizzo di variabili territoriali e geomorfologiche, tra cui elevazione del DTM, rugosità, pendenza, dissection, superficie, distanza e litologia.
3. **Addestramento dei modelli**: suddivisione dei dati in training set e test set (80% e 20%) e applicazione di due algoritmi:
   - Random Forest
   - Support Vector Machine (SVM)
4. **Valutazione delle prestazioni**: confronto dei modelli attraverso accuratezza, matrice di confusione, classification report e curva Precision-Recall.
5. **Predizione e integrazione GIS**: applicazione del modello selezionato a un secondo dataset, esportazione delle predizioni in formato CSV e successiva elaborazione dei risultati in QGIS.

## Risultati

Il confronto tra i due classificatori ha evidenziato prestazioni differenti:

| Modello | Accuratezza |
|---|---:|
| Random Forest | 97,58% |
| Support Vector Machine (SVM) | 88,58% |

Il modello Random Forest ha ottenuto le prestazioni migliori ed è stato quindi selezionato per la fase di predizione sul secondo dataset.

## Tecnologie e strumenti

- **Python** – sviluppo e implementazione dei modelli
- **Pandas** – gestione e manipolazione dei dati
- **Scikit-learn** – addestramento e valutazione dei classificatori
- **Matplotlib** – visualizzazione dei risultati
- **Joblib** – salvataggio e caricamento del modello
- **Google Colab** – ambiente di sviluppo
- **QGIS** – visualizzazione e analisi geospaziale dei risultati


## Contesto accademico

Progetto realizzato nell'ambito del corso di **Artificial Intelligence and Big Geo Data Management**, presso l'Università degli Studi di Napoli "L'Orientale".


