agent {
  label 'DevServer'
}
stages{

        stage('build')
        {
                steps{
                        sh 'mvn clean package'

                }
  post {
    success {
                archiveArtifacts artifacts: '**/target/*.war'
    }
  }
        }



}
}
