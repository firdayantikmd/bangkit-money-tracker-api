# bangkit-money-tracker-api
This is the a simple app deployed to Google App Engine. The front end app can be found here https://github.com/firdayantikmd/bangkit-money-tracker.git.

## Prerequisites
1. You have to cerate a Google Cloud Storage Bucket to store the uploaded images.
2. You have to create a Cloud SQL instance and create a database and the `records` tabel using the provided script in this repository.

## How to deploy?
1. Create a Google Cloud Platform project: First, you need to create a new Google Cloud Platform project, or use an existing one, where you will deploy your application.
2. Activate Cloud Shell and open the Editor.
3. Clone this repository and change directory to `bangkit-money-tracker-api`.
```
cd bangkit-money-tracker-api
```
4. Use the gcloud app deploy command to deploy the application to App Engine. This command will upload the code and configuration files to Google Cloud Platform and will create a new instance of the application.
```
gcloud app deploy
```
