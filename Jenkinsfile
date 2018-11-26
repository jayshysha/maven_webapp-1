pipeline {
    agent any
    tools { 
        maven 'Maven 3.1.1' 
        //maven 'maven 3.3.9'
        jdk 'JDK1.8' 
       // jdk 'JAVA8'
    }
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                ''' 
            }
        }

        stage ('Build') {
            steps {
                echo 'This is a minimal pipeline.'
            }
        }
    }
}
