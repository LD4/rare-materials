# RMAG profiles
The RMAG profiles are a set of proof of concept BIBFRAME templates for description of rare materials. They are intended to help catalogers gain hands-on experience in linked data cataloging and template creation, and to inform the further development of ARM and other linked data standards and practices. The modeling the RMAG profiles is derived from our choice of plaform and standards:

* [BIBFRAME model](https://www.loc.gov/bibframe/docs/bibframe2-model.html)
* Program for Cooperative Cataloging BF2 Sinopia  Profiles
* [Art & Rare Materials (ARM) ontology extension](https://github.com/Art-and-Rare-Materials-BF-Ext/arm/tree/main/v1.0)
* [DCRMR: Descriptive Cataloging of Rare Materials (RDA Edition)](https://rbms.info/dcrm/dcrmr/)
* [Sinopia](https://github.com/LD4P/sinopia/wiki/Ontology-and-vocabulary-support-and-BIBFRAME-optimization)

Currently, the RMAG Profiles Working Group is focusing on the development of an RMAG Profiles for **Item** level description. Subsequent work will address Profiles for the descripton of rare materials at the **Work** and **Instance** level.

## Testing the resource templates

The templates are openly available in the linked data editor Sinopia ([Stage environment](https://stage.sinopia.io/)). The Sinopia [Wiki](https://github.com/LD4P/sinopia/wiki) includes good information about creating a user account and working in Sinopia. Click on any of the links below to access the appropriate template and feel free to to test it out!

### Main resource templates

*These resource templates correspond to the main BIBFRAME entities.*

* RMAG Item ([RMAG:RT:ARM:Item](https://stage.sinopia.io/editor/RMAG:RT:ARM:Item))
* RMAG Instance  (comming soon)
* RMAG Work  (comming soon)

### Auxiliar resource templates

*These auxiliar templates support further detail in the description of those entities. Auxiliar templates are embeded on the main templates.*

* RMAG Citation (ARM) ([RMAG:RT:ARM:Citation](https://stage.sinopia.io/editor/RMAG:RT:ARM:Citation))
* RMAG Enclosure (ARM) ([RMAG:RT:ARM:Enclosure](https://stage.sinopia.io/editor/RMAG:RT:ARM:Enclosure)) - **includes bindings*
* RMAG Item History (ARM) ([RMAG:RT:ARM:ItemHistory](https://stage.sinopia.io/editor/RMAG:RT:ARM:ItemHistory))
* RMAG Marking (ARM) ([RMAG:RT:ARM:Marking](https://stage.sinopia.io/editor/RMAG:RT:ARM:Marking))
* RMAG Measurement Group (ARM) ([RMAG:RT:ARM:MeasurementGroup](https://stage.sinopia.io/editor/RMAG:RT:ARM:MeasurementGroup))
* RMAG Note (ARM) ([RMAG:RT:ARM:Note](https://stage.sinopia.io/editor/RMAG:RT:ARM:Note))
* RMAG Pagination Foliation (ARM) ([RMAG:RT:ARM:PaginationFoliation](https://stage.sinopia.io/editor/RMAG:RT:ARM:PaginationFoliation))
* RMAG Physical Condition (ARM) ([RMAG:RT:ARM:PhysicalCondition](https://stage.sinopia.io/editor/RMAG:RT:ARM:PhysicalCondition))
* RMAG Signature Statement (ARM) ([RMAG:RT:ARM:SignatureStatement](https://stage.sinopia.io/editor/RMAG:RT:ARM:SignatureStatement))

## Community feedback

While the RMAG templates are still under development, we welcome feedback from the rare materials cataloging community. Use this form to share your thoughts, questions or concerns: 

***[RMAG Templates Feedback Form](https://forms.gle/KQkYnLkyJjRhRM9Q9)**

We also welcome community input regarding a series of standing questions around modelling decissions:

***[Modelling Questions for Feedback](https://docs.google.com/spreadsheets/d/1o0wk36IR8LWQYhFfQwZkw_hvxGLmLpc6hSvXIlDSKtg/edit?usp=sharing)**

Thanks for your feedback!

## Notes about the process

In June 2022, the LD4 Rare Materials Affinity Group launched a survey to gauge the broad community input regarding modelling linked data templates for the descriptoin of rare materials. The survey was distributed on RMAG, DCRM-L, BIBFRAME and LD4 lists. Work on the resource templates started on August 2022 with the formation of the RMAG Profiles Working Group.  

The RMAG resource templates are based on the PCC BIBFRAME profiles and include all the classes of the ARM ontology extension v1.0 relevant to the description of rare books. These templates are a work in process and are subject to change, specially as they get tested by the community and feedback is provided. 

Progess on template development and standing modelling questions can be followed up on the [RMAG Profiles Development Tracking](https://docs.google.com/spreadsheets/d/1NwL6oDXh8qtCRPy5B42_PhRJcrrYrEKXF8C2Lm49K74/edit?usp=sharing) Spreadsheet.

The RMAG Profiles Working Group is working in coordination with the RBMS Bibliographic Standards Committee Linked Data Implementation Steering Group, however the templates themselves have not been vetted by the RBMS Bibliographic Standards Committee, the Program for Cooperative Cataloging, or any other standards body.

## Contact
For questions about the RMAG Profiles Working Group reach out to the [RMAG conveners](https://github.com/LD4/rare-materials#approach).
