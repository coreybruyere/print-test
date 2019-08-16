---
layout: layouts/home.njk
title: Home
date: 2016-01-01T00:00:00.000Z
permalink: /
navtitle: Home
tags:
  - nav
---

# Iframe Print Test

This is a template for building a simple blog website with the [Eleventy static site generator](https://www.11ty.io), with deployment to [Netlify](https://www.netlify.com).

Includes [Netlify CMS](https://www.netlifycms.org) for WYSIWYG content editing, and [Netlify Forms](https://www.netlify.com/docs/form-handling) for processing your site's form data.

## Nothing other than the Iframe below should be printed

### PDF with object + iframe

<div class="iframe-wrap">
  <object data="https://www.w3.org/WAI/ER/tests/xhtml/testfiles/resources/pdf/dummy.pdf" type="application/pdf">
    <iframe src="https://docs.google.com/viewer?url=https://www.w3.org/WAI/ER/tests/xhtml/testfiles/resources/pdf/dummy.pdf&embedded=true"></iframe>
  </object>
</div>

### PDF with object + embed

<div class="iframe-wrap">
  <object data="ttps://www.w3.org/WAI/ER/tests/xhtml/testfiles/resources/pdf/dummy.pdf" type="application/pdf">
    <embed src="ttps://www.w3.org/WAI/ER/tests/xhtml/testfiles/resources/pdf/dummy.pdf" type="application/pdf" />
  </object>
</div>

### PDF with iframe only

<div class="iframe-wrap">
  <iframe src="https://research.google.com/pubs/archive/44678.pdf"
   width="800px" height="600px" >
</div>
