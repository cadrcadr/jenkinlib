#!groovy

@Library('jenkinslib') _     

def mytools = new org.devops.tools()



pipeline {
    agent { node {  label "test" }}

    stages {
        //下载代码
        stage("GetCode"){ 
            steps{  
                timeout(time:5, unit:"MINUTES"){   
                    script{ 
                        mytools.PrintMes("获取代码",'green')
                    }
                }
            }
        }
    }
}
