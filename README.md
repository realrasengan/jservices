# Toc IRC Services
## Simple take on Nickname and Memo Services

When someone /quits, the services will create a nickname to hold that nickname.  When someone returns,
they simply msg their old nickname 'RELEASE' and they will automatically regain control of their nick.

Any messages received will be sent to them like a memoserv.

Additionally, emails received on port 25 will be forwarded to the nickname on the IRC network.

## Install
1. Download
```
git clone https://github.com/toc-irc/jservices
cd jservices
npm install node-mailin
```

2. Setup example.conf and rename
```
mv example.conf services.conf
```

3. Run
```
sudo node services.js
```

## Copyright

Copyright (c) 2020 Andrew Lee <andrew@imperialfamily.com>

All Rights Reserved.

