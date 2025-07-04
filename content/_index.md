+++
[paige.pages]
disable_collections = true
disable_pages = true
disable_sections = true
+++

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Horizontal Banner of Vertical Images</title>
  <style>
    body {
      margin: 0;
      padding: 0;
    }

    .banner {
      display: flex;
      overflow-x: auto;
      white-space: nowrap;
      padding: 20px;
      background-color: #f8f8f8;
    }

    .banner img {
      height: 300px; /* keeps them vertical */
      width: auto;
      margin-right: 16px;
      border-radius: 8px;
      object-fit: cover;
      flex-shrink: 1;
    }
  </style>
</head>
<body>
  <div class="banner">
    <img src="olympic_hiking.png" alt="Vertical Image 1">
    <img src="new_york_dog.png" alt="Vertical Image 2">
    <img src="brooklyn_bridge.png" alt="Vertical Image 3">
    <img src="glass_flowers.png" alt="Vertical Image 4">
    <img src="montana_road.png" alt="Vertical Image 5">
  </div>
</body>