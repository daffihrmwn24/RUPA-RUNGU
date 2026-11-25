# Rupa Rungu — Studio portfolio
Static, dependency-free website with responsive navigation, search, category filters, grid/list, native dialog case studies, mixed media gallery, process accordion, journal and local brief export.

## Run
Serve the repository root with any static HTTP server. Vercel preset: Other. No build step.

## Add a project
Edit content.js. Example shape (do not publish until approved):
```js
{ id:"unique-id", title:"Approved title", category:"Film & Video", year:"2026", published:false, cover:"assets/approved-cover.jpg", coverAlt:"Description", description:"", context:"", challenge:"", approach:"", outcome:"", credits:[], media:[{type:"youtube",id:"VIDEO_ID",section:"Video",title:"Final film",approved:false}] }
```
Media types: photo (url), video (url), youtube (id), drive (id). Only approved:true media are rendered. Only published:true projects are rendered. The repository is public: NEVER commit confidential data even with published:false. Use publicly cleared assets only. The brief form is local only; no backend/contact delivery. Official logo and precise palette pending confirmation. No personal portfolio work was copied.
