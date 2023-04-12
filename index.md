## The Waste Impact Calculator project and its repositories

The Waste Impact Calculator (WIC) is a framework for estimating the life cycle environmental impacts associated with solid waste materials and treatments, and projecting the impact consequences of solid waste management decisions (e.g. comparing waste prevention to recycling).  While it was created with the needs of the Oregon Department of Environmental Quality in mind, it should be relevant to many other parties interested in materials, waste, and waste management.

WIC may be expressed in many ways.  At the most basic level it helps you contrast the weight and impacts of materials, for example:

![a screenshot comparing weight to impacts](wic-screenshot.png)

The [Waste Impact Calculator web app](https://rstudioconnect.deq.state.or.us/content/706a4deb-f353-4d08-826d-85bf7856c154) is a good place to start.  It includes:

* a video introduction to the WIC framework (on the landing page)
* a detailed presentation of the life cycle impacts of solid waste from Oregon counties and the USA as a whole.

More formal documentation can be found in these resources:
* *[Technical Overview of the Waste Impact Calculator](https://github.com/OR-Dept-Environmental-Quality/wic-base/blob/main/documentation/technical-overview-of-the-wic.pdf)* provides a thorough explication of the rationale for and approach behind WIC.
* *[Impact modeling for the Waste Impact Calculator](https://github.com/OR-Dept-Environmental-Quality/wic-base/blob/main/documentation/impact-modeling-for-the-wic.pdf)* describes details of life cycle modeling for individual materials.
* *[Example applications of the Waste Impact Calculator](https://github.com/OR-Dept-Environmental-Quality/wic-base/blob/main/documentation/example-applications-of-the-wic.pdf)* contains a fully fleshed out and documented example analysis.
* [This talk for the American Center For Life Cycle Assessment](https://youtu.be/Turv-Mpnf4g) introduces WIC for life cycle professionals.


### WIC repositories

WIC project work occurs in several repos, listed below. Some of these are still works in progress.  Official releases will (eventually) be available for download within each repo.

* [wic-data](https://github.com/OR-Dept-Environmental-Quality/wic-data) -- Most users will be interested in this.  The repo contains an installable R package containing impact factors and example datasets for using the Waste Impact Calculator framework. Help files contain links to documentation, including worked examples.
* [wic-base](https://github.com/OR-Dept-Environmental-Quality/wic-base) -- The fundamental data and processing behind the material in *wic-data*.  Includes detailed documentation on life cycle impact modeling for individual materials.
* wic-wastesheds -- compilation and creation of weight-based solid waste profiles Oregon, Oregon's counties, and the United States as a whole, under 3 management scenarios related for recycling rates.  These scenarios are applied in the Waste Impact Calculator web app (the wic-app repository, see below).
* wic-app -- a shiny app featuring solid waste weights and impacts for Oregon, Oregon's counties, and the United States as a whole.
* wic-eyo -- a shiny app allowing the user to enter their own data, and produce results similar to those produced by wic-app.

### Technical review

The life cycle impact modeling work for WIC releases tagged 1.0 was reviewed by an independent technical authority, Dr. Christoph Koffler of [Sphera](https://sphera.com/).  The reviewer's comments can be found in the documentation folder of the [wic-base](https://github.com/OR-Dept-Environmental-Quality/wic-base) repo.  Releases after 1.0 contain new features and data, bug fixes, and improved documentation and examples, so they should not substantially affect the relevance of the reviewer's comments.

### Contact the authors

* [Martin J. Brown](https://github.com/DEQmbrown2) 
* [Peter Canepa](https://github.com/DEQpcanepa)
