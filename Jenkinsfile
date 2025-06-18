pipeline{
    agent any
    environment{
        name = "Shiva"
        courses = "devops and gcp"
    }
    stages{
        environment{
            cloud ="gcp"
        }
        stage('Build'){
            steps{
                echo "Welconme ${name}"
                echo "you registered for ${courses}"
                echo "You certificated in ${cloud}"
            }
        }
        stage('sonar'){
            steps{
                echo "Welconme ${name}"
                echo "you registered for ${courses}"
                echo "You certificated in ${cloud}"
            }
        }
    }
}
