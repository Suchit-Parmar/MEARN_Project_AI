# TODO: Fix Vercel Build - Three.js Incompatibility

## Steps:
1. ✅ [Complete] Update frontend/package.json: 
   - three -> ^0.169.0
   - @react-three/drei -> ^9.122.0

2. [Pending] cd frontend && npm install

3. [Pending] cd frontend && npm run build (verify fix)

4. [Pending] git add . && git commit -m "fix: update three.js to resolve BatchedMesh import error" && git push

5. [Pending] Retry Vercel deploy
