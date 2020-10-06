pipeline
{
	  agent any
	  stages 
    {
      stage("build") { steps{ sh 'mvn package' } }
      stage("teste") { steps{ sh './mvnw test' } }
      stage("deploy"){ steps{ sh 'startup.sh'  } }
     
    }
}
