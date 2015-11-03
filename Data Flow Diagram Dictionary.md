the DFD Dictionary will be here. 

Entities

    1) Corporate Developer - The developers who will be pulling source code from external locations. 
    This can include public and private repositories as well as software received via supply chains.
    
    2) Corporate Managers - Internal corporate individuals who will be the recipients of the Project 
    Model or any other software manifests. From these documents, they can make impactful decisions. 
    
    3) National Vulnerability Database - External repository of package vulnerability information.

Processes

    1) Manage Code Streams - For facilitating the travel of data throughout other various processes and 
    entities in the Data Flow Diagram
    
    2) Version Control / Build System - For version control and organization of the various packages or 
    files within the project
    
    3) License Scanner - For finding license information about a given file or package
    
    4) Manage CPE Information - For finding CPE Information about a given package
    
    5) Update CPE Information - For updating the NIST CPE Information Data Store
    
    6) Manage CVE Information - For finding CVE Information about a given package, using its CPE information
    
    7) Manage Project Information - For corporate managers to manage the project and make impactful decisions 
    regarding the project as a whole
    
    8) Manage Policy Information - For corporate managers to score how compliant the project is with corporate 
    policy guidelines


Data Flows

    1) File/Package - A source file or package comprised of multiple source files
    
    2) Project File - A collection of all the different packages and files that make up the project; 
    could also be given as a project model
    
    3) File License and Vulnerability Information - Relevant License and Vulnerability Information about 
    a file or package as requested by a corporate developer
    
    4) File SHA1 Request - A request as to whether or not the hash of a file exists in the database; if not, 
    a hash of the file along with its relevant CPE and CVE information will need to be added to the SPDX Database
    
    5) File SHA1 Response - A yes/no response as to whether or not the hash of a file exists in the database
    
    6) File License, CPE & CVE Info - If the SHA1 Response returns as a 'no' then a hash of the file with this 
    relevant information is created and stored on the SPDX database
    
    7) License Info - License info about a particular file or package resulting from a license scan such as 
    from FOSSology

    8) Package Name - The name of a package for which CPE info needs to be found
    
    9) CPE Info - Relevant CPE naming information about a file or package, from the internal CPE Information 
    data store
    
    10) CPE Request - A request to the internal list of CPE Information for CPE Info about a file or package
    
    11) CPE Update Request - A request to update the Master CPE File from the National Vulnerability Database
    
    12) Master CPE File - An XML file containing all the CPE information, from the National Vulnerability Database, 
    updated daily

    13) CVE Info - Vulnerability information about a package returned from a given CPE

    14) Policy Compliance Request - A request by a corporate manager to see whether a particular project 
    model fits within defined corporate policy guidenlines
    
    15) Policy Guideine Response - A report or score on how well a given project model fits within corporate 
    policy guidelines
    
    16) Project File/Info Request - A request from a corporate manager for a project model or information about 
    the project
    
    17) Project File/Info Response - A project model or relevant project information given to a corporate manager
    

Data Stores

    1) NIST CPE Information - An internal data store where CPE information is stored for comparison. Updated daily 
    from the National Vulnerability Database
    
    2) SPDX Database - Database that store information about files within a project. This information is stored via a 
    SHA1 hash.
    
    3) Corporate Policy Database - Corporate guidelines for acceptable policy which can be set by a policy manager 
    to be used to determine wether a project model is acceptable for use
    
