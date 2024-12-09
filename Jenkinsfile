pipeline {
    agent any
    stages {
        stage ('QRBuild'){
            steps {
                echo "Build pipeline"
                sh "hostname -i"
            }
        }
        stage ('ScanFortify') {
            steps {
                echo "Scanning the code"
            }
        }
        stage ('dockerbuild') {
            steps {
                echo "Docker Pipeline"
            }
        }
        stage ('devdeploy') {
            steps {
                echo "devdeploy pipeline"
            }
        }

    }
}
