# image-lambda

- a description of how to use your lambda.
* Upload an image and the lambda will resize it for you and place it into a new bucket.

- A description of any issues you encountered during deployment of this lambda.
- Still working out some bugs, recieved an error

* In the README add a description of how to use your lambda,
- a description of any issues you encountered during deployment of this lambda, and an image and thumbnail that your Lambda processed.

- My issue (-zip-file fileb://function.zip --handler index.handler --runtime nodejs12.x \
--timeout 10 --memory-size 1024 \
--role arn:aws:iam::myID(ITookitout):role/lambda-s3-role --cli-binary-format raw-in-base64-out)
- I have the lambda in a file but having it actually connect to my account from my repo is causing problems.  I have to work through this again.