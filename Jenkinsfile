pipeline {
    agent any
    stages{
        stage('自定义构建'){
            steps {
                echo '构建开始'
                sh 'g++ main.cpp -o test'
            }
        }
    }
}
