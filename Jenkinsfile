node {
    stage("checkout"){
        git 'https://github.com/rayaTS/first_github_ripo.git'
    }
    stage("install requirements"){
        sh "pip install -r requirements.txt"
    }
    stage("run script"){
        sh "python 1.py"
    }
}
