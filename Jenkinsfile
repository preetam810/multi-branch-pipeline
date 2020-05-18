pipeline{
    agent any
    
    stages{
        stage('Build'){
            steps{
               echo "Build" 
               echo "$BRANCH_NAME" 
            }
            
        }
        
        stage("Deploy"){
            steps{
                echo "Deploy"
            }
            
        }
        
    }
}
