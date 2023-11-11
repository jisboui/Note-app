## Note-app

A basic note-taking app with Next.js 13 and Pocketbase. 

### Setup

1. Download Pocketbase from [pocketbase.io](pocketbase.io)
2. Navigate to the unzipped directory
`cd pocketbase_0.7.9_darwin_arm64`
3. Start Pocketbase:
`./pocketbase serve`
4. Open the [Admin UI](http://127.0.0.1:8090/_/), create collection, and update security rules to allow read/write access. 
5. Add `experimental: { appDir: true }` to `next.config.js`
6. run `npm run dev` in the terminal and navigate to `http://localhost:3000/`
