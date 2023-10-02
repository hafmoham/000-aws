pipeline {
  agent any
  tools { 
        maven 'Maven_3_5_2'  
    }
   stages{
    stage('CompileandRunSonarAnalysis') {
            steps {	
		sh 'eksctl create cluster --name eks-oct-2023 --region us-east-1 --node-type t2.medium --nodes-min 2 --nodes-max 2 --zones us-east-1a,us-east-1b'
            }
        } 
  }
}
