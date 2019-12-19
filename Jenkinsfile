pipeline{
    agent any
    stages{
        stage('Cloning'){
            steps{
                git 'https://github.com/dadisantoshkumar/docker-react.git'
           }
        }
    stage('Build'){
        steps{
            sh '''
            
'''
        }
        post{
            success{
                echo 'Now Archiveing...'
                archiveArtifacts artifacts: '**/target/*.war'
            }
        }
    }
}
}
