---
title: "pour note a jour,( pour intégrer dans votre site web)"
order: 1
in_menu: true
---
# Use SqueakJS on your own website
# Instead of passing options by URL to this page, you can download SqueakJS from GitHub and use it on your own website like this:

        <html>
            <head>
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