#whatsapp-clone

###Installation

 1. Clone repo
 2. `npm install`
 3. Make the following soft links:
 	- "node-modules" to "api/node-modules"
 	- "package.json" to "api/package.json"
 	- "package-lock.json" to "api/package-lock.json"
 	- "src/declarations" to api/declarations.d.ts"
 	- "src/declarations" to api/server/declarations.d.ts"
 
 4. Apply patch https://github.com/Urigo/meteor-client-bundler/issues/54
 5. `ionic serve`