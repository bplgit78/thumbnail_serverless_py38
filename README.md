Serverless lambda
Stephan Marek's "AWS Lambda and the Serverless Framework - Hands-On Learning!" course uses python 2.x and is outdated but an excellent source for learning serverless.
This code updates it to use python 3.8. The main difference is the usage of io.ByteIO instead of cStringIO.StringIO as cStringIO is not available in python 3.8
