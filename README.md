# Svadatekstgenerator

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">    
    <title>My document</title>
</head>
<body>
<br> </br>
    <button onclick ="SvadaTekst()">Klikke her for mer svada!</button>
    <br></br>
    <label><h3><b><span id="fortune"></span></b></h3></label>

    <div id="Fortune"></div>
    
    
</body>

<script>    

let TekstSvad = [
    "Man fanger ikke fisk med tørre fingre.",
    "Når solen daler i vest, arbeider den late best.",
    "Hvorfor gjøre i dag, det man kan få andre til å gjøre i morgen.",
    "Han slipper å ro som lar seg drive med strømmen.",
    "Skogen ville være uendelig stille om det bare var de beste fuglene som sang",
    "Det er lett å løpe når lykken følger etter.",
    "Gresset er grønt nok på vår side av gjerdet når vi bare husker å vanne det",
    "Et egg er et egg, sa gutten, han tok det største.",
    "Den som ikke sparer fra lokket, skal snart se bunnen.",

];

    function SvadaTekst(){

        let randNumb = Math.floor(Math.random()* TekstSvad.length);

        document.getElementById("fortune").innerHTML = TekstSvad[randNumb];
    
    }

</script>

</html>
