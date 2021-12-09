pipeline{
  agent any
  stages{
    stage("hello"){
      steps{
        script{
          git url: "", branch: "main"
        }
        sh "cat README.md"
      }
    }
  } 
}   
    
