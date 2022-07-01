pipeline {
    agent any

    stage ('build') {
        steps {
            echo 'hello'
        }
    }
    stage ('test') {
        steps {
            sh './vendor/bin/phpunit --log-junit test.xml -c phpunit.xml'
        }
    }
}