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
       
       customWorkspace "/mnt/game-of-life"
       sh "yum install maven -y"
       sh "mvn clean install"
        echo "hello"
        
      }
    }
       
  }
}

