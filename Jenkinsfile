pipeline{
    agent any

    stages{
        stage('Compile stage'){
            steps{
                bat 'mvn -B -DskipTests clean package'
            }
        }
        stage('Testing stage'){
            steps{
                bat 'mvn test'
            }
        }
    }
}