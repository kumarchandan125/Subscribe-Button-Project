<!DOCTYPE html>
  <html lang="en">
    <head>
      <title>Dom project</title>
  </head>
  <body>

    <p>Youtube Subscribe Button</p>
      <button onclick="
        const buttonElement=document.querySelector('.js-subscribe-button');
        if(buttonElement.innerHTML=== 'Subscribe'){
          buttonElement.innerHTML='Subscribed';
        }else{
          buttonElement.innerHTML='Subscribe';
        }
      " class="js-subscribe-button">Subscribe</button>


      <script>

      </script>
  </body>
</html>
