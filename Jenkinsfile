Jenkinsfile (Declarative Pipeline)
pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                sh 'echo  "Hello World"'

                sh '''
                    "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}