@Library('pipeline-library-demo')_
 stage('Demo') {
     echo 'Hello world'
     sayHello 'Alex'
 }
 stage('init') {
     echo 'Hello world'
     sayHello 'Init'
 }
 stage('test') {
     echo 'Hello world'
     sayHello 'Test'
 }
 stage('Deploy') {
     echo 'Run the python script'
     node {
        mkobitVar.runMyPython()
     }
 }