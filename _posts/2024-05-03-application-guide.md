---
layout: post
title: Application Guide
subtitle: how to use the application
gh-repo: daattali/beautiful-jekyll
---

**You will be labeled according to the numbers as well as working through the numerical sequence.**

Table of content
1. [Inputs](#inputs-page)
   1. [Modify Model](#1-modify-model)
   2. [Inputs Dashboard](#2-inputs-dashboard)
   3. [Other Buttons](#3-other-buttons)
2. [Results](#results-page)
   1. [Objective](#1-objective)
   2. [Map](#2-map)
3. [Side Panel](#side-panel)
   1. [Data options](#data-options)
   2. [Input Data](#input-data)
   3. [Output Data](#output-data)

*******

## Inputs page

![inputs](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/inputs.PNG?raw=true")
Overview

### 1. Modify Model

#### 1.1 Input your data

![modify model](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/modify_model.PNG?raw=true")

1 & 2: Base location latitude(N°) and longitude(E°)

3 & 4: Recon location latitude(N°) and longitude(E°)

5: Size of recon location(km²). This will be the size of the land you want your UAV operating.

6: The duration you want your UAV operating.

7: The minimum coverage in percentage you want your UAV cover in recon location.

8.1: Select a UAV from our default data.

![dropdown select](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/dropdown_select.PNG?raw=true")

This dialog will popout in your screen for you to fill out.

8.2: You can upload your data as csv format with 'Name', 'Coverage', 'Endurance' and 'Speed' columns.

8.3: A tooltip to remind you when you hover it.

8.4 & 8.5 & 8.6 & 8.7: You can also type in your data in UI.

8.8: Button to add your type in data into system

8.9: This will be showing on your screen after you add your data.

![system info](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/system_info.PNG?raw=true")

1. You can edit added data by click the editing icon.
2. You can remove added data by click the trash icon.

### 2. Inputs Dashboard

A simple dashboard for you to overview your inputted data.
![inputs dashboard](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/inputs_dashboard.PNG?raw=true")

### 3. Other Buttons

Some other buttons.

![inputs other buttons](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/other_buttons.PNG?raw=true")

1. A map feature allow you to toggle map with the data you inputted.
2. After you confirm you inputted data you can run the model.
2.1. An error message pops up in the lower right corner of the screen.

************

## Results page

![results](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/results.PNG?raw=true")

Overview

### 1. Objective

![objective dropdown](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/objective_dropdown.PNG?raw=true")

You can select 1 objective from the 3 objective we provide:

`Maximize Coverage Area`, `Maximize duration at Point B` and `Minimize Drones Used`.

![objective2](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/objective2.PNG?raw=true")

1. Selected drones(with drone info).
2. other useful info for selected objective.

![objective1](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/objective1.PNG?raw=true")

If model have no valid combinations found will show like the above image.

### 2. Map

![map](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/map.PNG?raw=true")

There will be a polyline connect with both base and recon location.

1. Click on the marker of Recon location will show more info of recon location with calculated radius(blue circle).
2. Click on the marker of Base location will show more info of base location.

**********

## Side Panel
A simple options for you to save data locally.
### Data options

![data](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/data.PNG?raw=true")

1 & 2 & 3 Save, load and clear inputted data.
4 & 5 & 6 Save, load and clear inputted and results data.

**You must run model before you click on any option of output data section.**

#### Input Data

![input_data](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/input_data.PNG?raw=true")

Confirmation dialog before save data after click on option.

#### Output Data

![output_data](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/output_data.PNG?raw=true")

Confirmation dialog before save data after click on option.

**********