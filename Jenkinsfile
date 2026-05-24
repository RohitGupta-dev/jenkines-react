pipeline{
    agent any

        stages{
            stage("Install Dependency")
            step {
                bat 'npm install'
            }

            stage("build React app")
            step{
                bat "npm run build"
            }

            stage("Success")
            step {
                echo "React build Sucessfull"
            }
        }
}