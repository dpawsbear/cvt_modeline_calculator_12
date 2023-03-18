pipeline {
  agent {
    node {
      label 'build_server'
    }

  }
  stages {
    stage('build_host') {
      steps {
        echo 'build start'
      }
    }

    stage('build_wddm') {
      steps {
        echo 'build_wddm'
      }
    }

    stage('install host') {
      steps {
        echo 'install host'
      }
    }

    stage('install wddm') {
      steps {
        echo 'install wddm'
      }
    }

    stage('finish') {
      steps {
        echo 'log message'
      }
    }

  }
}