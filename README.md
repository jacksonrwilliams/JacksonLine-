#JacksonLine- Analytical Programming Final Project 

I created my own version of a surf condition report for my two favorite beaches: Ocean Beach in San Francisco and Mission Beach in San Diego. I have always found mainstream surf reports, such as those on Surfline, to be too generalized and not precise enough for individual beaches. My goal was to create a surf forecast based on data and experiences surfing these specific beaches, rather than relying on generalized reports that often prove to be inaccurate. I will continuously make changes to the conditional statements in code to reflect my changing views of what ocean and wind parameters create good surf conditions. 

In addition to the surf forecast, I included additional features such as a wetsuit temperature search and buttons for checking if it's too cold or too windy for surfing. This allows me to make informed decisions about whether I want to brave the conditions on any given day. Overall, I am excited to have my own reliable surf forecast based on my own expertise and experience.

##My GUI 
<img width="468" alt="image" src="https://user-images.githubusercontent.com/116693034/212137666-a1e3175d-539a-4a71-a7f4-a5ff40f25966.png">

- Spot Selection: the user will either select Mission Beach, SD or Ocean Beach, SF and hit the surf report button which produces a messagebox on whether you should go surfing or not. This also will produce a csv file with the conditions from the api at that given hour. 

<img width="251" alt="image" src="https://user-images.githubusercontent.com/116693034/212137746-55f69c2d-af83-44eb-9d50-b46577ae3c6f.png">

- Either this or a message box saying you should go surf will pop up. The csv file below will be created on the user’s computer. 

<img width="468" alt="image" src="https://user-images.githubusercontent.com/116693034/212137786-20edccf4-0a0c-44c4-9404-1d73a4a37bf3.png">

- Type in a Temperature for the Water We Will Tell You What Wetsuit to Use: the user will type into the search box and then a messagebox will pop up with wetsuit they should wear.  

<img width="468" alt="image" src="https://user-images.githubusercontent.com/116693034/212137809-2c666c9d-6fb5-4275-9818-0e0a1a51e4b9.png">

- Max Wind Speed at the Spot and Water Temperature Minimum Selection functions in the same way, where the user will type into the search box, change the spot selection for what beach that they want to look at, and then hit the button of their desired function.  

<img width="468" alt="image" src="https://user-images.githubusercontent.com/116693034/212137842-dc2b9a6b-013c-4962-87b5-381988b69419.png">

##API Key and Source 
Source: Stormglass.io

##Modules Required to Run my Program
- import arrow
- import tkinter, tkinter.messagebox, tkinter.ttk
- import csv 
- import pandas as pd 
- import numpy as np
- import requests 
- import json
- import tkinter as tk
- from tkinter import ttk
- import time 
- from datetime import datetime
