</script>

</head>

<body>

< div  stili = "konum: mutlak; genişlik: 100 piksel; yükseklik: 297 piksel; z-endeksi: 1; sol: 35 piksel; üst: 41 piksel"  id = "katman1" >
<div style="position: absolute; width: 100px; height: 297px; z-index: 1; left: 35px; top: 41px" id="layer1">
  <title>Copy and Paste</title>             

    <script language="javascript" type="text/javascript"> 

        function onCopy(event){ 

            var selection = window.getSelection(); 

            event.clipboardData.setData("text/html","<i>" + selection + "</i>"); 

            event.preventDefault(); 

        } 

 

        function onCut(event){ 

             var selection = window.getSelection(); 

             event.clipboardData.setData("text/html","<i>" + selection + "</i>"); 

             var range = selection.getRangeAt(0); 

             range.extractContents(); 

             

            event.preventDefault(); 

        } 

 

        function onPaste(event){ 

            var insertion = document.createElement("b"); 

            insertion.innerHTML = event.clipboardData.getData("text/html"); 

             var selection = window.getSelection(); 

             var range = selection.getRangeAt(0); 

             range.insertNode(insertion); 

            event.preventDefault(); 

        } 

    </script> 

</head> 

<body onCopy="onCopy(event)" 

     onPaste="onPaste(event)" 

     onCut="onCut(event)"> 

<p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium  

doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore  

veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam 

voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur  

magni dolores eos qui ratione voluptatem sequi nesciunt.</p> 

</body> 

</html>
