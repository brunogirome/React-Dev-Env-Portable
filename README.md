<link rel="stylesheet" href="editormd/css/editormd.css" />
<div id="test-editor">
    <textarea style="display:none;">
	![React-Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/256px-React-icon.svg.png)	![Node-Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/256px-Node.js_logo.svg.png)	![Git-Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/256px-Git-logo.svg.png)	![VSCode-Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Visual_Studio_Code_1.18_icon.svg/128px-Visual_Studio_Code_1.18_icon.svg.png)
##Content

###NodeJS
Version: **x64** 10.16.3 
[Source](https://github.com/crazy-max/nodejs-portable "Source")

####Visual Studio Code
Version: **x64** 1.38.1
[Source](https://code.visualstudio.com/Download "Source")

####Git Portable
Version: **x64** 2.23.0
[Source](https://git-scm.com/download/win "Source")

####Fira Code (Font)
Version: v.2
[Source](https://github.com/tonsky/FiraCode "Source")

####Font Loader
Version: 2.1
[Source](https://www.trishtech.com/font-loader/ "Source")

---

## First Git Setup

#####Generating SSH Key: 
`$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`

#####Cliping SSH Key:
`$ clip < ~/.ssh/id_rsa.pub`

>######Adding server origin: 
>`git remote add origin http:\\link-to-repository.com.git`

---

##Useful links

[Git Guide](https://rogerdudler.github.io/git-guide/index.pt_BR.html "Source")
    </textarea>
</div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="editormd/editormd.min.js"></script>
<script type="text/javascript">
    $(function() {
        var editor = editormd("test-editor", {
            // width  : "100%",
            // height : "100%",
            path   : "editormd/lib/"
        });
    });
</script>