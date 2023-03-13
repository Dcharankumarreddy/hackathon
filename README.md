# hackathon
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div id="sectionMyProjectsHome">
        <div class="my-projects-home-page">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4WHwjbM41RPKX2pTTpBS26l2l_SHbUpTJhTj7wydDQak4DxBILwamXXfJjfrC0Jz0wLw&usqp=CAU" class="software-developer-image" />
            <h1 class="my-projects-heading">Agriculture</h1>
            <p class="my-projects-description">
                solutions for infected and disease ridden plants
            </p>
            <div class=" edges d-flex flex-row justify-content-center">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4WHwjbM41RPKX2pTTpBS26l2l_SHbUpTJhTj7wydDQak4DxBILwamXXfJjfrC0Jz0wLw&usqp=CAU" class="my-project-image" onclick="display('sectionAdvancedTechnologies')" />
                <img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/What_is_Media_and_Information_literacy.jpg" class="my-project-image" onclick="display('sectionDiwali')" />
            </div>
            <div class="edges d-flex flex-row justify-content-center">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRcQEhgIm69vAnNPtQhuGUgYUZDX3r_ooTCsg&usqp=CAU" class="my-project-image" onclick="display('sectionFoodOrder')" />
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/news-paper-img.png" class="my-project-image" onclick="display('sectionNews')" />
            </div>
        </div>
    </div>
    <div id="sectionAdvancedTechnologies">
        <div class="advanced-technologies-bg-container d-flex flex-column justify-content-end">
            <div class="advanced-technologies-card">
                <h1 class="advanced-technologies-title"> Image scanner</h1>
                <p class="advanced-technologies-description">
                    click scanner button to scan the plant

                </p>
                <button class="advanced-technologies-learn-more-button">
                    <a href="https://teachablemachine.withgoogle.com/models/5DD30xSvY/" target="_blank">
                        SCANNER
                    </a </button>
                    <button class="btn btn-primary" onclick="display('sectionMyProjectsHome')">
                        Back
                    </button>
            </div>
        </div>
    </div>
    <div id="sectionDiwali">
        <div class="diwali-top-section">
            <h1 class="diwali-top-section-heading">
                Detail information about cotton plants
            </h1>
        </div>
        <div class="diwali-bottom-section">
            <div class="d-flex flex-row justify-content-center">
                <div class="diwali-card-item" onclick="display('sectionhome1 ')">
                    <img src="https://www.shutterstock.com/image-photo/close-fresh-cotton-leaves-on-260nw-480426439.jpg" class="diwali-card-image" />
                    <h1 class="diwali-card-name"> Information</h1>
                    <p class="diwali-card-price" onclick="display('sectionhome1 ')">Cotton leaves</p>
                </div>
                <div class="diwali-card-item" onclick="display('sectionhome5')">
                    <img src="https://e7.pngegg.com/pngimages/920/539/png-clipart-cotton-graphics-adobe-shop-cotton-flower-logo-flower.png" class="diwali-card-image" />
                    <h1 class="diwali-card-name">Information</h1>
                    <p class="diwali-card-price" onclick="display('sectionhome5')">Cotton flowers</p>
                </div>
            </div>
            <div class="d-flex flex-row justify-content-center">
                <div class="diwali-card-item" onclick="display('sectionhome3')">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRPZ5QIRKyluNP3F-wlAVgMp5Xm_XljnBkwZQ&usqp=CAU" class="diwali-card-image" />
                    <h1 class="diwali-card-name">Information</h1>
                    <p class="diwali-card-price" onclick="display('sectionhome3')">Cotton boll</p>
                </div>
                <div class="diwali-card-item" onclick="display('sectionhome4')">
                    <img src="https://wildflowerfinder.org.uk/Flowers/C/Cottonweed/PaulaOMearaCottonweed_18th_Sept_2011_012p4.jpg" class="diwali-card-image" />
                    <h1 class="diwali-card-name">Information</h1>
                    <p class="diwali-card-price" onclick="display('sectionhome4')">Weed preventation</p>
                </div>
            </div>
            <div class="d-flex flex-row justify-content-center">
                <button class="btn btn-primary" onclick="display('sectionMyProjectsHome')">
                    Back
                </button>
            </div>
        </div>
    </div>
    <div id="sectionFoodOrder">
        <div class="food-order-bg-container d-flex flex-column justify-content-end">
            <div class="order-card">
                <h1 class="order-card-heading">Related Videos</h1>
                <p class="order-card-paragraph">
                    Here are some informative videos
                </p>
                <button class="order-card-button" onclick="display('sectionFavouritePlaces')">
                    watch now
                </button>
                <button class="btn btn-primary" onclick="display('sectionMyProjectsHome')">
                    Back
                </button>
            </div>
        </div>
    </div>
    <div id="sectionNews">
        <div class="news-bg-container d-flex flex-column justify-content-end">
            <div class="news-card">
                <p class="news-category">NEWS OF THE DAY</p>
                <h1 class="news-title">
                    Article about cotton plants diseases
                </h1>
                <p class="news-description">
                    Cotton is one of the most important commercial crop and it is the back bone
                    of national economy of country. No other fiber comes close to duplicating all of the
                    desirable characteristics combined in cotton. It provides thousands of useful products
                    and supports millions of jobs as it moves from' field to fabric (www.cotton.org ).
                    Cotton is a white fibrous agricultural product that has a wide variety of uses,
                    from textile production, to creating paper, to producing oil and food products.
                    Cotton is grown all around the globe and is traded internationally as well.
                </p>
                <button class="news-button">
                    <a href="https://link.springer.com/chapter/10.1007/978-3-030-16848-3_6" target="_blank">
                        Read more
                    </a>
                </button>
                <button class="btn btn-primary" onclick="display('sectionMyProjectsHome')">
                    Back
                </button>
            </div>
        </div>
    </div>
    <div id="sectionFavouritePlaces">
        <div class="ott-platforms-bg-container">
            <h1 class="ott-platforms-heading"> Related videos</h1>
            <div class="ott-platforms-card-container d-flex flex-row" onclick="display('sectionDetailedView0')">
                <div>
                    <h1 class="ott-platforms-card-heading">weed management</h1>
                    <p class="ott-platforms-card-description">
                        Weed management is an important aspect of cotton production as weeds can
                        compete with the
                        cotton plant for nutrients, water, and light, reducing yield and quality.

                    </p>
                </div>
                <img src="https://agritech.tnau.ac.in/agriculture/images/cotton/Trianthema%20portulacastrum.jpg" class="ott-platforms-card-image" />

            </div>

            <div class="ott-platforms-card-container d-flex flex-row" onclick="display('sectionDetailedView1')">
                <div>
                    <h1 class="ott-platforms-card-heading">Cotton leaves</h1>
                    <p class="ott-platforms-card-description">
                        The leaves on cotton plants are simple, but they vary greatly from species to
                        species. Some are almost completely smooth, while others are hairy (with many trichomes).
                        Most leaf blades are thin and papery, but there are some that are thick and leathery
                    </p>
                </div>
                <img src="https://www.researchgate.net/profile/Faiz-Hashmi-2/publication/348221274/figure/fig2/AS:976509187678210@1609829341348/Picture-of-healthy-cotton-leaf.ppm" class="ott-platforms-card-image" />
            </div>


            <div class="ott-platforms-card-container d-flex flex-row" onclick="display('sectionDetailedView2')">
                <div>
                    <h1 class="ott-platforms-card-heading">Cotton flower</h1>
                    <p class="ott-platforms-card-description">
                        Cotton is a soft, fluffy staple fiber that grows in a boll, or protective case,
                        around the seeds of the cotton plants of the genus Gossypium in the mallow family Malvaceae. The fiber is almost pure cellulose,
                        and can contain minor percentages of waxes, fats, pectins, and water.
                    </p>
                </div>
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/Darwin%27s-cotton-flower.jpg/330px-Darwin%27s-cotton-flower.jpg" class="ott-platforms-card-image" />
            </div>


            <div class="ott-platforms-card-container d-flex flex-row" onclick="display('sectionDetailedView3')">
                <div>
                    <h1 class="ott-platforms-card-heading">Cotton boll</h1>
                    <p class="ott-platforms-card-description">
                        small green triangular pods, called bolls, that mature after a period of
                        55–80 days. During this period the seeds and their
                        attached hairs develop within the boll, which increases considerably in size.
                    </p>
                </div>
                <img src="https://felixinstruments.com/app/uploads/2021/02/48948371081_b5df961833_k.jpg" class="ott-platforms-card-image" />
            </div>
            <div>
                <button class="btn btn-dark" onclick="display('sectionFoodOrder')">
                    <--back </button>
            </div>
        </div>

    </div>

    </div>

    <div id="sectionDetailedView0">
        <div class="detailed-view-bg-container">
            <button class="button1">
                <a href="https://amzn.eu/d/6C8B9tx" target="_blank">
                    link 1
                </a>
            </button>
            <button class="button1">
                <a href="https://amzn.eu/d/b97E3wp" target="_blank">
                    link 2
                </a>
            </button>
            <button class="button1">
                <a href="https://amzn.eu/d/876hB7r" target="_blank">
                    link 3
                </a>
            </button>
            <div class="detailed-view1-card-container">
                <div class="col-10 col-md-6  col-lg-4 col-xl-3 md-3">
                    <div class="embed-responsive embed-responsive-16by9">
                        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/8Smq6HANAGo" allowfullscreen></iframe>
                    </div>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Weed management</h1>
                    <p class="detailed-view-card-description">
                        Weed management is an important aspect of cotton production as
                        weeds can compete with the cotton plant for nutrients, water, and light, reducing yield and quality.
                    </p>
                </div>
                <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                    <--back </button>
            </div>
        </div>
    </div>
    <div id="sectionDetailedView1">
        <div class="detailed-view-bg-container">
            <button class="button1">
                <a href="https://amzn.eu/d/6C8B9tx" target="_blank">
                    link 1
                </a>
            </button>
            <button class="button1">
                <a href="https://amzn.eu/d/b97E3wp" target="_blank">
                    link 2
                </a>
            </button>
            <button class="button1">
                <a href="https://amzn.eu/d/876hB7r" target="_blank">
                    link 3
                </a>
            </button>
            <div class="detailed-view1-card-container">
                <div class="col-10 col-md-6  col-lg-4 col-xl-3 md-3">
                    <div class="embed-responsive embed-responsive-16by9">
                        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/8M46rWZCD-I" allowfullscreen></iframe>
                    </div>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Cotton leaves</h1>
                    <p class="detailed-view-card-description">
                        The leaves on cotton plants are simple, but they vary greatly from species
                        to species. Some are almost completely smooth, while others are hairy (with many trichomes). Most leaf blades are thin and papery,
                        but there are some that are thick and leathery
                    </p>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                <--back </button>
        </div>
    </div>
    <div id="sectionDetailedView2">
        <div class="detailed-view-bg-container">
            <button class="button1">
                <a href="https://amzn.eu/d/6C8B9tx" target="_blank">
                    link 1
                </a>
            </button>
            <button class="button1">
                <a href="https://amzn.eu/d/b97E3wp" target="_blank">
                    link 2
                </a>
            </button>
            <button class="button1">
                <a href="https://amzn.eu/d/876hB7r" target="_blank">
                    link 3
                </a>
            </button>
            <div class="detailed-view1-card-container">
                <div class="col-10 col-md-6  col-lg-4 col-xl-3 md-3">
                    <div class="embed-responsive embed-responsive-16by9">
                        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/nRKccd36n1U" allowfullscreen></iframe>
                    </div>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Cotton Flower</h1>
                    <p class="detailed-view-card-description">
                        .Cotton is a soft, fluffy staple fiber that grows in a boll, or protective case,
                        around the seeds of the cotton plants of the genus Gossypium in the mallow family Malvaceae. The fiber is almost pure cellulose,
                        and can contain minor percentages of waxes, fats, pectins, and water.
                    </p>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                <--back </button>
        </div>
    </div>
    <div id="sectionDetailedView3">
        <div class="detailed-view-bg-container">
            <button class="button1">
                <a href="https://amzn.eu/d/6C8B9tx" target="_blank">
                    link 1
                </a>
            </button>
            <button class="button1">
                <a href="https://amzn.eu/d/b97E3wp" target="_blank">
                    link 2
                </a>
            </button>
            <button class="button1">
                <a href="https://amzn.eu/d/876hB7r" target="_blank">
                    link 3
                </a>
            </button>
            <div class="detailed-view1-card-container">
                <div class="col-10 col-md-6  col-lg-4 col-xl-3 md-3">
                    <div class="embed-responsive embed-responsive-16by9">
                        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/qQchygxoi_o" allowfullscreen></iframe>
                    </div>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Cotton boll</h1>
                    <p class="detailed-view-card-description">
                        small green triangular pods, called bolls, that mature after a period
                        of 55–80 days. During this period the seeds and their attached hairs develop within
                        the boll, which increases considerably in size.
                    </p>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                <--back </button>
        </div>
    </div>
    <div id="info">

        <div id="sectionhome ">
            <div>
                <img src="https://kj1bcdn.b-cdn.net/media/29874/farm.jpeg?width=1200" class="img" />
                <div class="txt">
                    <h1 class="heading"> Detailed Information </h1>
                    <p class="para">Redefining the future of loT with LoRaWAN</p>
                    <button class="btn btn-primary" onclick="display('section1')">Know more</button>
                    <button class="btn btn-primary" onclick="display('section2')">Know more</button>
                    <button class="btn btn-primary" onclick="display('section3')">Know more</button>
                    <button class="btn btn-primary" onclick="display('section4')">Know more</button>
                </div>
            </div>
        </div>

        <div id="sectionhome1 ">
            <div class="main-image d-flex flex-column justify-content-end">
                <div class="image-card">
                    <P class="para">INFORMATION</P>
                    <h1 class="heading">Cotton leaves</h1>
                    <p class="para">.Early infections of leaves produce small, circular, brown to tan spots with
                        purple margins varying in size from 1 to 10 mm in diameter. These spots often show a concentric

                        growth that derives in concentric rings pattern, defined more clearly on the upper surface of leaves. As they grow, their center gradually becomes dry and turns grayish, occasionally cracking and falling out (shot-hole effect). These spots may also come together and produce irregular dead areas in the middle of the leaf blade. Under humid conditions, the fungi produce and release large amounts of spores, which may result in the sooty black appearance of the lesions. On stems, the development of lesions begins as small sunken spots which may later develop into cankers, splitting and cracking the tissue. Flowers buds may be shed in the case of severe infections, which eventually may
                        lead to the failure of boll development.</p>
                    <button class="click">
                        <a href="https://www.bighaat.com/blogs/kb/diseases-of-cotton-gossypium-hirsutum-and-management-strategies" target="_blank">
                            Read more
                        </a>
                    </button>
                    <button class="btn btn-primary" onclick="display('sectionDiwali')">
                        Back
                    </button>

                </div>

            </div>

        </div>
        <div id="sectionhome2 ">
            <div class="main-image1 d-flex flex-column justify-content-end">
                <div class="image-card">
                    <P class="para">INFORMATION</P>
                    <h1 class="heading">Cotton Flowers</h1>
                    <p class="para">
                        Early infections of leaves produce small, circular, brown to
                        tan spots with purple margins varying in size from 1 to 10 mm in diameter
                        . These spots often show a concentric growth that derives in concentric rings
                        pattern, defined more clearly on the upper surface of leaves. As they grow,
                        their center gradually becomes dry and turns grayish, occasionally cracking and
                        falling out (shot-hole effect). These spots may also come together and produce irregular dead areas in the middle of the leaf blade. Under humid conditions, the fungi produce and release large amounts of spores, which may result in the sooty black appearance of the lesions. On stems, the development of lesions begins as small sunken spots which may later develop into cankers, splitting and cracking the tissue. Flowers buds may be shed in the case of severe infections,
                        which eventually may lead to the failure of boll development.
                    </p>
                    <button class="click">
                        <a href="https://www.bighaat.com/blogs/kb/diseases-of-cotton-gossypium-hirsutum-and-management-strategies" target="_blank">
                            Read more
                        </a>
                    </button>
                    <button class="btn btn-primary" onclick="display('sectionDiwali')">
                        Back
                    </button>

                </div>

            </div>
        </div>
        <div id="sectionhome3">
            <div class="main-image2 d-flex flex-column justify-content-end">
                <div class="image-card">
                    <P class="para">INFORMATION</P>
                    <h1 class="heading">Cotton boll</h1>
                    <p class="para">
                        Boll rot is caused by a number of different species, mainly fungi but bacteria can play a part too. Bacteria themselves
                        cannot be seen by eyes but you can see the symptoms they cause. Symptoms of boll rot include the appearance of very
                        small light brown spots on bolls which then become dark brown or black and join together.
                        The boll rot first appears as wet spots which make bolls black. On the infected boll, fungi may develop. In severe
                        cases of attack, the bolls can drop from the plant. Infected bolls either do not open at all, or only partially open
                        . The cotton inside the infected bolls becomes yellow which lowers the price of the cotton in the market. This disease can lower the yield of the cotton crop by up to 20%.
                        We see the disease usually on young green bolls. Disease is more likely if the plant has had excess nitrogen and been watered too much.
                        Wet weather and high humidity both increase primary infection of the boll. The disease can also be spread by cotton bugs, which can transfer this disease from infected to healthy bolls by puncturing them with their mouth parts.
                        .</p>
                    <button class="click">
                        <a href="https://www.bighaat.com/blogs/kb/diseases-of-cotton-gossypium-hirsutum-and-management-strategies" target="_blank">
                            Read more
                        </a>
                    </button>
                    <button class="btn btn-primary" onclick="display('sectionDiwali')">
                        Back
                    </button>

                </div>

            </div>
        </div>
        <div id="sectionhome4">
            <div class="main-image3 d-flex flex-column justify-content-end">
                <div class="image-card">
                    <P class="para">INFORMATION</P>
                    <h1 class="heading">Weed prevention</h1>
                    <p class="para">Preventive methods include crop rotation, cover crops (when used as green manures or dead mulches), tillage systems, seed bed preparation, soil solarization, management of drainage and irrigation systems and of crop residues.

                        Cultural methods include crop sowing time and spatial arrangement, crop genotype choice, cover crops (when used as living mulches), intercropping, and crop fertilization.

                        Curative methods include any chemical, physical (e.g. mechanical and thermal) and biological methods used for direct weed control in an already established crop. A list of the main methods that can be used in an integrated weed management strategy.</p>
                    <button class="click">
                        <a href="https://www.bighaat.com/blogs/kb/diseases-of-cotton-gossypium-hirsutum-and-management-strategies" target="_blank">
                            Read more
                        </a>
                    </button>
                    <button class="btn btn-primary" onclick="display('sectionDiwali')">
                        Back
                    </button>

                </div>

            </div>
        </div>
        <div id="sectionhome5">
            <div class="main-image1 d-flex flex-column justify-content-end">
                <div class="image-card">
                    <P class="para">INFORMATION</P>
                    <h1 class="heading">Cotton Flowers</h1>
                    <p class="para">
                        .Early infections of leaves produce small, circular, brown to
                        tan spots with purple margins varying in size from 1 to 10 mm in diameter
                        . These spots often show a concentric growth that derives in concentric rings
                        pattern, defined more clearly on the upper surface of leaves. As they grow,
                        their center gradually becomes dry and turns grayish, occasionally cracking and
                        falling out (shot-hole effect). These spots may also come together and produce irregular dead areas in the middle of the leaf blade. Under humid conditions, the fungi produce and release large amounts of spores, which may result in the sooty black appearance of the lesions. On stems, the development of lesions begins as small sunken spots which may later develop into cankers, splitting and cracking the tissue. Flowers buds may be shed in the case of severe infections,
                        which eventually may lead to the failure of boll development.
                        .</p>
                    <button class="click">
                        <a href="https://www.bighaat.com/blogs/kb/diseases-of-cotton-gossypium-hirsutum-and-management-strategies" target="_blank">
                            Read more
                        </a>
                    </button>
                    <button class="btn btn-primary" onclick="display('sectionDiwali')">
                        Back
                    </button>

                </div>

            </div>
        </div>
    </div>


    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>

</html>
