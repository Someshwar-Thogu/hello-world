pipeline {

    agent any
    
    tools { 
        maven 'M2_HOME' 
        jdk 'JAVA_HOME' 
    }

    stages {

        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }

        }
    }
}
