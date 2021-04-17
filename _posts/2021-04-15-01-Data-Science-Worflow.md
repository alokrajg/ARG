---
toc: true
layout: post
description: A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.
categories: [data_science]
image: images/ds_project.jpg
title: Data Science Workflow
---
# Step by step procedure to setup any data science project.
![ds_project]({{site.baseurl}}/images/ds_project.jpg " ")

## Basic setup
1. Install cookiecutter

   ```
   conda install cookiecutter
   ```

2. Starting a new project

   ```
   cookiecutter https://github.com/drivendata/cookiecutter-data-science
   ```
   
3. Create a virtual environment

   ```
   conda create -n virtual-env-name python==3.8
   conda activate virtual-env-name
   ```
   
4. Install all the genearl packages for data science

   ```
   conda install --file requirements.txt
   ```
   or
   
   ```
   conda install pip
   pip install -r requirements.txt
   ```
   
5. Open jupyter lab for data exploration and analysis
   
   ```
   jupyter lab
   ```
   
