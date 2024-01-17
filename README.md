# Trashidermy

![my alt text](assets/raccoon-icon.jpg)

Raccoon customization for the new generation. We are here to bring your taxidermy game to the next level. Additionally has functionality to track raccoon visits to trashcans in your neighborhood.

## Installation

### Prerequisites

In order to install this project you must install `trash.io` and `bandit` in your local environment.

[trash.io](www.trashytrash.com)

[bandit](www.stealingurtrash.com)

### Server

In order to begin run `pipenv install` followed by `pipenv shell` and `cd server`.

Add the following code to the `app.py` file:

```shell
app.config['api_key'] = os.environ.get('API_KEY')
```

### Client

Run the following commands in your terminal:

```shell
npm install --prefix client
npm start --prefix client
```

## Dependencies

```
opposable-thumbs >= 1.0.0
bandit >= 2.3.4
trash.io ~> 2.0.0
```

## Contributing

Reach out to me at [@brewchetta](https://github.com/brewchetta) or make a pull request to be reviewed. Give me money.

## LICENSE

This project uses the [MIT license](LICENSE).