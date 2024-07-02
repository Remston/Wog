pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'date'
                script{
                    if(ENV == "prod"){
                        echo 'We in prod!!!'
                    }
                }
                
            }
        }
        stage('Upload to prod') {
            steps {
                echo 'df'
            }
        }
    }
}
