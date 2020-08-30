# SpringAwsLambda

Use below command to compile this project
mvn clean install

It will generate 2 jar :
1.SpringAwsLambdaFunction-0.0.1-SNAPSHOT.jar
2.SpringAwsLambdaFunction-0.0.1-SNAPSHOT-aws.jar

In Lambdab upload 2nd file which extends with -aws.jar
mention handler with package
# com.cts.springcloudfunction.Welcome
