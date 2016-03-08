---
published: true
title: Pulsar Voices
layout: post
tags: [pulsar, CSIRO, ATNF, data, datavis]
---
### Background / Goal
<a href="http://www.atnf.csiro.au/research/pulsar/psrcat/">Pulsar data</a> is available from <a href="http://www.atnf.csiro.au/outreach/education/everyone/pulsars/index.html">ATNF at CSIRO.au</a>. Our team at <a href="http://sciencehackau.github.io/melbourne/">#SciHackMelb</a> has been working on a #datavis to give researchers and others a novel way to explore the Pulsar corpus, especially through the sound of the frequencies at which the Pulsars emit pulses.

Source data: <a href="http://www.atnf.csiro.au/research/pulsar/psrcat/">http://www.atnf.csiro.au/research/pulsar/psrcat/</a>

![](https://pbs.twimg.com/media/Cc0Dws-UYAA7Yz4.jpg)

### The Team:
* Tony - web dev, php, JavaScript, SQL, phpmyadmin, CDs, html, visualising pulsar
* Gary - python tech, visualising sound of a single pulsar
* Chris - data manager, accessing CSIRO pulsar data and manipulating it to a useful format
* Anderson - SQL
* Michael - transforming pulsar coordinates, azimuthal to cartesian
* Richard - data analyst, datavis advisor, data management
* AAD - R analysis of pulsar distance, frequency distribution
* Advisors: CSIRO Jess Robertson (focus on simple, doable outcome), AAD

### Data:
* RA - east/west coordinates (0 - 24 hrs, roughly equates to longitude)
* Dec - north/south coordinates (-90, +90 roughly equates to latitude i.e. 90 is above north pole, and -90 south pole)
* P0 - the time in seconds that a pulsar repeats its signal
* f - 1/P0 which ranges from 700 cycles per sec, to some which pulses which occur every few seconds
* kps - distance from Earth in kilo-parsecs. 1 kps = 3,000 light years. The furthest data is 30 kps. The galactic centre is about 25,000 light years away i.e. about 8kps.
* See description at: <a href="https://figshare.com/s/540578d3cefdd6529ea6">figshare</a>

### Method
We plotted RA, Dec on a rectangular screen roughly to see pulsar location.
One of us, Gary, worked on one pulsar data, turning the frequency into sound. A graph shows the variation in pulse between pulses. Another of the team, piotted a histogram of the range of pulsar frequencies, which shows a nice bi-modal distribution. Why is it bi-modal, we will have to ask a pulsar scientist.

### What next, still to do
* load data, description, images fileset to figshare :: DOI ; DONE except DOI
* add overview images as option eg frequency bi-modal histogram
* colour code pulsars by distance; DONE
* add pulsar detail sound to Top three Observants; 16 pulsars processed but not loaded
* add tones to pulsars to indicate f; DONE
* add tooltips to show location, distance, frequency, name; DONE
* add title and description; DONE
* project data onto a planetarium dome with interaction to play pulsar frequencies; DONE kind of, see below 
* zoom into parts of sky to get separation between close data points; DONE kind of, see below.
* set upper and lower tone boundaries, so tones aren't annoying
* colour code pulsars by frequency bins e.g. >100 Hz, 10 - 100, 1 - 10, <1 Hz


### Projected Pulsar location to Google Maps / Google Earth
How to turn Pulsar data into Google map/Google Earth;

Google Drive -> Add new Google Map -> Import -> psrcatSparse.csv -> Add Title, description

Google Maps; maps.google.com -> Login -> Menu -> My Maps -> Select Pulsar Map -> See Map -> Click Earth (bottom left corner). Data projected onto Google Earth. -> Collapse Side Panel

Can rotate, zoom in/out. To see data on map marker; view -> expand side panel.
Doesn't seem any way to share Google Earth view, but can share Map view.

<a href="https://www.google.com/maps/d/edit?mid=z4ltNGIQ4Lp4.kXadYfc58UmE&usp=sharing">See Google Map</a>
Status of map: Public on the web - Anyone on the Internet can find and view

<iframe width="420" height="315" src="https://www.youtube.com/embed/F119gqOKJ1U" frameborder="0" allowfullscreen></iframe>
Pulsars projected onto Google Earth.