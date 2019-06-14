pipeline{
        agent any

                stages{

                        stage('build'){steps{echo "this is build stage"}}
                        stage('test'){steps{echo "this test stage"
                                            input ("do you want to continue Y/N")}
                               }
                        stage('deploy'){steps{echo "this deploy stage"}}


                        }

}
