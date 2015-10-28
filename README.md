HTML!

<!DOCTYPE html>
<html>
    <head>
        <title>Deliverable 2</title>
    <link rel="stylesheet" type="text/css"                                 href="Deliverable2.css">
        <meta charset="UTF-8">
        <meta name="description" content="This website gives you some problems and possible solutions to using airport ticket vending machines">
        <meta name="keywords" content="Airport, tickets, machines, problems, solutions">
        <meta name="author" content="Marcus Aurelius Hovet, Jostein Olstad & Lasse Husebråten">
    </head>   
    <body>
        
        <!-- Header -->
        
        <div id="headerbox">
      
            
        <!-- Body -->
            
        <div id="content">
            
        </div>    
        
        <!-- Bottom / Footer -->
            
        <footer>
            <div id="footer">
            </div>
        </footer>    
            
            
        
    </body>
</html>

CSS

/* CSS / HEADER */

html {
    background: #D3F1FF
}

#headerbox {
    background: #33CCFF;
    margin: 0px;
    width: 100%;
    height: 125px;
    top: -20px;
    position: absolute;
    left: 0px;
    right: 0px;
    padding: 10px;
    margin-bottom: 10px;
    }

/* CSS / BODY */

#content {
    background: #FFFFFF;
    margin: 0 auto;
    width: 800px;
    height: 100%;
    position: static;
    z-index: -1;
    border-radius: 12px;
    margin-top: 180px;
    margin-bottom: 50px;
    padding-top: 600px;
    box-shadow: 10px 10px 10px #888888;
}

/* CSS / FOOTER */

#footer {
    background: #33CCFF;
    height: 200px;
    width: 100%;
    position: relative;
    padding: 0px;
    margin: 0px;
}
