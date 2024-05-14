pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch1"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is Sprint1 branch1"'
            }
        }

        stage("hotfix") { 
             steps { 
                sh 'echo "This is hotfix branch"'
            }
        }  
    }
}
