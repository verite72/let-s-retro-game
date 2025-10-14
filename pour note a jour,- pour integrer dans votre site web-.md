---
title: "pour note a jour,( pour intégrer dans votre site web)"
order: 1
in_menu: true
---
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"> 
<html>
<head>
<link rel="SHORTCUT ICON" href="/Images/web.ico">
<meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1">
<meta name="Author" lang="fr" content="Philomaine">
<meta name="Description" content="Site dédié au retrogaming">
<meta name="Keywords" lang="fr" content="JAVASCRIPT HTML DHTML">
<meta name="Identifier-URL" content="https://verite72.github.io/let-s-retro-game/">
<meta name="Reply-to" content="xcipm6jmo@mozmail.com">
<meta name="revisit-after" content="31">
<meta name="Publisher" content="Troumad">
<meta name="Copyright" content="">
<title>AU RETROGAME</title>
<script type="text/javascript">
 drltxt="Apprendre à se passer de Microsoft"
 var nb=0;
 var longtxt=drltxt.length
 var largeur=150
 var pos=1-largeur

function deroulement()
{
 var scroller
 if(pos==longtxt)
 {
  window.status=drltxt
  nb++
  if (nb==1)
  {
   drltxt='Etre libre'
   longtxt=drltxt.length
   largeur=150
   pos=1-largeur
   setTimeout("deroulement()",3000)
  }
  else if (nb==2)
  {
   drltxt='Vivre sans MicroSoft'
   longtxt=drltxt.length
   largeur=150
   pos=1-largeur
   setTimeout("deroulement()",3000)
  }
  else
  { window.status=drltxt + ", vivre libre" }
 }
 else
 {
  pos++
  scroller=""
  if (pos<0)
  {
   for (var i=1;i<=Math.abs(pos);i++)
   { scroller=scroller+" "  }
   scroller=scroller=scroller+drltxt.substring(0,largeur-i+1)
  }
  else
  { scroller=drltxt.substring(pos,largeur+pos) }
  window.status=scroller
  setTimeout("deroulement()",50)
 }
}
</script>
# Use SqueakJS on your own website
# Instead of passing options by URL to this page, you can download SqueakJS from GitHub and use it on your own website like this:

    
                <script src="squeak.js"></script>
                <script>
                    window.onload = function() {
                        SqueakJS.runSqueak("mini.image", sqCanvas, { /*put options here*/ });
                    }
                </script>
            </head>
            <body>
                <canvas id="sqCanvas"></canvas>
            </body>
        </html> 