pipeline{
    agent{
        docker{
         image 'maven:3-alpine'
         args '-v C:\Users\ntando.nkomo\.m2'
        }
    }

    stages{
        stage('build'){
			
			steps{
				sh 'mvn -B -DskipTests clean package'
			 }
        }
    }

}