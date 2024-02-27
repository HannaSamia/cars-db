# Cars Database

## About

This repository contains a comprehensive database of vehicles, organized into four main categories: bikes, buses, cars, and trucks. The data have been meticulously collected from various sources and are freely available for use.

## Contents

- `bikes.json`: Contains detailed information about various bike models.
- `buses.json`: Includes data on a wide range of buses.
- `cars.json`: A detailed database of car models, including specifications and features.
- `trucks.json`: Data on truck models, including heavy and light trucks.

## Data Format

Each JSON file in this repository follows a structured format, providing detailed information about each vehicle model. Here is a general structure of the data you can expect:

### bikes: 
```json
  "RECORDS": [
    {
      "id": 1,
      "make": "acabion",
      "model": "da vinci 650-vi",
      "year": "2011",
      "category": "Prototype / concept model",
      "displacement": null,
      "Power": "804"
    }
]
```

### buses:

```json
  "RECORDS": [
    {
      "id": 1,
      "model": "021",
      "type": "Single deck",
      "make": "Jelcz",
      "year": "1967 to 1979",
      "nationality": "Poland"
    }
]
```

### cars:

```json
  "RECORDS": [
    {
      "year": "2004",
      "manufacturer": "Alfa Romeo",
      "model": "156",
      "id": "126",
      "label": "2.0 I4 FWD",
      "trim_level": "2.0 I4 FWD",
      "car_type": "Sedan"
    }
]
```

### trucks:

```json
  "RECORDS": [
    {
      "id": 1,
      "make": "American LaFrance",
      "model": "American Lafrance Condor",
      "class": "Medium",
      "cabin": "COE",
      "nationality": "United States"
    }
]
```

### vehicles

```csv
"make","model","cylinders","displ","drive","fueltype","fueltype1","id","trany","vclass","year","atvtype","evmotor","createdon","modifiedon","basemodel","bodyType","driveType","nationality"
"Chevrolet","S10 Pickup 2WD","4","2.2","2-Wheel Drive","Diesel","Diesel","28228","Manual 4-spd","Small Pickup Trucks 2WD","1984","Diesel",,"2013-01-01","2013-01-01","S10
```

