pipeline {

agent {

label{

  label "built-in"
  sh "yum install maven -y"
  customWorkspace "/mnt/game-of-life"
  sh "mvn clean install"

}
}
  
  stages {
   
    
    stage ("on master")
    {
      
      steps {
       
        echo "hello"
        
      }
    }
       
  }
}

