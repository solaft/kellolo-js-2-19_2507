<template>
<div>
    <header class="container px-0 my-4">
    <div class="row col-12 d-flex px-0 mx-0">

        <div class="logo d-flex justify-content-center px-0
                                    col-7
                                    col-xl-2 offset-xl-0
                                    col-lg-2 offset-lg-0
                                    col-md-3 offset-md-4
                                    col-sm-4 offset-sm-4">
            <a href="#" class="pr-2"><img src="../assets/imgs/logo.png" alt="logo"></a>
            <a href="#" class="pr-3 pr-xl-3 pr-lg-0 pr-md-2 pr-sm-2 brand">bran<span>d</span></a>
        </div>

        <div class="d-flex align-items-center
                                    col-12 pt-3
                                    col-xl-5 pl-xl-4 px-xl-0
                                    col-lg-5 pl-lg-5 pr-lg-0 px-lg-0 pt-lg-0
                                    col-md-7 px-md-0
                                    pt-sm-3 ">
            <div class="dropdown">
                <button class=" btn-lg btn btn-secondary dropdown-toggle" type="button" id="dropdownMenu2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    Browse
                </button>
                <div class="dropdown-menu" aria-labelledby="dropdownMenu2">
                    <div class="dropdown-item">woman</div>
                    <a href="#" class="dropdown-item" type="button">Dresses</a>
                    <a href="#" class="dropdown-item" type="button">Tops</a>
                    <a href="#" class="dropdown-item" type="button">Sweaters/Knits</a>
                    <a href="#" class="dropdown-item" type="button">Jackets/Coats</a>
                    <a href="#" class="dropdown-item" type="button">Blazers</a>
                    <a href="#" class="dropdown-item" type="button">Denim</a>
                    <a href="#" class="dropdown-item" type="button">Leggings/Pants</a>
                    <a href="#" class="dropdown-item" type="button">Skirts/Shorts</a>
                    <a href="#" class="dropdown-item" type="button">Accessories</a>

                    <div class="dropdown-item">men</div>
                    <a href="#" class="dropdown-item" type="button">Tees/Tank tops</a>
                    <a href="#" class="dropdown-item" type="button">Shirts/Polos</a>
                    <a href="#" class="dropdown-item" type="button">Sweaters</a>
                    <a href="#" class="dropdown-item" type="button">Sweatshirts/Hoodies</a>
                    <a href="#" class="dropdown-item" type="button">Blazers</a>
                    <a href="#" class="dropdown-item" type="button">Jackets/vests</a>
                </div>
            </div>
            <div class="input-group">
                <input type="text" class="form-control" placeholder="Search for Item..." aria-label="Recipient's username" aria-describedby="basic-addon2">
                <div class="input-group-append">
                    <button class="btn btn-outline-secondary" type="button"><i class="fas fa-search"></i></button>
                </div>
            </div>
        </div>

        <div class="row headerAccountAndCart d-none  align-items-center
                                    col-12 offset-0 px-0 pt-3 mx-auto justify-content-center
                                    col-xl-2 offset-xl-3 mt-xl-0
                                    col-lg-3 offset-lg-2 pt-lg-0
                                    col-md-3 offset-md-2 mt-md-0 mr-md-0 d-md-flex
                                    col-sm-4 offset-sm-4 pt-sm-3 justify-content-sm-end ">


            <div class="headerCart pr-4" >
               <label for="cart_checkbox" class="label_cart_checkbox"></label>
                <a href="#"><img src="../assets/imgs/cart.png" alt="headerCart"></a>
                <input type="checkbox" id="cart_checkbox">
                <div class="headerCartWrap">
                    <div class="headerCartWrapBlock"></div>
                    <div class="headerCartWrapInAll">
                        <div id="basket" class="d-flex flex-column"></div>
                    </div>
                </div>

            </div>


            <div class="dropdown">
                <button class="btn-lg btn btn-secondary dropdown-toggle" type="button" id="dropdownMenu2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    My Account
                </button>
                <div class="dropdown-menu" aria-labelledby="dropdownMenu2">
                    <button class="dropdown-item" type="button">Action</button>
                    <button class="dropdown-item" type="button">Another action</button>
                    <button class="dropdown-item" type="button">Something else here</button>
                </div>
            </div>
        </div>

    </div>

    <div class="row mx-0 d-md-none pt-3 justify-content-between">

        <div class="burgermenu justify-content-between align-items-center
                                col-2 pt-1
                                col-sm-6">
            <div class="dropdown">
                <button class="btn btn-secondary px-4 pt-2" type="button" id="dropdownMenu2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><i class="burgerMenu fas fa-bars"></i></button>
                <div class="dropdown-menu" aria-labelledby="dropdownMenu2">
                    <a href="#" class="dropdown-item" type="button">home</a>
                    <a href="#" class="dropdown-item" type="button">man</a>
                    <a href="#" class="dropdown-item" type="button">women</a>
                    <a href="#" class="dropdown-item" type="button">kids</a>
                    <a href="#" class="dropdown-item" type="button">accessories</a>
                    <a href="#" class="dropdown-item" type="button">featured</a>
                    <a href="#" class="dropdown-item" type="button">hot deals</a>
                </div>
            </div>
        </div>

        <div class="headerAccountAndCart d-flex align-items-center justify-content-end
                                col-2 pt-1
                                col-sm-6">
            <div class="headerCart pr-4" >
                <a href="#"><img src="../assets/imgs/cart.png" alt="headerCart"></a>
                <div class="headerCartWrap">
                    <div class="headerCartWrapBlock"></div>
                    <div class="headerCartWrapInAll">
                        <div class="d-flex headerCartWrapIn">
                            <a href="#" class="d-flex ">
                                <img src="../assets/imgs/myAccount1.jpg" alt="">
                                <div>
                                    <div>Rebox Zane</div>
                                    <span><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star-half-alt"></i></span>
                                    <div class="headerCartWrapPrice">1 <span>x</span> $250</div>
                                </div>
                            </a>
                            <a href="#"><i class="fas fa-times-circle"></i></a>
                        </div>

                        <div class="d-flex">
                            <a href="#" class="d-flex headerCartWrapIn">
                                <img src="../assets/imgs/myAccount2.jpg" alt="">
                                <div>
                                    <div>Rebox Zane</div>
                                    <span><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star-half-alt"></i></span>
                                    <div class="headerCartWrapPrice">1 <span>x</span> $250</div>
                                </div>
                            </a>
                            <a href="#"><i class="fas fa-times-circle"></i></a>
                        </div>

                        <div class="headerCartWrapTotalPrice">
                            <div>total</div>
                            <div>$500.00</div>
                        </div>

                        <button type="button" class="productsButtonIndex">Checkout</button>
                        <button type="button" class="productsButtonIndex">Go to cart</button>
                    </div>
                </div>

            </div>

            <div class="dropdown">
                <button class="btn-lg btn btn-secondary dropdown-toggle" type="button" id="dropdownMenu2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    My Account
                </button>
                <div class="dropdown-menu" aria-labelledby="dropdownMenu2">
                    <button class="dropdown-item" type="button">Action</button>
                    <button class="dropdown-item" type="button">Another action</button>
                    <button class="dropdown-item" type="button">Something else here</button>
                </div>
            </div>
        </div>

    </div>
