Hendrix George — Digital Portfolio (self-hosted version)

WHAT'S HERE
  index.html   the whole blog (one file)
  images/      put your photos here

ADD YOUR PHOTOS
  1. Save your studio photo as images/studio.jpg and your guitar portrait as images/about.jpg
  2. In index.html, find PHOTOS and set:
       hero: "images/studio.jpg",
       about: "images/about.jpg"

EDIT POSTS
  Open index.html in any text editor and scroll to the CONTENT section near the bottom.
  - Each week is one entry in POSTS. Paste paragraphs into body:[ "...", "..." ].
  - Change status:"draft" to status:"published" when a week is ready.
  - Add a YouTube video:  { type:"youtube", label:"YouTube Video", id:"VIDEO_ID" }
    (VIDEO_ID is the part after watch?v= in the YouTube link)
  - Add an interactive site: { type:"web", label:"Name", url:"https://...", embed:"https://..." }
  - New subject later: give posts a different subject:"..." and a filter appears automatically.
    Leave week out (or set week:null) for posts that aren't weekly.
  - Add references to BIBLIOGRAPHY.

PUT IT ONLINE (free options)
  Netlify Drop: go to app.netlify.com/drop and drag this whole folder onto the page.
  GitHub Pages: make a repository, upload these files, then Settings > Pages > Deploy from branch.
