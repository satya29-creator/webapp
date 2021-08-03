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
              deploy adapters: [tomcat8(credentialsId: '04d9d1d2-be73-4567-9c77-0a366dbe85fe', path: '', url: 'http://localhost:8080/')], contextPath: null, war: '**/*.war'

               
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
