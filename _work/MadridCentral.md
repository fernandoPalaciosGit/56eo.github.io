---
title: MadridCentral
externalLink:
order: 1
---
#### Prototype-Madrid Central


![]({{ site.url }}/assets/images/Madrid_Central.gif)

## Background:

Madrid's City Hall have introduced new restrictions on traffic in the heart of the capital. This measurement was aligned with the air quality strategy for reducing the high values of pollution were matched last years in the town.

## Lifetime:
30th nov 2018: Started
1st jul-30th sep 2019: Right party, ciudadanos and vox want to apply a moratorium on sanctions  for citizens who enter in madrid
Only from 1-8th jul 2019: it was admitted that moratorium bc several greenparties and institurions pushed.
Jul 2019: Europe comission sentence Spain for: systematically violate "legal nitrogen dioxide (NO2) limits. Specially at Madrid, Barcelona y Vallès-Baix Llobregat.
Main points:
472 hectares of the city center off-limits to traffic
except for local residents and public transportatio
Non-residents with appropriate energy labels
exceptions are made for people with reduced mobility, ambulances, taxis, private-hire cars and delivery vans
Electric vehicles will also be allowed
Map restriction:
https://elpais.com/elpais/2018/11/30/inenglish/1543565577_207058.amp.html

## Expectation:
will reduce emissions NOx by 30-40% as a result of eliminating through traffic and banning the biggest polluters from the area.
Even so, They only have one field station called “del Carmen” which measures air quality in the “zona restringida” among 24 stations around Madrid center. And after activating the restriction plan, Carmen's station got lower pollution values, even though the others stations continues increasing.
Although, the first three months of 2019 have been the worst, only after 2011 and 2012. And we only can compare from 2011 because in 2010 the location office the measurement stations was changed.
Moreover, Comparing the median of the first three months from 2011-2018 to confront the one in 2019 in terms of removing the meteorological factor, we conclude that 2019 is still above the median.
Looking at the adverse air quality situation in Madrid, we conduct a new visualization of tropospheric NO2 via spatial and temporal scale by analysing satellite images.
NO2 has been monitored by satellite since 1995 with GOME, since 2002 with SCIAMACHY, and since 2004 with the OMI instrument; the latter two instruments having the advantage of a high spatial resolution. As the last satellite, Sentinel 5p is in charged to monitor the atmosphere conditions Launched in October 2017.
This is an experiment aiming at giving more transparency to the Madrid’s citizens according pollution trends.

Links to undestand intro

RESULTS(briefly documented app along time, WHAT DO WE EXPECT FROM)
https://www.getrevue.co/profile/maps/issues/spatial-awareness-7-maps-spatial-newsletter-by-robin-hawkes-190525
https://haqast.org/wp-content/uploads/sites/91/2019/02/4_Lee.pdf
https://visibleearth.nasa.gov/view.php?id=92215
https://twitter.com/AntjeInness/status/1154697090490142721?s=19
This App can overlap actual air quality field data with satellite ones.
This app can give an NO2/spatial/temporal perspective in madrid never seen before
This app can draw more air quality indices:



MARKETING

Collaboration with “calida del aire comunidad de madrid”
Collaboration with TRAFICO. They can show along highways how one produces pollution and how that influence in his or her neighborhood.
Collaboration with a newspaper or all of them
Collaboration with “universidad politecnica de madrid”
Publish to twitter
Principal responsible of mapping new european rights in meditarrean and associated with madrid central issue: @KarmenuVella
European comissioner and related with madrid case: @MAC_europa

Outputs: @Pablo_Lion, #MadridCentral, @lalalalia, @Ferfollos, @Troposfera, @EeAmadrid,, @demadridcentral, .@MasMadridLGTBI @MasMadrid__ @MasCarabanchel @MasArganzuela @MasHortaleza , #MadridCentralFunciona
@ClimateKICspain @itdupm, In English, ckicnordic
Publish in this way: example, comparing with and without ICE...
Madrid and Barcelona, with and without NO2

WORKFLOW
Download vector layer (neightborhoods, buildings)
Create Twitter 56eo and link to a broad fruitful network
Download sahpefile of “zona restringida de trafico”
GEE- extract NO2 or others or others

//vectorizing all the tiffs via google earth engine to lighten workload ?-Ideally all the work is done on the platform itself, otherwise manually at home-
Extract NO2 troposphere, not stratosphere, have a look pag 15-76 - TO KNOW
IMPORTANT: ABOUT NO2 AND ITS DISTRIBUTION
Conversion:

NO2 micrograms/m3 (Field sensor) vs NO2 columns in mol/m2 (S5p) vs mol/cm2 (SI unit)

The multiplication factor to convert mol/m2 to molec/cm2 is 6.02214×1019
The multiplication factor to convert mol/m2 to DU is 2241.15.
The O2–O2 concentration is given in mol2/m5: the multiplication factor to convert this to the commenly used unit molec2 /cm5 is 3.62662×1037
Look how is the distribution by element and decide spatial and temporal scale
CALIBRATE THE MODEL WITH others: look to another data
App- ayuntamiento de madrid
App-poor of prediction
ABC_NO2 by district in madrid
EL CONFIDENCIAL_ APP
IMPACT OF RESTRICTION -GRAPHIC
El mundo_APP
2018 report of pollution in madrid
There are 24 quality air field sensor in Madrid
Acoording to EU, the limit is 200 micrograms/m3/h, this range can not be exceeded more than 18 hours per year in any field sensor.
In 2018 only 2 sensors overpassed the limit, more
Look to field data: 24 quality air field sensor in Madrid
Visualization?
Write the conclusions in EO56 site google
Select one basemap with mapbox
Visualization by cartodb
See marketing



BACKGROUND
Data from field sensors:
Data downloaded
Look diagrams
Vector layer:
DOWNLOAD “CADASTRAL MESH” FROM SEDE CATASTRAL BY A PERSONAL DIGITAL CERTIFICATE AND TIPS
Download it by datos abiertos madrid

MORE INFO

Troposphere: 0-10km from 20 to -60 °C
Ozone layer: 20-30km from -60 to -50 °C
Stratosphere: 10-50km from -60 to 0°C


APPS THAT ALREADY EXIST
https://unearthed.greenpeace.org/2018/10/29/nitrogen-dioxide-no2-pollution-world-map/
https://www.greenpeace.org.au/research/new-satellite-data-reveals-worlds-largest-air-pollution-emission-hotspots-greenpeace-media-briefing/
https://geoservice.dlr.de/web/maps/s5p:tropomi:l3:daily
https://earthdata.nasa.gov/earth-observation-data/near-real-time/hazards-and-disasters/air-quality
