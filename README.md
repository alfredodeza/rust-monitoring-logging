# [![Coursera Course](./assets/banner.svg)](https://insight.paiml.com/prr?utm_source=GitHub "Coursera Course")

# Rust Monitoring and Logging

_Week 2 of Rust for DevOps_

This repository is part of the Rust for DevOps course:

- [week 1](https://github.com/alfredodeza/rust-setup) 
- [week 2](https://github.com/alfredodeza/rust-monitoring-logging) 👈 You are here!
- [week 3](https://github.com/alfredodeza/rust-systems-programming/) 
- [week 4](https://github.com/alfredodeza/advanced-ci-cd-concepts)


## Example project: Redact Personal Identifiable information as a service

This example project will allow you to explore how to add and enable different logging and monitoring tecnhiques to a Rust project. The simple microservice accepts a JSON string as input to the `/redact` endpoint and return a JSON string with the PII redacted based on regular expressions stored as JSON.

This project is part of a course on Rust For DevOps which will teach you how to use Rust while you learn DevOps principles like logging, testing, monitoring, automation, CI/CD, containers, and deployment.

## Contents
This course is divided into three lessons, each covering different aspects of Rust programming. This week has several examples located in the [./examples](./examples) directory. Make sure you have Rust installed and you are using [Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=academic-0000-alfredodeza).

This repository is *Codespaces ready*, and it is set as a template repository. You can create a new repository from this template and start working on your own with Codespaces. This means that Rust, Copilot, and all the extensions are already installed and configured for you.

### Lesson 1: Prometheus and Grafana
- [Introduction to Prometheus](./examples/1-prometheus/)
- [Integrating Prometheus with Grafana](./examples/2-prometheus-grafana/)
- [Creating custom endpoints](./examples/3-custom-endpoint/)

### Lesson 2: Adding Logging

- [Adding logging to your Rust application](./examples/4-adding-logging/)
- [Controlling verbosity in Rust](./examples/5-controlling-verbosity/)


### Lesson 3: Structured Logging
- [Exploring structured logging in Rust](./examples/6-structured-logging/)


## Resources
Explore additional content that you can use to learn more about the topics covered in this course.

**Coursera Courses**

- [Linux and Bash for Data Engineering](https://www.coursera.org/learn/linux-and-bash-for-data-engineering-duke)
- [Open Source Platforms for MLOps](https://www.coursera.org/learn/open-source-platforms-duke)
- [Python Essentials for MLOps](https://www.coursera.org/learn/python-essentials-mlops-duke)
- [Web Applications and Command-Line tools for Data Engineering](https://www.coursera.org/learn/web-app-command-line-tools-for-data-engineering-duke)
- [Python and Pandas for Data Engineering](https://www.coursera.org/learn/python-and-pandas-for-data-engineering-duke)
- [Scripting with Python and SQL for Data Engineering](https://www.coursera.org/learn/scripting-with-python-sql-for-data-engineering-duke)

**O'Reilly Courses and Books**

- [Python for DevOps](https://www.oreilly.com/library/view/python-for-devops/9781492057680/) (Book)
- [Practical MLOps](https://www.oreilly.com/library/view/practical-mlops/9781098103002/) (Book)
- [Linux For Beginners](https://learning.oreilly.com/videos/-/27922450VIDEOPAIML/) (Video)
- [GitHub Codespaces Course](https://learning.oreilly.com/videos/-/27724023VIDEOPAIML/) (Video)
- [Python Command-line Tools course](https://learning.oreilly.com/videos/python-command-line/50131VIDEOPAIML/) (Video)
