# Lessons from Archives: Strategies for Collecting Sociocultural Data in Machine Learning

### Introduction
- "Haphazardly categorizing people in the data used to train ML models can harm
  vulnerable groups and propagate societal biases"
- "archives have institutional and procedural structures in place that regulate
  data collection, annotation, and preservation that ML can draw from"

**Archivism:**
- an institutional mission statement that defines the concepts or subgroups to
  collect data on
- full-time currators responsible for weighing the risks and benefits of
  gathering different types of data and theoretical frameworks for appraising
collected data
- codes of conduct/ethics and a professional framework for enforcing them
- standardized forms of documentation akin to what was proposed in Datasheets
  for Datasets


* community based activism to ensure various cultures are represented in the
  manner in which they would like to be seen
* data consortia for sharing data across institutions to reduce cost of labor
  and inrastructure


### WHAT ARE ARCHIVES?
**archives** - collections of materials, historical and current, systematically
stored for academic, scholarly, heritage, and legacy purposes; large-scale,
collective human record-keeping
* "An organization that collects the records of individuals, families, or other
  organizations" (308)
* institutional, governmental, foundational, research-oriented


- guidelines for how to label data
- collection and accessibility of private information
- sharing datasets across platforms
- critical reflections on diversity and inclusivity
- theory of appraisal and selection

### DIFFERENCES BETWEEN ARCHIVAL AND ML DATASETS
1. Level of intervention and supervision
- "In practice, data collection in significant ML subfields is done without
  following rigorous procedure or set of guidelines ... encourages data
  collection to be indiscriminate" (308)
2. Differing motivations and objectives
- ML datasets end goal == meeting or beating accuracy measures on defined tasks
  from training large models
- "Curatorial sets aim to preserve heritage and memory, educate and inform, and
  have historically tended to be concerned with authenticity, privacy and
  inclusivity, and rarity of sources" (308)

**laissez-fair collection** - "wild west"; lack of systematic process for
generating datasets; ML data collection

**interventionist collection** - curatorial; see above


### NEED FOR INTERVENTIONIST COLLECTION
- "datasets composed without an adequate degree of intervention will replicate
  biases accrued from multiple levels of filtering" (309)
- "before collection, data are subject to two levels of bias - historical and
  representational" (309)

**historical biases** - structural, empirical inequities inherent to society
that is reflected in the data; "ML datasets produce derivatives and outcomes
that reflect these biases" (309)

**representational biases** - comes from the divergence between the true
distribution and digitized input space; can result from uneven access to digital
tools or sociocultural constraints that prevent digitization or preservation;
bias the availability of certain types of data
- "Common sources of natural human language in NLP include crowdsourced material
  such as Twitter text or data from public platform sites ... Taken without
  intervention, these datasets suffer from ... sources of biases" (309)
    - reflect a certain demographic composition: overrepresent age/location
      demographic

**'natural' datasets** - crawled from the internet; (FlickR images, crowdsourced
Twitter/public platform text
- "Taken without intervention, these datasets suffer from above sources of
  biases"
- "materials found on the internet reflect a certain demographic composition"


### LESSONS FROM ARCHIVES

#### Inclusivity
- "Inclusivity has become an issue in ML because data collection practices have
  not been driven by agenda that prioritizes fair representation or diversity,
rather by tasks or convenience"
- "source-based datasets, where collection methods or questions are defined by
  the availability of datasets ... produces biased data ... and replicates these
biases in models"


**mission statement** - "data collection in archives starts with a statement of
commitment to collecting the cultural remains of certain concepts, topics or
demographic groups"
- "Data collection driven by concepts is more costly and time consuming. It
  necessitates domain expertise ... and exploration" 
- "Announcing public Mission Statements also allows datasets to be open to
  continuous contributions. Researchers can update datasets based on changing
sociocultural norms" *


#### Consent
- "crowdsourcing has emerged as a staple approach in collecting human labels for
  datasets aimed to reduce cost and speed up data collection by outsourcing to
human participants" 
- "ML researchers without sufficient domain knowledge of minority groups
  frequently miscategorize data, imposing undesirable or even detrimental labels
onto groups" 


**community archives** - open for public input, democratize the collection
process, give agency to minority groups to represent themselves ... add
diversity to historical records


#### Power

**consortia models** - increase parity in data ownership; institutional
frameworks and services to share resources and collectively store and distribute
holdings 
- "Groups of libraries can make expensive purchases such as subscriptions to
  academic journals, pool resources for large scale projects ... and reduce
technological overhead costs ... also ... reduce redundant collections, instead
focusing on increasing the size of unique collections"


#### Transparency 
- "Transparency and accountability form central tenets of archival ethics" 
- "archives abide by rigorous record-keeping standards, enhancing not only
  transparency but also effective operations with other institutions"

**Three categories of standards to communicate holdings consistent across
institutions:**

1. data content (content, order and syntax of data)
2. data structure (organization of data)
3. data value (terms used to describe data)


"archives also record the process of data collection ... keep records of the
decisions and evaluations of the appraisal flow"


#### Ethics & Privacy
- "Standards, regardless of importance, become more difficult to implement as
  objectives move farther from final market transactions and ethical practices
in data collection are often overlooked for their distance from the end-product"
- "promoting full-time employment in data collection will introduce means of
  raising incentives for data collectors to comply by ethical standards"
- "establishing cross-institutional organizations that lie above direct
  employers can help ensure that ethical principles withstand profit-driven
motives"

### TWO LEVELS OF ACTIONABLES
- macro == community/private institutions/policymakers/government organizations
    - develop consortia
    - establish organizations to enforce ethical guidelines
    - support community archives
    - develop dedicated data collection/annotation processes
- micro == individual researchers/practitioners/administrators
    - define mission statements
    - hire full-time data collectors 
    - work towards public datasets
    - adopt documentation standards
    - develop substantial collection development policies
    - make informed committee decisions


