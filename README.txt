1. To insert top nav bar in page, paste this before <body>

<nav>
      <div>
        <ol>
          <li>
            <a href=""><ion-icon name="home-outline"></ion-icon></a>
          </li>
          <li>
            <a href=""><ion-icon name="add-outline"></ion-icon></a>
          </li>
        </ol>
      </div>
      <div>
        <input type="search" placeholder="Search" />
        <span class="fa fa-search"></span>
      </div>
      <ol>
        <li>
          <a href="login.html"
            ><ion-icon name="notifications-outline"></ion-icon
          ></a>
        </li>
        <li>
          <a href=""><img class="circle" src="images/greg.jpg" alt="" /></a>
        </li>
        <li>
          <a href=""><ion-icon name="analytics-outline"></ion-icon></a>
        </li>
      </ol>
    </nav>
  </head>
  <br><br><br>

  and also this, before </body> closing topnavright

    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>

2. app.css and style.css has been merged. Only refer to style.css if your page includes a top nav bar.
Top nav bar will not work without style.css.

#Updated by Umar 4/5 11pm.

