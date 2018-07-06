node {
    checkout scm
    stage('Build'){
        echo 'Building...'
        withMaven(
            maven: 'mvn'
            ){
        sh 'mvn clean install || true'
        }

    }
    stage('Test'){
        echo 'Testing...'
    }
    stage('Deploy'){
        echo 'Deploying...'
    }
}