# JUDICIAL DECISION SUPPORT AND CASE TRAIGE SYSTEM

## GOAL 

1) ASSIST COURTS IN PRIORTIZING CASES AND PREDICITNG DELAYES TO REDUCE BACKLOGS,UNDERTRIAL DETENTION,ADMIN OVERLOAD 

## WHY ??


## ARCHITECTURE 

JDSTS/
│
├── data/
│   ├── raw_pdfs/
│   ├── extracted_text/
│   └── cases.csv
│
├── notebooks/
│   └── colab_pipeline.ipynb
│
├── backend/
│   ├── main.py
│   ├── models.py
│   └── routes.py
│
├── ml/
│   ├── priority_model.py
│   ├── delay_model.py
│   └── embeddings.py
│
├── agent/
│   └── agent.py
│
├── utils/
│   ├── pdf.py
│   └── features.py
│
└── README.md
