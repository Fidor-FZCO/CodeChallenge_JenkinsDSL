

Create a Jenkins job (PIPELINE JOB) using Jenkins Job DSL.(Jenkinsfile)
	⁃	The job should take input parameters
	⁃	pull code from GitHub, 
	⁃	build it with Maven 
	⁃	Trigger a downstream job upon SUCCESS. 
It should be configured to poll the SCM (GitHub repo) every five minutes and trigger the job upon code changes. 

More Info:

	•	The job should be parameterised. Use the provided String fields with parameterName, parameterDefaultValue and parameterDescription to add a job parameter;
	•	The code should be pulled from GitHub from the repository URL provided in the repo field;
	•	SCM trigger should be added to poll the repository every 5 minutes;
	•	The steps method should be used to run the following maven command on the project: mvn clean install;
	•	If the job ends in SUCCESS, a downstream job called deploy should be triggered.

Once the task is completed, in a webex demo session demonstrate the following;
Jenkins job should be triggered automatically for any change in Gitrepo,
build using maven and 
it should trigger downstream job successfully
  
