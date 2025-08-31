---
title: "Squeak JS"
order: 4
in_menu: true
---
<!DOCTYPE html>
<html lang="fr">
<!-- scribouilli-git-hash: 51411af -->
            <head>
                <script src="squeak.js"></script>
                <script>
                    window.onload = function() {
                        SqueakJS.runSqueak("my.image", sqCanvas, { /*put options here*/ });
                    }
                </script>
            </head>
            <body>
                <canvas id="sqCanvas"></canvas>
            </body>
        </html>
   <html> 
