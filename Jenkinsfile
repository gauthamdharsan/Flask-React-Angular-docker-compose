node {
    def app
        stage('Checkout') {
            git url: 'https://github.com/gauthamdharsan/pipeline-samp.git'
        }
   
        stage ('Run') {
          sh "docker-compose --version"
          sh "docker-compose up -d"
        }
     }
        //stage('build') {
        //    sh 'mvn clean package'

        //    def pom = readMavenPom file:'pom.xml'
        //    print pom.version
        //    env.version = pom.version
            
       // }
        
        //stage('Image') {
        //    dir ('.') {
        //        def app = docker.build "gauthamdharsan/gateway-service:${env.BUILD_NUMBER}"
          
        //    }
        //}
        
        //stage('Push image') {
        //    docker.withRegistry('https://registry.hub.docker.com', 'docker') {
        //        app.push("${env.BUILD_NUMBER}")
        //        app.push("latest")
            
        //    }
        //}
        
        
