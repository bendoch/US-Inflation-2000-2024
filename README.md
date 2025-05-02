# 📊 Analisi dell’inflazione negli Stati Uniti (2000–2024)

Questo progetto nasce con l’obiettivo di esplorare e comprendere l’evoluzione dell’inflazione negli Stati Uniti d’America dal 2000 al 2024, estendendo poi l’analisi in chiave predittiva fino al 2030.

L’attenzione si concentra su tre aspetti fondamentali:

- 💵 Il potere d'acquisto del dollaro
- 📈 L'indice dei prezzi al consumo (CPI)
- 💰 I salari

Il report risultante è pensato per essere facilmente fruibile: offre una **panoramica iniziale sintetica**, ma anche la possibilità di **interagire con i dati**, consentendo agli utenti di concentrarsi sugli aspetti di maggiore interesse.

---

## 🔍 Fonti e strumenti utilizzati

I dati sono stati interamente reperiti dal sito ufficiale del [U.S. Bureau of Labor Statistics (BLS)](https://www.bls.gov/), e si presentavano già in una forma piuttosto strutturata.  
Per la fase di pulizia e trasformazione (ETL), è stato utilizzato **Power Query in Microsoft Excel**, uno strumento rapido ed efficace per preparare i dati in modo leggibile e coerente.

L’analisi predittiva è stata invece realizzata in **Python**, sfruttando un approccio riproducibile e trasparente attraverso un notebook interattivo.

Infine, per la parte visual è stato utilizzato **PowerBI**, con l'aggiunta di formule DAX spiegate nel file ETL.txt.

---

## 🗂️ Struttura della repository

La repository è suddivisa in tre sezioni principali:
Il main branch contenente il report e due cartelle:

├── data/ ← Dati grezzi <br>
│ ├── Sample_CSV__Consumer_Price_Inflation_001.csv ← Serie storica del CPI <br>
│ └── wages.url ← Link al file dei salari (Google Drive)<br>
│<br>
├── pipeline/ ← Processo ETL e codice analitico<br>
│ ├── ETL.txt ← Descrizione dei passaggi eseguiti in Power Query<br>
│ └── forecast.ipynb ← Analisi predittiva in Python<br>

---

## 🌐 Accesso al report

Il report completo è disponibile in due lingue:

- 🇮🇹 [Versione italiana](usa_infl_2000-2024_ita.pbix)
- 🇬🇧 [English version](usa_infl_2000-2024_eng.pbix)

Entrambe le versioni contengono spiegazioni dettagliate e riassuntive dei risultati, oltre a grafici e tabelle interpretative.

---

## ⚙️ Requisiti tecnici

Il notebook Python è stato sviluppato nell'ambiente JupyterLab e utilizza le seguenti librerie:

- `pandas`
- `prophet`
- `matplotlib`

Non è richiesto alcun setup complesso: il file `.ipynb` può essere eseguito anche in ambienti online come Google Colab.

---

## 📫 Contatti

Per suggerimenti, domande o contributi, è possibile aprire una **Issue** o un **Pull Request** direttamente su questa repository.

---


