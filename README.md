<html lang="mn" class=" js flexbox canvas canvastext webgl no-touch geolocation postmessage no-websqldatabase indexeddb hashchange history draganddrop websockets rgba hsla multiplebgs backgroundsize borderimage borderradius boxshadow textshadow opacity cssanimations csscolumns cssgradients cssreflections csstransforms csstransforms3d csstransitions fontface generatedcontent video audio localstorage sessionstorage webworkers no-applicationcache svg inlinesvg smil svgclippaths"><head><style>
  .nl-wrap{
    position:relative; min-height:100vh; width:100%;
    display:flex; align-items:center; justify-content:center;
    background:#0b1220; color:#eaf2ff; overflow:hidden;
  }
  .nl-bg{
    position:absolute; inset:0;
    background:
      radial-gradient(50% 40% at 60% 50%, rgba(0,0,0,.65) 0%, rgba(0,0,0,.2) 55%, rgba(0,0,0,0) 80%),
      linear-gradient(180deg, rgba(10,14,20,.35), rgba(10,14,20,.85)),
      url('/images/nologin-bg.jpg') center/cover no-repeat;
    filter:saturate(115%) contrast(105%);
    transform:scale(1.02);
  }
  .nl-stars::before{ content:""; position:absolute; inset:0;
    background-image: radial-gradient(rgba(255,255,255,.12) 1px, transparent 1.5px);
    background-size: 3px 3px; opacity:.06; pointer-events:none;
  }

  /* CARD — centered content */
  .nl-card{
    position:relative; z-index:2; width:100%; max-width:640px;
    margin:24px; padding:28px 24px;
    background:rgba(17,23,36,.55);
    border:1px solid rgba(255,255,255,.08);
    border-radius:16px;
    box-shadow:0 10px 40px rgba(0,0,0,.45), inset 0 1px 0 rgba(255,255,255,.06);
    backdrop-filter:saturate(140%) blur(10px);

    display:flex; flex-direction:column; align-items:center; /* <- center horizontally */
    text-align:center;                                       /* <- center text */
  }

  /* RESPONSIVE LOGO */
  .nl-logo{ display:flex; align-items:center; justify-content:center; margin-bottom:14px; }
  .nl-logo img{
    width: clamp(160px, 45vw, 300px);   /* scales with viewport */
    height:auto;                        /* keeps aspect ratio */
    max-width:100%;                     /* never overflow */
  }

  .nl-title{ font-weight:800; font-size:28px; line-height:1.15; margin:6px 0 10px; letter-spacing:.2px; }
  .nl-sub{ color:#b9c6dc; margin:0 0 18px; font-size:15px; }

  .nl-actions{ display:flex; flex-wrap:wrap; gap:12px; justify-content:center; width:100%; }
  .nl-btn{
    display:inline-flex; align-items:center; justify-content:center;
    padding:12px 18px; border-radius:12px; text-decoration:none; font-weight:700;
    border:1px solid transparent; transition:transform .08s ease, background .2s ease, border-color .2s ease;
  }
  .nl-btn:active{ transform:translateY(1px) }
  .nl-btn--primary{ background:#3b82f6; color:#fff; border-color:#2f6ad1; }
  .nl-btn--primary:hover{ background:#2f6ad1 }
  .nl-btn--ghost{ background:rgba(255,255,255,.06); color:#eaf2ff; border-color:rgba(255,255,255,.14); }
  .nl-btn--ghost:hover{ background:rgba(255,255,255,.10) }

  @media (max-width:520px){
    .nl-card{ padding:22px 18px; border-radius:14px }
    .nl-title{ font-size:22px }
    .nl-sub{ font-size:14px }
    .nl-btn{ flex:1 1 auto; }
  }
</style>

</head><body class=" layout-boxed "><div class="nl-wrap">
  <div class="nl-bg nl-stars" aria-hidden="true"></div>

  <div class="nl-card">
    <a class="nl-logo" href="https://www.manga.mn">
      <img src="/zuragtnom-logo.png" alt="Zuragtnom">
    </a>

    <h1 class="nl-title">Тавтай морил! 👋</h1>
    <p class="nl-sub">Энэ контент зөвхөн бүртгэлтэй хэрэглэгчдэд нээлттэй. Нэвтэрч орон уншаарай.</p>

    <div class="nl-actions">
      <a class="nl-btn nl-btn--primary" href="/auth/login">Нэвтрэх</a>
      <a class="nl-btn nl-btn--ghost" href="/auth/register">Бүртгүүлэх</a>
    </div>
  </div>
</div>



<!--[if lt IE 8 ]><html lang="mn" class="ie7"> <![endif]-->
<!--[if IE 8 ]><html lang="mn" class="ie8"> <![endif]-->
<!--[if IE 9 ]><html lang="mn" class="ie9"> <![endif]-->
<!--[if (gt IE 9)|!(IE)]><!--> <!--<![endif]-->
    
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
        <title>Зурагт Номын Ертөнцөөр аялцгаая! v1.0.3 | 
</title>
        <meta name="description" content="">
        <meta name="keywords" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <meta http-equiv="Content-Security-Policy" content="upgrade-insecure-requests">


                
        <meta name="google-site-verification" content="">
        
                                <link rel="shortcut icon" href="https://manga.mn//uploads/favicon.png">
                
        <link rel="canonical" href="https://www.manga.mn">

        <link rel="stylesheet" href="https://manga.mn/css/bootswatch/cerulean/bootstrap.min.css">
        <link rel="stylesheet" href="https://manga.mn/css/style.css">
        <link rel="stylesheet" href="https://www.manga.mn/css/font-awesome.min.css">

        <script async="" src="//www.google-analytics.com/analytics.js"></script><script src="https://www.manga.mn/js/vendor/modernizr-2.6.2-respond-1.1.0.min.js"></script>
        <script src="https://www.manga.mn/js/vendor/jquery-1.11.0.min.js"></script>
        <script src="https://www.manga.mn/js/vendor/bootstrap.min.js"></script>
        <script src="https://www.manga.mn/js/vendor/jquery.autocomplete.min.js"></script>
        <script src="https://www.manga.mn/js/main.js"></script>

        
        <style>
    .error-page {
        width: 600px;
        margin: 100px auto;
    }
    .error-page>.headline {
        float: left;
        font-size: 100px;
        font-weight: 300;
    }
    .error-page>.error-content {
        margin-left: 190px;
        display: block;
    }
    .error-page>.error-content>h3 {
        font-weight: 300;
        font-size: 25px;
    }
</style>

        <!--[if lt IE 9]>
        <script src="https://www.manga.mn/js/vendor/html5shiv.js"></script>
        <script src="https://www.manga.mn/js/vendor/respond.min.js"></script>
        <![endif]-->
        <script>if (window != top)
    top.location.href = location.href</script>
    
    
        
        
        
                
        
        
             
            
        <!--[if lt IE 7]>
            <p class="browsehappy">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>
        <![endif]-->

                <!-- Google Analytics -->
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', "", 'auto');
  ga('send', 'pageview');

</script>        

    
    
    <script src="https://code.jquery.com/jquery-2.2.4.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

    
<script defer="" src="https://static.cloudflareinsights.com/beacon.min.js/vcd15cbe7772f49c399c6a5babf22c1241717689176015" integrity="sha512-ZpsOmlRQV6y907TI0dKBHq9Md29nnaEIPlkf84rnaERnq6zvWvPUqr2ft8M1aS28oN72PdrCzSjY4U6VaAw1EQ==" data-cf-beacon="{&quot;version&quot;:&quot;2024.11.0&quot;,&quot;token&quot;:&quot;ae3b2119c37d4c51ba6a656b4b336cfc&quot;,&quot;r&quot;:1,&quot;server_timing&quot;:{&quot;name&quot;:{&quot;cfCacheStatus&quot;:true,&quot;cfEdge&quot;:true,&quot;cfExtPri&quot;:true,&quot;cfL4&quot;:true,&quot;cfOrigin&quot;:true,&quot;cfSpeedBrain&quot;:true},&quot;location_startswith&quot;:null}}" crossorigin="anonymous"></script>

</body></html>
