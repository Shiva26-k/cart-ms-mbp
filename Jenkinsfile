pipeline{
    agent any
    environment {
        name = "Shiva"
        courses = "devops and gcp"
    }
    stages{
        stage("Build"){
            environment {
                cloud = "gcp"
            }
            steps{
                echo "Welcome ${name}"
                echo "You registered for ${courses}"
                echo "You certified in ${cloud}"
            }
        }

    }
}
