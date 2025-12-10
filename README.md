# heroku-multi-manager
# Heroku Multi Manager

1. Install:
   npm install

2. Set environment variables (recommended):
   export GITHUB_TOKEN=ghp_xxx_newtoken
   export PORT=3000

   (Windows PowerShell)
   $env:GITHUB_TOKEN="ghp_xxx_newtoken"

   Alternatively, you may copy the token into backend/config.js as GITHUB_TOKEN (NOT recommended).

3. Start:
   npm start

4. Open: http://localhost:3000
   - Paste your Heroku API Key in the settings input and click Save.
   - Click "Refresh apps" to load apps for that Heroku account.
   - Multi-select apps and run actions. For link/redeploy, enter `owner/repo` into the Action Data input.
