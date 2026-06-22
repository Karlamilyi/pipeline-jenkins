pipeline {
    agent any
    stages {
        stage('Checkout') { steps { echo 'Code récupéré' } }
        stage('Build')    { steps { sh 'echo "Build OK"' } }
        stage('Test')     { steps { sh 'echo "Tests OK"' } }
        stage('Deploy')   { steps { sh 'echo "Deploy OK"' } }
    }
}
