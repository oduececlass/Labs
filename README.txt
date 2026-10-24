Circuit Studio Labs — GitHub folder package

Password: Labs (case-sensitive)

Upload the extracted CONTENTS of this folder to your GitHub repository. Keep index.html at the top level and preserve every subfolder and filename. Upload the files and folders, not the ZIP as a website.

Folder layout
index.html       Main landing page and password prompt
assets/          Page styles and JavaScript
videos/          Five ordinary MP4 files; replace individually when needed
captions/        English SRT and VTT caption files
images/          Video preview pictures
studio/          Current Circuit_Studio_Core.html, including reset and view exports
guides/          Printable student quick guide
circuits/        CS/CE practice circuits and vector references
.nojekyll        Static-file marker

Use the GitHub Pages URL for the deployed index.html. No absolute repository URL is hard-coded, so the same folders work at a domain root or in a repository subpath.

All files in this package are below 25,000,000 bytes. The largest file is Circuit Studio Core, approximately 21.9 MB. Videos are approximately 3–4.2 MB each. Videos load individually when selected; they are not embedded in index.html.

For local use, extract the ZIP and open index.html in a current browser. The separate Core HTML file can also be opened directly. The password prompt checks Labs; no video folders need to be selected.

Password scope: this is a classroom landing-page gate, not server authentication. The separate video, guide, and Core files remain publicly accessible through their direct URLs in a public repository. The earlier single-file encrypted bundle is not used in this package.

To update a video, replace its MP4 in videos/ while keeping the filename. Replace the matching SRT/VTT files in captions/ if the narration changes. To update Circuit Studio, replace studio/Circuit_Studio_Core.html. Video titles and chapter times are in the metadata script in index.html.
