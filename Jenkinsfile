pipeline{
  agent any
  stages{
    stage('Build'){
        steps{
            publishChecks(name: 'Build', status: 'in_progress', summary: 'Building...')
            echo 'Building the project with Jenkinsfile 2'
        }
    }
    stage('Test'){
        steps{
            echo 'Testing the project pipeline 2'
        }
    }
    stage('Deploy'){
        steps{
            echo 'Deploying the project'
        }
    }
  }
}
