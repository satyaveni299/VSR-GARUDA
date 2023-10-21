
this is html code and in the bottom we've kept css code
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="smoke.css">
    <title>smoke effect on Name</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>


</head>

<body>
    <div id="sectionname">

        <section class="name-container">

            <video src="C:\Users\KAVYANEE\OneDrive\Desktop\smoke.mp4" autoplay muted></video>
            <h1>
                <span class="vsr">V</span>
                <span class="vsr">S</span>
                <span class="vsr">R</span>

            </h1>
            <h1 style="color:white;font-size:56px;margin-top:120px;">VIRTUAL SENSING ROBOT</h1>

            <button class="next" onclick="display('sectionimages')"><svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="currentColor" class="bi bi-arrow-right-circle-fill" viewBox="0 0 16 16">
                    <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0zM4.5 7.5a.5.5 0 0 0 0 1h5.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.708.708L10.293 7.5H4.5z" />
                </svg> Next
            </button>
        </section>
    </div>


    <div id="sectionimages">
        <p style="font-size:56px;color:black;font-weight:bold;text-align:center">VSR GARUDA MODEL</p>
        <div class="d-flex flex-row justify-content-center">
            <div class="container p-5 ml-5" style="height:100vh width:100vw;">
                <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner  ">
                        <div class="carousel-item active text-center">
                            <h1 style="color:white" class="mt-4"></h1>
                            <div class="middle-container  " style="height:70vh; background-color:black">
                                <img class="d-block w-100 carousel-image" style="height:60vh;" src="  https://netrinoimages.s3.eu-west-2.amazonaws.com/2015/05/27/389661/193022/eagle_3d_model_c4d_max_obj_fbx_ma_lwo_3ds_3dm_stl_2042862_o.jpg  " id="carousel-image" alt="First slide">

                            </div>
                        </div>
                        <div class="carousel-item text-center">
                            <h1 style="color:white" class="mt-4"></h1>
                            <div class="middle-container " style="height:70vh; background-color:black">
                                <img class="d-block w-100 css-image" src="" alt="Second slide">
                                <p style="color:white;font-size:30px;margin:20px;padding:80px;">
                                    We've named our virtual sensing robot GARUDA. According to history, Garuda symbolizes speed, power, and protection. Our virtual sensing robot is designed to protect the environment from natural hazards, prevent accidents by detecting potential issues before they occur, and safeguard animals from harm. Just like the ancient Garuda, this robot is dedicated to protecting."
                                </p>
                            </div>
                        </div>
                        <div class="carousel-item text-center">
                            <h1 style="color:white" class="mt-4"></h1>
                            <div class="middle-container " style="height:70vh; background-color:black">
                                <img class="d-block w-100 js-image" src="" alt="Third slide">
                                <p style="color:white;font-size:38px;margin:20px;padding:80px;">
                                    It is an idea which can definitely bring the change.
                                </p>
                            </div>
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>

            </div>


        </div>
        <div class="d-flex flex-row">
            <button style="color:black;height:65px;width:154px;border:0px;border-radius:5px;margin-left:490px;margin-top:50px;font-size:30px;font-weight:bold;padding:3px;" onclick="display('sectionname')">Back</button>
            <button style="color:black;height:65px;width:154px;border:0px;border-radius:5px;margin-left:50px;margin-top:50px;font-size:30px;font-weight:bold;padding:3px;" onclick="display('sectionfeatures')">Next</button>
        </div>
    </div>



    <div id="sectionfeatures">

        <div class="home-section">


            <p style="font-size:78px;color:white;font-weight:bold;text-align:center">FEATURES OF GARUDA </p>
            <div class=" d-flex flex-row">
                <div class="item-card">
                    <p style="margin-top:0px; font-size:35px;font-weight:bold;">GPS</p>
                    <img src="https://static.vecteezy.com/system/resources/previews/000/573/624/original/map-pointer-gps-icon-vector.jpg " class="item-image" style="height:125px;width:145px;" onclick="display('sectiongps')" />

                </div>

                <div class="item-card">
                    <p style="margin-top:5px; font-size:35px;font-weight:bold;">LIVE CAM</p>
                    <img src="https://image.freepik.com/free-icon/webcam-tool-black-circular-shape_318-56301.jpg  " class="item-image" style="height:105px;width:105px;" onclick="display('sectionlivecam')" />

                </div>
            </div>
            <div class="d-flex flex-row">
                <div class="item-card">
                    <p style="margin-top:0px; font-size:35px;font-weight:bold;">SEARCH</p>
                    <img src="https://tse4.mm.bing.net/th?id=OIP.Bso6si4xtedIzIDLgXk2UQHaHa&pid=Api&P=0&h=220" class="item-image" style="height:105px;width:105px;" onclick="display('sectionsearch')" />

                </div>
                <div class="item-card">
                    <p style="margin-top:0px; font-size:35px;font-weight:bold;">OBJECT DETECTION</p>
                    <img src="https://cdn4.iconfinder.com/data/icons/object-detection-technology/24/material_scan_reader_recognition_cancel_error_fail-256.png  " class="item-image" style="height:105px;width:105px;" onclick="display('sectionobject')" />

                </div>
            </div>

            <div class="d-flex flex-row">
                <div class="item-card">
                    <img src="data:image/webp;base64,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" class="item-image" style="height:125px;width:125px;" onclick="display('sectionhazard')" />
                    <p style="margin-top:0px; font-size:35px;font-weight:bold;">NATURAL HAZARDS</p>
                </div>
                <div class="item-card">
                    <img src=" https://cdn.vectorstock.com/i/1000x1000/87/69/deforestation-glyph-icon-vector-28428769.webp   " class="item-image" style="height:105px;width:125px;" onclick="display('sectionillegal')" />
                    <p style="margin-top:0px; font-size:35px;font-weight:bold;">ILLEAGAL ACTIVITY</p>
                </div>
            </div>
            <div class="d-flex flex-row">
                <button style="color:black;height:65px;width:154px;border:0px;border-radius:5px;margin-left:535px;margin-top:50px;font-size:30px;font-weight:bold;padding:3px;" onclick="display('sectionimages')">Back</button>

            </div>
        </div>
    </div>


    <div id="sectiongps">
        <div class="gps-container p-4">
            <img src="https://tse3.mm.bing.net/th?id=OIP.9Ey8AKn4k9dDAPbRQuOSzgHaEe&pid=Api&P=0&h=220" class="forest-image">
            <a href="https://www.google.com/maps" style="font-size:40px; margin-left:440px; margin-top:250px;">Watch Here<a />
                <p style="font-size:25px; margin:10px"> The VSR GARUDA locates the animal positions for every frequent of time if the animal or the wild life creature gets closer to the human-animal interaction area .Then it gives the notifications repeatedly to the
                    forest officers what type of animal is approaching so that we can save the human lives.</p>

                <button style="color:black;height:65px;width:154px;border:0px;border-radius:5px;margin-left:490px;margin-top:50px;font-size:30px;font-weight:bold;padding:3px;" onclick="display('sectionfeatures')">Back</button>
        </div>
    </div>

    <div id="sectionlivecam">
        <div class="p-3">
            <iframe width="1140" height="715" src="https://www.youtube.com/embed/SABaMN08NmY?si=nAmBM1broDAmBftg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            <p style="font-size:35px;">This is an example video of how the VSR GARUDA scans the area....</p>
            <div class="d-flex flex-row">
                <button style="color:black;height:65px;width:154px;border:0px;border-radius:5px;margin-left:550px;margin-top:50px;font-size:30px;font-weight:bold;padding:3px;" onclick="display('sectionfeatures')">Back</button>
            </div>
        </div>
    </div>

    <div id="sectionsearch">
        <div class="searching-container p-3" style="background-color:#225db0;height:100vh;color:white;">
            <p class="searching-title" style="font-size:55px;font-weight:bold;text-align:center;color:white;">Searching</p>
            <div class="d-flex flex-row">
                <p class="input" style="color:white;">Input</p>
                <button class="input-button">upload here</button>
            </div>
            <p class="input-para">Upload the image of the object/human that you are searching for </p>
            <button style="color:black;height:65px;width:154px;border:0px;border-radius:5px;margin-left:510px;margin-top:50px;font-size:30px;font-weight:bold;padding:3px;" onclick="display('sectionfeatures')">Back</button>

        </div>
    </div>
    <div id="sectionobject">
        <div class="object-detection">
            <h2 style="padding:25px;font-size:65px;color:white;font-weight:bold;">OBJECT DETECTION</h2>
            <div class="d-flex flex-row " style="margin:30px;margin-left:190px">
                <div class="tree-card">
                    <p style="text-align:center;font-size:33px;color:grey;font-weight:bold">Trees Detection</p>
                    <img src="https://img.freepik.com/free-vector/hand-drawn-tree-life-brown-shades_23-2148703761.jpg?w=740&t=st=1697642579~exp=1697643179~hmac=babbb3b3a18480a5bf9729487f2dfac0a241e0fe1ae528ad264654408639760d" class="image" style="margin-bottom:35px;">

                </div>
                <div class="tree-card">
                    <p style="text-align:center;font-size:33px;color:grey;font-weight:bold">Human Detection</p>
                    <img src="https://www.pngitem.com/pimgs/m/78-787644_transparent-humans-png-people-line-icon-png-png.png" class="image">
                </div>
            </div>
            <div class="d-flex flex-row" style="margin:30px;margin-left:190px">
                <div class="tree-card">
                    <p style="text-align:center;font-size:33px;font-weight:bold;color:grey">Animal Detection</p>
                    <img src="data:image/jpeg;base64,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" class="image">

                </div>
                <div class="tree-card">
                    <p style="text-align:center;font-size:33px;font-weight:bold;color:grey">Weapon Detection</p>
                    <img src="data:image/jpeg;base64,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" class="image">
                </div>
            </div>

            <button style="color:black;height:65px;width:154px;border:0px;border-radius:5px;margin-left:539px;margin-top:50px;font-size:30px;font-weight:bold;padding:3px;" onclick="display('sectionfeatures')">Back</button>
        </div>
    </div>

    <div id="sectionhazard">
        <div class="fire-container m-4 ">
            <img src="https://visiontir.com/wp-content/uploads/2020/12/fuego_forestal_1200x575-1024x491.jpg" style="width:100vw;">
            <h1 class="mt-3 " style="font-size:55px;font-weight:bold;margin-bottom:30px;">Detecting Stages Of Fire</h1>
            <p class="hazard-stage" style="font-size:25px;font-weight:bold;">smoke detecting</p>
            <div class="d-flex flex-row">

                <button class="hazard-msg" style="width:800px;border-radius:12px;font-size:25px">Here it shows the condition of the fire ........</button>
                <svg xmlns="http://www.w3.org/2000/svg" width="76" height="76" fill="currentColor" class="bi bi-bell-fill" viewBox="0 0 16 16" class="logo">
                    <path d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zm.995-14.901a1 1 0 1 0-1.99 0A5.002 5.002 0 0 0 3 6c0 1.098-.5 6-2 7h14c-1.5-1-2-5.902-2-7 0-2.42-1.72-4.44-4.005-4.901z" />
                </svg>
            </div>
            <p class="hazard-stage" style="font-size:25px;font-weight:bold;">Initial Stage</p>
            <div class="d-flex flex-row">

                <button class="hazard-msg" style="width:800px;border-radius:12px;font-size:25px;">Here it shows the condition of the fire ........</button>
                <svg xmlns="http://www.w3.org/2000/svg" width="76" height="76" fill="currentColor" class="bi bi-bell-fill" viewBox="0 0 16 16" class="logo">
                    <path d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zm.995-14.901a1 1 0 1 0-1.99 0A5.002 5.002 0 0 0 3 6c0 1.098-.5 6-2 7h14c-1.5-1-2-5.902-2-7 0-2.42-1.72-4.44-4.005-4.901z" />
                </svg>
            </div>
            <p class="hazard-stage" style="font-size:25px;font-weight:bold;">Intermediate Stage</p>
            <div class="d-flex flex-row">

                <button class="hazard-msg" style="width:800px;border-radius:12px;font-size:25px;">Here it shows the condition of the fire ........</button>
                <svg xmlns="http://www.w3.org/2000/svg" width="76" height="76" fill="currentColor" class="bi bi-bell-fill" viewBox="0 0 16 16" class="logo">
                    <path d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zm.995-14.901a1 1 0 1 0-1.99 0A5.002 5.002 0 0 0 3 6c0 1.098-.5 6-2 7h14c-1.5-1-2-5.902-2-7 0-2.42-1.72-4.44-4.005-4.901z" />
                </svg>
            </div>
            <p class="hazard-stage" style="font-size:25px;font-weight:bold;">Advanced Stage</p>
            <div class="d-flex flex-row">

                <button class="hazard-msg" style="width:800px;border-radius:12px;font-size:25px;">Here it shows the condition of the fire ........</button>
                <svg xmlns="http://www.w3.org/2000/svg" width="76" height="76" fill="currentColor" class="bi bi-bell-fill" viewBox="0 0 16 16" class="logo">
                    <path d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zm.995-14.901a1 1 0 1 0-1.99 0A5.002 5.002 0 0 0 3 6c0 1.098-.5 6-2 7h14c-1.5-1-2-5.902-2-7 0-2.42-1.72-4.44-4.005-4.901z" />
                </svg>
            </div>


            <button style="color:black;height:65px;width:154px;border:0px;border-radius:5px;margin-left:510px;margin-top:50px;font-size:30px;font-weight:bold;padding:3px;" onclick="display('sectionfeatures')">Back</button>

        </div>
    </div>

    <div id="sectionillegal">
        <div class="mining-container m-3">
            <img src="https://ichef.bbci.co.uk/news/800/cpsprodpb/CF7E/production/_118781135_rs78184_for_5377-lpr.jpg" style="width:100vw;margin:10px">

            <h1 class="ml-1 mt-5 mb-4" style="font-size:55px;text-align:center;">Illegal Mining</h1>
            <p class="ill-para" style="font-size:45px">
                Official Mining Details
            </p>
            <div class="d-flex flex-row">
                <p class="input-name">Input</p>
                <button class="input-button1">upload here</button>
            </div>
            <p class="input-para1">Upload the official details of the mining </p>
            <p style="font-size:45px">Current Mining Details</p>
            <button class="input-button2" style="margin-left:130px;height:78px;width:800px;border-radius:13px;font-size:24px;">The Current Mining details are captured by the VSR GARUDA's scanning ability.</button>
            <p style="font-size:29px; color:red">Here it shows the warning message if any illegal mining happens according to the given mining details after scanning the mining location ⚠️.</p>

            <button style="color:black;height:65px;width:154px;border:0px;border-radius:5px;margin-left:510px;margin-top:50px;font-size:30px;font-weight:bold;padding:3px;" onclick="display('sectionfeatures')">Back</button>





        </div>
    </div>



    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>

