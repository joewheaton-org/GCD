---
title: Geomorphic Change Detection
---

![customLogo]({{ site.baseurl }}/assets/images/customLogo.png)

Welcome to the GCD Software website. Here you will find [downloads](http://gcd.joewheaton.org/downloads), help and background on the GCD software. GCD 6 is currently under development and will be released in late April, 2014.

## Background

The GCD software was developed primarily for [morphological sediment budgeting](http://sites.google.com/a/joewheaton.org/www/Home/research/projects-1/morphological-sediment-budgeting) in rivers. The volumetric change in storage is calculated from the difference in surface elevations from digital elevation models (DEMs) derived from repeat topographic surveys. As each DEM has an uncertain surface representation (which might vary in space and time), our ability to detect changes between surveys is highly dependent on surface representation uncertainties inherent in the individual DEMs. The fundamental problem is separating out the changes between the surveys that are due to geomorphic change as opposed to noise in the survey data. GCD provides a suite of tools for quantifying those uncertainties independently in each DEM and propagating them through to the DEM of difference. The program also provides ways for segregating the best estimates of change spatially using different types of masks. The overall suite of tools is more generically applicable to many different spatial raster-based change detection problems.

The methodological development is described in ([Wheaton et al., 2010](http://dx.doi.org/10.1002/esp.1886)a), the Wheaton ([2008](http://sites.google.com/a/joewheaton.org/www/Home/research/projects-1/morphological-sediment-budgeting/phdthesis)) thesis, and the Wheaton et al. ([2010b](http://dx.doi.org/10.1002/rra.1305)) RRA paper. The [Matlab version of the code](http://gcd.joewheaton.org/downloads/older-versions/dod-3-0) (DoD 3) is provided as supplemental information with the [ESPL paper ](http://dx.doi.org/10.1002/esp.1886)so that readers can test or extend the code as they see fit for their purposes.

## Funding

Current funding for the Geomorphic Change Detection Software development (GCD 6) is being provided by:

- The National Science Foundation (Geoinformatics: [Award #1226127](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1226127) - '[Making Point Clouds Useful for Earth Science'](http://etal.joewheaton.org/projects/current-projects/development-of-integrated-airborne-and-ground-based-lidar-tools-for-earth-sciences))  - [ZCloudTools](http://zcloudtools.boisestate.edu/)
- Idaho Power Company
- Bonneville Power Administration via [Eco Logical Research](http://ecologicalresearch.net/)

![nsf1]({{ site.baseurl }}/assets/images/nsf1.gif)

![ELRLogo]({{ site.baseurl }}/assets/images/ELRLogo.png)

![bpaTransparent]({{ site.baseurl }}/assets/images/bpaTransparent.png)

![IPC_GreenOnTransparent]({{ site.baseurl }}/assets/images/IPC_GreenOnTransparent.png)

Previous funding for GCD Software Development was provided by 

- The USGS's [Grand Canyon Monitoring & Research Center](http://www.gcmrc.gov/gcmrc.aspx)  
- The [US Army Corps of Engineers Kansas City District](http://www.nwk.usace.army.mil/)
- Utah State University [ICRRR](https://www.cnr.usu.edu/icrrr/) (Intermountain Center for River Rehabilitation and Restoration)

[![http://www.gcmrc.gov/gcmrc.aspx](http://gcd.joewheaton.org/_/rsrc/1468741653880/home/USGS_logo.png?height=73&width=200)](http://www.gcmrc.gov/gcmrc.aspx)       [![http://www.nwk.usace.army.mil/](http://gcd.joewheaton.org/_/rsrc/1468741653879/home/612px-US-ArmyCorpsOfEngineers-Logo.svg.png?height=153&width=200)](http://www.nwk.usace.army.mil/)    [![https://www.cnr.usu.edu/icrrr/](http://gcd.joewheaton.org/_/rsrc/1468741653880/home/ICRR_Logo.png)](https://www.cnr.usu.edu/icrrr/)

## Software Development

The GCD Software was originally developed by [Joe Wheaton](http://www.joewheaton.org/) ([Utah State University Department of Watershed Sciences](http://www.cnr.usu.edu/wats/)) and [James Brasington](http://www.reesscan.org/meet-the-team/brasington) ([Queen Mary University](http://www.geog.qmul.ac.uk/staff/brasingtonj.html)). The newest version of the GCD is currently under development by [North Arrow Research](http://northarrowresearch.com/) and [ET-AL](http://etal.joewheaton.org/). The current development team consists of [Philip Bailey](http://www.essa.com/team/index.html#pb) ([North Arrow Research](http://northarrowresearch.com/)), [James Hensleigh](http://etal.joewheaton.org/people/researchers-technicians/james-hensleigh) (USU), Matt Reimer ([North Arrow Research](http://northarrowresearch.com/)),  and Joe Wheaton (USU). [Nick Ochosk](http://www.essa.com/team/index.html#no)i ([ESSA](http://www.essa.com/)) and [Frank Poulsen](http://www.essa.com/team/index.html#fp) ([ESSA](http://www.essa.com/)) were instrumental in the initial development of GCD 5. [ESSA ](http://gcd.joewheaton.org/goog_535400767)[Technologies](http://essa.com/) generously invested in kind donations of development time in GCD 5 development.  [Chris Garrard ](http://www.gis.usu.edu/~chrisg/)(USU [RSGIS Lab](http://www.gis.usu.edu/)) was the primary developer of GCD 4.

[![img](http://gcd.joewheaton.org/_/rsrc/1468741653880/home/NA_Logo_150pxTall.png)](http://northarrowresearch.com/)         [![essa.com](http://gcd.joewheaton.org/_/rsrc/1468741653879/home/ESSATechnologies_500x500.png?height=198&width=200) ](http://essa.com/)

[![Ecogeomorphology & Topographic Analysis Laboratory2-05]({{ site.baseurl }}/assets/images/Ecogeomorphology & Topographic Analysis Laboratory2-05.png)](http://etal.joewheaton.org)



We are indebted to many helpful and patient Beta Testers, including all the participants of the GCD Workshops, Sara Bangen, Rocko Brown, Nicole Czarnomski, Kenny DeMeurichy, Paul Grams, Alan Kasprak, Eric Larson, Ryan Leary, Chuck Podolack, Robert Ross, Keelin Schaffrath, and Cara Walter. 

## What's Next

GCD 6 is currently in development. See [Extending GCD  Software](http://gcd.joewheaton.org/extending-gcd-software) for latest developments (GCD 6).

#### Note:

DoD is an acronym for DEM (digital elevation model) of Difference (not Department of Defense). DoDs are derived from repeat topographic surveys and used in change detection studies and [morphological sediment budgeting](http://www.joewheaton.org/Home/research/projects-1/morphological-sediment-budgeting).

GCD Software by [ET-AL](http://gcd.joewheaton.org/gcd.joewheaton.org) is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

