pipeline
{

  agent any
  
  stages
  {
    stage("build")
    { 
      steps{
          echo 'build da aplicacao'
          sh mvn package
          } 
    }
    stage("teste"){ steps{echo 'teste da aplicacao'} }
    stage("deploy"){ steps{echo 'deploy da aplicacao'} }
  }
}
