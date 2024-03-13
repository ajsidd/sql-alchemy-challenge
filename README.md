# Climate App API

## Description

This repository contains code for a Flask-based API to analyze climate data from the Hawaii climate database. It includes functionality to retrieve precipitation data, station information, temperature observations, and temperature statistics within a specified date range.

## Prerequisites

- Python 3.x
- Flask
- SQLAlchemy
- Pandas
- Matplotlib

## Getting Started

1. Clone the repository to your local machine:

```
git clone https://github.com/ajsidd/sql-alchemy-challenge.git
```

2. Install the required dependencies:

```
pip install Flask SQLAlchemy pandas matplotlib
```

3. Run the Flask app:

```
python app.py
```

4. Access the API endpoints in your web browser or using a tool like Postman:

- Homepage: [http://localhost:5000/](http://localhost:5000/)
- Precipitation data: [http://localhost:5000/api/v1.0/precipitation](http://localhost:5000/api/v1.0/precipitation)
- Station information: [http://localhost:5000/api/v1.0/stations](http://localhost:5000/api/v1.0/stations)
- Temperature observations: [http://localhost:5000/api/v1.0/tobs](http://localhost:5000/api/v1.0/tobs)
- Temperature statistics (start date): [http://localhost:5000/api/v1.0/start_date](http://localhost:5000/api/v1.0/start_date)
- Temperature statistics (start and end dates): [http://localhost:5000/api/v1.0/start_date/end_date](http://localhost:5000/api/v1.0/start_date/end_date)

## Usage

- `/api/v1.0/precipitation`: Returns a JSON representation of precipitation data for the last year.
- `/api/v1.0/stations`: Returns a JSON list of weather stations.
- `/api/v1.0/tobs`: Returns a JSON list of temperature observations for the most active station for the last year.
- `/api/v1.0/start_date`: Returns JSON-formatted minimum, average, and maximum temperatures from a specified start date.
- `/api/v1.0/start_date/end_date`: Returns JSON-formatted minimum, average, and maximum temperatures between specified start and end dates.

## Contributing

Contributions to improve the functionality or documentation of this project are welcome. Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The data used in this project is provided by the Hawaii Climate Database.
- Thanks to the Flask and SQLAlchemy developers for their excellent libraries.
