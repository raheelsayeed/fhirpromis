ProcedureRequest • PRMIS Instruments
------------------------------------


### ProcedureRequest.category

```json
 "category": [
    {
      "coding": [
        {
          "system": "http://snomed.info/sct",
          "code": "386053000",
          "display": "Evaluation procedure (procedure)"
        }
      ],
      "text": "Evaluation"
    }
```


### ProcedureRequest.code

Notes

1. For reuse and standardization purposes, adherence to LOINC system is required. 
2. Most PROMIS instruments are not fully LOINC-ed


```json
    "coding": [
      {
        "system": "http://loinc.org",
        "code": "61952-8",
        "display": "PROMIS Bank v1.0 - Depression"
      }
   ]
```
### ProcedureRequest Timing/Occurance

#### Instant

```json
  "occurrenceDateTime": "2018-05-22T17:34:25"
```


#### Planned, Scheduled / Regular Frequency

_do instrument every once every week starting {start} till {end}_

- Can set to weekly/monthly/daily/yearly

```json
 "occurrenceTiming": {
    "event": [
      "2018-05-22T17:34:24"
    ],
    "repeat": {
      "boundsPeriod": {
        "start": "2018-04-10",
        "end": "2018-06-28"
      },
      "frequency": 1,
      "period": 1.0,
      "periodUnit": "wk"
    }
  }
```

 
