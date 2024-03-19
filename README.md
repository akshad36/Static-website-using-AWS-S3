Prepare Your Website Files: First, you need to prepare your static website files. These could be HTML, CSS, JavaScript, images, etc. Make sure they are ready and organized in a folder structure.

Sign in to AWS Console: Go to the AWS Management Console and sign in to your AWS account.

Create an S3 Bucket:

Navigate to the S3 service.
Click on "Create bucket".
Choose a globally unique name for your bucket (this will also be your website URL).
Select the region where you want to create the bucket.
Keep the default settings for the rest of the configuration or adjust as needed.
Click "Create bucket".
Upload Website Files to S3 Bucket:

Once your bucket is created, select it from the list.
Click on the "Upload" button.
Upload all your website files and folders.
Make sure to set the correct permissions for your files so that they are publicly accessible.
Enable Static Website Hosting:

In the properties tab of your bucket, find the "Static website hosting" card.
Click on "Edit".
Select "Enable" for static website hosting.
Enter the name of your main HTML file (e.g., index.html) as the index document.
Optionally, you can also specify an error document.
Click "Save changes".
Set Permissions:

In the bucket's permissions tab, ensure that the bucket policy allows public read access. You can use a policy like the following:
json

Access Your Website:

Once the static website hosting is enabled, AWS will provide you with a website endpoint URL.
You can access your website using this URL.
Optional: You can also configure a custom domain name for your S3 static website by using Amazon Route 53 or a third-party DNS provider.

By following these steps, you'll have successfully created a static website using Amazon S3.
