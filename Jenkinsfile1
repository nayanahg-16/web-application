pipeline{
    agent any
    
    stages{
        stage('hostname'){
            steps{
                sh 'hostname'
            }
        
        stage('hostname-I'){
            steps{
                sh 'hostname -I'
            }
        }

        stage('CPU'){
            steps{
                sh 'lscpu'
            }
        }

        stage('disk'){
            steps{
                sh 'du -sh'
            }
        }
        }
    }
}
