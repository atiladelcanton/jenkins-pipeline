def getGitBranchName() {


   def branchName = scm.branches[0].name


   branchName = branchName.replace('/','-').toLowerCase()


   return branchName


}

pipeline {
	agent any

    stages {
         stage('Branch') {
            echo scm
        }
    }
}