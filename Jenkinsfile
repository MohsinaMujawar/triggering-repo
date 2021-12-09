pipeline{
  agent any
  stages{
    stage("hello"){
      steps{
        script{
          git url: "https://github.com/MohsinaMujawar/triggering-repo.git", branch: "main"
        }
        sh "cat README.md"
      }
    }
  } 
}   
    
