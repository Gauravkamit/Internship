# Internship
Stand alone image generation

Title: Stand-alone Image Generation tool for System Upgrade.

Objective:
To create an updatable USB stick, containing update binaries for multiple systems (android, Ubuntu etc). The sources can be obtained from single or multiple storages (git, artifact, repos etc) in different formats (ipk,apk,deb etc) and use the benchmark tool to handle the sources/packages to create an upgradable image. The updatable stick shall then be used for updating Ubuntu or Android images on targets.

Overview:
Software upgrade intends to update a product with a newer version of the same product. This will add new feature to the existing product or it could be newer firmware version etc. To make this standalone we need to bring in a tool that can process data from multiple sources and output an upgradable image. It involves benchmarking open source distribution tool (opensuse, redhat, open embedded) which can work on packages to generate binaries.  It should be able to get the packages, get sources and create packages, extract or install the packages and perform post handling to generate binaries.

 

Educational Requirement:
•	Under graduation or post-graduation in Computer/Information science
•	Candidate with good software development and programming skills

Skill Set Requirement:
•	Advanced knowledge in scripting(Perl/Python etc) and  object oriented programming
•	Good knowledge in XML creation and XML parsing
•	Good knowledge in software configuration management and design 
•	Analytical, problem solving skills 
•	Good communication, self – learning, self - driven 

Essential Duties and Responsibility:
•	Needs to handle several complex tasks and responsibilities - research, designing, development, implementation, testing, debugging, modifying, etc., to meet the product requirements. 
•	Documentation of design and implementation
•	Effective interaction with the team and maintain positive energy
•	Adhere to the timelines and quality standards

Task description:
•	Connect and download from git or artifactry or any other source
•	Should be able to process multiple package types such as ipk,apk,deb etc
•	Should be able to create multiple package types from source paths.
•	Process(Install) packages to generate binaries in multiple formats (tar,image,iso formats)
•	Tool shall be configurable to perform post handling based on configurations passed (prelinker etc)
•	Tool shall be able to generate binaries for the paths configured (ex:/var/opt/bosch/persistent)
•	Tool shall run on any Linux / Ubuntu distribution.
•	Tool shall be able to run in Docker environment.
Note: Docker is used to run software packages called "containers". It is a tool that can package an application and its dependencies in a virtual container that can run on any Linux server. This helps enable flexibility and portability on where the application can run.
