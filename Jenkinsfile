node {
stage('stage1'){
echo 'This is stage 1--------'
}
  stage('stage2'){
  echo 'This is stage 2--------'
  sh 'docker --version'
  }
  stage('stage3'){
  echo 'This is stage 3--------'
  sh 'docker pull nginx:latest'
  }
  stage('stage4'){
  echo 'This is stage 4--------'
  sh 'docker run -p 80:8000 nginx'  
  }
  stage('stage5'){
  echo 'This is stage 5--------'
  echo 'All task has been completed'  
  }
}
