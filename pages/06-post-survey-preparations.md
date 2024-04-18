---
layout: home
permalink: /post-survey-procedures
title: "Post-survey Procedures"
excerpt: "<br>"
image:
  feature: /banners/00_banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

## Data processing

Image/video post-processing, selection and annotation method and detail will depend on the objectives of the survey/project. For example, if the objective is to describe benthic habitats/biota/communities, then consider limiting the imagery to the ‘on bottom’ part of the towed camera transect, prior to running any selection processes. If documented properly using adequate metadata, imagery can be analysed, processed and annotated in a number of different ways to achieve different purposes. It is also important to document the reasons for, and effect of, removing selected imagery/footage from annotations/analyses.



*   A general workflow for data processing methodology can be found in Williams et al. (2012a). If constructing photomosaics from imagery, key requirements for raw image processing and positional data are as follows:
*   It is recommended that at least one of the stereo images is in colour and enhanced following similar procedures as outlined by Shortis and Harvey (2009) and Bryson et al. (2016). 
*   All stereo images should be georectified following Williams et al. (2012b).
*   Positional data should be post-processed using Simultaneous Localisation and Mapping (SLAM) as demonstrated in (Barkby et al. 2009) and (Palomer et al. 2013).


## Annotation framework

Scoring of individual images can be done using a number of annotation software tools. Examples include, Transect measure, Coral Point Count, CoralNet and Squidle+. For national consistency Squidle+ is recommended as it allows for different approaches to subsample images, which appears to influence inferences from data, as well as stratified and random point count distribution on images. It also automatically imports the collected towed camera data once it is uploaded to the AODN making it ready for analysis, and has tools for exploring survey data as well as analyses. In addition, it supports multiple annotation schemes, and will provide consistency through translation between schemes, which is an important point that differentiates Squidle+. 

There are two main approaches recommended for annotating georeferenced imagery from towed camera systems:

*   Annotation of individual images/frame grabs (real-time or post-acquisition)
*   Annotation of photomosaics

