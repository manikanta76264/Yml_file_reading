pipeline{
	agent any
	stages{
	stage('reading yml'){
	steps{
		sript { datas = readYml file: ('pipeline.yml')}
	  echo "my name is ${datas.pipeline.anme}"

	}
	}
	}
}
