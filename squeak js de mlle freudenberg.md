---
title: "squeak JS de Mlle Freudenberg"
order: 1
in_menu: true
---
<!DOCTYPE html>
<html lang="fr">
<!-- scribouilli-git-hash: 51411af -->
            <head>
                <script src="squeak.js"></script>
                <script>
                    window.onload = function() {
                        SqueakJS.runSqueak("https://freudenbergs.de/bert/squeakjs/scratch/Scratch.image", sqCanvas, { "1 GuessingAgeGame.sb" });
                    }
                </script>
            </head>
            <body>
                <canvas id="sqCanvas"></canvas>
            </body>
        </html> 