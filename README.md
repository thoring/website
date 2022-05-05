# website
<!DOCTYPE html>
<html lang="en">
<head>
    <!--Opening-->
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Major-Project</title>
    <link rel="stylesheet" href="./assets/css/style.css">
    <link rel="stylesheet" href="./themify-icons/themify-icons.css"

</head>

<body>
    <div id="main">
        <div id="header">
            <!--Begin: Nav-->
            <ul id="nav">
                <li><a href="">Home</a></li>
                <li><a href="">Band</a></li>
                <li><a href="">Tour</a></li>
                <li><a href="">Contact</a></li>
                <li>
                    <a href="">
                        More 
                        <i class="ti-angle-down"></i>
                    </a>
                    <ul class="subnav">
                        <li><a href="">Merchandise</a></li>
                        <li><a href="">Extras</a></li>
                        <li><a href="">Media</a></li>
                    </ul>
                </li>
            </ul>
            <!--End: Nav-->
            <!--Begin: Search Button-->
            <div class="search-button">
                <i class="search-icon ti-search"></i>
            </div>
            <!--End: Search Button-->
        </div>
        <div id="slider">
            <!-- Text content-->
            <div class="text-content">
                <h2 class="text heading">New York</h2>
                <div class="text-description">The atmosphere in New York is lorem ipsum.</div>
            </div>    
        </div>
        
        <div id="content">
            <!-- About section-->
            <div class="content-section">
                <h2 class="section-heading">THE BAND</h2>
                <p class="section-sub-heading">We love music</p>
                <p class="about-text">We have created a fictional band website. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                </p>
                <div class="list">
                    <div class="list-item">
                        <p class="item-name">Name</p>
                        <img src="assets/css/d.jpg" alt="Name" class="item-avatar">
                    </div>

                    <div class="list-item">
                        <p class="item-name">Name</p>
                        <img src="assets/css/d.jpg" alt="Name" class="item-avatar">
                    </div>

                    <div class="list-item">
                        <p class="item-name">Name</p>
                        <img src="assets/css/d.jpg" alt="Name" class="item-avatar">
                    </div>
                </div>
            </div>

            <!--Tour Section-->
            <div class="tour-section">

                <div class="content-section">
                    <h2 class="section-heading text-white">TOUR DATES</h2>
                    <p class="section-sub-heading text-white">Remember to book your ticket!</p>
                    
                    <ul class="tickets-list">
                        <li>March <span class="sold-out">Sold out</span></li>
                        <li>April</li> <span class="quantity">3</span></li>
                        <li>May</li> <span class="quantity">5</span></li>
                    </ul>
                </div>
            </div>
            
            <!--Contact Section-->
            <div class="content-section">
                <h2 class="section-heading">CONTACT</h2>
                <p class="section-sub-heading">Fan? Drop a note!</p>
        </div>
        
    </div>
    CSS
  
  
  
  /* Reset CSS */
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

/* font for all html */

html{
    font-family: Arial, Helvetica, sans-serif;
}

.clear{
    clear:both
}

.text-white{
    color: #fff !important;
}

/* main */
#main{

}

/* header */

#header {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    height: 46px;
    background-color: #000;
    z-index: 1;
}

#nav{
    display: inline-block;
}

#nav, .subnav{
    list-style-type: none;
}

#nav > li{
    display: inline-block;
}

#nav li{
    position: relative;
}

#nav > li > a{
    color: #fff;
    text-transform: uppercase;
}
#nav li a{
    text-decoration: none;
    line-height: 46px;
    padding: 0 24px;
    display: block;
}

#nav li:hover .subnav{
    display: block;
}

#nav > li:hover > a, 
#nav .subnav li:hover  a{
    color: #000;
    background-color: #ccc;
}

#nav .subnav{
    display: none;
    min-width: 160px;
    position: absolute;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

#nav .subnav a{
    color: #000;
    padding: 0 12px;
    line-height: 38px;
}

#nav .ti-angle-down{
    font-size: 14px;
}
#header .search-button{
    float: right;
    padding: 0 21px;
}
#header .search-icon{
    color: #fff;
    font-size: 20px;
    line-height: 46px;
}

#header .search-button:hover{
    background-color: #f44336;
    cursor:cell;
}

#slider{

    margin-top: 46px;
    padding-top: 50%;
    background: url('https://www.w3schools.com/w3images/ny.jpg')top center / cover no-repeat;
}

#slider .text-content{
    position:absolute;
    bottom: 47px;
    color: #fff;
    width: 100%;
    text-align: center;
}

#slider .text-heading{
    font-weight: 500;
    font-size: 24px;
}

#slider .text-description{
    font-size: 15px;
    margin-top: 25px;
}


#content{

}

#content .content-section{
    width: 800px;
    padding: 64px 0;
    margin-right: auto;
    margin-left: auto;
}

#content .section-heading{
    font-size: 30px;
    text-align: center;
    font-weight: 500;
    letter-spacing: 4px;
}

#content .section-sub-heading{
    font-size: 15px;
    text-align: center;
    margin-top: 25px;
    font-style: italic;
    opacity: 0.6;
}
#content .about-text{
    margin-top: 25px;
    font-size: 15px;
    text-align: justify;
    line-height: 1.4;

}

#content .member-item{
    float: left;
}


/*tour section*/
.tour-section{
    background: #000;
}

.tickets-list{
    background-color: #fff;
    list-style-type: none;
    margin-top: 40px;

}


.tickets-list li{
    color: #757575;
    font-size: 16px;
    padding: 11px 16px;
    border-bottom: 1px solid #ddd;
}


.tickets-list .sold-out{
    background-color:#f44336;
    color: #fff;
    padding: 4px 4px;
    margin-left: 16px;

}


.tickets-list .quantity{
    float: right;
    width: 24px;
    height: 24px;
    background-color: #000;
    color: #fff;
    border-radius: 50%;
    text-align: center;
    line-height: 24px;
    margin-top: -32px;
}


#footer{

}
