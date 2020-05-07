# How to upload new versions

    aws --profile prod s3 sync --exclude ".git/*" . s3://sg-shotgunsoftware/tier1/cloudformation_templates
