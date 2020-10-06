pipeline
{
	  agent any
	  stages 
    {
      stage("build") { steps{ sh 'mvn package' } }
      stage("teste") { steps{ echo " testando aplicacao"  } }
      stage("deploy"){ steps{ sh 'startup.sh'  } }
     
    }
}
