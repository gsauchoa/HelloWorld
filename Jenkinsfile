pipeline
{
	  agent any
	  stages 
    {
      stage("build") { steps{ sh 'mvn package' } }
      stage("teste") { steps{echo 'teste da aplicacao'} }
      stage("deploy"){ steps{echo 'deploy da aplicacao'} }
    }
}
