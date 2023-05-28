pipeline {
     agent any
     tools {nodejs "nodejs"}
     stages {
        stage("Build") {
            steps {
                echo "building the project..."
                sh "sudo npm install"
                sh "sudo npm run build"
            }

        }
    
    }
}