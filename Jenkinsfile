pipeline{
	
	agent any
	environment {
		def datas = readYml file: 'pipeline.yml'
	}
	stages{
	stage('reading yml'){
	steps{
	
	  echo "my name is ${datas.pipeline.name}"

	}
	}
	}
}
