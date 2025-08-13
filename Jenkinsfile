pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                sh ' "c:\\Windows\\System32\\cmd.exe" /c python --version'
            }
        }
        stage('hello'){
            steps{
                sh ' "c:\\Windows\\System32\\cmd.exe" /c python demoxy.py %X_VALUE% %Y_VALUE%'
            }
        }
    }
}
