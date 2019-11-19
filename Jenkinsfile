pipeline{
	
	agent any
	environment {
		def datas = readYaml file: 'pipeline.yml'
	}
	stages{
	stage('reading yml'){
	steps{
	
	  echo "my name is ${datas.pipeline.name}"

	}
	}
	}
}
