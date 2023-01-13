---
layout: post
title: Flake it till you make it
subtitle: Excerpt from Soulshaping by Jeff Brown
---

<!--Get the samples from https://www.adobe.com/go/pdfembedapi_samples-->
<!DOCTYPE html>
<html>
<head>
 <title>Adobe Acrobat Services PDF Embed API Sample</title>
 <meta charset="utf-8"/>
 <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"/>
 <meta id="viewport" name="viewport" content="width=device-width, initial-scale=1"/>
</head>
<body style="margin: 0px">
 <div id="adobe-dc-view"></div>
 <script src="https://documentservices.adobe.com/view-sdk/viewer.js"></script>
 <script type="text/javascript">
    document.addEventListener("adobe_dc_view_sdk.ready", function()
    {
        var adobeDCView = new AdobeDC.View({clientId: "c54db441c1f649a8b2a724cbf8918ffc", divId: "adobe-dc-view"});
        adobeDCView.previewFile(
       {
          content:   {location: {url: "https://github.com/amandatallman/work-samples/blob/3e5e4a2c84b3f88748aa9c8cce819704e26aad1b/McIntosh%20AMT.pdf"}},
          metaData: {fileName: "Bodea Brochure.pdf"}
       });
    });
 </script>
</body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title>Title of the document</title>
  </head>
  <body>
    <h1>PDF Example with iframe</h1>
    <iframe src="https://github.com/amandatallman/work-samples/blob/3e5e4a2c84b3f88748aa9c8cce819704e26aad1b/McIntosh%20AMT.pdf" width="100%" height="500px">
    </iframe>
  </body>
</html>