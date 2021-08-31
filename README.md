## ShotSpotter Alerts per Census Tract

#### Objective
The purpose of this project is the examine the locations and efficacy of acoustic gunshot sensors supplied by ShotSpotter, a publicly traded company under scrutiny from social justice organizations and watchdog groups that promises an extraordinary accuracy rate of 97% on its technology.

The ShotSpotter system uses AI, hundreds of listening devices set up around the city, and spatial triangulation to identify a gunshot, its location, and its time of occurrence. 

In the case of [United States v. Michael Williams](https://apnews.com/article/artificial-intelligence-algorithm-technology-police-crime-7e3345485aa668c97606d4b54f9b6220) in Chicago this year, ShotSpotter evidence put a man in prison for murder in a case that had what AP called "scant evidence". The Brighton Park Neighborhood Council, et al. filed an amicus brief in Williams' case containing an [in-depth analysis](https://endpolicesurveillance.com/) of ShotSpotter performance, which is rare. 

The analysis studied over 40,000 ShotSpotter alerts between July 2019 and April 2021 and found that 88.72% of alerts "did not result in police recording any kind of incident involving a gun," and that 85.60% of ShotSpotter did not result in a case report being filed by police. The amicus brief also emphasized that the ShotSpotter system is consistently fooled by loud or sudden noises such as vehicle engines and fireworks.

#### Infographic

In this GH repo, you'll find (1) a source KML of DC's census tracts from opendata.gov; (2) a GeoJSON converted using geojson.io to satisfy compatibility with MapBox's API (not to mention, I just like using GeoJSON); and (3) a source code HTML file containing the infographic CSS and MapBox JS (all in one file because I hate myself).

#### Other Research
1. Starting on Jan 1, 2019, ShotSpotter started an "autoacknowledged" feature that brought humans into the equation. If sensors picked up a possible gunshot but the AI wasn't sure, it would send the noise over to a listening center where an employee would listen to the sound and then have the ability to change its classification. This presents a "natural experiment" between years 2018 and 2019. 
