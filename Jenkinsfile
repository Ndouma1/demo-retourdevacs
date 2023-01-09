pipeline {
    agent any

    tools {
        jdk "jdk17-0-5"
    }
        stages{
        stage("Build"){
            steps {
                git 'https://github.com/Ndouma1/demo-retourdevacs.git'
                sh "chmod +x ./gradlew"
                sh "./gradlew build"
            }
        }
   }}
