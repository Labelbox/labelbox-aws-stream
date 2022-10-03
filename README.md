# Data Streaming with AWS using AWS Lambda Functions

## This repo will provide with 3 deployable Lambda Functions:
 * **stream_data_rows** - This will create a Labelbox data row every time a new asset is uploaded to the AWS bucket
 * **update_metadata** - This will update Labelbox Metadata for existing data rows any time an object's metadata is modified in AWS
 * **delete_data_rows** - This will delete a data row every time an asset is deleted in the AWS bucket


Prerequisites:
1. Set up Delegated Access to Labelbox, and ensure that the default setting is to the target bucket.
    * See how here: https://docs.labelbox.com/docs/import-aws-s3-data
2. Only files supported by Labelbox will be uploaded
    * See latest supported data types here: https://docs.labelbox.com/docs/supported-data-types
3. The AWS account performing these steps has access to the AWS bucket and permissions to create Lambda functions
4. The Labelbox account performing these steps has Admin-level permissions in a Labelbox organization

## How to Use:
1. Authenticate your AWS CLI in your Terminal:
```

```
2. 
```
```
3. Create / Redeploy your AWS function from GitHub:

4. Clone Repo and Define Variables:
```
git clone https://github.com/Labelbox/labelbox-aws-stream.git
cd labelbox-aws-stream
AWS_BUCKET_NAME="my-bucket"
LABELBOX_API_KEY="my-api-key"
LABELBOX_INTEGRATION_NAME="my-integration-name"
```
Deploy ```stream_data_rows```:
```
```
Deploy ```update_metadata```:
```
```
Deploy ```delete_data_rows```:
```
```
