# IWXXM 2.1.1 Implementation in Java Language
IWXXM (ICAO Meteorological Information Exchange Model) is a format for reporting weather information in XML/GML. IWXXM includes XML/GML-based representations for products standardized in International Civil Aviation Organization (ICAO) Annex III and World Meteorological Organization (WMO) No. 49, Vol II, such as METAR/SPECI, TAF, SIGMET, AIRMET, Tropical Cyclone Advisory and Volcanic Ash Advisory. IWXXM products are used for operational exchanges of meteorological information for use in aviation.
Unlike the traditional forms of the ICAO Annex III / WMO No. 49 products, IWXXM is not intended to be directly used by pilots. IWXXM is designed to be consumed by software acting on behalf of pilots, such as display software.
See details at https://en.wikipedia.org/wiki/IWXXM

![IWXXM](https://wiswiki.wmo.int/img/tiki/wmologo2016_fulltext_horizontal_rgb_en.png "iwxxm")

### What is IWXXM 2.1.1 Implementation?
IWXXM (the ICAO Meteorological Information Exchange Model) is a data format for reporting aviation weather information in XML/GML, and is specified in both XML Schema and Schematron. So, to get information from IWXXM, developers need to  convert XML to specific program language type. This module is written by Java and convert IWXXM Schema to Java Classes.


### How to build

```sh
$ mvn clean compile

# To package, 
$ mvn package
```

### License

**This is Free Software with no limitation**

