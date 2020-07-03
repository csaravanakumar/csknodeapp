node {

    stage('Code Checkout') {
        /* Cloning the Repository to our Workspace */
	    checkout scm
	    echo "code checked in"
    }

    stage('Maven Build') {
        /* This builds the actual image */
        def mavhome=tool name: 'maven-3', type: 'maven'
        bat 'mvn package'
        echo "package completed"
    }

    stage(' Maven Test') {
        
          echo "code checked in"
    }

    stage('Push Image') {
         echo "code checked in"
    }
}
