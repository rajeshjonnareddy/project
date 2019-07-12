node {  
    stage('--clean--') { 
         sh "mvn -f pom.xml clean"
    }
    stage('--Test--') { 
        sh "mvn -f pom.xml test"
    }
    stage('--Deploy--') { 
        "mvn -f pom.xml package"
    }
}
