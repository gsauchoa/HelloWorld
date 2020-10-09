pipeline
{
	agent any
	stages 
    {
      stage("Buildando") { steps{ sh 'mvn package' } }
      stage("teste") { steps{ echo " testando aplicacao"  } }
      stage("Implantacao"){ steps{ sh 'startup.sh'  } }
     
    }
}
