	Use Case 1
	
	1. Title: Check In Code
	2. Primary Actor: Corporate Developer
	3. Goal in Context: The corporate developer is able to successfully check in source code into the SPDX database. 
	4. Stakeholders and Interests:
		-Corporate Developer: To successfully retain open source code in the SPDX database.
		-Corporate Manager: To receive clear and relevant information submitted by the corporate developer.
	5. Preconditions:
		1. Open source code is obtained from sources out of the corporation.
		2. The SPDX Database is available and works properly.
	6. Main Success Scenario: The Corporate Developer successfully check in source code into the  SPDX database.
	7. Failed End Conditions: The Corporate Developer is not able to store file/package information into the SPDX 
	database. 
	8. Trigger: A Corporate Developer wants to store certain file or package in the SPDX file to be used later in 
	a project. 


	Use Case 2

	1. Title: Determine License and Vulnerability Information
	2. Primary Actor: Corporate Manager
	3. Goal in Context: The corporate manager is able to determine license and vulnerability information from 
	provided project information. 
	4. Stakeholders:
		-Corporate Manager: To receive clear and relevant project information.
		-Corporate Developer: To provide the relevant file/package level information. 
		-Project Owner: To clearly understand corporate manager decisions to green/red light a project. 
	5. Preconditions:
		- Relevant and accurate file/package information is in the SPDX database. 
		- Proper project information has been provided
	6. Main Success Scenario: Corporate manager receives well-formed license and vulnerability information for 
	the requested project packages. 
	7. Failed End Conditions: Corporate manager receives poorly-formed license and vulnerability information for 
	the requested project packages. 
	8. Trigger: Corporate manager uploads or identifies project information to which license and vulnerability 
	information is provided. 


	
	Use Case 3

	1. Title: Analyze Source Code
	2. Primary Actor: Corporate Developer
	3. Goal in Context: The Corporate Developer is able to successfully check package/file information without 
	storing the information in the SPDX Database. 
	4. Stakeholders and Interests: 
		- Corporate Developer: To receive a successful report of submitted source code.
	5. Preconditions:
		- Proper package/file information is provided.
		- All the database involved in the process contain information about the package/file submitted. 
	6. Main Success Scenario: The Corporate Developer is able to successfully retrieve the proper package/file 
	information. 
	7. Failed End Conditions: The Corporate Developer is not able to retrieve correct package/file information 
	from the database or the infomation is not stored in SPDX Database. 
	8. Trigger: Corporate Developer wants to learn more about the source code without committing any of the 
	information to the SPDX Database.
	
	Use Case 4

	1. Title: Project Policy Check
	2. Primary Actor: Corporate Manager
	3. Goal in Context: The Corporate Manager is able to compare policy documents against the given manifest.
	4. Stakeholders and Interests:
		- Corporate Developer: To receive a positive report for the compared document(s).
	5. Preconditions: 
		- A manifest containing license and vulnerability information is provided. 
		- The proper policy document is available.
	6. Main Success Scenario: The Corporate Manager is able to compare the documents and the type of licenses 
	and amount of vulnerabilities are sufficient with "green lighting" the project.
	7. Failed End Conditions: A comparison is not able to be made between the documents and the project fails 
	policy check.
	8. Trigger: The Corporate Manager has collected license and vulnerability information and is interested in 
	utilizing the project.
