pipeline{
    agent any

        stages{
            stage("Install Dependency"){

                steps {
                    bat 'npm install'
                }
            }

            stage("build React app"){

                steps{
                    bat "npm run build"
                }
            }

            stage("Success"){

                steps {
                    echo "React build Sucessfull"
                }
            }
        }
}