pipeline {
    agent any

    stages {
        stage('create packer AMI'){
            steps { 
                echo "Packer AMI pipeline"
            }
        }
    }

    stage('Azure deployment'){
        steps {
        echo "deployment in azure pipeline"
    }
    }
    stage('upload to SIG'){
        steps {
            echo "SIG in azure pipeline"
    }
    }
}
  
