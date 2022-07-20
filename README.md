<!DOCTYPE html>
<html lang='en'>
    <head>
        <title>built templates 2</title>
        <meta charset='utf-9'>
        <meta name='viewport' content='width=device-width, initial-scale=1.0'>
        <link rel='stylesheet' href='style-template2.css' type='text/css'>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@500;700&display=swap" rel="stylesheet">
        <link rel='stylesheet' href='bootstrap/css/bootstrap.min.css'>
      <style>
        /* CSS RESET */


html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}



/* -------------LIMIT CSS RESET IN WEBSITE---------------- */


body {
    background-image: url(background.png);
}
#container {
    position: fixed;
    width: 100%;
    height: 50px;
    background: slategray;
    z-index: 4;
}
.container2 {
    position: relative;
    top: 50px;
    width: 960px;
    background-color:white;
    margin: auto;
    overflow:auto;
} header {padding: 20px;} div > h1 { color: white; margin-bottom: 20px; font-size: 40px; font-family: 'poppins', arial, sans-serif; }
/* NAVBAR STYLE */
.list-link li {display: inline-block; list-style-type: none; margin-right: 5px;}
li .core-link {padding: 5px;text-decoration: none; color: slateblue; }
.core-link:hover { background-color: rgb(82, 70, 158); color: white; }
.core-link:visited {background-color: white; color: brown; }
.nav-search1, .nav-search2 {
    border-radius: 8px;
    margin-right: 6px;
    font-family: 'poppins', 'lato', century gothic, arial, sans-serif;
}
.nav-search1 { color: rgb(165, 42, 42);} .nav-search2 {padding: 8px; color: white; background-color: rgb(165, 42, 42); }
.picture-bg {
    border-top: 5px solid slateblue;
    border-bottom: 5px solid brown; 
    width: 100%;
    height: 350px;
    background-size: cover;
    background-position: 0 -160px;
    background-repeat: no-repeat;
    background-image: url(coding.png);
}
.main-content { margin-top:10px; float:left; padding: 20px; width: 600px;
} .main-content > h2 { font-size: 28px; font-family: 'poppins', arial, sans-serif;} .author {text-decoration: none; color:brown;}
.subtitle {max-width: 80%; line-height: 40px; }
.main-content p {margin-top: 20px; margin-bottom: 20px; font-family: arial, sans-serif; line-height:24px; letter-spacing:0.3px;}
.sidebar {
    float: right;
    width: 330px;
    margin-top:30px;
} .image-author { float:left; margin-right: 20px;  width: 50px; height: 50px;} .text-sidebar {box-sizing: border-box; padding-right: 20px;}
footer {
    background-color: rgb(44, 54, 57);
    color: white;
    padding: 20px;
    margin: auto;
    width:960px;
} footer > p {text-align: center; color: white; font-family: 'poppins', arial, sans-serif; font-size: 20px;}
      </style>
    </head>
    <body>
        <div id='container'>
            <h1>VERVER</h1>
        </div>
        <div class='container2'>
            <header>
                <form>
                        <ul class='list-link'>
                            <li><a href="#" class="core-link">SOFTWARE</a></li>
                            <li><a href="#" class="core-link">PROGRAMMING</a></li>
                            <li><a href="#" class="core-link">HARDWARE</a></li>
                            <li><a href="#" class="core-link">EDUCATION</a></li>
                            <li><a href="#" class="core-link">HELP</a></li>
                            <li style='position: relative; left: 70px;'> <input type='search' class='nav-search1' placeholder='Search'> </li>
                            <li style='position: relative; left: 70px;'><submit class='nav-search2'>Search</submit></li>
                        </ul>
                </form>
            </header>
            <div class='picture-bg'></div>
            <div class='main-content'>
                <h2 class='subtitle'>TEKNOLOGI CSS SEKARANG MELUAS HINGGA REACT DAN VUE JS JARANG DIKETAHUI</h2>
                <p>Ditulis oleh <a href='#' class='author'>Moh. Bismagal Bilak</a> pada 26 Juni 2022.</p>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Recusandae laboriosam neque deserunt obcaecati eius voluptate quisquam commodi distinctio enim, iusto, quas iure, illo officiis deleniti explicabo perspiciatis aliquid excepturi quam vitae eum unde. Perferendis, est nulla. Possimus aut neque beatae in esse mollitia provident vel tempora ad dolore delectus, ipsa distinctio id dolor facere dolores cupiditate, perspiciatis ullam iste magnam fugiat! Soluta veritatis maiores placeat praesentium eaque perspiciatis, quam laudantium ipsum ab maxime, vero atque, culpa tempore at amet. Distinctio optio, doloremque consequatur nisi adipisci corporis, officia temporibus magnam eos cupiditate dolor? Perspiciatis atque suscipit modi consequatur nemo quibusdam nulla.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos laborum, culpa sint dolorem iusto quasi consectetur delectus iure sapiente, dolor corporis maiores amet? Exercitationem provident vitae sapiente excepturi illo amet aut dolorum tenetur harum non beatae ipsa, placeat asperiores fuga consectetur quisquam! Vitae libero exercitationem incidunt enim, rerum voluptatem sapiente corporis natus inventore voluptates repudiandae cum facere ducimus quisquam nostrum velit earum totam maiores cupiditate saepe quam! Magnam necessitatibus expedita dolorem, ipsa, esse obcaecati eveniet consequuntur dolor, omnis explicabo voluptatum.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet sunt velit eaque quisquam ratione, debitis eius, fuga nihil nobis hic quibusdam reprehenderit alias! Deleniti inventore officia, ea quis dolorum iure, in impedit maxime eos a eligendi rerum, dolores odio vitae quod beatae? Rem corrupti architecto officiis. Amet quidem recusandae alias assumenda soluta, tempora eius, iste possimus ex molestiae natus voluptatibus. Eum maxime laboriosam perspiciatis tempore, minus sed harum repudiandae culpa ratione recusandae itaque voluptas saepe, iusto repellendus facere placeat doloremque ducimus voluptatem quis vel hic vero. Voluptatibus, neque! Saepe, rerum?</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum, esse nobis alias eum non consequuntur maiores laborum, sapiente dignissimos officia porro quasi doloremque, expedita laudantium earum! Vero id dolore mollitia! Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis autem incidunt veritatis cum ducimus ipsam temporibus id officia quam vitae amet voluptatem placeat saepe ipsum possimus distinctio, culpa et sit!</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium quibusdam tenetur placeat? Eveniet iure totam voluptatum corporis dolorem consectetur! Nemo consectetur harum laborum architecto ea corrupti consequuntur labore? Quo, ad?</p>
            </div>
            <div class="sidebar">
                <h2 class='author-profile'>Profil Penulis</h2>
                <img src="author.jpg" class='image-author' alt="Bisma Galbilak">
                <p class='text-sidebar'>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam harum non maiores ex id error voluptas, velit veritatis voluptatibus consequatur dolores reprehenderit animi nostrum reiciendis. Voluptatum obcaecati dolore libero eos illum nam explicabo, quas quod mollitia, exercitationem neque dolorem recusandae architecto itaque magni reprehenderit ipsa! Minima quibusdam vero aliquid, officiis iusto laudantium, laboriosam sed temporibus doloremque a exercitationem debitis fuga impedit odit nam aperiam quia maiores consequatur odio. Cumque deleniti quibusdam id hic voluptatibus doloremque ad ullam rem aspernatur provident?</p>
            </div>
        </div>
        <footer>
            
            <p>VERVERLOCK</p>
        </footer>
    </body>
</html>
