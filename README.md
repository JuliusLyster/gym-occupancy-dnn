# Eksamensprojekt: Forudsig travlhed i fitnesscenter

Jeg forudsiger, om et campus-fitnesscenter er roligt, moderat eller travlt ud fra tid, vejr og semester-info.

Jeg løser det med et Deep Neural Network (DNN) på tabeldata — samme type metode som churn-eksemplet i pensum, og relateret til people counting uden at bruge YOLO.

## Datasæt

Crowdedness at the Campus Gym:  
https://www.kaggle.com/datasets/nsrose7224/crowdedness-at-the-campus-gym

Jeg omsætter `number_people` til 3 klasser:

| Klasse | Betydning | Regel |
|---|---|---|
| 0 | Roligt | ≤ 20 |
| 1 | Moderat | 21–50 |
| 2 | Travlt | > 50 |

## Filstruktur

```
Machine Learning Eksamen/
├── README.md
├── AFLEVERING.md
├── DOKUMENTATION.md
├── data/data.csv
├── screenshots/
└── notebooks/gym_occupancy_dnn.ipynb
```

## Sådan kører jeg projektet

1. Jeg uploader `notebooks/gym_occupancy_dnn.ipynb` og `data/data.csv` til Google Colab
2. Jeg kører alle celler

## Aflevering

Jeg afleverer via Wiseflow.
