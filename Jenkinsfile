node ('Ubuntu-app-agent'){  
    def app
    stage('Cloning Git') {
        /* Let's make sure we have the repository cloned to our workspace */
       checkout scm
    }  
    /*stage('SAST'){
        build 'Security-SAST-Snyk'
    }

    
    stage('Build-and-Tag') {
    /* This builds the actual image; synonymous to
         * docker build on the command line 
        app = docker.build("virgomanalert/snakegame")
    }
    stage('Post-to-dockerhub') {
    
     docker.withRegistry('https://registry.hub.docker.com', 'b7b298ab-a52b-4670-b3d8-c017c754b95e') {
            app.push("latest")
        			}
         }
    stage('SECURITY-IMAGE-SCANNER'){
        build 'Security-Container-Aqua-Microscanner'
    }
  
    */
    stage('Pull-image-server') {
         sh "echo 'see_me > /tmp/log.txt'"
         sh "docker-compose down"
         sh "docker-compose up -d"	
      }
    
    /*stage('DAST')
        {
        build 'Security-DAST-ZAP'
        }*/
 
}