</html>

............#css code.........,.........

@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.vsr {
    font-size: 190px;
}

.next {
    color: white;
    background-color: black;
    border: 0px;
    margin-top: 800px;
    margin-left: 600px;
    font-size: 47px;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

video {
    object-fit: cover;
}

section {
    background: #000;
    height: 100vh;
}

h1 {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 100%;
    text-align: center;
    letter-spacing: 1rem;
    text-transform: uppercase;
    color: #f5f5f5;
    font-size: 5em;
    font-family: sans-serif;
}

h1 span {
    display: inline-block;
    animation: animate 1s ease-in-out;

}

@keyframes animate {
    0% {
        opacity: 0%;
        transform: rotateY(90deg);
        filter: blur(10px);
    }

    100% {
        opacity: 1;
        transform: rotateY(0deg);
        filter: blur(0px);
    }
}

h1 span:nth-child(1) {
    animation-delay: 0.6s;
}

h1 span:nth-child(2) {
    animation-delay: 1s;
}

h1 span:nth-child(3) {
    animation-delay: 1.7s;
}

h1 span:nth-child(4) {
    animation-delay: 2.3s;
}

h1 span:nth-child(5) {
    animation-delay: 2.7s;
}

h1 span:nth-child(6) {
    animation-delay: 3.2s;
}

h1 span:nth-child(7) {
    animation-delay: 3.7s;
}

h1 span:nth-child(8) {
    animation-delay: 4s;
}

.home-section {
    background-color: #225db0;
    height: 190vh;
    width: 100vw;
    background-size: cover;
}

.object-detection {
    background-color: #225db0;
    background-size: cover;
    height: 160vh;

}

.image {
    height: 220px;
    width: 270px;
    margin: 20px;
    margin-left: 35px;
    margin-bottom: 55px;
    border-radius: 10px;
    border-radius: 18px;
}

.tree-card {
    background-color: white;
    height: 310px;
    width: 360px;
    border-radius: 13px;
    margin: 15px;

}

.heading-empower {
    color: white;
    font-family: Sans-Serif;
    font-weight: bold;
    font-size: 55px;

}

.para-empower {
    color: white;
    text-align: center;
    font-size: 19px;
}

.item-card {
    background-color: white;
    color: black;
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
    border-bottom-left-radius: 15px;
    border-bottom-right-radius: 15px;
    height: 36vh;
    width: 42vw;
    text-align: center;
    padding: 20px;
    margin: 11px;
    margin-left: 70px;
    margin-top: 15px;


}

.name-container {
    height: 130vh;
    width: 100vw;
}

.item-image {
    height: 100px;
}

.forest-image {
    width: 100vw;

}

.searching-title {
    color: black;
    font-size: 65px;
    margin: 15px;
}

.input {
    color: black;
    font-size: 45px;
    margin: 29px;
    margin-top: 79px;


}

.input-para {
    font-size: 25px;
    margin-left: 170px;
}

.input-button {
    height: 100px;
    width: 1000px;
    font-size: 49px;
    margin-top: 59px;
}

.input-name {
    font-size: 35px;
    color: grey;
    font-weight: bold;
    margin-right: 20px;
    margin-left: 15px;

}

.input-button1 {
    width: 65vw;
    margin-left: 15px;
    border-radius: 15px;
    font-size: 32px;
}

.input-para1 {
    margin-left: 125px;
    margin-top: 15px;
    font-size: 25px;
}



