# angrybots-chunked-js

Demo is here: http://cosinusoidally.github.io/angrybots-chunked-js

If it fails to load you might want to try cloning the repo and loading it from localhost (with python -m SimpleHTTPServer or similar).

This is to illustrate a workaround that can be used to reduce the startup memory usage of large asm.js codebases in Chrome. Unfortunately it also regresses performance quite significantly.

This is a hacked together version of the WebGL version of the Unity AngryBots demo. It is based on the version in the https://github.com/lukewagner/AngryBotsPacked repo.
