---
layout: home
permalink: /post-survey-procedures
title: "Post-survey procedures"
excerpt: ""
image:
  feature: 5x8_BRUV.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

## **Data management**

Large amounts of data are created from BRUVS with large video files, field data sheets, and software output. It is therefore important to consistently label folders and files to easily locate data and to simplify analysis. We also recommend documenting the file naming and folder structure in a post-survey report (Appendix C).

## **Processing video footage**

### **Fish annotations**

It was recently recognised by the national BRUVs steering group that, where possible, species composition, abundance and length data for all species should be recorded. It is recommended that every fish within a MaxN frame should be measured. However, fish that occur in large schools, and are of similar size, can be attributed to binned length measurement using the Number field associated with each length in EventMeasure-Stereo (see below). It is important to document the range from camera as this is likely to change between regions/ecosystems. This information is included in the standard outputs of EventMeasure-Stereo and is imported by default into GlobalArchive (see Section 5.7.4). Fish that occur in large schools can be attributed to binned length measurement using the Number field associated with each length in EventMeasure-Stereo.

There are several software packages available, but it is important the output from the analysis of data is in the same or similar formats to facilitate comparison of data between campaigns, studies, and organisations. The most commonly used annotation software is EventMeasure-Stereo from SeaGIS ([https://www.seagis.com.au](https://www.seagis.com.au/)). If afforded then the EventMeasure-Stereo software is recommended, unless your organisation already has an alternative established stereo-video annotation workflow (e.g. AIMS). The essential information produced by such annotation software includes three main outputs:

* Point information

* Length measurements

* 3-D point information

Point information is typically used to calculate MaxN values, while length and 3D point information is used to calculate length and biomass metrics. EventMeasure-Stereo has established queries built-in to produce typical metrics over a user defined period within the footage. In addition, EventMeasure-Stereo annotation datasets held within GlobalArchive ([http://globalarchive.org/](http://globalarchive.org/)) can be queried in a similar fashion to produce such metrics (see the manual for[ GlobalArchive](https://docs.google.com/document/d/1C5t4GM9AiRWiVimmWulmOfsu0HQ4SfDSdPr5gBldOZg/edit?usp=sharing)).While there are a number of relative abundance metrics available, MaxN (maximum number of individuals for given species counted within the field of view at the same time) is the most widely accepted (Cappo et al. 2007, Harvey et al. 2007).

Type of fish length (e.g fork length or total length for fish and disc length for rays) should be clearly indicated as part of the adequate annotation information for each Campaign.

### **Habitat classification from field of view**

Scoring of habitat information from the field of view is a relatively quick process and can provide extra information about habitat type. Classification of benthic composition and relief should be recorded from still image grabs for each deployment (e.g percent cover of benthos types) (Recommended). Collecting this information as continuous variables will enable regression approaches to be used to investigate the influence of habitat within the field of view on the fish assemblage.  To enable comparisons between studies it is important that researchers use comparable classification schemes. Recent studies (McLean et al. 2016, Collins et al. 2017) have adopted the CATAMI classification scheme (Althaus et al. 2013) in a systemised approach to scoring habitat composition and relief from forward facing imagery using TransectMeasure from SeaGIS ([https://www.seagis.com.au](https://www.seagis.com.au/)). This approach and standardised annotation schema have been documented in an open-access[ GitHub repository](https://github.com/TimLanglois/Habitat-annotation-of-forward-facing-benthic-imagery) (Langlois 2017).

## **Quality control and data curation**

Quality control and data curation are vital, but are potentially time consuming. These time considerations (and associated costs) should be considered during the survey planning stages.

All data corrections should be made within the original annotation files (i.e. within EventMEasure) to ensure data consistency over time. Four complementary approaches for QAQC of data are recommended:

* Analysts should first be adequately trained by completing deployments for which a species composition and density are known to which they can be compared.

* Once the first annotation for a deployment is completed, a different analyst should view each MaxN annotation to double check the species ID and abundance estimates.

* Footage from any previously unrecorded (i.e. range or depth extensions) or unidentifiable species should be sent to the project taxonomist for formal ID. It is important to send footage clip rather than still images.

* R workflows are provided in a[ GitHub repository](https://github.com/TimLanglois/Stereo-or-mono-video-annotation-workflows) to enable comparison with regional species lists and likely minimum and maximum sizes for each species[ (Langlois et al. 2017)](https://paperpile.com/c/cxZoCG/dSL3).

It cannot be stressed enough that any corrections** **should be made to the annotation files before data is exported to GlobalArchive or other repositories (i.e. only QC-d annotations should be publicly released).

A national BRUV steering group has been set up to oversee a nationally coordinated BRUV monitoring program (Table 5.1). Any new BRUV deployments should be discussed with this steering group to ensure that, where possible, they can be integrated within the national program (*Recommended*).

 

Table 5.1 Key contacts in national BRUV steering group, as of Jan 2018.

<table>
  <tr>
    <td>Name</td>
    <td>State</td>
    <td>Organisation</td>
  </tr>
  <tr>
    <td>Euan Harvey*</td>
    <td>Western Australia</td>
    <td>Curtin</td>
  </tr>
  <tr>
    <td>Tim Langlois</td>
    <td>Western Australia</td>
    <td>UWA</td>
  </tr>
  <tr>
    <td>Neville Barrett</td>
    <td>Tasmania</td>
    <td>IMAS</td>
  </tr>
  <tr>
    <td>Jacquomo Monk</td>
    <td>Tasmania/Victoria</td>
    <td>IMAS</td>
  </tr>
  <tr>
    <td>Alan Jordan</td>
    <td>New South Wales</td>
    <td>NSW DPI</td>
  </tr>
  <tr>
    <td>Hamish Malcolm</td>
    <td>New South Wales</td>
    <td>NSW DPI</td>
  </tr>
  <tr>
    <td>Daniel Ierodiaconou</td>
    <td>Victoria</td>
    <td>Deakin</td>
  </tr>
  <tr>
    <td>Charlie Huveneers</td>
    <td>South Australia</td>
    <td>Flinders University</td>
  </tr>
  <tr>
    <td>Leanne Currey</td>
    <td>Queensland</td>
    <td>AIMS</td>
  </tr>
</table>


***** Chair

 

## **Data release**

GlobalArchive (www.globalarchive.org) is a centralised repository for stereo- and single-camera fish image annotation data, in particular from Baited Remote Underwater stereo-Video (stereo-BRUVs) and Diver Operated stereo-Video (stereo-DOVs). A user manual for GlobalArchive is available in an open-access[ GitHub repository](https://github.com/TimLanglois/GlobalArchive). Metadata should be made publicly available via[ GlobalArchive](http://globalarchive.org/) as soon as possible after survey completion and data QA/QC and validation. This should include positional data, as well as the purpose of the sampling campaign, the survey design, all sampling locations, equipment specifications, and any challenges or limitations encountered. Annotations can also be uploaded once complete. Spatial metadata from GlobalArchive data will in the future be harvested by the Australian Ocean Data Network, and the metadata will accordingly be available on their national portal. Until this is done, metadata should be published on both GlobalArchive and AODN to ensure data discoverability *[Recommended]*.

 

There is currently no national repository for BRUV imagery so we recommend following agency-specific protocols to ensure public release. A national marine imagery repository (including for BRUV imagery) will be scoped in 2018 and updates provided in Version 2 of this field manual.

 

Following the steps listed below will ensure the timely release of video and associated annotation data in a standardised, highly discoverable format.

 

1. Immediate post-trip reporting should be completed by creating a metadata record documenting the purpose of the BRUV sampling campaign, the survey design, all sampling locations, equipment specifications, and any challenges or limitations encountered. This can be done far in advance of annotation (scoring) of raw video which is time-consuming and often does not occur for some time following completion of sampling.

2. Publish metadata record to the[ Australian Ocean Data Network (AODN) catalogue](http://catalogue.aodn.org.au/geonetwork/srv/eng/main.home) as soon as possible after metadata has been QC-d. This can be done in one of two ways:

    * If metadata from your agency is regularly harvested by the AODN, follow agency-specific protocols for metadata and data release.

    * Otherwise, metadata records can be created and submitted via the[ AODN Data Submission Tool](https://metadataentry.aodn.org.au/submit). Note that user registration is required, but this is free and immediate.

Lodging metadata with AODN in advance of annotation data being available is an important step in documenting the BRUV campaign and enhancing future discoverability of the data.    

3. Annotate video (fish counts and length) using EventMeasure or similar software.

4. Upload annotation data and any associated calibration, taxa and habitat data to GlobalArchive.

5. Upload raw video data to a secure, publicly accessible online repository (contact AODN if you require assistance in locating a suitable repository for large video collections).

6. Add links to GlobalArchive campaign and raw video storage location to previously published metadata record. You may also wish to attach or link a copy of the annotation data directly to the published metadata record.

7. Produce a technical or post-survey report documenting the purpose of the survey, sampling design, sampling locations, sampling equipment specifications, annotation schema, and any challenges or limitations encountered. Provide links to this report in all associated metadata. See Appendix C *[Recommended]*

