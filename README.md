Copy code
#My final project

I created my own version of a surf condition report for my two favorite beaches: Ocean Beach in San Francisco and Mission Beach in San Diego. I have always found mainstream surf reports, such as those on Surfline, to be too generalized and not precise enough for individual beaches. My goal was to create a surf forecast based on data and experiences surfing these specific beaches, rather than relying on generalized reports that often prove to be inaccurate. I will continuously make changes to the conditional statements in code to reflect my changing views of what ocean and wind parameters create good surf conditions. 

In addition to the surf forecast, I included additional features such as a wetsuit temperature search and buttons for checking if it's too cold or too windy for surfing. This allows me to make informed decisions about whether I want to brave the conditions on any given day. Overall, I am excited to have my own reliable surf forecast based on my own expertise and experience.

##My GUI 

- Spot Selection: the user will either select Mission Beach or Ocean Beach and hit the surf report button which produces a messagebox on whether you should go surfing or not. This also will produce a csv file with the conditions from the api at that given hour. 

- Either this or a message box saying you should go surf will pop up. The csv file below will be created on the user’s computer. 

- Type in a Temperature for the Water We Will Tell You What Wetsuit to Use: the user will type into the search box and then a messagebox will pop up with wetsuit they should wear.  

- Max Wind Speed at the Spot and Water Temperature Minimum Selection functions in the same way, where the user will type into the search box, change the spot selection for what beach that they want to look at, and then hit the button of their desired function.  

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
