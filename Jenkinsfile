pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: 'f8a79ffc-fb31-4b43-8951-f63915fa11f0', url: 'https://github.com/josefaherreras/NewSpringMvcRest.git'
            }
        }
    }
}