</header>


<div class="headerLine"></div>


<nav class="nav container d-none d-md-flex justify-content-center mt-3">
    <div class="navAll">
        <a class="nav-link" href="index.html">Home</a>
        <div class="dropNav">
            <div class="dropNavIn">
                <div class="dropNavItem">woman</div>
                <a href="#" class="dropNavItem" type="button">Dresses</a>
                <a href="#" class="dropNavItem" type="button">Tops</a>
                <a href="#" class="dropNavItem" type="button">Sweaters/Knits</a>
                <a href="#" class="dropNavItem" type="button">Jackets/Coats</a>
                <a href="#" class="dropNavItem" type="button">Blazers</a>
                <a href="#" class="dropNavItem" type="button">Denim</a>
                <a href="#" class="dropNavItem" type="button">Leggings/Pants</a>
                <a href="#" class="dropNavItem" type="button">Skirts/Shorts</a>
                <a href="#" class="dropNavItem" type="button">Accessories</a>
            </div>
            <div class="dropNavIn">
                <div class="dropNavItem">woman</div>
                <a href="#" class="dropNavItem" type="button">Dresses</a>
                <a href="#" class="dropNavItem" type="button">Tops</a>
                <a href="#" class="dropNavItem" type="button">Sweaters/Knits</a>
                <a href="#" class="dropNavItem" type="button">Jackets/Coats</a>
                <a href="#" class="dropNavItem" type="button">Blazers</a>
                <div class="dropNavItem">woman</div>
                <a href="#" class="dropNavItem" type="button">Denim</a>
                <a href="#" class="dropNavItem" type="button">Leggings/Pants</a>
                <a href="#" class="dropNavItem" type="button">Skirts/Shorts</a>
            </div>
            <div class="dropNavIn">
                <div class="dropNavItem">woman</div>
                <a href="#" class="dropNavItem" type="button">Dresses</a>
                <a href="#" class="dropNavItem" type="button">Tops</a>
                <a href="#" class="dropNavItem" type="button">Sweaters/Knits</a>
                <a href="#" class="dropNavItem" type="button">Jackets/Coats</a>
                <a href="">
                    <div>Super sale!</div>
                    <img src="../assets/imgs/navDrop.jpg" alt="nav img">
                </a>
            </div>
        </div>
    </div>

    <a class="nav-link" href="#">Man</a>
    <a class="nav-link" href="#">Women</a>
    <a class="nav-link" href="#">Kids</a>
    <a class="nav-link" href="#">Accoseriese</a>
    <a class="nav-link" href="#">Featured</a>
    <a class="nav-link" href="#">Hot Deals</a>
