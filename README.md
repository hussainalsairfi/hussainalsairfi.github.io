# Hussain Al-Sairfi Research Website

Static GitHub Pages site prepared for **https://hussainalsairfi.github.io**.

## Upload now
1. Extract the ZIP file.
2. In the empty GitHub repository, click **uploading an existing file**.
3. Open the extracted folder and drag **all files and folders inside it** into GitHub. Do not upload the ZIP itself and do not upload the outer folder as one extra level.
4. Use commit message: `Publish academic research website`.
5. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then save.
6. The site should appear at **https://hussainalsairfi.github.io** after GitHub finishes deployment.

## What is included
- One profile homepage and a publication index.
- Dedicated machine-readable pages for 11 current research outputs, including the doctoral thesis.
- Google Scholar / Highwire citation meta tags.
- Schema.org JSON-LD for the researcher and every research output.
- Open Graph cards, sitemap, Atom feed, robots.txt, llms.txt, JSON-LD and CSV metadata.
- Maximum-crawl `robots.txt`, plus a search-only alternative.
- Original ionic-strength infographic; no third-party journal logos or copied figures.

## Future papers
Do **not** delete or rebuild the existing site. After a new paper is officially accepted online or published, add one new folder under `publications/`, add its card to `index.html` and `publications/index.html`, and update `sitemap.xml`, `llms.txt`, `feed.xml` and metadata. The included `metadata/publication_template.json` shows the required fields. Sending the DOI or final PDF is sufficient for a future update.

## Custom subdomain later
Keep **https://hussainalsairfi.bio** as the short public hub. After GitHub Pages works, a subdomain such as `research.hussainalsairfi.bio` can be connected through GitHub Pages and the domain DNS. Do not add a CNAME before the Pages site is live and the subdomain is entered in **Settings → Pages → Custom domain**.

## Rights
The site links to official publisher or institutional records. It does not redistribute journal PDFs. Upload a PDF only after confirming the applicable licence or repository-sharing right.
