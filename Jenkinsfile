pipeline{
	agent any
	stages{
	stage('reading yml'){
	steps{
	def datas = readYml file: 'pipeline.yml'
	  echo "my name is ${datas.pipeline.name}"

	}
	}
	}
}
