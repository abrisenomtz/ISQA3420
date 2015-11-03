	Use Case 1
	
	1. Title: Check In Code
	2. Primary Actor: Corporate Developer
	3. Goal in Context: The corporate developer is able to successfully check in source code into the SPDX database 
	4. Stakeholders and Interests:
		-Corporate Developer: To successfully retain open source code in the SPDX database.
		-Corporate Manager: To receive clear and relevant information submitted by the corporate developer.
	5. Preconditions:
		1. Open source code is obtained from sources out of the corporation.
		2. The SPDX Database is available and works properly.
	6. Main Success Scenario: The Corporate Developer successfully check in source code into the  SPDX database.
	7. Failed End Conditions: The Corporate Developer is not able to store file/package information into the 
	SPDX database. 
	8. Trigger: A Corporate Developer wants to store certain file or package in the SPDX file to be used 
	   later in a project. 
	9. Notes:


	Use Case 2

	1. Title: Determine License and Vulnerability Information
	2. Primary Actor: Corporate Manager
	3. Goal in Context: The corporate manager is able to determine license and vulnerability information from provided 			project information. 
	4. Stakeholders:
		-Corporate Manager: To receive clear and relevant project information.
		-Corporate Developer: To provide the relevant file/package level information. 
		-Project Owner: To clearly understand corporate manager decisions to green/red light a project. 
	5. Preconditions:
		- Relevant and accurate file/package information is in the SPDX database. 
		- Proper project information has been provided
	6. Main Success Scenario: Corporate manager receives well-formed license and vulnerability information for the				requested project packages. 
	7. Failed End Conditions: Corporate manager receives poorly-formed license and vulnerability information for the 			requested project packages. 
	8. Trigger: Corporate manager uploads or identifies project information to which license and vulnerability 				information is provided. 
	9. Notes:

	
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
	7. Failed End Conditions: The Corporate Developer is not able to retrieve correct package/file information from the 		database or these infomation is store in SPDX Database. 
	8. Trigger: Corporate Developer wants to learn more about the source code without committing any of these
	9. information in the SPDX Database .
