pipeline {
    agent any

    stages
    {
        stage('BUILD')
        {
            steps 
            {
                echo 'build application'
            }
        }
        stage('TEST') 
        {
            steps
            {
                echo 'test application'
            }
        }
         stage('DEPLOY') 
        {
            steps 
            {
                echo 'deploy application'
            }
        }
    }
    post
    {
        always
        {
          echo 'Done'
        }
    }
}
