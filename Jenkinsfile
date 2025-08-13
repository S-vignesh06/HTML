pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                bat ' "c:\\Windows\\System32\\cmd.exe" /c python --version'
            }
        }
        stage('hello'){
            steps{
                bat ' "c:\\Windows\\System32\\cmd.exe" /c python demoxy.py %X_VALUE% %Y_VALUE%'
            }
        }
    }
}
