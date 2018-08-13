# jquery.qrcode.js

 edit jquery.qrcode.js , let it cant generate qrcode with ImgUrl or  Base64 imgData, return qrcode with circle logo image

## with imgUrl

```

jQuery('#qrcodeCanvas').qrcode({
		     	 render    : "canvas",
		         text    : "http://sorryu.cn",
		         width : "200",               //二维码的宽度
                 height : "200",              //二维码的高度
                 background : "#ffffff",       //二维码的后景色
                 foreground : "#000000",        //二维码的前景色
                 src: 'img/shaoye.jpeg'
             });

             ```
             
## with  Base64 imgData

```
jQuery('#qrcodeBase64Canvas').qrcode({
		     	 render    : "canvas",
		         text    : "http://sorryu.cn",
		         width : "200",               //二维码的宽度
                 height : "200",              //二维码的高度
                 background : "#ffffff",       //二维码的后景色
                 foreground : "#000000",        //二维码的前景色
                 src: 'baseImgData' 
		     }); 

```
