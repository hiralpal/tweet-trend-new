pipeline{
    agent{
        node{
            label 'maven'
        }
    }
enivronment {
    PATH = "/opt/apache-maven-3.9.9/bin:$PATH"

}
    stages{
        stage('Build'){
            steps{
                sh 'mvn clean deploy'
            }
        }
    }
}