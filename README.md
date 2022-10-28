<!DOCTYPE html>
<html lang="es" >

@@ -106,12 +107,7 @@
}

body {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-evenly;
  min-height: 100vh;
  margin: 0;

  background: #333;
  color: #cca;
}
@@ -120,39 +116,53 @@
  text-align: center;
}

.info {
  align-self: flex-end;
  margin: 3rem 1rem 1rem;
  text-align: right;
  font-size: 0.85em;
  font-style: italic;
  font-family: serif;
  opacity: 0.75;

        .content, .sidebar {
  margin: 10px;
  padding: 20px;
}
.info a {
  color: inherit;

.content {
  //background-color: navy;
  //color: white;
}

.sidebar {
  //background-color: yellow;
}
    </style>
</style>



    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet"/>


</head>

<body translate="no" >
  <h1><code>/ Largirucho /</code></h1>
<div class="c">
  <div class="i"><img class="img" src="https://pbs.twimg.com/profile_images/1227274555976232960/MBlI3d_y_400x400.jpg"/></div>
  <div class="s1"></div>
  <div class="s2"></div>
  <div class="s3"></div>
  <h1><code>/ Gran Hermano /</code></h1>



<blockquote class="info">Con el apoyo de: <a href="https://largirucho.com/">Largirucho</a></blockquote>






</body>
