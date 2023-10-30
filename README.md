## Note-app

A basic note-taking app with Next.js 13 and Pocketbase. 

### Setup

1.after cloning the repo : 
`cd [directory]`

2. Download Pocketbase from [pocketbase.io](pocketbase.io)
3. Navigate to the unzipped directory
`cd pocketbase_0.7.9_darwin_arm64`
4. Start Pocketbase:
`./pocketbase serve`
5. Open the [Admin UI](http://127.0.0.1:8090/_/), create collection, and update security rules to allow read/write access. 
6. Add `experimental: { appDir: true }` to `next.config.js`
7. run `npm run dev` in the terminal and navigate to `http://localhost:3000/`
