Sciovirtual
==================================================
See the website: https://sciovirtual.org/

Netifly Link: https://sciovitrualtest.netlify.app/

Further Changes: https://docs.google.com/document/d/1AozPjwwfMY7HjGjCfOLzI6K8nSn-GvHvHJ985_Fyp44/edit

Even Further Changes: https://docs.google.com/document/d/1Aw9xO2Z9-NdUAPDilfXsjhdIYLP6_xMmSf5PTGxjRjc/edit

Timesaving Folder
--------------------------------------
Includes html files that shorten the time it takes to edit things.
Edit the code here
```html
<div id="sampleid"></div>
```
And here
```html
<script src="https://code.jquery.com/jquery-3.3.1.js" integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
    crossorigin="anonymous"></script>
  <script>
    $(function () {
      $("#sampleid").load("/sample.html");
    })
  </script>
```


Assets Folder
--------------------------------------
- Images
- Vendor files
- CSS

New HTML Files
----------------
Update this part to update the active status for the links in the navbar. Change the child number.
```css
.nav-item:nth-child(1)>a {
  color: lightgray !important;
}
.nav-item:nth-child(1):before {
  content: "";
  position: absolute;
  width: 36px;
  height: 3px;
  top: 0;
  left: calc(50% - 18px);
  background: #FF9900;
  border-radius: 1px;
}
#menu li:nth-child(1)>a {
  color: #FF9900;
}
```

