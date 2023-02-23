pipeline {

agent {

label{

  label "built-in"
  sh "sudo yum install maven -y"
  customWorkspace "/mnt/game-of-life"
  sh "sudo mvn clean install"

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

