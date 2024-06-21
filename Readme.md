To check if aws is configured or not, run "aws configure list"
$ aws configure list
      Name                    Value             Type    Location
      ----                    -----             ----    --------
   profile                <not set>             None    None
access_key     ****************5TMJ shared-credentials-file    
secret_key     ****************brAL shared-credentials-file    
    region                us-east-1      config-file    ~/.aws/config

To make sure that github-actions can interact with aws, 
Settings => Secrets and Variables => Actions => New Repository Secret 
AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY

Currently, aws use has administrative previlleges. But, you should always follow the principle of least previlleges while accessing outside of training environent.

