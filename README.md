# Hubzilla Project Website

## Overview

This repo contains the Hubzilla project webpage elements, which can be imported using the website import tool. After importing the elements, you can visit `https://your.hub/page/your_channel/hubzilla` to view the website. 


## Assets
If you wish to host the page assets yourself (CSS, JS, images, etc) you will need to copy the `assets/{vendor,js,css,img}` folders to a publicly accessible location and update the paths accordingly in the `pages/hubzilla-project/hubzilla-project.html` source file.

## Notes

* **The importing channel must have AllowCode permission**. Administrators set this permission on a per-channel basis at `/admin/channels`.

* Due to a quirk in the import process, the presence of a `.git` folder in the uploaded zip file causes a failure, so for convenience the `hubzilla-website.zip` file has been created for you to upload directly.
