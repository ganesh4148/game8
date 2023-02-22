pipeline {

agent {

label{

  label "built-in"
  customWorkspace "/mnt/ganesh"

}
}
  
  stages {
   
    
    stage ("on master")
    {
      
      steps {
        
        sh "mvn install"
        
      }
    }
  }
}

