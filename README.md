## Overview
This is a simple Node Express app used to explore Moment.js' path traversal vuln (CVE-2022-24785).

## Setup
```bash
git clone git@github.com:pS3ud0RAnD0m/momentjs.git # This requires ssh key-based auth since this repo is private.
cd momentjs
cat package.json # Change 'moment' to '2.29.4' if wanting to test bypasses of the current patch.
npm install
node app.js
```
