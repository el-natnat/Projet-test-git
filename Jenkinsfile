/* groovylint-disable CompileStatic */
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building branch 2'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing branch 2..'
                dir('C:\\Users\\nbreuil\\OneDrive - SOCIÉTÉ CORIOLIS\\Documents\\Cormeziant-Sources') {
                // some block
                }
                fileExists 'C:\\Users\\nbreuil\\OneDrive - SOCI\ÉTÉ CORIOLIS\\Documents\\Cormeziant-Sources\\a.bat'
                bat 'cd C:/Users/nbreuil/OneDrive - SOCIÉTÉ CORIOLIS/Documents/Cormeziant-Sources/'
                bat 'a.bat'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying branch 2'
            }
        }
    }
}
