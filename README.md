# Hovedopgave 2018
Vejledning: Extract til folder og kør ved hjælp af localhost. Grunden til at man skal benytte sig af localhost er at browser ikke vil køre js filerne, men i stedet kun vil åbne html, som vil stå uden sankey. Dette skyldes browser sikkerheds indstillinger som forhhindrer eksekvere scripts på lokale filer.
Hvis man ønsker at ændre i dataen skal man blot ændre i sankey.csv og følge det samme format.

For at skifte mellem filerne skal man ændre linjen         

        // load the data (using the timelyportfolio csv method)
        d3.csv("sankey.csv", function(error, data) 
        
 og erstatte "sankey.csv" med navnet på filen mman vil læse, i dette tilfælde "asbest.csv"
