MUHAMMAD HAFEEZ — CHEF PORTFOLIO WEBSITE
========================================

FILES
- index.html: the complete responsive one-page portfolio website.
- README.txt: setup and publishing instructions.

BEFORE PUBLISHING — IMPORTANT
1. Open index.html and replace Mhaf99990@gmail.com  with your real professional email.
2. In the "Behind the Plate" section, replace the placeholder with your video:
   - Upload your edited video to YouTube as Public or Unlisted.
   - Open the video on YouTube, choose Share > Embed, and copy the iframe code.
   - In index.html, find:
       <div class="video-placeholder"> ... </div>
     Replace that whole div with the iframe, for example:
       <iframe width="100%" height="315"
         src="https://www.youtube.com/embed/VIDEO_ID"
         title="Behind the Plate - Muhammad Hafeez"
         frameborder="0"
         allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
         allowfullscreen></iframe>
   - Replace VIDEO_ID with the ID from your YouTube link.
3. Replace the sample dish photos with your own photos when possible. Only publish photos you have permission to use.
4. Add your earlier employer names, roles, and dates. Do not add unverified claims.
5. Test the site on your phone before sharing it with recruiters.

PUBLISH WITH GITHUB PAGES (FREE)
1. Sign in at https://github.com/
2. Create a new PUBLIC repository named: chef-portfolio
3. Upload index.html to the repository's top/root level (not inside a folder).
4. Open repository Settings > Pages.
5. Under Build and deployment, select "Deploy from a branch".
6. Choose branch "main" and folder "/ (root)", then Save.
7. Wait a few minutes. GitHub will show the published website URL on the Pages settings screen.
   It will usually look like: https://YOUR-USERNAME.github.io/chef-portfolio/

NOTE
- This website is a starter portfolio. The included photos are external sample images and are not photographs of your actual dishes.
- Your email and video are intentionally placeholders until you provide your details.
- Do not upload passport details, ID numbers, or other private documents to a public repository.
