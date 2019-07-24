pipeline {
    agent any
    tools { 
        maven 'Maven_home' 
        jdk 'Java-1.8' 
    }
    stages {
         stage ('Initialize') {
            steps {
                bat '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                ''' 
            }
        }
        stage('build') {
            steps {
               echo 'This is a minimal pipeline.'
            }
        }
    }
}
