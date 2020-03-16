# How to upload new versions

    aws s3 sync . --exclude ".git/*" s3://sg-shotgunsoftware/tier1/cloudformation_templates
