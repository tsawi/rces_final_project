#FILE INFORMATION: This file contains source parameters for glacial earthquakes in Greenland
# occurring during 1993-2013. The earthquake detection parameters (detection location and time)
# are obtained following Ekstrom (2006) and Nettles and Ekstrom (2010). The earthquake centroid
# parameters were determined for 1993-2005 by Tsai and Ekstrom (2007); for 2006-2010 by
# Veitch and Nettles (2012); and for 2011-2013 by Olsen and Nettles (2017). 
# If you use results from this merged catalog, please cite the three papers:
# Tsai and Ekstrom, 2007, JGR: 10.1029/2006JF000596;
# Veitch and Nettles, 2012, JGR: 10.1029/2012JF002412.
# Olsen and Nettles, 2017, Journal of Glaciology, submitted, 2017.
#----------------------
#FORMAT:  File format is similar to Table 1 of TE07, but with region numbers updated to match 
# VN12/ON17, and with additional info in the last three columns. The columns are:
# centroid latitude, longitude; amplitude in units of 1.e14 kg-m; force azimuth; centroid time
# shift from detection time; original detection year, month, day, hour, minute, second;
# original detection latitude, longitude; original estimated earthquake magnitude MSW; region;
# detection type; event name.
#----------------------
#NOTES:
#- Event names for 1993-2005 should not be considered fixed at this time.
#- This file corrects an error in region identifiers for two events in Table 1 of VN12: 
#   200705300257 4b --> 4a
#   200706090516 4a --> 4b
#- Region definitions: 0: Daugaard-Jensen Glacier; 1: Kangerdlugssuaq Glacier; 2: Helheim Glacier;
#   3: Southeast Greenland (multiple glaciers); 4a: Tracy Glacier; 4b: Kong Oscar Glacier;
#   4c: Sverdrup Glacier; 4d: Hayes Glacier; 4e: Alison Glacier; 5a: Giesecke Braeer;
#   5b: Upernavik Isstroem; 6: Rinks Glacier; 7: Jakobshavn Isbrae; 8: Rolige Brae;
#   9: Sermeq Silardleq; 11: SW of Kangerdlugssuaq glacier.
#- The "detection type" column is "1" for standard detections; "2" for "NRT" detections; and
#  "3" for lower-quality detections; see VN12/ON17 for details.
#----------------------
#QUESTIONS: contact Meredith Nettles, nettles@ldeo.columbia.edu