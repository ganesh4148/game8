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
        sh "yum install maven -y"
        sh "mvn clean install"
        
      }
    }
       
  }
}

