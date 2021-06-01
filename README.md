Instructions
1.Step
    Open the Functions page on the Lambda console. Choose and filtered the functions with “auto” names.

2.Step
    Create a Function like below and see the details of functions . The functions should have the IAM roles with configured policies to access to the resources by Lambda Service. You can see the details of policy permissions attached to the role below . The role has permission of Start and Stop Functions. 

3. Step   
    The next step is trigger the Lambda function. That will run the function code . To see the existing trigger pass to the 4th step. Under Designer , choose Add trigger to add new one . > Set the trigger type to CloudWatch Events/EventBridge. > For Rule choose Create New Rule . > Configure the remaining options and choose Add.

4.Step 
    Click to the existing trigger to see details of the rules on Start and Stop jobs.


Notes: REF      https://aws.amazon.com/premiumsupport/knowledge-center/start-stop-lambda-cloudwatch/   