# Reading Class 37 

1- What is Amazon S3?

- Amazon Simple Storage Service, is a scalable and secure object storage service provided by Amazon Web Services (AWS). It is designed to store and retrieve any amount of data from anywhere on the web. S3 is widely used for various purposes, including data backup, web hosting, application hosting, content distribution, and big data analytics.

2- List at least 3 features that it offers to its users.

- Scalability, Accessibility, Security.

3- What is an object key?

- Object key is a unique identifier assigned to each object stored in an S3 bucket. The object key serves as the reference or name for the object within the bucket and is used to organize and retrieve data stored in Amazon S3. 

4- Which dependencies are needed to install Amplify AWS S3 to your ndroid application?

- dependencies {
    implementation 'com.android.support:appcompat-v7:28.0.0'
    implementation 'com.amplifyframework:core:1.24.0'
    implementation 'com.amplifyframework:core-android:1.24.0'
    implementation 'com.amplifyframework:aws-storage-s3:1.24.0'
}


5- What is needed in order to upload data to your bucket?

- Set Up AWS Amplify
- Add Required Permissions
- Initialize Amplify in Application
- Upload Data to S3

6- what method(s) initialize(s) the Amplify Auth and Storage categories?

- Initialize the Amplify categories, including Auth and Storage, in the onCreate method of Application class or the onCreate method of your main activity. 