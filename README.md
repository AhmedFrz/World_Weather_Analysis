# World_Weather_Analysis

## Installation 
pip install citipy


## Looking up with coordinates

>>> from citipy import citipy
>>> city = citipy.nearest_city(22.99, 120.21)
>>> city
<citipy.City instance at 0x1069b6518>
>>>
>>> city.city_name     # Tainan, my home town
'tainan'
>>>
>>> city.country_code
'tw'                  # And the country is surely Taiwan
