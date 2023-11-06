# What Is FairStack
FairStack is a reference architecture for scientific data software stack of scientific data centers, with the aim of guiding the construction of a reusable public scientific data software stack to efficiently establish scientific data centers at a high level.

The FairStack Architecure:
![The FairStack Architecure:](https://raw.githubusercontent.com/fair-stack/.github/main/profile/arch.svg)

FairStack also refers to any public software stack that obays to the above reference architecture. 
# The Functionality Scope of FairStack
FairStack can serve as the fundamental technical infrastructure for enabling FAIRified data management and sharing services within scientific data centers by managing, sharing, and utilizing data in a unified and FAIR way across popular research paradigms in different disciplines.

Popular research paradigms include open science, data-intensive research, also known as the 4th paradigm, AI4Science, and convergence science. They are driving innovation in scientific data management and service methods, imposing higher-level capability requirements on scientific data software stacks. For example, the open science paradigm demands software stacks to support open data sharing, fostering cross-institutional research cooperation and aiding public decision-making following the FAIR (Findable, Accessible, Interoperable, Reusable) Principles. The 4th paradigm necessitates capabilities like heterogeneous data integration and storage, high-performance big data processing, and online data analysis services to address the opportunities and challenges posed by massive scientific data. AI4Science requires software stacks to provide AI (Artificial Intelligence) model training and inference tools, various pre-trained models, and AI-ready data product preparation and management capabilities to support AI-powered domain-specific applications. The convergence science paradigm mandates software stacks not only to enable open sharing of data resources, but also to facilitate researchers in discovering interdisciplinary connections among data. This includes providing panoramic data views and promoting online collaborative data analysis.

# FairStack Modules
| Module | Prototype | Brief Introduction | Demonstration |
|--------|-----------|--------------------|---------------|
| AI1    | FairMan   | Distributes and maintenances functional modules and operators in a software store style. | [Link](https://market.casdc.cn) |
| AP1    | πFlow | A big data pipeline processing system built upon Apache Spark and Docker with 100+ operators. | / |
| AM1    | DataSpace | Collects and stores multi-source heterogeneous data in a unified and collaborative manner for scientific research teams. | [Link](http://data.iscr.ac.cn) |
| AM2    | PandaDB   | A data fusion store system which can call AI models at runtime to extract semantics and correlations of unstructured data. | / |
| AM4    | OpenCSDB  | A linked data service. | [Link](http://open.csdb.cn) |
| AA1    | InstDB    | A data sharing service engine, supporting DOI/CSTR registering, various data licenses, and peer review of data submission. | [Link](https://www.nbsdc.cn) |
| AA2    | DataLab   | A data analysis service engine, providing online programming analysis and workflow analysis services. | [Link](https://market.casdc.cn/datalab) |
| AD1    | PackOne   | Provides drivers of heterogeneous infrastructure such as OpenStack, EVCloud, and CSTCloud. | / |


# The BASE Principles: FairStack's Guidline
FairStack is designed under the guidance of the *BASE* principles — Basic, Adaptable, Sustainable, and End-to-end. These principles operate incrementally, governing the definition of functionality, interface specifications, system implementation and application construction of the public stack.

The BASE Principles:
![The BASE Principles:](https://raw.githubusercontent.com/fair-stack/.github/main/profile/base-principles.svg)
