node {  
    stage('--clean--') { 
         sh "mvn clean"
    }
    stage('--Test--') { 
        sh "mvn test"
    }
    stage('--Deploy--') { 
        sh "mvn package"
    }
}
