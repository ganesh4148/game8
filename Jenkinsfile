pipeline {

agent {

label{

  label "built-in"
  customWorkspace "/mnt/game-of-life"

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

