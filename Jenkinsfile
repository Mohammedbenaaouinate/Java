
node {
    
   stage('Clone') {
	   git 'https://github.com/Mohammedbenaaouinate/Java.git'
   }
   stage('Build') {
	   sh 'javac Main.java'
   }
   stage('Run')  {
 	  sh 'java Main'
   }
}

