<script>
  import "../app.css";
  import Nav from './Nav.svelte';
</script>

<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
          rel="stylesheet">
    <title>Jacob Penn</title>
</head>

<body class="h-screen mx-auto bg-light-grey text-dark-grey">
<Nav/>
<div class="px-10 mt-32">
    <h1 class="text-[10vw]/[9vw] font-bold">JACOB&nbsp;PENN</h1>
    <h1 class="text-[10vw]/[9vw] font-bold">AUDIO&nbsp;PERSON</h1>
    <p class="text-[3vw]/[3.4vw] font-semibold mt-8">
        With engineering, product design and <br>
        entrepreneurship, I aim to create powerful <br>
        experiences in music production & technology.
    </p>
    <div class="mt-20">
        <a href="mailto:jake@minimal.audio">
            <p class="text-[1.5vw] inline border-[.1vw] rounded-full border-dark-grey py-5 px-10 hover:font-bold">
                jake@minimal.audio
            </p>
        </a>
    </div>
    <div class="mt-20 flex flex-row justify-between">
        <p>All Access</p>
        <p>Discover</p>
    </div>
</div>
<div>
    <img src="landing_all_access.png" alt="All Access Ad">
</div>
<slot/>
</body>
