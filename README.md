<!DOCTYPE html>

<html>

  <head>

    <meta http-equiv="content-type" content="text/html; charset=utf-8" />

    <meta name="" content="">

    <title>Heart</title>

    <style type="text/css" media="all">

      body {
        margin: 0;

        padding: 0;

        display: flex;

        align-items: center;

        justify-content: center;

        min-height: 92vh;

        background: black;
        }
      
  .heart {

        height: 100px;

        width: 100px;

        background: red;

        position: relative;

        transform: rotate(-45deg);

        box-shadow: -10px 10px 90px red;

        animation: heart 0.6s linear infinite;

      }
      @keyframes heart {

        0% {

          transform: rotate(-45deg) scale(1.00);

        }

        80% {

          transform: rotate(-45deg) scale(0.90);

        }
        100% {

          transform: rotate(-45deg) scale(0.80);

        }

      }

      .heart::before {

        content: "";

        position: absolute;

        height: 100px;
        width: 100px;

        background: red;

        top: -55%;

        border-radius: 50px;

        box-shadow: -10px 10px 90px red;
        }
        .heart::after {

        content: "";

        position: absolute;

        height: 100px;

        width: 100px;

        background: red;

        right: -55%;

        border-radius: 50px;

        box-shadow: -10px 10px 90px red;

      }

        .heart::after {

        content: "";

        position: absolute;

        height: 100px;

        width: 100px;

        background: red;

        right: -55%;

        border-radius: 50px;

        box-shadow: -10px 10px 90px red;

      }
      </style>

  </head>

  <body>

    <div class="heart">

      

    </div>

  </body>

</html>

