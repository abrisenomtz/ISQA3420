the DFD Dictionary will be here. 

Entities

    Corporate Developer - The developers who will be pulling source code from external locations. This can include public and private repositories as well as software received via supply chains.
    Corporate Managers - Internal corporate individuals who will be the recipients of the Project Model or any other software manifests. From these documents, they can make impactful decisions. 
    

Data Flows

    CPE Info/Information - Relevant vulnerability information about a file or package, from the internal CPE Information data store
    CPE Request - A request to the National Vulnerability Database for an updated listing of CPE information, to be stored for reference
    CPE Response - An XML file listing CPE Information, to be stored in the NIST CPE Information data store for reference
    File - Source file
    File Information Request - A request about a file in the project, for use by the corporate manager in a project model
    File Information Response - Relevant information about a file in the project. This includes copyright, license and vulnerability information
    File License & CPE Information - For any file that does not have a SHA1 in the database, a new record is created for that file
    File SHA1 Request - A request as to whether or not the hash of a file exists in the database; if not, a hash of the file is added to the SPDX Database
    File SHA1 Response - A yes/no response as to whether or not the hash of a file exists in the database
    License Info - License info about a particular file or package resulting from a FOSSology search
    Package - Source pacakage comprised of one or more files
    Package Query - A request to the internal NIST CPE Information data store to find vulnerability information about a given package
    Policy Compliance Request - A request by a corporate manager to see whether a particular project model fits within defined corporate policy guidenlines
    Policy Compliance Report - A comparison between a score on how well a given project model fits within corporate policy guidelines and acceptable standards for a given project
    Policy Guidelline Request - A request for a policy compliance score for a given project model
    Policy Guideine Response - A report or score on how well a given project model fits within corporate policy guidelines
    Project Model Request - A request from a corporate manager for a project model 
    Project Model Response - A project model given to a corporate manager
    

Data Stores

    NIST CPE Information - An internal data store where CPE information is stored for comparison. Updated daily from the National Vulnerability Database
    SPDX Database - Database that store information about files within a project. This information is stored via a SHA1 hash.
    Corporate Policy Database - Corporate guidelines for acceptable policy which can be set by a policy manager to be used to determine wether a project model is acceptable for use
    
