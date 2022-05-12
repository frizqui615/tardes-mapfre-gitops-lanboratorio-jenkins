pipeline {
<<<<<<< HEAD

agent any



stages {

stage('Hello') {

steps {

echo 'Hello World'

}

}

stage('Secreto') {

agent {label 'docker-agent'}

steps {

sh """

hostname

pwd

ls -la /

"""

}

}

}

=======
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
>>>>>>> 2f8057fb8963f66506c515f026a46b153570cae3
}
