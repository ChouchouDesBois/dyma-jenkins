pipeline{
    agent{
        label "node"
    }
    stages{
        stage("build"){
            steps{
                echo "========executing A========"
            }
        }

        stage ("test"){
            steps{
                echo "========executing B========"
            }
        }

        stage("deployment"){
            steps{
                echo "========executing C========"
            }
        }
    }
    
}