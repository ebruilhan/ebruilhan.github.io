# ebruilhan.github.io
<!DOCTYPE html>
<html lang="tr">
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>EBRU İLHAN-RESUME</title>
        <meta charset="utf-8">
        <link rel="icon" type="image/png" href=ben.png>
        <style>

            @media print {  
                body {
                    -webkit-print-color-adjust: exact; 
                    print-color-adjust: exact; 
                    background-image: url('https://i.imgur.com/XA4PKyG.jpeg'); 
                    background-size: cover;
                    background-repeat: no-repeat;
                    background-position: center;
                    margin:0;
                    padding:0;
                }
                html, body {
                    page-break-inside: avoid;
                    break-inside: avoid;
                    overflow: visible;
                    display:block;
                   /*overflow: visible !important;*/ 
                }
                #about-me {
                    page-break-inside: avoid;
                }
            }
            * {
                margin: 0;
                padding: 0;
                box-sizing: border-box;
            }
            body {
                font-family: Arial, sans-serif;
                display: flex;
                height: 100vh;
                margin:4em auto;
                background-image:url('https://i.imgur.com/XA4PKyG.jpeg');
                background-size: cover;
                background-attachment: fixed;
                height: 100vh;
                background-repeat: no-repeat;
                background-position: center;
                display: -webkit-flex; 
                display: -ms-flexbox; 
                display:flex; 
            }     
            .footer {
                color: rgb(24,245,255);
                text-align: center;
                padding: 15px;
                position: fixed;
                bottom: 0px;
                width: 100%;
            }
            .footer p {
                margin: 0;
                font-size: 14px;
                font-style: italic;
            } 
            /* The left part(personal information) */
            .left-side {
                width: 60%;
                padding: 20px;
            }
            h1 {
                font-size: 32px;
                color: #333;
            }
            h2 {
                font-size: 24px;
                color: #555;
            }         
            p {
                font-size: 16px;
                color: #666;
                margin-top: 10px;
            }
            ul {
                margin-top: 10px;
                padding-left: 20px;
            }
            li {
               font-size: 16px;
               color: #444;
            }
            .certification_link {
                color:blue;
                text-decoration: none;
                font-weight: bold;
            }   
            .certification_link:hover {
                color: orange;
            }
            .certification_link:active {
                color: red;
            }
            .certification_link:visited {
                color: purple;
            }
            /* The right part (Profile picture  & contact icons) */
            .right-side {
                width: 40%;
                text-align: center;
                position: relative;
                gap:10px;
                margin-top: 20px;          
            }
            .profile-pic {
                width: 250px;
                height: 250px;
                border-radius: 50%;
                object-fit: cover;
                margin-top: 40px;
                margin-right: 50px;
                border: 4px solid #333;           
            }
            .social_links {
                background-color: white;
                position: absolute;
                top: 60px; 
                right: 50px; 
                display: flex; 
                justify-content: space-between; 
                gap: 20px; 
                border:solid 2px white;
            }
            .socia_-links a {
                margin-bottom: 30px;
                margin-top:30px;
            }
            .social_links img {
                width: 30px;
                height: 30px;
                transition: transform 0.3s ease;
            }
            .social_links img:hover {
                transform: scale(1.1);
            }
        </style>
    </head>
    <body>
        <!-- The left part(informations) --> 
        <div class="left-side"  >
            <h1 style="color:darkred ;font-size: 45px;text-align: center;">EBRU İLHAN-RESUME</h1>
            <br><br>
            <h2 style="color:purple">About Me</h2>
            <p>
                <ul type="square" >
                    <li style="font-size: 15px;">
                        I am a professional with a strong passion in the fields of technology and product 
                        development.  Currently I am a sophomore computer engineering student  
                        and I want to improve myself in the fields of software development 
                        and especially artificial intelligence in the future.
                        I am cooperative in teamwork, which is one of my strongest qualities. 
                        My goal is to develop effective and efficient products
                        by always keeping the user experience at the forefront.       
                    </li>  
                </ul><br><br><br>              
            </p>
            <h2 style="color:purple">Personal İnformation</h2>
            <ul>
                <li>Ebru İlhan</li>
                <li>2210206061</li>
                <li>2210206061@ogrenci.karabuk.edu.tr</li>
                <li >
                    <a href="https://www.google.com.tr/maps/place/Prof.+Dr.+Necmettin+Erbakan+Park
                    %C4%B1/@41.0357681,28.6422546,17z/data=!3m1!4b1!4m6!3m5!1s0x14b55f396e517e05:
                    0x36a9019fc0a916aa!8m2!3d41.0357641!4d28.6448295!16s%2Fg%2F11c7vv8sfd?hl= 
                    tr&entry=ttu&g_ep=EgoyMDI1MDMxOS4yIKXMDSoJLDEwMjExNjM5SAFQAw%3D%3D"
                    target="_blank" style="color:darkcyan">İstanbul-Esenyurt</a>                  
                </li>
            <br><br><br>
            </ul>  
            <h2 style="color:purple">Education İnformation</h2>
            <ul type="disc">
                <li>Abdulkadir Aksu Anadolu High School</li>
                <li>Karabuk University</li>
                    <ul type="circle">
                        <li>Computer Engineering</li>
                    </ul>
            </ul><br><br><br><br>          
            <h2 style="color:purple">Skills</h2>
            <ul>
                <li>Java</li>
                <li>Object Orianted Programming</li>
                <li>C</li>
                <li>Html</li>
                <li>Css</li>
                <li>Web Design</li>
                <li>Database Managament System</li>
                <li>
                    <a href="sertifikamm.pdf"  target="_blank" class="certification_link">My Certification</a>
                </li>      
            </ul><br><br><br>
            <h2 style="color:purple">Languages</h2>
            <ul>
                <li>Kurdish</li>
                <li>Turkish</li>
                <li>English</li>
            </ul><br><br><br>    
        </div><br><br><br>
        <!-- The right part(profile picture and social media icons) -->
        <div class="right-side">
            <img src="https://i.imgur.com/n5x0BEz.jpeg" class="profile-pic">

        </div> 
        <br><br><br>
        <div class="social_links" >
            <a href="mailto:ilhanebru724@gmail.com">
                <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="E-posta">
            </a>
            <a href="tel:+905347738514">
                <img src="https://cdn-icons-png.flaticon.com/512/159/159832.png" alt="Telefon"></a>

            <a href="https://www.linkedin.com/in/ebru-ilhan-3103b2341/" target="_blank">
                <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
            </a>
            
             <a href="https://www.instagram.com/ebru_ilhn724" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/174/174855.png" alt="Instagram" width="24" height="24">
            </a>
        </div><br><br><br><br>     
        <div class="footer">          
            <p >© Ebru İlhan - All Rights Reserved Worldwide.</p>
        </div><br><br><br>     
    </body>
</html> 
