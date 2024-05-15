pipeline {
    agent {
        label 'agent1'
    }

   
    stages {
        stage('parameterStage') {
           steps {
				echo 'Hello World'
				//redirigir la salida estándar (stdout) y la salida de error (stderr) a la consola agregando 2>&1 
                sh "bash jobscript.sh 2>&1"
			}
        }
    }
}