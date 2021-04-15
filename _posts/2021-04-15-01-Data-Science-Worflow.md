---
toc: true
layout: post
description: A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.
categories: [data_science]
title: Data Science Workflow
---
# This is the step by step procedure to setup any data science project.
![ds_project]({{site.baseurl}}/assets/image/ds_project.jpg "")

## Basic setup
1. Install cookiecutter

   ```pip install cookiecutter```

2. Starting a new project

   ```cookiecutter https://github.com/drivendata/cookiecutter-data-science```
   
3. Create a virtual environment

   ```pipenv shell```
   
4. Install all the genearl packages for data science

   ```pip install -r requirements.txt```
   
5. Open jupyter lab for data exploration and analysis
   
   ```jupyter lab```
   
