pipeline{
    agent any

    stages{
        satges("git checkout"){
            steps{
                git branch: 'main' , url: 'https://github.com/KARANVISHWAJYOTH/DEVOPS.git'
                    
               
            }
        }
        satge("Build"){
            steps{
                echo "running the build stage"
            }
        }
        stage("test"){
            steps{
                echo " running in test cases !!"
            }
        }
        stage("depolyment"){
            steps{
                echo " running in deployment stage"
            }
        }
    }
}