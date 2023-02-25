# Data Preparation stage

-convert my data into train.tsv and test.tsv into 70:30 ratio

```
data.xml
    |-train.tsv
    |-test.tsv
```

- We are choosing only 3 tags in the xml data - 1. row Id, 2. title and body, 3. Tags (stackoverflow tags specific to python)

|tags|feature names|
|-|-|
|row Id|row ID|
|title and body|text|
|stackoverflow tags|Label - Python|