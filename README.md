Kilonova Seekers IRIS Data
====

This repository contains data for the Kilonova Seekers IRIS project. Data is taken from the Gravitational-wave Optical Transient Observer [(GOTO)](https://goto-observatory.org/).

What do the columns mean? 
---
* *mjd*: Modified Julian Date
* *forced_mag*: Magnitude of object at that time. If blank, it means the object was not detected.
* *forced_mag_uncert*: Uncertainty on magnitude.
* *forced_uJy*: Flux of object, in micro-Jansky units.
* *forced_uJy_uncert*: Uncertainty on flux, in micro-Jansky.
* *forced_mag_sigma_limit*: If the forced mag column is blank, this gives a 5-sigma upper limit at that position - i.e. we can rule out seeing any source brighter than this magnitude at this time.
