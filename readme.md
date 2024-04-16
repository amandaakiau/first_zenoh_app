# Primeiro Zenoh app

## Pré-requisitos:

- Python >= 3.7

- pip >= 19.3.1

- (Optional) A Python virtual environment (for instance virtualenv or miniconda)

- Rust and Cargo. If you already have the Rust toolchain installed, make sure it is up-to-date with 

```sh
$ rustup update
```

## Instalação (em ambiente virtual python)

```sh
$ python -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

## Execução 

Executar o subscriber.py e z_sensor.py ao mesmo tempo.

bash1
```sh
$ source venv/bin/activate
$ python3 z_subscriber.py
```

bash2
```sh
$ source venv/bin/activate
$ python3 z_subscriber.py
```


## Referência 

https://zenoh.io/docs/getting-started/first-app/