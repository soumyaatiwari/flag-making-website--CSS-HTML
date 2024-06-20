# flag-making-website--CSS-HTML
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>CSS Flag Project</title>
  <style>
    .flag {
      width: 900px;
      height: 600px;
      position: relative;
      background-color: #CE1126;

    }

    .flag > div {
      background-color: #002868;
      height: 300px;
      width: 100%;
      position: absolute;
      top: 150px;
    }

    .flag > div > div {
      background-color: white;
      position: absolute;

      height: 200px;
      width: 200px;
      border-radius: 50%;
      top: 50px;
      left: 350px;
    }

    p {
      font-size: 5rem;
      color: white;
      text-align: center;
      padding: 0;
      margin: 0;
    }

    .flag>div div p {
      color: black;
    }
  </style>
</head>
