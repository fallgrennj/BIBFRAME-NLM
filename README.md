##Experimentation with BIBFRAME at the National Library of Medicine

####June 24, 2015, update

In order to demonstrate possible cataloging applications of a modular approach to BIBFRAME (BF), NLM prepared a supplementary spreadsheet mapping the PCC RDA BIBCO Standard Record Metadata Application Profile (BSR, as of April 14, 2015), BF Lite (as of June 8, 2015) and RDA RDF (as of June 23, 2015) properties, and then used that spreadsheet to manually create examples of original PCC- compliant cataloging.

Knowing that many libraries are following PCC cataloging guidelines, NLM identified all the required elements related to modern print monographs in the BSR and mapped each element to a corresponding BF Lite property and to a corresponding RDA RDF property. In cases where the BF Lite property is broader than the BSR element, NLM mapped the BSR element both to BF Lite and to a more specific property or several more specific properties in other schema.  Where no BF Lite property is available, NLM identified other properties that could be used, mainly from Zepheira’s BF extended vocabularies.  

Using the mappings in the spreadsheet, NLM manually created examples of BF descriptions for two print monographs that would meet the PCC BSR standards, using BF Lite where possible and extensions as needed. There are two mockups for each resource. The first mockup provides extensions in other schema when there is no BF Lite property available.  The second mockup provides supplementary extensions in cases where the BF Lite property maps to more specific properties in other schema. NLM recognizes that there are other mapping possibilities than those we have chosen for these mockups.

####Links

Spreadsheet: Comparison Chart of BSRCore to BF Lite
https://docs.google.com/spreadsheets/d/1i91zJqd8Y6IGTiMoKi2KgkD_7x9ZfstCZvLXvGUEph0/edit?usp=sharing 

Mockup:  Fifteen Minute Hour
https://docs.google.com/document/d/1N9Xrjc52_Z2VlHVuutvERUl7NW9PzwvV3iRAyjnoQj0/edit?usp=sharing 

Mockup:  Workshop on Artificial Ecological Systems
https://docs.google.com/document/d/1ObWV5W0r3VisGpPArBNzMSPnIC5hxyur5IBeXYHVDp8/edit?usp=sharing   

  
  
  
  
    
####June 12, 2015

