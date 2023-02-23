pipeline {

agent {

label{

  label "built-in"
}
}
  
  stages {
   
    
    stage ("on master")
    {
      
      steps {
       sh "yum install maven -y"
        dir("/mnt/game-of-life"){
          
          sh "mvn install" 
        
        }
        
      }
    }
       
  }
}

