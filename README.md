# EduTechAutoGenFaq
NLP and topic depictions for forum data

# EduTechAutoGenFaq

NLP and topic depictions for forum data. This is done to improve the Piazza Forum by providing an autogenerated trending page and FAQ.
1. Reddit extractions : experiment.py to see how I extracted the reddit data files
2. Topics extractions : machine_learning.py to see how I extract the topic
3. Dash Visualization : dash_main.py to see how I visualize it in dash deployed locally

## Getting Started

Clone this repository to your local.g
Run the dash_main.py. This will run a Flask App Server (lazy loading) to your local
Go to the port specified (default is 8050)
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
See deployment for notes on how to deploy the project on a live system.

### Prerequisites

1. python 3
2. pandas
3. sklearn
4. dash


```
pip install pandas
```

### Installing

To get your application running, you will need to:
1. Clone this repository
2. Install relevant libraries (refer to prerequisites)
3. Run dash_main.py with python 3
4. Access the server (localhost:8050)

## Deployment

To deploy this, you might want to use heroku https://www.heroku.com/ as your deployment cloud server
## Built With

* [Dash](https://dash.plot.ly/) - The data visualization framework used
* [Flask](https://flask.pocoo.org/docs/1.0/) - The web library used
* [Pandas](https://pandas.pydata.org/) - Data structure and analysis tools used


## Authors

* **Vincent Tatan** - *Initial work* - [Vincent tatan](https://gist.github.com/VincentTatan)
* **Ranon Sim** - *Team mate * - [Ranon Sim](https://www.linkedin.com/in/ranon-sim/)


## License

This project is a project started by a programmer. Feel free to use, no licensing is invoked.

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc