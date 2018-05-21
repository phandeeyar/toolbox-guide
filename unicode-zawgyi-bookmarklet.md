---
description: >-
  Zawgyi force and Unicode is a browser script used to change browser font to
  unicode or zawgyi forcefully.It works on bookmark bar.
---

# Unicode/Zawgyi Bookmarklet

You can create a bookmark by click on Star button in your address bar.\( I tested on google chrome. So, it may be in different place in other browsers \).Create a bookmark and go to edit bookmark. Copy the following code and name the bookmark to zawgyi and unicode. Whenever your browser is unicode and you want to show zawgyi in browser, click on zawgyi bookmark. Then, all the words including typing will change to zawgyi instantly . The same way will work for unicode.



![Screen Shot 2017-08-09 at 11.40.24 AM.png](https://lh5.googleusercontent.com/ZwIQriNuEStIrtAvF1_BIPmAipF2h-mjD_-73nOUljS6TdLaKDEgfKqZDa9Dk0cnk70pC_-Pia0la8mcFbJmC8rpo2tJH31bk_3STWxX668QsPxIyyQc8QhhYZZ_k2PJCFoxP6kD)

**You can see zawgyi force and unicode force in the following screenshot.**  


![Screen Shot 2017-08-09 at 11.39.19 AM.png](https://lh3.googleusercontent.com/ApzWelFZRONAm6jkOgfnShEyukJlpDUTCgR3XERQqFYRK19Nudbm5dsWVy1q42I6x-M3WgugPXysRaadRE8ck7zJIQHPDWt1YM9Fet1QHHG3HboJN_6qFOf9UrHzQC-vRQflFQ_E)

### Zawgyi Force

Copy the following code and put it in bookmark bar. Note that it needs Zawgyi One font to work. Download Zawgyione font in [here.](https://www.rfa.org/burmese/help/ZawgyiOne.ttf)

```javascript

javascript:(function(){fontfamily='Zawgyi-One'; document.getElementsByTagName('body')[0].style.fontFamily=fontfamily; var tag=['body','p','li','span','textarea','input','div','a','td','h1','h2','h3']; var p; for(j=0;j<tag.length;j++){ if(document.getElementsByTagName(tag[j])!=null) {p=document.getElementsByTagName(tag[j]); for(i=0;i<p.length;i++) { if( p[i].style !=undefined){ p[i].style.fontFamily=fontfamily;} } } } var iframe=document.getElementsByTagName('iframe'); for(k=0;k<iframe.length;k++) { doc=iframe[k].contentDocument;for(j=0;j<tag.length;j++){if(document.getElementsByTagName(tag[j])!=null) { p=doc.getElementsByTagName(tag[j]); for(i=0;i<p.length;i++) { if( p[i].style !=undefined){ p[i].style.fontFamily=fontfamily;} } } } } })();
```

### Unicode Force

Copy the following code and put it in bookmark bar. Note that it needs pyidaungsu font to work. Download Pyidaungsu font in [here.](http://www.unicode.today/)

```javascript
javascript:(function(){fontfamily='Pyidaungsu'; document.getElementsByTagName('body')[0].style.fontFamily=fontfamily; var tag=['body','p','li','span','textarea','input','div','a','td','h1','h2','h3']; var p; for(j=0;j<tag.length;j++){ if(document.getElementsByTagName(tag[j])!=null) {p=document.getElementsByTagName(tag[j]); for(i=0;i<p.length;i++) { if( p[i].style !=undefined){ p[i].style.fontFamily=fontfamily;} } } } var iframe=document.getElementsByTagName('iframe'); for(k=0;k<iframe.length;k++) { doc=iframe[k].contentDocument;for(j=0;j<tag.length;j++){if(document.getElementsByTagName(tag[j])!=null) { p=doc.getElementsByTagName(tag[j]); for(i=0;i<p.length;i++) { if( p[i].style !=undefined){ p[i].style.fontFamily=fontfamily;} } } } } })();
```

### Credit

The script was created by Saturn God.  ****[**blog.saturngod.net**](http://blog.saturngod.net/knowledgebase/myanmar-bookmarklet)