</nav>


<div class="newArrivalsBg pb-5 pt-5">
    <div class="px-md-0 container d-flex flex-column flex-sm-row justify-content-between align-items-center ">
        <div class="newArrivals">New Arrivals</div>
        <div class="newArrivalsPath mt-4 mt-sm-0">
            <a href="#">home</a>
            <a href="#">men</a>
            <a href="#">new arrivals</a>
        </div>
    </div>
</div>
<!-------------------------------HEADER END----------------------------->
<main>

    <details class="container mt-5 border-bottom pb-4">
        <summary class="checkoutSummary d-flex justify-content-center
                        d-lg-flex justify-content-lg-start
                        d-md-flex justify-content-md-center
                        d-sm-flex justify-content-sm-center">
            01. <span>Shipping Adress</span>
        </summary>
        <div class="row container pl-5">

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-4
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-4">
                <div class="detailsTitle">Check as a guest or register</div>

                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>

                <div class="detailsRadio form-check pt-3">
                    <input type="radio" class="form-check-input with-gap" id="radioGap1" name="groupOfRadioGap">
                    <label class="form-check-label pl-1" for="radioGap1">checkout as guest</label>
                </div>

                <div class="detailsRadio pt-2 form-check">
                        <input type="radio" class="form-check-input with-gap detailsRegisterWrapRadio" id="radioGap2" name="groupOfRadioGap" checked>
                        <label class="form-check-label pl-1" for="radioGap2">register</label>
                </div>

                <div class="detailsTitle pt-3">register and save time!</div>
                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>
                <div class="detailsTitleBottom pt-3"><i class="fas fa-angle-double-right"></i> Fast and easy checkout</div>
                <div class="detailsTitleBottom pt-1"><i class="fas fa-angle-double-right"></i> Easy access to your order history and status</div>

                <div class="detailsButton row-cols-3 pt-4">
                    <button type="button" class="col btn btn-outline-secondary">Continue</button>
                </div>
            </div>

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-5
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-5">
                <div class="detailsTitle">Already registed?</div>

                <div class="detailsTitleBottom pt-1">Please log in below</div>

                <form class="pt-3">
                    <div class="form-group">
                        <label for="exampleInputEmail1">Email address<span> *</span></label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" required>
                    </div>
                    <div class="form-group">
                        <label for="exampleInputPassword1">Password<span> *</span></label>
                        <input type="password" class="form-control" id="exampleInputPassword1" required>
                    </div>
                    <div class="requiredText">* Required Fileds</div>
                    <div class="detailsButton row-cols-3 pt-4 d-flex align-items-center">
                        <button type="button" class="col btn btn-outline-secondary">log in</button>
                        <div class="col">Forgot Password ?</div>
                    </div>
                </form>
            </div>
        </div>
    </details>

    <details class="container mt-5 border-bottom pb-4">
        <summary class="checkoutSummary d-flex justify-content-center
                        d-lg-flex justify-content-lg-start
                        d-md-flex justify-content-md-center
                        d-sm-flex justify-content-sm-center">
            02. <span>BILLING INFORMATION</span>
        </summary>
        <div class="row container pl-5">

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-5
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-5">
                <div class="detailsTitle">Check as a guest or register</div>

                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>

                <div class="detailsRadio form-check pt-3">
                    <input type="radio" class="form-check-input with-gap" id="radioGap1" name="groupOfRadioGap">
                    <label class="form-check-label pl-1" for="radioGap1">checkout as guest</label>
                </div>

                <div class="detailsRadio pt-2 form-check">
                    <input type="radio" class="form-check-input with-gap detailsRegisterWrapRadio" id="radioGap2" name="groupOfRadioGap" checked>
                    <label class="form-check-label pl-1" for="radioGap2">register</label>
                </div>

                <div class="detailsTitle pt-3">register and save time!</div>
                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>
                <div class="detailsTitleBottom pt-3"><i class="fas fa-angle-double-right"></i> Fast and easy checkout</div>
                <div class="detailsTitleBottom pt-1"><i class="fas fa-angle-double-right"></i> Easy access to your order history and status</div>

                <div class="detailsButton row-cols-3 pt-4">
                    <button type="button" class="col btn btn-outline-secondary">Continue</button>
                </div>
            </div>

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-5
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-5">
                <div class="detailsTitle">Already registed?</div>

                <div class="detailsTitleBottom pt-1">Please log in below</div>

                <form class="pt-3">
                    <div class="form-group">
                        <label for="exampleInputEmail1">Email address<span> *</span></label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" required>
                    </div>
                    <div class="form-group">
                        <label for="exampleInputPassword1">Password<span> *</span></label>
                        <input type="password" class="form-control" id="exampleInputPassword1" required>
                    </div>
                    <div class="requiredText">* Required Fileds</div>
                    <div class="detailsButton row-cols-3 pt-4 d-flex align-items-center">
                        <button type="button" class="col btn btn-outline-secondary">log in</button>
                        <div class="col">Forgot Password ?</div>
                    </div>
                </form>
            </div>
        </div>
    </details>

    <details class="container mt-5 border-bottom pb-4">
        <summary class="checkoutSummary d-flex justify-content-center
                        d-lg-flex justify-content-lg-start
                        d-md-flex justify-content-md-center
                        d-sm-flex justify-content-sm-center">
            03. <span>SHIPPING INFORMATION</span>
        </summary>
        <div class="row container pl-5">

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-5
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-5">
                <div class="detailsTitle">Check as a guest or register</div>

                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>

                <div class="detailsRadio form-check pt-3">
                    <input type="radio" class="form-check-input with-gap" id="radioGap1" name="groupOfRadioGap">
                    <label class="form-check-label pl-1" for="radioGap1">checkout as guest</label>
                </div>

                <div class="detailsRadio pt-2 form-check">
                    <input type="radio" class="form-check-input with-gap detailsRegisterWrapRadio" id="radioGap2" name="groupOfRadioGap" checked>
                    <label class="form-check-label pl-1" for="radioGap2">register</label>
                </div>

                <div class="detailsTitle pt-3">register and save time!</div>
                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>
                <div class="detailsTitleBottom pt-3"><i class="fas fa-angle-double-right"></i> Fast and easy checkout</div>
                <div class="detailsTitleBottom pt-1"><i class="fas fa-angle-double-right"></i> Easy access to your order history and status</div>

                <div class="detailsButton row-cols-3 pt-4">
                    <button type="button" class="col btn btn-outline-secondary">Continue</button>
                </div>
            </div>

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-5
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-5">
                <div class="detailsTitle">Already registed?</div>

                <div class="detailsTitleBottom pt-1">Please log in below</div>

                <form class="pt-3">
                    <div class="form-group">
                        <label for="exampleInputEmail1">Email address<span> *</span></label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" required>
                    </div>
                    <div class="form-group">
                        <label for="exampleInputPassword1">Password<span> *</span></label>
                        <input type="password" class="form-control" id="exampleInputPassword1" required>
                    </div>
                    <div class="requiredText">* Required Fileds</div>
                    <div class="detailsButton row-cols-3 pt-4 d-flex align-items-center">
                        <button type="button" class="col btn btn-outline-secondary">log in</button>
                        <div class="col">Forgot Password ?</div>
                    </div>
                </form>
            </div>
        </div>
    </details>

    <details class="container mt-5 border-bottom pb-4">
        <summary class="checkoutSummary d-flex justify-content-center
                        d-lg-flex justify-content-lg-start
                        d-md-flex justify-content-md-center
                        d-sm-flex justify-content-sm-center">
            04. <span>SHIPPING METHOD</span>
        </summary>
        <div class="row container pl-5">

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-5
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-5">
                <div class="detailsTitle">Check as a guest or register</div>

                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>

                <div class="detailsRadio form-check pt-3">
                    <input type="radio" class="form-check-input with-gap" id="radioGap1" name="groupOfRadioGap">
                    <label class="form-check-label pl-1" for="radioGap1">checkout as guest</label>
                </div>

                <div class="detailsRadio pt-2 form-check">
                    <input type="radio" class="form-check-input with-gap detailsRegisterWrapRadio" id="radioGap2" name="groupOfRadioGap" checked>
                    <label class="form-check-label pl-1" for="radioGap2">register</label>
                </div>

                <div class="detailsTitle pt-3">register and save time!</div>
                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>
                <div class="detailsTitleBottom pt-3"><i class="fas fa-angle-double-right"></i> Fast and easy checkout</div>
                <div class="detailsTitleBottom pt-1"><i class="fas fa-angle-double-right"></i> Easy access to your order history and status</div>

                <div class="detailsButton row-cols-3 pt-4">
                    <button type="button" class="col btn btn-outline-secondary">Continue</button>
                </div>
            </div>

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-5
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-5">
                <div class="detailsTitle">Already registed?</div>

                <div class="detailsTitleBottom pt-1">Please log in below</div>

                <form class="pt-3">
                    <div class="form-group">
                        <label for="exampleInputEmail1">Email address<span> *</span></label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" required>
                    </div>
                    <div class="form-group">
                        <label for="exampleInputPassword1">Password<span> *</span></label>
                        <input type="password" class="form-control" id="exampleInputPassword1" required>
                    </div>
                    <div class="requiredText">* Required Fileds</div>
                    <div class="detailsButton row-cols-3 pt-4 d-flex align-items-center">
                        <button type="button" class="col btn btn-outline-secondary">log in</button>
                        <div class="col">Forgot Password ?</div>
                    </div>
                </form>
            </div>
        </div>
    </details>

    <details class=" container mt-5 border-bottom pb-4">
        <summary class="checkoutSummary d-flex justify-content-center
                        d-lg-flex justify-content-lg-start
                        d-md-flex justify-content-md-center
                        d-sm-flex justify-content-sm-center">
            05. <span>PAYMENT METHOD</span>
        </summary>
        <div class="row container pl-5">

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-5
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-5">
                <div class="detailsTitle">Check as a guest or register</div>

                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>

                <div class="detailsRadio form-check pt-3">
                    <input type="radio" class="form-check-input with-gap" id="radioGap1" name="groupOfRadioGap">
                    <label class="form-check-label pl-1" for="radioGap1">checkout as guest</label>
                </div>

                <div class="detailsRadio pt-2 form-check">
                    <input type="radio" class="form-check-input with-gap detailsRegisterWrapRadio" id="radioGap2" name="groupOfRadioGap" checked>
                    <label class="form-check-label pl-1" for="radioGap2">register</label>
                </div>

                <div class="detailsTitle pt-3">register and save time!</div>
                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>
                <div class="detailsTitleBottom pt-3"><i class="fas fa-angle-double-right"></i> Fast and easy checkout</div>
                <div class="detailsTitleBottom pt-1"><i class="fas fa-angle-double-right"></i> Easy access to your order history and status</div>

                <div class="detailsButton row-cols-3 pt-4">
                    <button type="button" class="col btn btn-outline-secondary">Continue</button>
                </div>
            </div>

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-5
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-5">
                <div class="detailsTitle">Already registed?</div>

                <div class="detailsTitleBottom pt-1">Please log in below</div>

                <form class="pt-3">
                    <div class="form-group">
                        <label for="exampleInputEmail1">Email address<span> *</span></label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" required>
                    </div>
                    <div class="form-group">
                        <label for="exampleInputPassword1">Password<span> *</span></label>
                        <input type="password" class="form-control" id="exampleInputPassword1" required>
                    </div>
                    <div class="requiredText">* Required Fileds</div>
                    <div class="detailsButton row-cols-3 pt-4 d-flex align-items-center">
                        <button type="button" class="col btn btn-outline-secondary">log in</button>
                        <div class="col">Forgot Password ?</div>
                    </div>
                </form>
            </div>
        </div>
    </details>

    <details class=" container mt-5 border-bottom pb-4">
        <summary class="checkoutSummary d-flex justify-content-center
                        d-lg-flex justify-content-lg-start
                        d-md-flex justify-content-md-center
                        d-sm-flex justify-content-sm-center">
            06. <span>ORDER REVIEW</span>
        </summary>
        <div class="row container pl-5">

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-5
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-5">
                <div class="detailsTitle">Check as a guest or register</div>

                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>

                <div class="detailsRadio form-check pt-3">
                    <input type="radio" class="form-check-input with-gap" id="radioGap1" name="groupOfRadioGap">
                    <label class="form-check-label pl-1" for="radioGap1">checkout as guest</label>
                </div>

                <div class="detailsRadio pt-2 form-check">
                    <input type="radio" class="form-check-input with-gap detailsRegisterWrapRadio" id="radioGap2" name="groupOfRadioGap" checked>
                    <label class="form-check-label pl-1" for="radioGap2">register</label>
                </div>

                <div class="detailsTitle pt-3">register and save time!</div>
                <div class="detailsTitleBottom pt-1">Register with us for future convenience</div>
                <div class="detailsTitleBottom pt-3"><i class="fas fa-angle-double-right"></i> Fast and easy checkout</div>
                <div class="detailsTitleBottom pt-1"><i class="fas fa-angle-double-right"></i> Easy access to your order history and status</div>

                <div class="detailsButton row-cols-3 pt-4">
                    <button type="button" class="col btn btn-outline-secondary">Continue</button>
                </div>
            </div>

            <div class="col-lg-6 offset-lg-0 px-lg-0 pt-lg-4
                        col-md-6 offset-md-4 px-md-0 pt-md-5
                        col-sm-6 offset-sm-3 px-sm-0 pt-sm-5">
                <div class="detailsTitle">Already registed?</div>

                <div class="detailsTitleBottom pt-1">Please log in below</div>

                <form class="pt-3">
                    <div class="form-group">
                        <label for="exampleInputEmail1">Email address<span> *</span></label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" required>
                    </div>
                    <div class="form-group">
                        <label for="exampleInputPassword1">Password<span> *</span></label>
                        <input type="password" class="form-control" id="exampleInputPassword1" required>
                    </div>
                    <div class="requiredText">* Required Fileds</div>
                    <div class="detailsButton row-cols-3 pt-4 d-flex align-items-center">
                        <button type="button" class="col btn btn-outline-secondary">log in</button>
                        <div class="col">Forgot Password ?</div>
                    </div>
                </form>
            </div>
        </div>
    </details>

