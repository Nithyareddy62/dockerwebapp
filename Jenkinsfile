node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/repository/docker/nithyareddy62/demo', 'dockerHub') {

        def customImage = docker.build("miltonc/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
