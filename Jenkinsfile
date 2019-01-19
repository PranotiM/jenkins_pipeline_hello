node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
node {
    stage('package'){
        echo "package"
    }
}
node {
    stage('install'){
        echo "install"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