</main>
<!-------------------------------FOOTER ST----------------------------->
<!-------------------------------SUBSCRIBE ST----------------------------->

<div class="subscribeBg mt-5 pt-5 pb-5">
    <div class="container">
        <div class="row pb-5 pt-0 pt-lg-5">

            <div class="d-flex col-lg-6 px-0 mt-5 mb-5 pr-0 pr-lg-5">
                <div class="col-2 col-md-2 d-flex align-self-start">
                    <img src="../assets/imgs/Avatar.png" alt="Avatar">
                </div>
                <div class="col-10 pl-5 pl-md-2 pl-lg-5">
                    <blockquote class="reviewsTextMassage ">
                        “Vestibulum quis porttitor dui! Quisque viverra nunc mi,
                        a pulvinar purus condimentum a. Aliquam condimentum mattis neque sed pretium”
                    </blockquote>
                    <div class="reviewsTextName mt-3">
                        Bin Burhan
                    </div>
                    <div class="reviewsTextFrom">
                        Dhaka, Bd
                    </div>
                    <div class="reviewsTextSwitch  mt-5 px-0
                                col-5
                                col-xl-4
                                col-lg-5
                                col-md-3
                                col-sm-4">
                        <div></div>
                        <div></div>
                        <div></div>
                    </div>
                </div>
            </div>

            <div class="subscribeEmail d-flex justify-content-center flex-column align-items-center col-lg-6 border-left ">
                <div class="subscribeEmailHead">
                    Subscribe
                </div>
                <div class="subscribeEmailText pb-4">
                    FOR OUR NEWLETTER AND PROMOTION
                </div>
                <form class="subscribeForm input-group mb-3 pl-1 pl-sm-4">
                    <input type="email" class="form-control pt-4 pb-4
                                                ml-xl-5
                                                col-lg-7 offset-lg-0 ml-lg-4
                                                col-md-6 offset-md-2
                                                col-sm-9 offset-sm-0" placeholder="Enter Your Email" aria-label="Enter Your Email" aria-describedby="basic-addon2">
                    <div class="input-group-append">
                        <button class="btn btn-outline-secondary" type="button">Subscribe</button>
                    </div>
                </form>
            </div>

        </div>
    </div>
