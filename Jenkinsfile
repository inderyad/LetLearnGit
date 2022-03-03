pipeline {
    agent any

    stages 
    {
        stage('Build') 
        {
            steps
            {
                echo 'Build App'
            }
        }
        
        stage('Test') 
        {
            steps
            {
                echo 'Test App'
            }
        }
        
        stage('Deploy') 
        {
            steps
            {
                echo 'Deploy APP'
            }
        }
    }
        post
        {
            always
            {
                emailext body: 'Pipeline Summary', subject: 'Pipeline Status', to: 'inderyad@gmail.com'
            }
        
        }
    }

