
# Healthcare Dataset

Contains data of patient including name, insurance details, hospital details, billing amount, etc. Used for practice as required by many healthcare company like United Healthcare Grop, IQVIA and UKG.


## Deployment


Download healthcare_dataset.csv

```bash
  create database healthcare_database;
  use healthcare_database;
```
Import healhcare_dataset.csv file into MySQL through Import table wizard.

```bash
  desc healthcare;
```

Create Index on name and necessary colum as it contains thousands of rows.

```bash
  create index ind_name on healhcare(name);
```


## Authors

- [Kaggle](https://www.kaggle.com)

