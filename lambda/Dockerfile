# Use the official AWS Lambda Python image as the base image
FROM public.ecr.aws/lambda/python:3.9

# Copy the function code
COPY app.py ${LAMBDA_TASK_ROOT}

# Set the command to invoke the Lambda function handler
CMD ["app.lambda_handler"]
