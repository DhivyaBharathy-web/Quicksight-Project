Set Up Amazon S3 Bucket
Go to the AWS Management Console and open the Amazon S3 console.
Click "Create bucket" and enter a unique name for your bucket.
In the "Properties" section, enable "Static website hosting."
Upload your website files to the bucket.
Set the bucket permissions to allow public access.
Purchase a Custom Domain through Amazon Route 53
Open the Amazon Route 53 console.
Choose "Domain registration" and then "Register domain."
Follow the prompts to purchase your custom domain.
In the "Route 53 hosted zones," create a new record set.
Enter your S3 bucket's endpoint as the alias target.
Open the Amazon S3 console and click "Create Bucket."
Name the bucket (e.g., "dhivya-amazon-project") and keep the settings as default.
Upload the CSV file and the "manifest.json" file into the bucket.
Replace the URL in the "manifest.json" file with the S3 URL of your dataset.
Open the AWS management console and navigate to Amazon Quicksight.
Sign up for a free trial of the Enterprise edition if you don't have an account.
Select Amazon S3 and tick the box for the S3 bucket you created.
Enter the link to your "manifest.json" file and connect to Quicksight.
Select "interactive sheet" to start creating visualizations.
Drag fields into the graph to create visualizations (e.g., Most popular brands).
Sort, filter, and customize the graphs as desired.
Experiment with different types of graphs like bar charts, pie charts, line graphs, etc.
