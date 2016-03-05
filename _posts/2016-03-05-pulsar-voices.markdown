---
published: true
title: Pulsar Voices
layout: post
tags: [pulsar, CSIRO, ATNF, data, datavis]
---
Pulsar data is available from ATNF at CSIRO.au. Our team at #SciHackMelb has been working on a #datavis to give researchers and others a novel way to explore the Pulsar corpus, especially through the sound of the frequencies at which the Pulsars emit pulses.


The Team:
Tony - webbed
Gary - python tech, visualising sound of a single pulsar
Chris - data manager, accessing CSIRO pulsar data and manipulating it to a useful format
Anderson - SQL
Richard - data analyst, datavis advisor, data management
AAD - R analysis of pulsar distance, frequency distribution
Advisors: CSIRO, AAD

Data:
RA - east/west coordinates (0 - 24 hrs, roughly equates to longitude)
Dec - north/south coordinates (-90, +90 roughly equates to latitude i.e. 90 is above north pole, and -90 south pole)
P0 - the time in seconds that a pulsar repeats its signal
f - 1/P0 which ranges from 700 cycles per sec, to some which pulses which occur every few seconds
kps - distance from Earth in kilo-parsecs. 1 kps = 3,000 light years. The furthest data is 30 kps. The galactic centre is about 25,000 light years away i.e. about 8kps.

We plotted RA, Dec on a rectangular screen roughly to see pulsar location.
One of us, Gary, worked on one pulsar data, turning the frequency into sound. A graph shows the variation in pulse between pulses. Another of the team, piotted a histogram of the range of pulsar frequencies, which shows a nice bi-modal distribution. Why is it bi-modal, we will have to ask a pulsar scientist.