In November 2014, the National Library of Medicine (NLM) announced that it was taking a different approach to BIBFRAME (BF) experimentation (see [NLM’s Early Implementers registration](http://www.loc.gov/bibframe/implementation/register.html)).  This new approach involved development of a core, widely shareable BF vocabulary that could be extended for greater granularity with existing descriptive schema.   In pursuit of this goal, NLM has been collaborating with Zepheira, George Washington University (GWU), and University of California, Davis (UCD) in development of the [BF Lite vocabulary](http://bibfra.me), as hosted by Zepheira.   Part of the perspective NLM brings to this collaboration is a focus on creating new cataloging data directly in BF rather than converting legacy bibliographic data.  

The scope of NLM’s work on BF development to date has been deliberately narrow in order to keep short term goals modest and achievable.  NLM and GWU produced a spreadsheet that correlated BF Lite with PCC RDA BIBCO Standard Record (BSR) elements and RDA RDF properties.  The broader group of collaborators used that spreadsheet as a starting point for discussion, evolving it to a static snapshot (as of 6/8/2015) of a portion of the BF Lite core vocabulary.  This resulting [spreadsheet](https://docs.google.com/spreadsheets/d/1QM8X4qHd-D6ogftRHywBwIvKGyMa_5Kp3YgNEsv7KpU/edit?usp=sharing) includes BF Lite properties and classes that expand beyond the BSR elements, but that NLM and GWU believe are appropriate for cataloging print monographs.  In contrast, the BF Lite vocabulary on http://bibfra.me continues to evolve and it includes properties and classes that are applicable more broadly than print monographs.  

To demonstrate how the BF Lite core vocabulary in the spreadsheet can be applied, NLM and GWU manually produced two mockups of original BF cataloging using that vocabulary with extensions from other schema.  Each mockup provides two examples of cataloging a print monograph using BF Lite with a modular approach: one extends BF Lite mainly with Zepheira’s BF extended vocabularies and the other extends BF Lite mainly with RDA RDF properties. These mockups are available on Google Drive: [The myth of the addicted army](https://docs.google.com/document/d/10jhz0P2bN_d_WZPmKDwhvQSDKrVvU99RWGiinKP6NUc/edit?usp=sharing) and [The contributions of Rudolph Virchow](https://docs.google.com/document/d/1WNcOy56l6f1vswWCa4PTBvkjoSDo2T2U3cj69moYwX8/edit?usp=sharing).  

It is our hope and expectation that both the spreadsheet and the BF Lite core vocabulary will be used by the community for experimentation, so that BF can evolve and develop in a tested, community driven manner.  NLM believes that BF development is still fluid and should evolve through thoughtful vetting and testing, with emphasis on creating new data rather than converting legacy data.  

####Background and Scope  

NLM has been involved in development of the BIBFRAME model and vocabulary since the beginning of the Bibliographic Framework Initiative in 2012.   

One of the original goals of BF was to develop a rule agnostic framework that is usable and useful to the wider cultural heritage community and supports linked data on the Web.  NLM envisions a modular BF structure that includes a widely shareable, core vocabulary incorporating descriptive elements from across the cultural heritage community. This common set of BF properties should be extended with properties from other community-specific descriptive schema, such as MODS RDF, RDA RDF, PRESSoo, VRA Core, et al.   

Early in discussions about developing a modular approach to BF, NLM learned that Zepheira shared a similar approach and was developing a core set of BF vocabulary elements, called BF Lite.  NLM and Zepheira agreed to collaborate on BF Lite, and through related collaborative efforts, representatives from GWU and UCD were added to the BF Lite collaborative team.    

####Methodology
Zepheira initially developed BF Lite through a comparison of five descriptive schema; any properties appearing in at least three of those five schema were retained as part of the BF Lite vocabulary.  With our initial project limited to print monographs, NLM compared Zepheira’s BF Lite vocabulary with PCC/RDA BIBCO Standard Record (BSR) elements and RDA RDF properties.  As part of this process, we continually questioned whether the BSR elements might be useful to other communities.  NLM and GWU then offered suggestions for changes to BF Lite.  Representatives from NLM, GWU, UCD, and Zepheira deliberated those suggestions and implemented changes and additions to BF Lite classes and properties upon agreement.   

The group also revised or added many new BF Lite definitions.  Sometimes we retained the original BF Lite definition; however, more often we reviewed and pulled definitions from elsewhere, including RDA RDF, LC’s BF vocabulary, MODS RDF, Schema.org, W3C, and the dictionary. Occasionally the final definition is a mashup from several of these sources.  In general, the definitions are deliberately broad so as not to proscribe mapping between different descriptive schema from a variety of communities. 
Development of the core vocabulary was also influenced by data modeling concerns. First and foremost, NLM’s data modeling focus is on extensibility and flexibility; however, we also had to consider usability and scalability.  In some cases this resulted in compromises that might favor choosing scalability over flexibility.    

The spreadsheet that resulted from this collaboration (and is being made publicly available) maps BF Lite primarily to the RDA RDF constrained vocabulary. Our hope is that using the constrained RDA RDF properties will facilitate application of BF Lite in an RDA cataloging environment, as well as round tripping back to RDA if desired.  We could not always make direct mappings between the BF and RDA models because they differ; therefore, we mapped RDA Expression properties to either BF Work or BF Instance as we believe appropriate.  Where an RDA RDF property seemed applicable to an RDA class for which it is not defined, we mapped the BF property to an unconstrained RDA RDF property.     

The worksheets for Work and Instance include not only the BF Lite properties for those Classes, but also certain properties of other BF Lite Classes that are likely to be used in cataloging a print monograph.   The remaining worksheets represent other BF Lite Classes (and their properties), which are referenced in the Work and Instance worksheets.    

The experimental BF vocabulary and mappings being publicly released are not complete or final, but rather a starting point.  The collaborative effort has initially focused on describing only print monographs and the model does not yet address items, holdings, and annotations.  However, we believe our efforts have produced a vocabulary sufficient to test the theory that a BF vocabulary built from a core of widely shareable properties provides flexibility and extensibility for describing diverse resources. If the library community adopts this modular approach, we hope that BF will be vetted and improved upon iteratively with input from multiple communities.  

####Further Experimentation  

To date, the library community’s BF experimentation has largely focused on MARC to BIBFRAME conversion. NLM is concerned that if BF is too closely aligned with the existing MARC structure it will be less attractive to other communities and less open to new ways of visualizing and presenting bibliographic data.  Therefore, NLM intends to produce a small set of bibliographic data for previously uncataloged print monographs using the BF Lite vocabulary, plus extensions. We expect to use cataloging tools being developed as part of UCD’s BIBFLOW project and will make our resulting data and findings available to the community.  

We hope that our pilot using the BF Lite vocabulary will demonstrate proof-of-concept of a modular approach to BF, and perhaps provide a starting point for a commonly agreed upon set of BF properties. NLM has discussed these plans with the Library of Congress (LC) and will continue to collaborate with LC on further development of the BF model. NLM’s pilot is intended to take place within the same time frame as LC’s upcoming pilot, and NLM expects that our BF development efforts will converge in the future.  

####Feedback 
NLM welcomes community feedback about our experimentation. We request that you post all comments, issues, and questions in this GitHub repository.  There is no login required to view the spreadsheet and mockups on Google Drive or to view comments and issues in the BIBFRAME-NLM repository; however, you will need to create a GitHub username and password to contribute comments, issues, or questions.  When contributing comments, issues, or questions, please apply the appropriate labels indicating what you are commenting on, e.g., the spreadsheet, the mockups, etc.   

####Links

BF Lite core spreadsheet  
https://docs.google.com/spreadsheets/d/1QM8X4qHd-D6ogftRHywBwIvKGyMa_5Kp3YgNEsv7KpU/edit?usp=sharing   

BF Lite  
http://bibfra.me  

Mockup: The contributions of Rudolph Virchow  
https://docs.google.com/document/d/1WNcOy56l6f1vswWCa4PTBvkjoSDo2T2U3cj69moYwX8/edit?usp=sharing  

Mockup: The myth of the addicted army  
https://docs.google.com/document/d/10jhz0P2bN_d_WZPmKDwhvQSDKrVvU99RWGiinKP6NUc/edit?usp=sharing   

Library of Congress BIBFRAME Implementation Register  
http://www.loc.gov/bibframe/implementation/register.html  

