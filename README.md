## Overview
This is a simple Node Express app used to explore Moment.js' path traversal vuln (CVE-2022-24785).

## Setup
```bash
git clone https://github.com/pS3ud0RAnD0m/momentjs.git
cd momentjs
cat package.json # Change 'moment' to '2.29.4' if wanting to test bypasses of the current patch.
npm install
node app.js
```
