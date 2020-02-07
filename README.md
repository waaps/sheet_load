<html>
  <head></head>
  <body>
  <script src='https://cdnjs.cloudflare.com/ajax/libs/tabletop.js/1.5.1/tabletop.min.js'></script>
<script type='text/javascript'>    
  var publicSpreadsheetUrl = 'https://docs.google.com/spreadsheets/d/e/2PACX-1vTj9VZdk5asv_GLVNswlHOHLHP9vOANCe3Hn1uPXstRTpIMLZbC0jOpgYMASnwtYBbesYck4m5MMlXq/pubhtml';
  //var publicSpreadsheetUrl = '1woTRKsaKGr2q_p_dH7b2c9sIoiAB2X8LmRmaU8uo9q0';

  function init() {
    Tabletop.init( {
      key: publicSpreadsheetUrl,
      simpleSheet: true }
    ).then(function(data, tabletop) { 
      console.log(data)
    })
  };

  window.addEventListener('DOMContentLoaded', init);
</script>
</body>
</html>
