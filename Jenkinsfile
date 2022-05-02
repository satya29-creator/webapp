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
              echo 'Deploy'
               
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
<!--Docker file--> 
