# Deploying infrastructure with Terraform

## Background

Having spent a lot of time creating services using the [Serverless framework](https://serverless.com/), I wanted to experiment with [Terraform](https://www.terraform.io/). This application is based on [this tutorial](https://medium.com/@bradford_hamilton/deploying-containers-on-amazons-ecs-using-fargate-and-terraform-part-2-2e6f6a3a957f).


## Features

The project includes the following features:

* **Infrastructure as code**, the backend infrastructure is defined in code using [Terraform](https://www.terraform.io/), allowing easy deployment in new environments
* **Fargate**
* **Autoscaling**
