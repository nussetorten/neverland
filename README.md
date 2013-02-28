neverland
=========

My girlfriend needs a place to store all of her camera RAW files.  What better opportunity to play around with AWS!  Neverland is a simple tool for Mac that lets you create and fill buckets in S3.  My goal is to automate zipping, uploading, downloading, and unzipping in as pleasant a way as possible.  I'll probably integrate a billing notification system as well using SNS topics, CloudWatch, etc.  The application will bind to an AWS account and initialize all necessary services.  Never worry about running out of space again!