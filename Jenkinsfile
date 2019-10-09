pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                build 'BuildWar'
                echo 'Build War Succeeded'
            }
        }
        stage('Deploy'){
            steps{
                build 'DeployWar'
                echo 'Deploy War Succeeded'
            }
        }
        stage('Test'){
            steps{
                build 'TestWar'
                echo 'Test War Succeeded'
            }
        }
    }
}
