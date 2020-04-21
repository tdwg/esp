---
title:  "How to contribute"
---

This site serves as a place to aggregate resources related to georeferencing for paleobiology specimens, and was initially developed in April 2020 to accompany the virtual workshop [Georeferencing for Paleo: Refreshing the approach to fossil localities](2020-workshop). We expect this site to persist for the foreseeable future, and as such encourage ongoing contributions. Below you will find a description of how to contribute content. If you have questions, they can be submitted as a [GitHub issue](https://github.com/tdwg/esp/issues) or (for now) emailed to Erica Krimmel (ekrimmel@fsu.edu).

### How this site is arranged

Within this directory ([georeferencing]({{ site.baseurl }}/_georeferencing)), resources are grouped by topic, e.g. "standards." Each topic has its own subdirectory as well as its own markdown file. Currently the following topics exist (links are to subdirectories):
- [data-management]({{ site.github_path }}/_georeferencing/data-management)
- [data-quality]({{ site.github_path }}/_georeferencing/data-quality)
- [geospatial-resources]({{ site.github_path }}/_georeferencing/geospatial-resources)
- [policies]({{ site.github_path }}/_georeferencing/policies)
- [standards]({{ site.github_path }}/_georeferencing/standards)
- [workflows]({{ site.github_path }}/_georeferencing/workflows)

You can contribute content to any of these topics in one of two ways: **(1)** upload a file to the most appropriate subdirectory, or **(2)** edit the markdown file to include links to content hosted on another website or videos hosted on YouTube/Vimeo. See below for detailed instructions.

This GitHub repository has restricted permissions, so please be aware the files you upload or change will be submitted as pull requests. If you would like to learn more about the Git workflow, please see [Understanding the GitHub flow](https://guides.github.com/introduction/flow/).

### Upload a file

#### Documents

You can upload text documents in any of the following formats: pdf, doc, csv, xlxs. Uploading a document means that it will be stored in this GitHub repository for use by the TDWG Earth Sciences and Paleobiology Interest Group, i.e. you are sharing the document widely.

How you name the document is important because the filename determines the title that appears on this site. Capitalize as you would in a sentence, use hyphens in place of spaces, and use underscores as a break. For example `Georeferencing-for-Research-Use_Seltmann-et-al-2018.pdf` becomes `Georeferencing for Research Use - Seltmann et al 2018`, and `KUMIP-Georeferencing-protocol_2013.docx` becomes `KUMIP Georeferencing protocol - 2013`. Avoid all punctuation other than hyphens and underscores. Including a year is helpful to other users.

After you upload your document, GitHub will automatically format and add it to this site on the page that corresponds with the subdirectory you uploaded it to. For example, a document uploaded to the [workflows subdirectory]({{ site.github_path }}/_georeferencing/workflows) will appear on the [workflows]({{ site.baseurl }}/georeferencing/workflows) page.

#### Images

You can upload images in any of the following formats: jpg, jpeg, png. Uploading an image means that it will be stored in this GitHub repository for use by the TDWG Earth Sciences and Paleobiology Interest Group, i.e. you are sharing the document widely.

How you name the image is important because the filename determines the title that appears on this site. Capitalize as you would in a sentence, use hyphens in place of spaces, and use underscores as a break. For example `LACMIP-EMu-Sites_IP-Locality-1-2020.png` becomes `LACMIP EMu Sites - IP Locality 1 2020`. Avoid all punctuation other than hyphens and underscores. Including a year is helpful to other users.

After you upload your image, GitHub will automatically format and add it to this site on the page that corresponds with the subdirectory you uploaded it to. For example, an image uploaded to the [workflows subdirectory]({{ site.github_path }}/_georeferencing/workflows) will appear on the [workflows]({{ site.baseurl }}/georeferencing/workflows) page.

### Edit the markdown file

#### Links to external resources

Adding a new link to an external resource is very simple. Find the markdown document for the page you wish to edit, for example, if you want to edit the [workflows]({{ site.baseurl }}/georeferencing/workflows) page, you will find the document called [workflows.md]({{ site.github_path }}/_georeferencing/workflows.md). Copy the code `- [title](url)` onto a new line under "Links to external resources" and replace "title" with your desired title and "url" with the link. You can add any descriptive text after the closing parenthesis.

#### Videos

Videos displayed on this site must be hosted on either YouTube or Vimeo. Once you have posted your video to YouTube/Vimeo, make a note of the video id. You can find the id by clicking the share button beneath your video and looking for an alphanumeric id that is included in the URL, e.g. if YouTube gives you "https://youtu.be/RlSwsE22nX0" then the video id is "RlSwsE22nX0" or if Vimeo gives you "https://vimeo.com/409848305" then the video id is "409848305."

Now, find the markdown document for the page you wish to edit, for example, if you want to edit the [workflows]({{ site.baseurl }}/georeferencing/workflows) page, you will find the document called [workflows.md]({{ site.github_path }}/_georeferencing/workflows.md). Copy the code {% raw %}`{% include iframe.html videoid = "" source = "" %}` {% endraw %}onto a new line under "Videos." Copy-paste your id in between the quotation marks for "videoid" and type either "youtube" or "vimeo" in between the quotation marks for "source."
