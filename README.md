# All Initial Files in /data
- flows.json
- flows.cred.json
- package.json
- settings.js

# flows.json
Your flows will be stored in the file called flows.json within the container.

# flows.cred.json
Your credentials will be stored in the file called flows_cred.json within the container.

# package.json
Your image information will be stored in the file called package.json within the container.

# settings.js
Your node-red settings will be stored in the file called settings.js within the container.

Makesure to specify your own secret, set the following property.
```
    ...

    credentialSecret: "d10774caafec8e49e22d40969852cbad5ca9cadde885ff31d69d4f4f59dad2ec",

    ...
```
