<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <meta name="description" content="Welcone to Vibez PH, your small discord community.">
    <meta name="author" content="Vibez PH">
    
    <meta property="og:site_name" content="Vibez PH" /> <!-- website name -->
    <meta property="og:site" content="www.vibezph.tk" /> <!-- website link -->
    <meta property="og:title" content="Vibez PH"/> <!-- title shown in the actual shared post -->
    <meta property="og:description" content="vibezph discord community" /> <!-- description shown in the actual shared post -->  
    <meta property="og:image" content="/png/thumbnail.png" /> <!-- image link, make sure it's jpg -->
    <meta property="og:url" content="" /> <!-- where do you want your post to link to -->
    <meta property="og:type" content="article" />
	
    <meta name="twitter:card" content="/png/thumbnail.png">
    
    <title>Vibez PH</title>
    <link rel="shortcut icon" type="image/png" href="/png/favicon.png"/>
    
    <link href="css/style.css" rel="stylesheet" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/fullPage.js/3.1.0/fullpage.min.css" integrity="sha512-RVmrWua3k1yTDEOg4Yzs2bK5+Thh7nM6jrhDq/6/5/Mwa0JbYe4pP4YMK5sqghKz01T3DgrwYc57Jaf1PSurCg==" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
    <link href="http://fonts.cdnfonts.com/css/kingthings-spikeless" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js" integrity="sha512-bLT0Qm9VnAYZDflyKcBaQ2gg0hSYNQrJ8RilYldYQ1FxQYoCLtUjuuRuZo+fjqhx/qtq/1itJ0C2ejDxltZVFg==" crossorigin="anonymous"></script>
	
    <style>
        #fp-nav ul li a span, .fp-slidesNav ul li a span {
            background: white !important;
        }
        
    </style>
    
</head>
<body>
    
    
    <div id="fullpage">
        <div id="wrapper" class="section">
            <!-- Make sure data-text equals the text you put inside the tags. -->
             <h1 class="glitch" data-text="VIBEZ PH">VIBEZ PH</h1>
            <span class="sub">community</span>
        
        </div>
        
        <div id="wrapper-2" class="section">
            

          <h1 class="infoTagline">
              A place where others <span class="infoTagline-highlight">meet</span> and <span class="infoTagline-highlight">talk</span>
              with others
            </h1>
            
            <h3 class="vb-header">non toxic community</h3>
            <p>Vibez PH has a growing non - toxic community that aims to chat people, meet, and play with them.</p>
            
            
            <img src="https://cdn.discordapp.com/attachments/753899837946331188/816502899739852830/Untitled_Artwork.png" class="previewImage1">
            

            <p class="previewTag">
              
              VibezPH is a Filipino Community,It is established to Socialse, pLay Games, <br>
               and share many more contents with friends that you could meet <br>
              The server is full of friendly people. We also offer events such as giveaways and more that makes us one! non toxic person. Enjoy chatting with others, <br>
              show love and show kindness. <br><br><span class="onlineUser"></span>

            </p>

            <a class="learn-more" href="https://discord.gg/mf5UFMfzYG" target="_blank">Join Now</a>

            <script>
              $.ajax({
                url: "https://discord.com/api/guilds/733175002383253636/widget.json",
                dataType: 'json',
                crossDomain: true,
                contentType: 'application/json',
		headers: {
            		'Access-Control-Allow-Origin': '*',
          	},
		cors: true,
          	beforeSend: function (xhr) {
            		xhr.setRequestHeader ("Authorization", "Basic " + btoa(""));
          	},
                success: function(data) {
                  console.log(data.presence_count)
	          console.log("test")
                  var text = `There are <b>${data.presence_count}</b> currently online user`
                  $(".onlineUser").html(text);
                },
                error: function(data) {
                  console.log(data);
	
                 
                }
              });
             </script> 
        </div>

        <div id="wrapper-3" class="section">

            <ul class="desktop">
                <li>
                  <a href="https://m.facebook.com/GelVibez/?ref=share">
                    <i class="fab fa-facebook" aria-hidden="true"></i>
                    <span> - Facebook</span>
                  </a>
                </li>
                <li>
                  <a href="https://twitter.com/vibezph?s=21">
                    <i class="fab fa-twitter" aria-hidden="true"></i>
                    <span> - Twitter</span>
                  </a>
                </li>
                <li>
                  <a href="https://discord.gg/mf5UFMfzYG">
                    <i class="fab fa-discord" aria-hidden="true"></i>
                    <span> - Discord</span>
                  </a>
                </li>
                <li>
                  <a href="https://www.instagram.com/vibezph_/">
                    <i class="fab fa-instagram" aria-hidden="true"></i>
                    <span> - Instagram</span>
                  </a>
                </li>
              </ul>

              <ul class="mobile">
                <li><a href="https://m.facebook.com/GelVibez/?ref=share"> <i class="fab fa-facebook-f" aria-hidden="true"></i> </a> </li>
                <li><a href="https://twitter.com/vibezph?s=21"> <i class="fab fa-twitter" aria-hidden="true" "></i> </a> </li>
                <li><a href="https://discord.gg/mf5UFMfzYG"> <i class="fab fa-discord" aria-hidden="true"></i> </a> </li>
                <li><a href="https://www.instagram.com/vibezph_/"> <i class="fab fa-instagram" aria-hidden="true"></i> </a> </li>
                
             </ul>

        </div>
    
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/fullPage.js/3.1.0/fullpage.min.js"></script>
    <script>
        new fullpage('#fullpage', {
            autoScrolling: true,
        })
    </script>
    
</body>
</html>
