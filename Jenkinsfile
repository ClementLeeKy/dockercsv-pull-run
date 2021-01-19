node {
      checkout scm

      stage ('Pull Docker Image from Local Registry') {
            bat 'docker pull localhost:5000/docker-csv'
      }
      
      stage ('Run Docker Container using Image from Registry') {
            dir("C:\\Users\\z0048yrk\\Desktop\\LTA\\demo") {
                  bat 'docker run docker-csv > output.csv'
            }
      }
}
