pipeline{
    agent any
    stages{
        stage('stage1'){
            steps{
                echo "This is my first pipeline job"
            }
        }
        stage('Build') {
            steps {
               sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}