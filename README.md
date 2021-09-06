


Features:
• Good Integration with github and Heroku therefore use Travis 
as CI /CD tool
• Automatic integration with GitHub
• Repository access to build pull requests
• Support for 21 languages like Android, C, C#, C++, Java, 
JavaScript (with Node.js), Perl, PHP, Python, R, Ruby, etc
• Pre-installed build & test tools
• Available services - databases, message queues, etc.
• Deployment to multiple cloud services
• Encrypt secure environment variables or files
• Virtual machines recreated after every build
• CLI client and API for scripting
• Comes with free cloud-based hosting which does not 
require maintenance or administration.
How we perform CI /CD using Github travis 
and Heroku
We are working on application decided to add new feature .Therefore 
we add new feature ,commit changes and push to feature branch .if 
feature requirements are met , then changes will be pushed to Github 
and merge to master branch . For each push pull request Travis CI 
trigger and check build is successful and test pass . For every open 
pull request a review app is created in Heroku for review purposes
