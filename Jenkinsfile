node {
    deleteDir()
    
    def CLEANED_BRANCH_NAME = env.BRANCH_NAME.replaceAll('/', '-')
    
    stage("Deploy Application") {
        switch (CLEANED_BRANCH_NAME) {
            case "master":
                echo "master build"

            default:
                echo "branch build build"
        }
    }
}
