pipeline {
  agent any
  
   stages{
     stage("git checkout"){
     steps{
      git branch: 'main', url: 'https://github.com/raja448/demo-counter-app.git'
     }
     }
    stage("unit testing"){
     steps{
      sh 'mvn test'
     }
     }
   }
}
