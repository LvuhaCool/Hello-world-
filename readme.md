<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luxestate</title>
    <style>
        
    color: #fff;
}
.location-melbourn {
    padding-left: 15px;
    padding-top: 12px;
}
.location-australia {
    padding-left: 15px;
    padding-top: 12px;
}
.add-line h3 {
    font-size: 25px;
    margin-top: 75px;
    margin-bottom: 40px;
    margin-left: 130px;
}
.add-line p {
    font-size: 13px;
    line-height: 30px;
    margin-left: 130px;
}
.add-line-right p {
    margin-left: 0;
    margin-right: 130px;
}
.add-line h3:last-of-type {
    margin-top: 25px;
}
.show-more {
    font-size: 18px;
    background: #1f373d;
    padding: 30px 70px 30px 55px;
    display: inline-block;
    margin-left: 130px;
    color: #fff;
    margin-top: 60px;
    border-radius: 3px;
}
footer {
    background: #1f373d;
    color: #fff;
    padding-top: 50px;
    padding-bottom: 80px;
}
.footer-block {
    display: flex;
    justify-content: space-between;
}
.footer-block h3 {
    font-size: 40px;
}
.footer-search input[type=text] {
    width: 442px;
    height: 70px;
    color: #919eb1;
    padding-left: 27px;
    font-size: 15px;
    background-image: url(./img/right.png);
    background-size: 30px, 17px;
    background-repeat: no-repeat;
    background-position: 94%;
}
hr {
    opacity: 0.3;
    margin-top: 47px;
    margin-bottom: 70px;
}
.footer-links {
    display: flex;
    justify-content: space-between;
    padding-right: 90px;
}
.footer-link {
    display: flex;
    flex-direction: column;
}
.footer-links-logo {
    font-size: 25px;
    margin-right: 26%;
}
.footer-link p {
    text-transform: uppercase;
    font-size: 13px;
    color: #919eb1;
    margin-bottom: 35px;
}
.footer-link a {
    color: #fff;
    text-decoration: none;
    font-size: 13px;
    margin-bottom: 20px;
}
.footer-link a:hover {
    opacity: 0.4;
}
@media screen and (max-width: 1100px) {
    .intro .intro-text {
        right: 80px;
    }
    .intro-img {
        margin-top: 100px;
    }
    .intro-img .intro-text {
        padding-top: 50px;
    }
     .intro .intro-contacts {
        margin-top: 100px;
    }
    .menu li a.logo {
        margin-right: 20px;
    }
    .cards {
        grid-template-columns: repeat(2, 1fr);
        grid-template-rows: repeat(3, 1fr);
        grid-column-gap: 0px;
        grid-row-gap: 30px;
    }
    .apart .buttons-search {
        margin-left: 4%;
    }
    .steps-container {
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .step-block {
        margin-top: 20px;
    }
    .steps-text, .step h2 {
        margin-left: 5%;
        margin-bottom: 15px;
    }
    .agent-cards {
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .agent-card {
        margin-top: 10px;
    }
    .add-line {
        flex-direction: column;
    }
    .location {
        margin-right: 200px;
    }
    .add-line {
        margin-left: 50px;
    }
    .add-line h3 {
        font-size: 25px;
        margin-top: 75px;
        margin-bottom: 40px;
        margin-left: 5%;
    }
    .add-line p {
        margin-left: 5%;
    }
    .add-line-right {
        margin-left: 5%;
        margin-right: 0;
    }
}
@media screen and (max-width: 950px) {
    .intro .intro-text {
        right: 120px;
    }
    .menu {
        display: block;
    }
    .menu li a {
        margin-top: 5px;
    }
    .menu li a:hover {
        background: none;
    }
    .menu li a.logo {
        margin-left: 82%;
    }
    .cards {
        grid-template-columns: repeat(2, 1fr);
        grid-template-rows: repeat(3, 1fr);
        grid-column-gap: 0px;
        grid-row-gap: 30px;
    }
    .apart input[type=submit] {
        border-radius: 4px;
    }
    .apart .all {
        margin-right: 30px;
    }
    .steps-container {
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .step-block {
        margin-top: 20px;
    }
    .steps-text, .step h2 {
        margin-left: 5%;
        margin-bottom: 15px;
    }
    .agent-cards {
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .agent-card {
        margin-top: 10px;
    }
    .add-line {
        flex-direction: column;
    }
    .location {
        font-size: 15px;
        height: 75px;
    }
    .add-line h3 {
        font-size: 25px;
        margin-top: 75px;
        margin-bottom: 40px;
        margin-left: 5%;
    }
    .add-line p {
        margin-left: 5%;
    }
    .add-line-right {
        margin-left: 5%;
        margin-right: 0;
    }
}
@media screen and (max-width: 820px) {
    .footer-link {
        margin-right: 10px;
    }
}
@media screen and (max-width: 765px) {
    .toggle {
        clear: both;
        display: block;
        text-align: center;
        font-size: 18px;
        line-height: 40px;
        width: 100%;
        color: #000;
        background-color: #ffcc01;
        transition: all 1s linear;
    }
    .toggle:hover {
        background-color: #d3a900;
    }
    #checkbox-menu:checked + label .touch li {
        opacity: 1;
        visibility: visible;
        transition: all .7s linear;
    }
    #checkbox-menu:checked + label .touch {
        height: 350px;
    }
    .menu {
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        height: 0px;
        transition: height .3s linear;
    }
    .menu li {
        display: flex;
        align-self: center;
        width: 95%;
        opacity: 0;
        visibility: hidden;
    }
    .menu li a {
        width: 95%;
        text-align: center;
        align-self: center;
        align-content: center;
    }
    .menu li a.logo {
        font-size: 21px;
        position: relative;
        right: 195px;
    }
    .menu li a.contacts {
        margin-right: 0px;
    }
    .intro {
        margin-top: 0;
        display: block;
        max-width: 100%;
    }
    .intro .intro-img {
        background-position: bottom 0px right 70px;
    }
     .intro .intro-text {
        position: relative;
        font-size: 35px;
        right: 95px;
        left: 30px;
        top: 100px;
        width: 100%;
        color: rgb(12, 10, 28);
    }
     .intro .intro-contacts {
        left: 0;
        top: -55px;
        padding: 20px 10px;
        position: relative;
        width: 450px;
        margin-top: 0;
    }
    .intro-contacts p {
        font-size: 13px;
        margin-right: 0;
    }
    .stats {
        margin-top: 0;
        flex-direction: column;
    }
    .stats-text {
        padding: 10px;
    }
    .stats-text h2 {
        font-size: 30px;
        margin-bottom: 30px;
    }
    .stats-text p {
        margin-top: 5px;
        font-size: 13px;
        line-height: 18px;
    }
    .square {
        height: 140px;
    }
    .cards {
        grid-template-columns: repeat(1, 1fr);
        grid-template-rows: repeat(6, 1fr);
        grid-row-gap: 10px;
        justify-items: center;
    }
    .apart input[type=text] {
        margin-top: 20px;
        width: 130px;
    }
    .apart input[type=submit] {
        border-top-left-radius: 0px;
        border-bottom-left-radius: 0px;
    }
    .buttons-search {
        flex-direction: column;
        margin-left: 4%;
    }
    .all {
        background: #fff;
        margin-top: 10px;
        margin-left: 0;
    }
    .steps-container {
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .step-block {
        margin-top: 20px;
    }
    .steps-text, .step h2 {
        margin-left: 5%;
        margin-bottom: 15px;
    }
    .serv-container {
        margin-top: 20px;
        flex-direction: column;
    }
    .serv-img-container {
        width: 100%;
    }
    .serv-text {
        width: 90%;
    }
    .serv-text .top-heading {
        margin-top: 30px;
    }
    .agent-cards {
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .agent-card {
        margin-top: 10px;
    }
    .add-line {
        flex-direction: column;
    }
    .location {
        font-size: 15px;
        height: 75px;
    }
    .add-line h3 {
        font-size: 25px;
        margin-top: 75px;
        margin-bottom: 40px;
        margin-left: 5%;
    }
    .add-line p {
        margin-left: 5%;
    }
    .add-line-right {
        margin-left: 5%;
        margin-right: 0;
    }
    .footer-block {
        flex-direction: column;
    }
    .footer-logo h3 {
        font-size: 25px;
        text-align: center;
    }
    .footer-search input[type=text] {
        width: 80%;
        height: 50px;
        margin-top: 15px;
        margin-left: 20px;
    }
    .footer-search {
        display: flex;
        justify-content: center;
    }
    .footer-links {
        flex-wrap: wrap;
        margin-left: 5%;
        padding-right: 5%;
    }
}
    </style>
    <script src="https://kit.fontawesome.com/8c5f8983b2.js" crossorigin="anonymous"></script>
</head>
<body>
    <header>
        <nav>
            <input type="checkbox" id="checkbox-menu">
            <label for="checkbox-menu">
                <ul class="menu touch">
                    <li><a href="#" class="logo">luxestate</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Apartment</a></li>
                    <li><a href="#">How it works</a></li>
                    <li><a href="#">Agents</a></li>
                    <li><a href="#" class="contacts">Contact us</a></li>
                    <li><a href="#">Join us</a></li>
                    <li><a href="#">Getting Started</a></li>
                </ul>
                <span class="toggle">&#9776;</span>
            </label>
        </nav>
    </header>
    <main>
        <section class="intro wrapper">
            <div class="intro-img">
                <p class="intro-text">Find Your New<br>Modern Apartment</p>
            </div>
            <div class="intro-contacts">
                <p><i class="fas fa-phone-alt"></i>(000) 123 45-67</p>
                <p><i class="fas fa-map-marker-alt"></i>Melbourn, Australia</p>
            </div>
        </section>
        <section class="stats wrapper">
            <div class="stats-text">
                <h2>Our Company's<br>Statistics</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                    Culpa consectetur optio assumenda vel dicta in vitae, 
                    adipisci praesentium cumque sit ut, dolorum doloremque error
                    voluptate voluptas tempore facilis aut suscipit corporis ullam sed? 
                    Aperiam, ipsum ratione! Consectetur maxime libero iure laudantium! 
                    Officiis qui eos eaque.</p>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                     Labore reiciendis ipsa dolorem iste culpa amet architecto laborum eum blanditiis,
                      exercitationem facilis hic ullam nostrum quas soluta veniam ratione dicta non,
                       omnis ab quam aut saepe esse repellendus?
                        Omnis soluta eos dolorum at, aperiam possimus tenetur.</p>
            </div>
            <div class="stats-num">
                <div class="stats-line">
                    <div class="square">
                        <span class="stats-square">748</span>
                        <span class="square-text">Apartments</span>
                    </div>
                    <div class="square">
                        <span class="stats-square">748</span>
                        <span class="square-text">Apartments</span>
                    </div> <!-- div.square -->
                </div> <!-- div.stats-line -->
                <div class="stats-line">
                    <div class="square">
                        <span class="stats-square">748</span>
                        <span class="square-text">Apartments</span>
                    </div>
                    <div class="square">
                        <span class="stats-square">748</span>
                        <span class="square-text">Apartments</span>
                    </div> <!-- div.square -->
                </div> <!-- div.stats-line -->
            </div> <!-- div.stats-num -->
        </section>
        <section class="apartments">
            <div class="wrapper apart">
                <h2>More than 500+<br>Apartments For Rent</h2>
                <div class="cards">
                    <div class="card">
                        <img src="./img/armchair.jpg" alt="Armchair in apartment" width="348px" height="379px">
                        <div class="card-container">
                            <p>Lorem ipsum dolor sit amet.</p>
                            <div class="card-info">
                                <div class="money">$3,500</div>
                                <div class="info">
                                    <span><i class="fas fa-shower"></i>2BA</span>
                                    <span><i class="fas fa-bed"></i>2BD</span>
                                </div> <!-- div.info -->
                            </div> <!-- div.card-info -->
                        </div> <!-- div.card-container -->
                    </div> <!-- div.card -->
                    <div class="card">
                        <img src="./img/armchair.jpg" alt="Armchair in apartment" width="348px" height="379px">
                        <div class="card-container">
                            <p>Lorem ipsum dolor sit amet.</p>
                            <div class="card-info">
                                <div class="money">$3,500</div>
                                <div class="info">
                                    <span><i class="fas fa-shower"></i>2BA</span>
                                    <span><i class="fas fa-bed"></i>2BD</span>
                                </div> <!-- div.info -->
                            </div> <!-- div.card-info -->
                        </div> <!-- div.card-container -->
                    </div> <!-- div.card -->
                    <div class="card">
                        <img src="./img/armchair.jpg" alt="Armchair in apartment" width="348px" height="379px">
                        <div class="card-container">
                            <p>Lorem ipsum dolor sit amet.</p>
                            <div class="card-info">
                                <div class="money">$3,500</div>
                                <div class="info">
                                    <span><i class="fas fa-shower"></i>2BA</span>
                                    <span><i class="fas fa-bed"></i>2BD</span>
                                </div> <!-- div.info -->
                            </div> <!-- div.card-info -->
                        </div> <!-- div.card-container -->
                    </div> <!-- div.card -->
                    <div class="card">
                        <img src="./img/armchair.jpg" alt="Armchair in apartment" width="348px" height="379px">
                        <div class="card-container">
                            <p>Lorem ipsum dolor sit amet.</p>
                            <div class="card-info">
                                <div class="money">$3,500</div>
                                <div class="info">
                                    <span><i class="fas fa-shower"></i>2BA</span>
                                    <span><i class="fas fa-bed"></i>2BD</span>
                                </div> <!-- div.info -->
                            </div> <!-- div.card-info -->
                        </div> <!-- div.card-container -->
                    </div> <!-- div.card -->
                    <div class="card">
                        <img src="./img/armchair.jpg" alt="Armchair in apartment" width="348px" height="379px">
                        <div class="card-container">
                            <p>Lorem ipsum dolor sit amet.</p>
                            <div class="card-info">
                                <div class="money">$3,500</div>
                                <div class="info">
                                    <span><i class="fas fa-shower"></i>2BA</span>
                                    <span><i class="fas fa-bed"></i>2BD</span>
                                </div> <!-- div.info -->
                            </div> <!-- div.card-info -->
                        </div> <!-- div.card-container -->
                    </div> <!-- div.card -->
                    <div class="card">
                        <img src="./img/armchair.jpg" alt="Armchair in apartment" width="348px" height="379px">
                        <div class="card-container">
                            <p>Lorem ipsum dolor sit amet.</p>
                            <div class="card-info">
                                <div class="money">$3,500</div>
                                <div class="info">
                                    <span><i class="fas fa-shower"></i>2BA</span>
                                    <span><i class="fas fa-bed"></i>2BD</span>
                                </div> <!-- div.info -->
                            </div> <!-- div.card-info -->
                        </div> <!-- div.card-container -->
                    </div> <!-- div.card -->
                </div> <!-- div.cards -->
                <div class="buttons-search">
                    <form>
                        <input type="text" placeholder="Search Locations">
                        <input type="submit" value="Search">
                    </form>
                    <button class="all">View All Apartments</button>
                </div> <!-- div.buttons-search -->
            </div> <!-- div.wrapper.apart -->
        </section>
        <section class="steps">
            <div class="wrapper">
                <h2>How It Works</h2>
                <p class="steps-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                <p class="steps-text mbtext">Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Assumenda, tempore voluptatibus?</p>
                <div class="steps-container">
                    <div class="step-block" id="stepbl1">
                        <p class="step-num">01</p>
                        <h4><span>01</span>Find Your Location</h4>
                        <p class="step-info">Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                             Tenetur dicta accusantium nulla quibusdam magnam.</p>
                        <p class="stepinfolast" id="stepbrdr1">Find Location</p>
                    </div>
                    <div class="step-block" id="stepbl2">
                        <p class="step-num">02</p>
                        <h4><span>02</span>How Many Rooms?</h4>
                        <p class="step-info">Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                             Tenetur dicta accusantium nulla quibusdam magnam.</p>
                        <p class="stepinfolast" id="stepbrdr2">Find Location</p>
                    </div>
                    <div class="step-block" id="stepbl3">
                        <p class="step-num">03</p>
                        <h4><span>03</span>Price</h4>
                        <p class="step-info">Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                             Tenetur dicta accusantium nulla quibusdam magnam.</p>
                        <p class="stepinfolast" id="stepbrdr3">Find Location</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="services wrapper">
            <h2>Services</h2>
            <p>Lorem ipsum dolor sit amet consectetur.</p>
            <p>Lorem ipsum dolor sit amet.</p>
            <div class="serv-container">
                <div class="serv-img-container">
                    <img src="./img/room2.jpg" alt="Room" width="649px" height="629px">
                </div>
                <div class="serv-text">
                    <h4 class="top-heading">Renting</h4>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                         Provident laboriosam explicabo aliquid ex aperiam eveniet corrupti,
                          enim at delectus molestias totam dolores exercitationem.</p>
                    <h4>Selling</h4>
                    <p>Lorem ipsum dolor sit amet consectetur,
                         adipisicing elit. Provident laboriosam
                          explicabo aliquid ex aperiam eveniet corrupti, enim at
                           delectus molestias totam dolores exercitationem.</p>
                    <h4>Building</h4>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                         Provident laboriosam explicabo aliquid ex aperiam eveniet corrupti,
                          enim at delectus molestias totam dolores exercitationem.</p>
                </div>
            </div>
        </section>
        <section class="agents">
            <div class="wrapper">
                <h2>Meet Our Agents</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.<br> 
                    Temporibus dolores maxime natus?</p>
            </div>
            <div class="agent-cards">
                <div class="agent-card">
                    <img src="./img/agent.jpg" alt="Agent" width="344px" height="381px">
                    <div class="agent-info">
                        <p>Agent</p>
                        <div class="agent-block">
                            <p class="agent-name">Mr. Luke Skywalker</p>
                            <div class="social">
                                <i class="fab fa-twitter"></i>
                                <i class="fab fa-facebook"></i>
                                <i class="fab fa-instagram"></i>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="agent-card">
                    <img src="./img/agent.jpg" alt="Agent" width="344px" height="381px">
                    <div class="agent-info">
                        <p>Agent</p>
                        <div class="agent-block">
                            <p class="agent-name">Mr. Luke Skywalker</p>
                            <div class="social">
                                <i class="fab fa-twitter"></i>
                                <i class="fab fa-facebook"></i>
                                <i class="fab fa-instagram"></i>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="agent-card">
                    <img src="./img/agent.jpg" alt="Agent" width="344px" height="381px">
                    <div class="agent-info">
                        <p>Agent</p>
                        <div class="agent-block">
                            <p class="agent-name">Mr. Luke Skywalker</p>
                            <div class="social">
                                <i class="fab fa-twitter"></i>
                                <i class="fab fa-facebook"></i>
                                <i class="fab fa-instagram"></i>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="add wrapper">
            <div class="add-line">
                <div class="line-img">
                    <img src="./img/room3.jpg" alt="Room" width="541px" height="330px">
                    <div class="location">
                        <div class="location location-melbourn">
                            <i class="fas fa-map-marker-alt"></i>
                            Melbourn, Australia
                        </div>
                    </div>
                </div>
                <div class="line-text">
                    <h3>Super Awesome ad</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                         Eius quas quaerat recusandae voluptatum repudiandae modi laudantium totam officiis
                          rerum sed consectetur excepturi doloremque quis quos iure, 
                          quasi suscipit ipsa commodi ducimus,
                         rem aliquam culpa temporibus?</p>
                </div>
            </div>
            <div class="add-line add-line-right">
                <div class="line-text">
                    <h3>Super Awesome ad</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                         Eius quas quaerat recusandae voluptatum repudiandae modi laudantium totam officiis
                          rerum sed consectetur excepturi doloremque quis quos iure, 
                          quasi suscipit ipsa commodi ducimus,
                         rem aliquam culpa temporibus?</p>
                </div>
                <div class="line-img">
                    <img src="./img/room3.jpg" alt="Room" width="541px" height="330px">
                    <div class="location">
                        <div class="location location-australia">
                            <i class="fas fa-map-marker-alt"></i>
                            Melbourn, Australia
                        </div>
                    </div>
                </div>
            </div>
            <div class="add-line">
                <div class="line-img">
                    <img src="./img/room3.jpg" alt="Room" width="541px" height="330px">
                </div>
                <div class="line-text">
                    <h3>Super Awesome ad</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                         Eius quas quaerat recusandae voluptatum repudiandae modi laudantium totam officiis
                          rerum sed consectetur excepturi doloremque quis quos iure, 
                          quasi suscipit ipsa commodi ducimus,
                         rem aliquam culpa temporibus?</p>
                    <div class="show-more">Show me more</div>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <div class="wrapper">
            <div class="footer-block">
                <div class="footer-logo">
                    <h3>luxestate</h3>
                    <h3>Explore Real Estate</h3>
                </div>
                <div class="footer-search">
                    <input type="text" placeholder="Subscribe to Our Newsletter">
                </div>
            </div>
            <hr>
            <div class="footer-links">
                <div class="footer-links-logo">
                    <h4>luxestate</h4>
                </div>
                <div class="footer-link">
                    <p>luxestate</p>
                    <a href="#">Agents</a>
                    <a href="#">Hunters</a>
                </div>
                <div class="footer-link">
                    <p>luxestate</p>
                    <a href="#">Agents</a>
                    <a href="#">Hunters</a>
                    <a href="#">Agents</a>
                    <a href="#">Hunters</a>
                </div>
                <div class="footer-link">
                    <p>luxestate</p>
                    <a href="#">Agents</a>
                    <a href="#">Hunters</a>
                </div>
                <div class="footer-link">
                    <p>luxestate</p>
                    <a href="#">Agents</a>
                    <a href="#">Hunters</a>
                    <a href="#">Agents</a>
                </div>
            </div>
        </div>
    </footer>
    <script src="./script.js"></script>
</body>
</html>