A how-to guide about setting up annotation media sets within Squidle+ is provided at [https://squidle.org/wik](https://squidle.org/wiki)<span style="text-decoration:underline;">i. </span>Annotation of individual images or photomosaics can be undertaken using two methods:

1. <span style="text-decoration:underline;">Full assemblage scoring of imagery</span> across space and time. It is important to note that this is a time consuming process, requiring a lot of replicate images to be scored to enable sufficient power to detect biologically meaningful change as most morphospecies are &lt; 10 % cover within images. This approach appears to be good for delineating bioregional and cross-shelf patterns at a morphospecies and CATAMI (Althaus et al. 2015) level (Monk et al. 2016, James et al. 2017). This approach would be effective in choosing an initial suite of indicators for national level monitoring and reporting. 

    As a general guideline for full assemblage scoring, we recommend that 25 random points per image from at least 50 images per transect leg are a good starting point for recording most morphospecies present within images (based on Perkins et al. 2016). It is important to note that the properties of the organism themselves will also influence the number of points/images to score. Obviously morphospecies that are less abundant require more effort, but also the 'clumpiness' of species will affect the scoring effort needed (Perkins et al. 2016). Van Rein et al. (2011) and Perkins et al.  (2016) suggest that, while a higher number of points per image can increase the detection rate of more organisms within an image, increasing the number of scored images using fewer points is likely to have a similar (or greater) effect. Ideally, increasing both the number of images scored and the number of points scored within an image would result in greater power (Roelfsema et al. 2006), but preference is usually for increasing the number of images (Perkins et al. 2016). Unfortunately, the adoption of this approach is likely to result in substantial increases in processing time and thus cost. 

2. <span style="text-decoration:underline;">Targeted scoring of indicators or proxies </span>(such as grouping fine level morphospecies into broader level CATAMI classes). This approach has been shown to work very well at an indicator morphospecies level for detecting change at a regional level (Perkins et al. 2017) as well as for detecting invasive species trends (Perkins et al. 2015, Ling et al. 2016). More recently this approach has been extended to mobile species, such as fish (Seiler et al. 2012) and lobster (Bessell[ et al.](https://paperpile.com/c/ymogqX/oYPe), unpublished data). Care needs to be taken if length data (using photogrammetry or structure from motion) is extracted from stereo pairs as Seiler et al.(2012) found precision can be poor for mobile species if camera separation is inadequate (see Boutros et al. 2015).  

    Since this approach requires substantially less effort to score each image, more images (i.e. often all images) can be scored, thus increasing statistical power. The drawback is that a narrower understanding of the environment may result.



## Data curation and quality control

Data quality control at both the collection and annotation stage is critical. Most importantly, the annotation schema needs to be consistent between studies. Where possible morphospecies and associated CATAMI parent classes should be used _[Recommended]_. Clearly, other annotation schemas are available and can be applied. Where an alternative schema is used to annotate towed camera imagery, it is most important that it can be mapped to CATAMI so that comparisons can be made with previous studies or between regions. Translations between schema can be readily applied within Squidle +. Squidle+ has a built-in QAQC interface to ensure the consistency of annotations with exemplars managed by schema custodians. The quality control of all annotations undertaken by novice scorers should be assessed against an experienced analyst (e.g. using confusion matrices; see Figure 4.4 in Chapter 4). Logically, it is important to correct any discrepancies between annotators. This can be done by re-examining the images to ensure an agreement can be reached between annotators. Alternatively, if an agreement cannot be reached, then the miss-classified morphospecies could be potentially grouped into a higher level CATAMI class.

## Data release

[Squidle+](http://squidle.greybits.com.au/) is a centralised online platform for standardised analysis and annotation of georeferenced imagery and video. Many national marine observing programs (for example IMOS through the Australian Ocean Data Network (AODN), or the Marine Geoscience Data System (MGDS) in the USA) routinely store imagery data online in an openly accessible location. Squidle + operates based on flexible distributed data storage facilities (i.e. imagery can be stored anywhere in an openly accessible online location) to reduce data duplication and inconsistencies, and provides a flexible annotation system with the capability to translate between different annotation schemes.

Following the steps listed below will ensure the timely release of imagery and associated annotation data in a standardised, highly discoverable format.



54. Create a metadata record describing the data collection. Provide as much detail as possible on the deployment (either directly in the metadata record itself, or in the form of attached field sheets as .csv, .txt or similar). Details of minimum metadata requirements are provided in the On-board Data Storage section above. Publish metadata record(s) to the [Australian Ocean Data Network (AODN) catalogue](http://catalogue.aodn.org.au/geonetwork/srv/eng/main.home) as soon as possible after metadata has been QC-d. This can be done in one of two ways:
*   If metadata from your agency is regularly harvested by the AODN, follow agency-specific protocols for metadata and data release. 
*   Otherwise, metadata records can be created and submitted via the [AODN Data Submission Tool](https://metadataentry.aodn.org.au/submit). Note that user registration is required, but this is free and immediate. As of January 2024, this tool is under maintenance, and metadata submissions should be sent to info@aodn.org.au until it is again active.

    	Lodging metadata with AODN in advance of annotation data being available is an important step in documenting the methods and location of acquired imagery and enhancing future discoverability of the data.

55. Upload raw imagery from the survey to a secure, publicly accessible online repository ([contact AODN](mailto:info@aodn.org.au) if you require assistance in locating a suitable repository).
56. Create a [Squidle+](https://squidle.org/) campaign as soon as possible after imagery is uploaded, choose the most appropriate annotation schema, and commence annotation of imagery.
57. Add links to the location of the [Squidle+](https://squidle.org/) campaign to the previously published metadata record. You may also wish to attach or link a copy of the annotation data directly to the record.
58. Produce a technical or post-survey report documenting the purpose of the survey, sampling design, sampling locations, sampling equipment specifications, annotation schema (e.g. morphospecies, CATAMI, etc.), and any challenges or limitations encountered. Provide links to this report in all associated metadata _[Recommended]_

The workflow for the discoverability and accessibility of marine imagery from towed systems is still under development, with several issues related to long-term support and functionality pending (Przeslawski et al. 2019).


## Data analysis

The breadth of research questions precludes any detailed advice on the analysis of data from underwater towed camera transects. However, one common attribute of the image-based data that will have to be contended with for all analyses is spatial proximity. The closeness of images, within and sometimes between transects, means that image data are unlikely to be independent (due to spatial autocorrelation). Yet, this is an assumption that most statistical methods rely upon.  The failure to meet this assumption means that the inferences from the statistical analysis may be: (i) over-confident, e.g. having a p-value that is too small; (ii) biased, i.e. the estimates do not reflect the truth; (iii) both, or; (iv) no effect. Obviously, the fourth category is what a researcher hopes for, but it is improbable and must be validated. However, if it is known that the study organism exhibits particularly low autocorrelation at the scales of interest then the analysis need not consider it explicitly.

Methods to analyse data, accounting for autocorrelation are available.  These include geostatistical models (see Foster et al. 2012 for an AUV-based example) and other models that incorporate dependence (e.g. Foster et al. 2009). However, in certain situations subsampling images will help (e.g. Mitchell et al. 2017 for a marine based example), but not necessarily alleviate it completely. Further, if the study is for a broad area, where transects are small and are well-separated, then amalgamating data to transect level may also be appropriate. The potential for observer bias, vignetting, and intra and inter station variability should also be carefully considered. 
