# Keras Model As a Rest API using Flask

- A baseline Keras pretrained model to classify a dog's breed from an image. We will use flask framework to deploy this model as a Rest API.
- This project is for demonstrating how to use your model as Rest API.


### Read the actual blog for more details

```
https://blog.keras.io/
```

### Install dependencies & activate virtualenv

- Go to the project directory path (in my case it is  E:\ML\Keras-Model-as-Rest-API) in anaconda prompt and run below three commands-

```
pip install pipenv
pipenv install
pipenv shell
```

- In case of any module not found error run following command-

```
pip install <module name>
```

### Starting your Keras Rest API

```
python run_keras_server.py
```

### Consuming your Keras REST API

Open another anaconda prompt and run this command from the project directory:

```
python simple_request.py
```
