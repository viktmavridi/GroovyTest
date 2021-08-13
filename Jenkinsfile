node {
  stage('SampleTryCatch') {
    try {
      sh 'exit 1'
    }
    catch (exc) {
      echo 'Something didn't work and got some exceptions'
      throw
    }
  }
}
