pipeline {
  agent any
  stages {
    stage('simple line') {
      steps {
        echo "I hope this pipeline build doesn't fail"
      }
    }
    stage('Thank you') {
      steps {
        echo "Thank you the build using the webhook successful"
  }
}
    stage('Add') {
      steps {
        echo "Trying one more build to check the option discard builds"
      }
    }
    stage('Discard builds') {
      steps {
        echo "The discard builds option worked"
  }
}
}
}
