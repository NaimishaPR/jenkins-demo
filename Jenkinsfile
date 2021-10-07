pipeline{
    agent any
    triggers {
        pollSCM '* * * * *'
    }
    stages {
        stage("poll scm") {
            steps {
                echo "Run code again for webhook demo1"
            }
        }
    }   
}    
