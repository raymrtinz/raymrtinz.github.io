<html>
    <head>
        <title>The LaSallian | Defending truth in tough times</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/uikit@3.5.5/dist/css/uikit.min.css"/>
        <script src="https://cdn.jsdelivr.net/npm/uikit@3.5.5/dist/js/uikit.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/uikit@3.5.5/dist/js/uikit-icons.min.js"></script>
        <link rel="stylesheet" href="ebrice.css">
    </head>
    <body>
        <!-- Cover -->
        <section id="top">
            <img src="assets/Cover/cover-serif-desktop.png" alt="cover" class="cover uk-animation-slide-bottom uk-visible@s">
            <img src="assets/Cover/cover-serif-iphone.png" alt="cover"class="cover uk-animation-slide-bottom uk-hidden@s">
        </section>

        <!-- iPad and Desktop NavBar -->
        <div uk-sticky>
            <nav class="uk-navbar-container uk-margin uk-visible@s" id="shadow" uk-navbar>
                <div class="uk-navbar-center">
                    <div class="uk-navbar-center-left"><div>
                        <ul class="uk-navbar-nav">
                            <li class="uk-active"><a href="#timeline" uk-scroll>The Media Struggles</a></li>
                            <li class="uk-active"><a href="#pwl" uk-scroll>In Closed Quarters</a></li>
                        </ul>
                    </div></div>
                    <a class="uk-navbar-item uk-logo" a href="#top" uk-scroll><img src="assets/logo/LOGO.png" alt="star" class="star"></a>
                    <div class="uk-navbar-center-right"><div>
                        <ul class="uk-navbar-nav">
                            <li class="uk-active"><a href="#articles" uk-scroll>Articles</a></li>
                            <li class="uk-active"><a href="#wots" uk-scroll>Vox Populi</a></li>
                        </ul>
                    </div></div>
                </div>
            </nav>
        </div>


        <!-- iPhone NavBar -->
        <div uk-sticky>
            <nav class="uk-navbar-container uk-margin uk-hidden@s" id="shadow" uk-navbar>
                <div class="uk-navbar-left">
                    <a class="uk-navbar-item uk-logo" a href="#top" uk-scroll><img src="assets/logo/LOGO.png" alt="star" class="star"></a>
                    
                </div>
                <div class="uk-navbar-right">
                    <a id="nav" href="#offcanvas-nav-primary" uk-icon="icon: menu" uk-toggle></a>
                </div>
            </nav>
        </div>

        <div id="offcanvas-nav-primary" uk-offcanvas="overlay: true">
            <div class="uk-offcanvas-bar uk-flex uk-flex-column">
                <ul class="uk-nav uk-nav-primary uk-nav-center uk-margin-auto-vertical">
                    <li class="uk-active"><a href="#timeline">The Media Struggles</a></li>
                    <li class="uk-active"><a href="#pwl">In Closed Quarters</a></li>
                    <li class="uk-active"><a href="#articles">Articles</a></li>
                    <li class="uk-active"><a href="#wots">Vox Populi</a></li>
                </ul>
        
            </div>
        </div>

        <!-- About the Cover and Editor's Note -->
        <section id="about">
            <div class="uk-section uk-section-default">
                <div class="uk-container">

                     <!-- Desktop -->
                     <div class="uk-grid-column-large uk-visible@s"uk-grid>
                        <div class="uk-width-1-2">
                            <h2><b>Editor's Note</b></h2>
                            <p id="note">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
                                Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
                                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
                                Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                                <br><br><b>Erinne Ong</b><br>Editor-in-Chief</p>
                        </div>
                        <div class="uk-width-1-2">
                            <h2><b>About the Cover</b></h2>
                            <p id="note">The cover tells a timeless narrative about the dangers to press freedom. 
                                Drawing from history, Philippine media has continuously struggled to promote and defend the truth. 
                                Our present is no exception—peering through controlled facades reveals we are in dark times indeed.</p>
                        </div>
                    </div>

                    <!-- iPhone -->
                    <div class="uk-hidden@s">
                        <h2><b>Editor's Note</b></h2>
                        <p id="note">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
                            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
                            Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
                            Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                            <br><br><b>Erinne Ong</b><br>Editor-in-Chief</p>
                    </div>
                    <div class="uk-hidden@s">
                        <h2><b>About the Cover</b></h2>
                        <p id="note">The cover tells a timeless narrative about the dangers to press freedom. 
                            Drawing from history, Philippine media has continuously struggled to promote and defend the truth. 
                            Our present is no exception—peering through controlled facades reveals we are in dark times indeed.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- The Media Struggles -->
        <section id="timeline">
            <div class="uk-section uk-section-secondary">
                <div class="uk-container">
                    <h3 id="kicker"><b>TIMELINE</b></h3>
                    <h1 id="title"><b>Media Struggles in the Philippines</b></h1>
                    <p id="byline">by <b>Jan Emmanuel Alonzo, Rafael Gabriel Arceo, John Robert Lee,</b> & <b>Glenielle Geraldo Nanglihan</b><br>Illustration by <b>Jacob Dy</b> & <b>Ruaina Moreno</b></p>
                    <hr class="uk-divider-icon">
                    <p id="description" class="uk-visible@s">Even after the EDSA Revolution, Philippine media has encountered several obstacles from closures <br> to lawsuits.
                    <b>The LaSallian</b> looks back at the decades worth of struggle journalists had to endure starting<br>from the Cory administration
                    up until the recent shutdown of ABS-CBN.</b></p>
                    <p id="description" class="uk-hidden@s">Even after the EDSA Revolution, Philippine media has encountered several obstacles from closures to lawsuits.
                        <b>The LaSallian</b> looks back at the decades worth of struggle journalists had to endure starting from the Cory administration
                        up until the recent shutdown of ABS-CBN.</b></p><br>
                    <!-- Displaying infographic for iPad and larger-->
                    <img class="uk-visible@s" src="assets/Infographic/infographic.png" alt="Infographic">
                    <!-- Infographic button for iPhone -->
                    <div uk-lightbox>
                        <a class="uk-button uk-button-default uk-width-1-1 uk-hidden@s" href="assets/Infographic/infographic.png">View Infographic</a>
                    </div>
                </div>
            </div>
        </section>
        

        <!-- Painting With Light -->
        <section id="pwl">
            <div class="uk-section uk-section-secondary">
                <div class="uk-container">
                    <h3 id="kicker"><b>PAINTING WITH LIGHT</b></h3>
                    <h1 id="title"><b>In Closed Quarters</b></h1>
                    <hr class="uk-divider-icon">
                    <p id="description">With a pandemic changing the world as we know it, <b>The LaSallian</b> takes a look at how <br>
                        journalism remains steadfast in delivering the truth despite the difficult circumstances.</p><br>
                    
                     <div uk-grid>
                        <div class="uk-grid-small-medium uk-grid-row-medium uk-grid-column-medium uk-child-width-1-3@s uk-text-center" uk-grid="masonry: true">
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/PWL/IMG_4215.JPG" style="max-height: 100%;">
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/PWL/IMG_4217.PNG" style="max-height: 100%;">
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/PWL/IMG_4214.JPG" style="max-height: 100%;">
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/PWL/IMG_4216.JPG" style="max-height: 100%;">
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/PWL/IMG_4212.JPG" style="max-height: 100%;">
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/PWL/IMG_4210.JPG" style="max-height: 100%;">
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/PWL/IMG_4211.JPG" style="max-height: 100%;">
                                    </div>
                                </div>
                            </div>
                            <div class="uk-visible@s"></div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/PWL/IMG_4237.JPG" style="max-height: 100%;">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        

        <!-- Articles -->
        <section id="articles">
            <div class="uk-section uk-section-muted">
                <div class="uk-container">
                    <h1 id="title"><b>Articles</b></h1><br>
                    <div uk-grid>
                        <div class="uk-grid-small-large uk-grid-row-large uk-child-width-1-3@s uk-text-center" uk-grid="masonry: true">
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/Articles/10Qs Mike Navallo_Ruaina Moreno (w_ byline).JPG" style="max-height: 100%;">
                                    </div>
                                    <div class="uk-card-body">
                                        <h3 class="uk-card-title"><b>Guarding press freedom: Mike Navallo on the current state of Philippine media</b></h3>
                                        <p id="byline">by <b>Magz Chin</b> & <b>John Robert Lee</b></p>
                                        <p>Aside from being a lawyer, Mike Navallo is one of ABS-CBN's most recognized reporters. His 
                                            track-record includes covering a handful of controversial political stories.</p>
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/Articles/Alternative Media, Lauren Sason (watermarked).jpg" style="max-height: 100%;">
                                    </div>
                                    <div class="uk-card-body">
                                        <h3 class="uk-card-title"><b>To the outskirts: The rise of alternative media</b></h3>
                                        <p id="byline">by <b>Jasper Buan</b> & <b>Rafael Gabriel Arceo</b></p>
                                        <p>Alternative media sheds light on stories that may be overlooked in society.</p>
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/Articles/Citizens Journalism, Ana Mapa (watermarked).jpg" style="max-height: 100%;">
                                    </div>
                                    <div class="uk-card-body">
                                        <h3 class="uk-card-title"><b>In the blink of an eye: Clement Corominas, citizen journalist</b></h3>
                                        <p id="byline">by <b>Jacob Dy</b> & <b>Glenielle Geraldo Nanglihan</b></p>
                                        <p>It only takes a few seconds to capture history. 
                                            With the advent of social media, it now only takes a few clicks too. </p>
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/Articles/Campus Journalism In The Time Of Dissent (w_ byline).JPG" style="max-height: 100%;">
                                    </div>
                                    <div class="uk-card-body">
                                        <h3 class="uk-card-title"><b>In the trenches: Campus journalism in the times of dissent</b></h3>
                                        <p id="byline">by <b>Diego Vergel de Dios</b> & <b>Glenielle Geraldo Nanglihan</b></p>
                                        <p>In the past, campus journalists have stood for freedom and dissent. 
                                            Today, they are being called upon again as attacks against the press intensify. </p>
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/Articles/Children_s Programming_Ruaina Moreno (w_ byline).jpg" style="max-height: 100%;">
                                    </div>
                                    <div class="uk-card-body">
                                        <h3 class="uk-card-title"><b>Anything can happen: Pressing issues in the world of 
                                            local children's educational programming</b></h3>
                                        <p id="byline">by <b>Magz Chin</b> & <b>Ana Mapa</b></p>
                                        <p>Millions of kids tune in to the TV to watch their favorite shows. 
                                            How these shows are made present a different side of the screen. </p>
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/Articles/Journalist’s Morale During Crises_Lauren _ Ruaina.PNG" style="max-height: 100%;">
                                    </div>
                                    <div class="uk-card-body">
                                        <h3 class="uk-card-title"><b>Trials and tribulations: Journalists' morale in times of turmoil</b></h3>
                                        <p id="byline">by <b>Jan Emmanuel Alonzo</b> & <b>Ramon Enrico Martinez</b></p>
                                        <p>As journalists strive to continue working even in spite of blows to their morale, 
                                            their desire to serve their fellow Filipinos keeps them going.</p>
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/Articles/Both Side Journalism (w_ byline).jpg" style="max-height: 100%;">
                                    </div>
                                    <div class="uk-card-body">
                                        <h3 class="uk-card-title"><b>No more neutrality</b></h3>
                                        <p id="byline">by <b>Jan Emmanuel Alonzo</b></p>
                                        <p>In the midst of several social and political issues, journalists are not meant to be neutral
                                            fence-sitters but critical voices for truth and justice.</p>
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/Articles/Lasallians in Journalism, Lauren Sason (watermarked).jpg" style="max-height: 100%;">
                                    </div>
                                    <div class="uk-card-body">
                                        <h3 class="uk-card-title"><b>Born and bred: Lasallians in media</b></h3>
                                        <p id="byline">by <b>John Robert Lee</b> & <b>Lauren Sason</b></p>
                                        <p>Chi Datu-Bocobo (AB-CA, '96) is a TV host for local news channel One PH. 
                                            Chesca Buencamino (AB-OC, '15) is a social media
                                            producer for CNN Philippines.</p>
                                    </div>
                                </div>
                            </div>
                            <div>
                                <div class="uk-card uk-card-default">
                                    <div class="uk-card-media-top">
                                        <img src="assets/Articles/Content Moderation, Ana Mapa (watermarked).jpg" style="max-height: 100%;">
                                    </div>
                                    <div class="uk-card-body">
                                        <h3 class="uk-card-title"><b>Rights and limits in policing social media</b></h3>
                                        <p id="byline">by <b>Jasper Buan</b> & <b>Diego Vergel de Dios</b></p>
                                        <p>In an effort to create a safe space on their platforms,
                                            social media companies moderate their content according to set policies.</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Vox Populi -->
        <section id="wots">
            <div class="uk-section uk-section-secondary">
                <div class="uk-container">
                    <h3 id="kicker"><b>VOX POPULI</b></h3>
                    <h2 id="title"><b>"What impact has journalism made on your life?"</b></h2>
                    <p id="byline">Graphics by <b>Ruaina Moreno</b> & <b>Lauren Sason</b></p>
                    <hr class="uk-divider-icon">
                    <p id="description" class="uk-visible@s">Journalism influences us in many different ways. As press freedom is under threat in society,
                        <br>students share their personal thoughts and experiences on how it impacts their life.</p>
                    <p id="description" class="uk-hidden@s">Journalism influences us in many different ways. As press freedom is under threat in society,
                        students share their personal thoughts and experiences on how it impacts their life.</p><br>
                    <div uk-slider="center: true; autoplay: true;">
                        <div class="uk-position-relative uk-visible-toggle uk-light" tabindex="-1">
                            <ul class="uk-slider-items uk-child-width-1-3@s uk-grid">
                                <li>
                                    <div class="uk-card uk-card-default">
                                        <div class="uk-card-media-top">
                                            <img src="assets/WOTS/IMG_4168_MicaVidez.PNG" style="max-height: 100%;">
                                        </div>
                                        <div class="uk-card-body">
                                            <h3 class="uk-card-title" id="person">Mica Videz (II, BS-MKT)</h3>
                                            <p>I can say that it transformed me to become more aware of the social issues around us 
                                                and it ingrained in me how being informed is a necessity to survive.</p>
                                        </div>
                                    </div>
                                </li>
                                <li>
                                    <div class="uk-card uk-card-default">
                                        <div class="uk-card-media-top">
                                            <img src="assets/WOTS/IMG_4170_JakeyCampos.PNG" style="max-height: 50%;">
                                        </div>
                                        <div class="uk-card-body">
                                            <h3 class="uk-card-title" id="person">Jakey Campos (I, BS-MKT)</h3>
                                            <p>Journalism has left an impact on my life because it has become more and more apparent that 
                                                we live in a society that favors certain biases over others.
                                                With journalism, we are given a stepping stone towards the truth. </p>
                                        </div>
                                    </div>
                                </li>
                                <li>
                                    <div class="uk-card uk-card-default">
                                        <div class="uk-card-media-top">
                                            <img src="assets/WOTS/IMG_4171_DaraGianan.PNG" style="max-height: 100%;">
                                        </div>
                                        <div class="uk-card-body">
                                            <h3 class="uk-card-title" id="person">Dara Gianan (II, AB-ISE)</h3>
                                            <p>As a former student journalist, [journalism] has impacted my life in a sense that it taught me 
                                                the power that writing has, the importance of civilian voice and vigilance, and the standards 
                                                that the youth should have with regards to accepting information. </p>
                                        </div>
                                    </div>
                                </li>
                                <li>
                                    <div class="uk-card uk-card-default">
                                        <div class="uk-card-media-top">
                                            <img src="assets/WOTS/IMG_4172_GianCarloTorres.PNG" style="max-height: 100%;">
                                        </div>
                                        <div class="uk-card-body">
                                            <h3 class="uk-card-title" id="person">Gian Carlo Torres (II, BS-IE)</h3>
                                            <p>Journalism created a huge impact on my beliefs and morals as a person today.
                                                It may not always be perfect, but it always serves its purpose.</p>
                                        </div>
                                    </div>
                                </li>
                                <li>
                                    <div class="uk-card uk-card-default">
                                        <div class="uk-card-media-top">
                                            <img src="assets/WOTS/IMG_4173_LoiseAmbat.PNG" style="max-height: 100%;">
                                        </div>
                                        <div class="uk-card-body">
                                            <h3 class="uk-card-title" id="person">Loise Ambat (II, BS-MKT)</h3>
                                            <p>For me, journalism has the power to change and shape our decisions.
                                                 It also serves as a tool that bridges the gap between the government and the people.</p>
                                        </div>
                                    </div>
                                </li>
                                <li>
                                    <div class="uk-card uk-card-default">
                                        <div class="uk-card-media-top">
                                            <img src="assets/WOTS/IMG_4174_HuseTimbungco.PNG" style="max-height: 100%;">
                                        </div>
                                        <div class="uk-card-body">
                                            <h3 class="uk-card-title" id="person">Huse Timbungco (II, AB-LIM)</h3>
                                            <p> Without journalism, how else would news centers be able to broadcast what they need to show us? 
                                                Journalism is a tool for people to spread important news to the masses. 
                                                We have a lot to be thankful for thanks to journalism.</p>
                                        </div>
                                    </div>
                                </li>
                            </ul>
                        </div>
                        <!-- <ul class="uk-slider-nav uk-dotnav uk-flex-center uk-margin"></ul> -->
                    </div>
                </div>
            </div>
        </section>

        <!-- Cover -->
        <img src="assets/Cover/back.png" alt="back" class="cover">

        <!-- Copyright -->
        <div class="uk-section uk-section-muted">
            <div class="uk-container">
                <p style="text-align: center;"><img src="assets/Logo/LOGO.png" id="tlslogo"><br>————</p>
                <div class="uk-grid-match uk-child-width-1-2@m" uk-grid>
                    <div>
                        <p id="note"><b>The LaSallian</b> is the official student publication of De La Salle University. 
                            It is of the students, by the students, and for the students. 
                            Our student writers, photographers, and artists are committed to the 59-year tradition of journalistic excellence and issue-oriented critical thinking.</p>
                    </div>
                    <div id="copyright">
                        Copyright © The LaSallian 2020
                        <br>Website by Rafael Gabriel Arceo and Ramon Enrico Martinez<br><br>
                        <ul class="uk-iconnav"> 
                            <li><a href="https://www.facebook.com/TheLaSallian/" target="_blank" uk-icon="facebook"></a></li>
                            <li><a href="http://twitter.com/thelasallian" target="_blank" uk-icon="twitter"></a></li>
                            <li><a href="https://www.instagram.com/thelasallian/" target="_blank" uk-icon="instagram"></a></li>
                            <li><a href="https://thelasallian.com" target="_blank" uk-icon="world"></a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </body>
</html>
