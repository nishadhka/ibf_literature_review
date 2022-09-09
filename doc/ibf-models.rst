Impact Based Forecasting Models
===============================

IBF model combines the components such as 1. data collection on exposure and vulnerability, past impact profile 2. Hazard forecasting, involves weather and climate model output, ensemble forecast output the first three components and produce impact forecast.

IBF models can be divided into two broad classes of frameworks based on time of forecast generation, event triggered forecasting system or pre event impact estimates. IBF systems are event triggered frameworks and Catastrophic models are pre event impact estimates framework 

Can be classed as follows,

IBF Workflow systems
---------------------

IRI Climate Data Library for map room on Drought hazard IBF and 

#. https://iridl.ldeo.columbia.edu/fbfmaproom2/djibouti

Data Science team at Netherland Red Cross has IBF system for following hazard types. The system follows, Trigger, manage and execute RCRC Early Action Protocols (EAP) for natural disasters. 

#. Flood, https://github.com/rodekruis/IBF_FLOOD_PIPELINE
#. Tropical cyclone, https://github.com/rodekruis/Typhoon-Impact-based-forecasting-model
#. Dengue, https://github.com/rodekruis/IBF-dengue-model

Catastrophic models
--------------------

Insurance industry uses catastrophic models to predict the loss due to catastrophic events, especially the natural hazards focused with IBF. Cat models which acts as the pre event impact estimates, has well developed tools and data standards improved upon its long usage in Insurance industry. Cat models also provides open data standards and schemas which can be used in IBF context 

Oasis Loss Modelling Framework
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
A open source framework for creating catastrophic model. https://github.com/OasisLmf. Which gives tools for model development kit for Oasis cat model https://github.com/OasisLMF/OasisLMF and open data standards for producing model input data https://github.com/OasisLMF/OpenDataStandards. Which provides format for defining exposure data and hazard impact data through Open Exposure Data (OED) format and the Open Results Data (ORD) format

Global Facility for Disaster Reduction and Recovery (GFDRR)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
GFDRR which provides Risk Data Library Standard (RDLS) https://docs.riskdatalibrary.org/ for to organize disaster and climate risk data. It has common data schemas to be used and produced in risk assessment such as hazard, exposure, vulnerability and modeled loss. 

Introduction to cat models, oasis and open data standards can be found

#. Oasis- Oasis LMF Webinar 1: Fundamentals of Catastrophe Modelling and Exposure Data https://www.youtube.com/watch?v=OCRG0q2UVAs
#. Building Catastrophe Models With Open Data And Open Software https://www.youtube.com/watch?v=a3c1E6m3egk


Further reads on Catastrophic models on Flood forecast impact
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. Accessing Insurance Flood Losses Using a Catastrophe Model and Climate Change Scenarios :footcite:t:`palan_accessing_2022`

Probabilistic risk modeling - Climada
--------------------------------------

Climada impact modeling framework gives open source tools for multi hazard impact model development tool. https://wcr.ethz.ch/research/climada.html. Which has probabilistic modeling facility for impact forecast through historic and probabilistic event sets for all major hazard types, data API for major climate related extreme weather hazard at high resolution.  


Further reads on Climada related papers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. Strengthening climate-resilient development and transformation in Viet Nam, :footcite:t:`rana_strengthening_2022`
#. Comparing an insurer's perspective on building damages with modelled damages from pan-European winter windstorm event sets: a case study from Zurich, Switzerland :footcite:t:`welker_comparing_2021`
#. Climate signals in river flood damages emerge under sound regional disaggregation :footcite:t:`sauer_climate_2021`
#. Global warming and population change both heighten future risk of human displacement due to river floods :footcite:t:`kam_global_2021`
#. Double benefit of limiting global warming for tropical cyclone exposure :footcite:t:`geiger_double_2021`
#. Regional tropical cyclone impact functions for globally consistent risk assessments :footcite:t:`eberenz_regional_2021`
#. Addressing the human cost in a changing climate :footcite:t:`desai_addressing_2021`
#. A framework for building climate storylines based on downward counterfactuals: The case of the European Union Solidarity fund :footcite:t:`ciullo_framework_2021`
#. CLIMADA v1.4.1: towards a globally consistent adaptation options appraisal tool :footcite:t:`bresch_climada_2021`
#. Be Prepared: Exploring Future Climate-Related Risk for Residential and Commercial Real Estate Portfolios :footcite:t:`westcott_be_2020`
#. Asset exposure data for global physical risk assessment :footcite:t:`eberenz_asset_2020`
#. CLIMADA v1: a global weather and climate risk assessment platform :footcite:t:`aznar-siguan_climada_2019`


Tools for IBF
-------------

#. SALib: An open-source Python library for Sensitivity Analysis :footcite:t:`herman_salib_2017`
#. Universal Regridder for Geospatial Data, https://github.com/JiaweiZhuang/xESMF, :footcite:t:`jiawei_zhuang_jiaweizhuangxesmf_2020`

.. footbibliography::
