
##Executive Summary
###Problem

            Open source software has provided corporations the opportunity to improve development processes 
    and ultimately increase productivity and revenue.Companies are taking advantage of the vast availability 
    of open source software to lower their costs by modifying existing code which  allows them to increase 
    efficiency and profit. In the actual software industry this approach is imperative to achieve competency 
    in the market, companies that fully engage open source software will have incredible benefits and those 
    who reject the idea will suffer the consequences. [1] Collaborative development not only represents prosperity 
    for corporations, it also signifies danger and risks to the corporation’s environment. Organization structure
    is a crucial factor in order to appropriately manage licenses and vulnerabilities involved in open source software. 
    Any organization involved in open source should be properly structured to provide an effective incorporation of 
    open source code. As the Linux Foundation stated “companies that have been using and participating in open source… 
    and have found success typically follow many of the same best practices… for establishing open source mastery 
    within a company”. [2] 
    
###Solution

            To aproach an efficient management system while engaging with Open Source Software, we have design a 
     mechanism to detect vulnerabilities and license in files and packages that enter the organization for projects.
     The system assigns the Corporate Developer the responsability to check in code into a version control management
     system to then be analyzed by a license scanner, this process will determine the licenses associated with each 
     file. Then the system will also look up the CPE information of a package in the NIST database, using this information
     the developer will obtain the CVE information with the vulnerabilities in the packages submitted. All this information
     about the packages and files will be stored in the SPDX database using SHA1 as identifiers for the files, this hashing
     encryption will ensure that the same file is not stored twice in the database. Using all the data collected for each
     package, the Corporate Mangager will make decisions about projects comparing the license information and vulnerabilities
     from each project with guidelines established in a policy document. This policy document will contain the criteria for
     accepting or rejectiog a project based on the information collected by the designed system. This system will try 
     to reduce human interaction with the collection of data, but will aggregate responsabilities to the users, included 
     the retribution back to the community depending on the licenses for the developer. This system is designed for a company
     to address the issue of intake of open source, collecting the data mentioned will allow them to make better decisions
     in the approval of OSS in projects. 
            
    
       
    
    References
    [1]http://www.linux.com/component/content/article/158-jim-zemlin/799252-2014-the-open-source-tipping-point/
    [2]http://www.linuxfoundation.org/publications/linux-foundation/download-free-publication-how-build-open-source-competency-your-company
  
