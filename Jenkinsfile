pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                sh 'ls'
            }
        }
        stage("test"){
            steps{
                input 'do you approve project ?'
                echo "=========== test ==========="
            }
        }
    }
}

