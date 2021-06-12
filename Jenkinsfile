pipeline {
    agent any

    stages {
        stage('Devp') {
            steps {
                echo 'Application under developing'
            }
        }
         stage('Testing') {
            steps {
                echo 'Application under Testing'
            }
        }
         stage('Delpoy') {
            steps {
                echo 'Application under Delpoying'
            }
        }
    }
    post {
        always {
emailext body: 'Summery demo', subject: 'Alert-jenkins', to: 'bnarendra340@gmail.com'        }
    }
}
