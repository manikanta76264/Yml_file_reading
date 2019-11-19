pipeline{
	def datas = readYml file: 'pipeline.yml'
	agent any
	stages{
	stage('reading yml'){
	steps{
	
	  echo "my name is ${datas.pipeline.name}"

	}
	}
	}
}
