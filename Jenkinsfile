pipeline{
    agnet any
    stages{
        stage('Build'){
            steps{
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}