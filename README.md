# Setup

### Run
```bash
npm install
npm run dev
```
### Deploy
```bash
npm run build
git add dist -f 
git commit -m "..."
git subtree push --prefix dist origin gh-pages
```