node{
    stage("checkout"){
        git "https://github.com/DanaShteiman/project1.git"
    }
    stage("run 1.py"){
        bat "python 1.py"
    }
    stage("copy file"){
        bat "copy 1.py myapp.py"
    }
}
