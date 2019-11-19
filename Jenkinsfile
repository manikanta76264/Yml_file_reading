pipeline{
	agent any
	stages{
	stage('reading yml'){
	steps{
	  datas = readYml file: 'pipeline.yml'
	  echo "my name is ${datas.pipeline.anme}"

	}
	}
	}
}
