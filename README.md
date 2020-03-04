# google-gcloud-sdk-Installation
google-gcloud-sdk Installation error logging

## download
select google website https://cloud.google.com/sdk/docs/downloads-versioned-archives?hl=zh-cn download version

## Install
1.install in console mode
2. cd in google-cloud-sdk 
3. ./google-cloud-sdk/install.sh
## Error
There was an error when I executed the above code installation
“-bash: install.sh: command not found”
## solve
1.create 

console: touch .bash_profile

2.open  

console: open -e .bash_profile

3.add

console: source '/Users/me_project/google-cloud-sdk/path.bash.inc'
source '/Users/me_project/google-cloud-sdk/completion.bash.inc'

tips: The path where the SDK is located

4. save

console: source .bash_profile

