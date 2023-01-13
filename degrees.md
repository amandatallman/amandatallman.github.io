---
layout: post
title: Flake it till you make it
subtitle: Excerpt from Soulshaping by Jeff Brown
---

<html>
  <head>
    <title>Title of the document</title>
  </head>
  <body>
    <h1>PDF Example with iframe</h1>
    <iframe src="https://github.com/amandatallman/work-samples/blob/d4ce4e1fcaedd67c3a4540e4640b7b9fb2204e6e/degrees/College%20Awards.pdf" width="100%" height="500px">
    </iframe>
  </body>
</html>

<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://documentservices.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "<YOUR_CLIENT_ID>", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "https://github.com/amandatallman/work-samples/blob/d4ce4e1fcaedd67c3a4540e4640b7b9fb2204e6e/degrees/College%20Awards.pdf"}},
			metaData:{fileName: "Bodea Brochure.pdf"}
		}, {embedMode: "IN_LINE"});
	});
</script>