</div>

<!-------------------------------SUBSCRIBE END----------------------------->
<footer class="container">
    <div class="row col-12 px-0 my-5 no-gutters">

        <div class="col-12 px-0
                    col-lg-6">
            <div class="logo d-flex justify-content-center pb-3 justify-content-lg-start">
                <a href="#" class="pr-2"><img src="../assets/imgs/logo.png" alt="logo"></a>
                <a href="#" class="pr-3 pr-xl-3 pr-lg-0 pr-md-2 pr-sm-2 brand">bran<span>d</span></a>
            </div>


            <div class="d-flex flex-column flex-sm-row px-5 px-sm-0 flex-lg-column">
                <div class="footerBrandText pb-4 pr-sm-3">
                    Objectively transition extensive data rather than cross functional solutions. Monotonectally syndicate
                    multidisciplinary materials before go forward benefits. Intrinsicly syndicate an expanded array of
                    processes and cross-unit partnerships.
                </div>
                <div class="footerBrandText pb-4">
                    Efficiently plagiarize 24/365 action items and focused infomediaries.
                    Distinctively seize superior initiatives for wireless technologies. Dynamically optimize.
                </div>
            </div>


        </div>
        <div class="bottomNav d-none justify-content-between flex-wrap
                    col-lg-6 pl-lg-4 pt-3
                    justify-content-md-between
                    pl-sm-0 d-sm-flex">
            <div class="footerColumn">
                <h2>COMPANY</h2>
                <a href="#">Home</a>
                <a href="#">Shop</a>
                <a href="#">About</a>
                <a href="#">How It Works</a>
                <a href="#">Contact</a>
            </div>
            <div class="footerColumn">
                <h2>INFORMATION</h2>
                <a href="#">Tearms&amp;Condition</a>
                <a href="#">Privacy Policy</a>
                <a href="#">How to Buy</a>
                <a href="#">How to Sell</a>
                <a href="#">Promotion</a>
            </div>
            <div class="footerColumn pt-5 pt-sm-0">
                <h2>SHOP CATEGORY</h2>
                <a href="#">Men</a>
                <a href="#">Women</a>
                <a href="#">Child</a>
                <a href="#">Apparel</a>
                <a href="#">Browse All</a>
            </div>
        </div>

        <div class="bottomNavXS col-12 d-flex flex-column d-sm-none">
            <h2 class="d-flex justify-content-around">COMPANY</h2>
            <div class="footerColumn d-flex justify-content-around px-5">
                <a href="#">Home</a>
                <a href="#">Shop</a>
                <a href="#">About</a>
                <a href="#">How It Works</a>
                <a href="#">Contact</a>
            </div>
            <h2 class="d-flex justify-content-around pt-5">INFORMATION</h2>
            <div class="footerColumn d-flex justify-content-around px-5 ">
                <a href="#">Tearms&amp;Condition</a>
                <a href="#">Privacy Policy</a>
                <a href="#">How to Buy</a>
                <a href="#">How to Sell</a>
                <a href="#">Promotion</a>
            </div>

            <h2 class="d-flex justify-content-around pt-5">SHOP CATEGORY</h2>
            <div class="footerColumn d-flex justify-content-around px-5 pt-sm-0">
                <a href="#">Men</a>
                <a href="#">Women</a>
                <a href="#">Child</a>
                <a href="#">Apparel</a>
                <a href="#">Browse All</a>
            </div>
        </div>

    </div>
</footer>

<div class="BgCopyrights">
    <div class="container">
        <div class="copyrights d-flex py-4
                    justify-content-around flex-column align-items-center
                    flex-sm-row justify-content-sm-between">
            <div>&copy; 2020  Brand  All Rights Reserved.</div>
            <div class="copyrightsIcons pt-3 pt-sm-0">
                <a class="facebookIcon"><i class="fab fa-facebook-f"></i></a>
                <a class="twitterIcon"><i class="fab fa-twitter"></i></a>
                <a class="linkedinIcon"><i class="fab fa-linkedin-in"></i></a>
                <a class="pinterestIcon"><i class="fab fa-pinterest-p"></i></a>
                <a class="googleIcon"><i class="fab fa-google-plus-g"></i></a>
            </div>
        </div>
    </div>
</div>
</div>
</template>