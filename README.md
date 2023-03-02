# YouML Kedro - YOLO

## Information

Create models for object detection with YOLO.
This is a Kedro project, which was generated using `Kedro 0.18.5`.
Take a look at the [Kedro documentation](https://kedro.readthedocs.io) to get started.

## Dependencies

*  Python >= 3.8

## Installation

* Create virtual environment

```shell
python3 -m venv <venv name>
```

* Install pipenv

```shell
pip install pipenv
```

* Install dependencies

```shell
pipenv install
```

## To start Kedro project

* Run kedro project

```shell
kedro run
```

* Run kedro test

```shell
kedro run test
```

* Visualize the project
```shell
kedro viz
```

## To create a new pipeline

* Generate a new pipeline template

```shell
kedro pipeline create <PIPELINE_NAME>
```

* To run a Kedro node by node name

```shell
kedro run --nodes=preprocess_companies_node
```

* To run a Kedro pipeline by catalog name

```shell
kedro run --pipeline=data_science
```
