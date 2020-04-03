<p align="center"><img src="https://image.flaticon.com/icons/png/512/139/139315.png" width="100"></p>

<p align="center">API Documentaion for COVID-19 in the Bicol Region</p>

## 🚀 Prerequisites

* Basic API knowledge 🤘

## ✨ Endpoints

1. Fetch all the cases in the Bicol region.

* `URL` - [https://ro5-covid-data.herokuapp.com/cases/](https://ro5-covid-data.herokuapp.com/cases/)
* `GET`
* `PARAM`
* `RESULT`

```json
[
  {
    "id": "1",
    "location": "Albay",
    "positive_case": "8",
    "negative_case": "23",
    "person_monitored": "38",
    "pending_result": "7"
  },
  ...
]
```

2. Fetch all the confirmed cases with patient details.

* `URL` - [https://ro5-covid-data.herokuapp.com/confirm/](https://ro5-covid-data.herokuapp.com/confirm/)
* `GET`
* `PARAM`
* `RESULT`

```json
[
  {
    "id": "1",
    "case_number": "1",
    "patient_number": "PH 766",
    "age": "52",
    "sex": "Male",
    "location": "Albay",
    "nationality": "Foreigner",
    "travel_history": "USA",
    "status": "Stable"
  },
  ...
]
```

3. Fetch the total cases in the Bicol region.

* `URL` - [https://ro5-covid-data.herokuapp.com/total/](https://ro5-covid-data.herokuapp.com/total/)
* `GET`
* `PARAM`
* `RESULT`

```json
[
  {
    "total_positive_case": "11",
    "total_person_monitored": "87"
  }
]
```

4. Fetch cases in the Bicol region by province.

* `URL` - [http://ro5-covid-data.herokuapp.com/location/?id=1](http://ro5-covid-data.herokuapp.com/location/?id=1)
* `GET`
* `PARAM` - /location/?{id}={1}
* `RESULT`

```json
[
  {
    "id": "1",
    "location": "Albay",
    "positive_case": "8",
    "negative_case": "23",
    "person_monitored": "38",
    "pending_result": "7"
  }
]
```

## 💻 Developer

Developed by Isaac [(facebook.com/isaacdarcilla)](https://web.facebook.com/isaacdarcilla)

## ✨ Support

Fork or star this repository for support.

## 🐞 Issues and Pull Requests

Not accepting any issues and pull requests. 

## 🚫 No Scammers
