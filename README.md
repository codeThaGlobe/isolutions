# FileMakerAndAPIs.com

**Built with**
 - BS4
 - Gulp
 - BrowserSync


**Hosted on AWS S3**
*To deploy with AWS CLI from command line use the following line which excludes unneeded files:*

    aws s3 sync . s3://filemakerandapis.com --exclude "*_layered_files/*" --exclude "*node_modules/*" --exclude "*sass/*" --exclude "*.py" --exclude "*.json" --exclude "*.git*" --exclude "**/*.DS_Store" --exclude "*.DS_Store" --exclude "*.map" --exclude "gulpfile.js" --exclude "*.md"





