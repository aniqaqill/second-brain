---
layout: default
description: "Dive to Airflow with 0 exp .."
---

<div style="text-align: center;">
  <img src="../image/airflow/airflow-logo.png" alt="Airflow Logo" style="width: 80%; max-width: 500px;">
</div>

## What is Airflow ? 

A pipeline orchestration in python ecosystem.
Building a Machine Leaning Pipeline.

Its tool for authoring, scheduling, and monitoring pipelines. As a result, is an ideal solution for ETL and MLOps use cases.


## Use Case 

1. Read an image dataset from a cloud-based storage

2. Process the images

3. Train a deep learning model with the downloaded images

4. Upload the trained model in the cloud

5. Deploy the model

More Example like ;

- Extracting data from many sources, aggregating them, transforming them, and store in a data warehouse.

- Extract insights from data and display them in an analytics dashboard

- Train, validate, and deploy machine learning models

## Key Stuff

- Webserver : Webserver is Airflow’s user interface (UI), which allows you to interact with it without the need for a CLI or an API. From there one can execute, and monitor pipelines, create connections with external systems, inspect their datasets, and many more.

- Executor : Executor: Executors are the mechanism by which pipelines run. There are many different types that run pipelines locally, in a single machine, or in a distributed fashion. A few examples are `LocalExecutor, SequentialExecutor, CeleryExecutor and KubernetesExecutor`

- Scheduler : The scheduler is responsible for executing different tasks at the correct time, re-running pipelines, backfilling data, ensuring tasks completion, etc.

- PostgreSQL : A database where all pipeline metadata is stored. This is typically a Postgres but other SQL databases are supported too.

Easy if you use `Docker Compose`

## Basic Concept

### DAG 

### Task

### Operator

### Task Dependencies

### XComs

### Taskflow

### Scheduling

## Advance Concept

### Branching

### Task Groups

### Dynamic Dags

### Unit Tests and Logging 

## Best Practice 

### Idempotency

### Atomicity

### Incremental

### Top-level code

### Complexity

## My Airflow Learning

- [Learn Airflow](./learn-airflow.md) 

## Referrence

1. [A complete Apache Airflow tutorial: building data pipelines with Python](https://theaisummer.com/apache-airflow-tutorial/#why-and-when-should-i-consider-airflow)

2. [Apache Airflow 2.0 Tutorial](https://medium.com/apache-airflow/apache-airflow-2-0-tutorial-41329bbf7211)

3. [More resources](https://airflow.apache.org/ecosystem/#learning-resources)

4. [Airflow  Youtube](https://www.youtube.com/channel/UCSXwxpWZQ7XZ1WL3wqevChA)

