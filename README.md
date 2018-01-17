# R-Projections-Workshop
A workshop on understanding and using projections for spatial data in R


# Potential Resources for Me:

1. [Rspatial.org](http://rspatial.org/spatial/rst/6-crs.html)
1. [Data Carpentry Intro to Geospatial Data with R](http://www.datacarpentry.org/R-spatial-raster-vector-lesson/)
1. [University of Colorado's Map Projections](https://www.colorado.edu/geography/gcraft/notes/mapproj/mapproj_f.html)
1. previous Projeciton workshop notes

Map Projection Fun:

1. [xkcd's Map Projections](https://xkcd.com/977/)
1. [Jason Davies' Map Projection Transitions](https://www.jasondavies.com/maps/transition/)


# Coordinate Reference System

CRS = Datum + Projection + Additional Parameters

## Datum

## Projection

## Additional Parameters

---------------------------------------
## Previous notes:

What is Latitude & Longitude?
= angular measurements from an arbitrary zero

What is a projection?
= making angular measurements on a sphere into a flat surface

WHY projections?
= minimizing distortions in the flattening process

Define Projection vs. Reproject


Let's break stuff! = the hands-on portion of the program

First, we'll look at projections visually.

Open QGIS

You'll need to turn off projection on the fly to see the difference between new layers.
 Options --> CRS tab --> Pick "Don't enable 'on the fly' reprojection' from the Default CRS for New Projects options.

Load a shapefile - suggestion: CA Counties

Reproject your shapefile
- right click --> save as --> pick a new name (put the EPSG code in the name) --> pick a new projection (start with CA Albers NAD 27)

Turn off projection on the fly... not much difference b/n CA Albers NAD 83 & NAD 27

Reproject the shapefile again with another... try UTM Zone 10 N (32610) and Australian Albers (3577)


Ideas:
 * Try making measurements like distance or area

