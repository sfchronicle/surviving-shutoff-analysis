# Intro

These scripts estimate the number of people in Northern California who rely on electric medical eqiupement affected by three planned power outages in October and November 2019. The end product is a geojson of points--centroids of ZIP codes--along with estimates of the number affected in each ZIP code at a number of dates and times.
To run this code you will need python 3, something to run jupyter notebooks, and a few python modules: osgeo, os, json, geojson, shutil, requests and copy.

This analysis went into this story: https://projects.sfchronicle.com/2019/surviving-a-shutoff/

# Workflow:

Run scripts in this order:
1. get_dme_zips
2. get_outage_data
3. json_to_geojson
4. check_intersects
5. add_centroids

# Questions?

Reach the developer @ejblom

