RENDER FIX

Because Render kept failing on pandas metadata generation in native Python mode,
this version uses Docker to guarantee Python 3.11.9 and avoid the pandas build issue.

How to deploy:
1. Create a new GitHub repository.
2. Upload ALL files from this folder.
3. Commit and push.
4. In Render:
   - New +
   - Web Service
   - Connect GitHub repo
   - IMPORTANT: set Environment / Language to Docker
5. Deploy.

Do not use the old Python runtime settings for this version.
Do not enter build or start commands manually.
Render will use the Dockerfile automatically.
