node {
    stage('Checkout SCM') {
        git branch: 'main', url: 'https://github.com/piku143526/vias-testing.git'
    }
    stage('Install node modules'){
        sh "npm install"
    }
    
    stage('Build'){
        sh "npm build angular_pro_test"
    }
  
}
