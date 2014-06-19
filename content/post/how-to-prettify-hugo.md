---
title: "How To Prettify Hugo"
description: "This quick post tells you how to get prettify code syntax highlighting over your hugo blogs."
date: "2014-06-19"
categories:
  - "hugo"
  - "prettify"
tags:
  - "hugo"
  - "prettify"
---

If you are looking for a quick way to add code syntax highlighting to your Hugo blog, this is for you.  Copy and paste the code below your jquery include in layouts/chrome/footer.html

````html
<script src="https://google-code-prettify.googlecode.com/svn/loader/run_prettify.js"></script>
<script type='text/javascript'>
	// Find any pre code blocks from markdown and add syntax highlighting
  	$( document ).ready(function() {
	    $(this).find("pre").addClass("prettyprint"); 
	});
</script>
````