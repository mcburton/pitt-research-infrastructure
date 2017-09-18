# Research Computing Infrastructure @ Pitt
This document is trying to inventory all of the research computing infrastructure (and services) available to Pitt researchers. It is currently organized by the organization that owns the resource, but should eventually be articulated as a kind of decision tree or narrative with various categories of things (computing, services, expertise, etc.).

## Use Cases

### Basic Website

* Needs a website for their personal profile, a research project, or a course.
* Wants a domain name to point to a website
* Wordpress, static site, basic pup
* Can be satisfied with EWI?

### Web Applications

* Needs a web application for research project, course, or service
* Complex website with custom front end/backend requirements,  
* Database backed website, API, web application
* Needs reflect the problems cloud computing solves
* Needs span from web frameworks (like heroku) to virtual machines (containers?)
* examples would be science gatewayss

### Low and Slow Data Collection

* Needs a long-running server for data collection, web scraping, polling an API
* No front-end, only back-end. Low to medium compute needs, but might be high network requirements (especially for web crawling/scraping)
* Examples would be the ongoing collection of social media data, scraping or archiving websites, polling rate-limited APIs

### Moving Big Data
* Large scale data needs to move locations
* Low computational, but very heavy network and data storage requirements
* Examples are moving data from collection/generation point to analysis location

### Data Science
* Needs to perform computational analysis, but also data cleaning and preparation. 
* Computing needs are moderate, might include any size of data
* Interactive, non-scheduled compute. especially for cleaning.
* Data visualization, machine leaning, 
* Uses industry-centric data science tools (Jupyter, Hadoop, Spark, RStudio, etc.)

### High Performance Computing
* Needs a lot of computational power for simulations or data processing
* HPC toolchains and architecture
* 


## Current Resources at Pitt

### CRC
The Center for Research Computing provides high performance computing infrastructure and services to Pitt researchers. 

The focus of the CRC documentation is on hardware offerings. There is little discussion of what you can *do* with their infrastructure, it is assumed you already know.

#### Services

* JupyterHub - no documentation
* Consultation - no explicit documentation that I can find (there is a sentence tucked away on [this page](CRC interfaces directly with researchers and provides software installation services, training workshops, and personalized consultation on improving software design/performance and computational workflows.) talking about “CRC interfaces directly with researchers and provides software installation services, training workshops, and personalized consultation on improving software design/performance and computational workflows.”
* Workshops - https://crc.pitt.edu/2017/08/24/crc-fall-2017-tutorial-announcement/
* CLC Bio? - http://core.sam.pitt.edu/CLCBioServer
* [Galaxy Server instance](https://galaxyproject.org) - http://core.sam.pitt.edu/galaxy



#### Systems & Infrastructure
* HPC Clusters & Storage - https://crc.pitt.edu/documentation/overview-to-crc-resources/
* 

#### Access & Information
* Application process - https://crc.pitt.edu/documentation/allocations-proposals-and-service-units/
* Apply for allocation - https://crc.pitt.edu/apply/
* There is a pile of information on the CORE website - http://core.sam.pitt.edu

### CSSD

#### Services
* Lab notebooks
* Box for Research
* Elements
* Lynda.com
* FISMA zone
* Store Simple (coming)
* Azure for Research (Coming)
* Accounts, MFA, Credentials, Identity

#### Systems & Infrastructure
* EWI Lite / EWI Pro
* Science DMZ 
* Research clusters at the NOC
* High speed data transfer
* Research Firewall zone


#### Access
* Submit tickets?


### University Library System

#### Services
* Research Data Management
* Consultation
* Workshop series

#### Systems & Infrastructure
* ???

#### Access
* Visit Library
* Make appointment with Digital Scholarship Services

### Beyond

* PSC initiative - https://www.psc.edu/prcinitiative
* XSEDE - https://www.xsede.org/
