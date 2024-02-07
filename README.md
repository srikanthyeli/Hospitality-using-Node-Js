# HOSPITALITY Application

Given an `app.js` file and database file `hospitality.db` with a table `hospitality`.

Write APIs to perform operations on the table `hospitality`, with the following columns,

**Hospitality Table**

| Column      | Type |
| ----------- | ---- |
| city        | TEXT |
| netSales    | INT  |
| netExpanse  | INT  |
| dailyTarget | INT  |
| date        | DATE |

### Invalid scenarios for all APIs

### API 1

#### Path: `/city/`

#### Method: `GET`

- **Scenario 1**

  - **Sample API**
    ```
    /city/
    ```
  - **Description**:

    Returns a list of all hospitality whose status is success''

  - **Response**

        ```[

    {
    "city": "Agra",
    "netSaies": 31276,
    "netExpanse": 61178,
    "dailyTarget": 6994237,
    "date": "2024-02-05"
    },
    {
    "city": "Bangulore",
    "netSaies": 27500,
    "netExpanse": 50123,
    "dailyTarget": 5094237,
    "date": 2017
    },
    {
    "city": "Delhi",
    "netSaies": 41276,
    "netExpanse": 51178,
    "dailyTarget": 6995647,
    "date": "2024-02-05"
    },
    {
    "city": "Goa",
    "netSaies": 35500,
    "netExpanse": 55000,
    "dailyTarget": 6075000,
    "date": "2024-02-05"
    },
    {
    "city": "jaipur",
    "netSaies": 40000,
    "netExpanse": 65000,
    "dailyTarget": 4550000,
    "date": "2024-02-05"
    }
    ]

```


```
