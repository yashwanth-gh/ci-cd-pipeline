pipeline {
    agent any  // Run on any available agent

    stages {
        stage('Checkout Code') {
            steps {
                // Pull code from GitHub repository
                git branch: 'main', url: 'https://github.com/yashwanth-gh/ci-cd-pipeline'
            }
        }

        stage('Build') {
            steps {
                // Echo message as a simple build step
                echo 'Working successfully! Jenkins has successfully pulled the code! and version control is intergrated in my ci/cd pipeline'
            }
        }
    }
}
