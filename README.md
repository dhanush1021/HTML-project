#index.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <!-- Compiled and minified CSS -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css"
    />

    <link
      href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="style.css" />
    <title>Google Drive</title>
  </head>
  <body>
    <div class="navbar-fixed">
      <nav class="nav-extended white">
        <div class="nav-wrapper white">
          <ul>
            <li>
              <a href="#!" class="title grey-text text-darken-1"
                >Google Drive</a
              >
            </li>
          </ul>
          <div class="search wrapper">
            <i class="material-icons">Search</i>
            <input type="search" name="search" placeholder="Search Drive" />
          </div>
          <ul class="right">
            <li>
              <a href="#!"
                ><i class="material-icons grey-text text-darken-1"
                  >notifications</i
                >
              </a>
            </li>
            <li>
              <a href="#!"
                ><img src="Zoro.png" alt="profile pic" class="circle"
              /></a>
            </li>
          </ul>
        </div>
        <div class="nav-wrapper nav-2">
          <ul>
            <li>
              <a
                herf="#!"
                class="waves-effect waves-light btn btn-flat white-text"
                >New</a
              >
            </li>
          </ul>
          <ul class="right">
            <li>
              <a herf="#!"
                ><i class="material-icons grey-text text-darken-1">info</i></a
              >
            </li>
            <li>
              <a herf="#!"
                ><i class="material-icons grey-text text-darken-1">settings</i>
              </a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
    <ul class="side-nav fixed floating transperant z-depth-0">
      <li class="active">
        <a herf="#"
          ><i class="material-icons blue-text text-darken-1">dashboard</i>My
          Drive</a
        >
      </li>
      <li>
        <a herf="#"><i class="matreial-icons">devices</i>Computers</a>
      </li>
      <li>
        <a herf="#"><i class="material-icons">people</i>shared with me</a>
      </li>
      <li>
        <a herf="#"><i class="material-icons">acess_time</i>Recent</a>
      </li>
      <li>
        <a herf="#"><i class="material-icons">camera</i>Google Photos</a>
      </li>
      <li>
        <a herf="#"><i class="material-icons">star</i>Starred</a>
      </li>
      <li>
        <a herf="#"><i class="material-icons">delete</i>Trash</a>
      </li>
      <li><div class="divider"></div></li>
      <li>
        <a herf="#"><i class="material-icons">storage</i>Upgrade storage</a>
      </li>
    </ul>
    <div class="main">
      <div class="container-fluid">
        <p class="subheader">Folders</p>
        <div class="card-panel folder">
          <i class="material-icons left">folder</i>Folder
        </div>
        <div class="card-panel folder">
          <i class="material-icons left">folder</i>Folder
        </div>
      </div>
    </div>
  </body>
  <!-- Compiled and minified JavaScript -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
</html>

#style.css
body {
  background-colour: #f0f0f0;
  font-size: 13px;
}
.card,
.card-panel {
  padding: 15px, 20px;
  box-shadow: 0 1px 4px 0 rgba(0, 0, 0, 0.14);
}
.container-fluid {
  padding: 1rem 2.5rem;
  margin: auto;
}
.row {
  margin: 0 -0.75rem;
}
.main {
  position: absolute;
  width: calc(100% - 250px);
  top: 125px;
  margin-left: 250px;
}
.subheader {
  color: rgba(0, 0, 0, 0.54);
  font-weight: 500;
}
/*nav*/
nav {
  box-shadow: 0 1px 8px rgba(0, 0, 0, 0.3);
}
nav ul li {
  text-align: center;
}
nav ul.right {
  padding-right: 12px;
}
nav ul.right li {
  max-width: 48px;
}
nav ul a {
  padding-right: 0 12px;
}
nav ul a img {
  height: 32px;
  width: 32px;
  vertical-align: middle;
  margin-left: -5px;
}
.nav-wrapper {
  padding-left: 12px;
}
.nav-wrapper ul a:hover {
  background-color: transparent;
}
.nav-wrapper .title {
  font-size: 1.4rem;
}
.nav-wrapper .btn-flat {
  background-color: #4285f4 !important;
  font-size: 13px;
  font-weight: 500;
  height: 30px;
  line-height: 30px;
  width: 94px;
}

#package.json
{
  "name": "static",
  "version": "1.0.0",
  "description": "This is a static template with no bundling",
  "main": "index.html",
  "scripts": {
    "start": "serve",
    "build": "echo This is a static template, there is no bundler or bundling involved!"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/codesandbox-app/static-template.git"
  },
  "keywords": [
    "static",
    "template",
    "codesandbox"
  ],
  "author": "Ives van Hoorne",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/codesandbox-app/static-template/issues"
  },
  "homepage": "https://github.com/codesandbox-app/static-template#readme",
  "devDependencies": {
    "serve": "^11.2.0"
  }
}
