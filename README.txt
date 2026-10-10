# My Gallery - GitHub Ready

OLD BIN (with your links):
https://api.npoint.io/6161fabf116efcde0e19
Current product: Miles Morales - https://i.postimg.cc/PxJsx18N/miles-morales-5120x2880-24345.png

This zip contains:
- index.html = main site (cache-buster added, no hard reload needed)
- admin.html = admin with Netlify Function + GitHub Gist support + old bin links
- netlify/functions/save.js = makes POST work on Netlify

HOW TO USE:

OPTION A - Keep npoint (quick):
1. Upload this folder to Netlify (drag folder)
2. Admin password admin123
3. Add product -> POST works via /.netlify/functions/save -> same bin address forever

OPTION B - GitHub Pages + Gist (permanent, recommended):
1. Create Gist at gist.github.com with file products.json content []
2. Copy Gist ID
3. Create GitHub token at github.com/settings/tokens with gist scope
4. In admin.html enter Gist ID + Token and click Post to GitHub
5. Push this folder to GitHub repo -> Enable Pages
6. Now posting works forever, same Gist link

CACHE ISSUE FIXED:
All fetches use ?t=Date.now() + cache:no-store so no hard reload for any user.

OLD VERSION LINKS KEPT:
Your Miles Morales product is still in bin 6161fabf116efcde0e19
