
# Who's that Pokemon Farcaster frame

To use with repl.it, create a `.replit` file with contents like this:

```
run = "node server.js"

modules = ["nodejs-20:v8-20230920-bd784b9"]
hidden = [".config", "package-lock.json"]

[nix]
channel = "stable-23_05"

[unitTest]
language = "nodejs"

[deployment]
deploymentTarget = "cloudrun"
ignorePorts = false
run = ["sh", "-c", "node server.js"]
```
