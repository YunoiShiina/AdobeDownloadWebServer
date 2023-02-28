<body bgcolor="#ffffff">
  <style>
    body {
      font-family: 'Rubik', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
      font-size: calc(10px + 0.33vw);
      -webkit-font-smoothing: antialiased;
      padding: 5vh 10vw;
      color: #000000; /*正文字体颜色*/
    }
    h1 {
      font-size: 4.5em;
      font-weight: 500;
      margin-bottom: 0;
    }
    p {
      font-size: 1.6em;
      font-weight: 300;
      line-height: 1.4;
      max-width: 26em;
    }
    a {
      text-decoration: none;
      color: #000000;  /*超链接字体颜色*/
      position: relative;
    }
    a:after {
      content: "";
      position: absolute;
      z-index: -1;
      top: 60%;
      left: -0.1em;
      right: -0.1em;
      bottom: 0;
      transition: top 200ms cubic-bezier(0, .8, .13, 1);
      background-color: rgba(32, 32, 32, 0.5); /*超链接边框颜色*/
    }
    a:hover:after {
      top: 0%;
    }
    body2 {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      overflow: hidden;
    }
  </style>