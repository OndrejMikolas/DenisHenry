/* ---===### denishenry.cz - Author: info@janpikla.cz - Updated: 15. April 2018 - 23:01:21 ###===--- */
@charset "UTF-8";
/* ==================================================================
Zakladni styly
================================================================== */
/*

#main {
	background: transparent;
}

.header-info {
	border-bottom: 0;
}

#menu {
	margin-top: 5px;
}

#header-cart-wrapper #header-cart,
#header-cart {
    background-color: #D62235;
    color: #FFF !important;
}

#header-cart-wrapper .header-cart-count {
    color: #D62235;
}
#header-cart-wrapper .header-cart-count {
    background-position: -54px -31px;
}

#header-cart-wrapper .header-cart-count::before {
    color: #FFF;
}

#header-cart-wrapper .header-cart-price {
    color: #FFF;
}

#logo {
	background: url(https://www.denishenry.cz/user/icons/denishenry.png) no-repeat center center / contain;

	img {
		visibility: hidden;
	}
}

@media screen and (max-width: 1024px) {
	#header:after {
		top: 39px;
	}
}

@media screen and (max-width: 728px) {
	#header:after {
		top: 55px;
	}
}

@media screen and (max-width: 640px) {
	#header:after {
		top: 30px;
		height: 55px;
	}

	#menu {
		margin-top: 0;
	}

	#header-in .header-email {
		display: none;
	}

	#header-cart-wrapper {
		top: 0.85rem;
	}
}

@media screen and (max-width: 480px) {
	#logo img {
		width: 123px;
	}
}
*/
@media screen and (min-width: 992px) and (max-width: 1440px) {
  body:not(.in-denis-henry-chef-club) .jpArtText {
    position: relative;
    left: -147px;
  }
}

@media screen and (min-width: 768px) and (max-width: 991px) {
  body:not(.in-denis-henry-chef-club) .jpArtText {
    position: relative;
    left: -110px;
  }
}

#header {
  background: transparent;
  position: relative;
}

#header:after {
  content: "";
  width: 5000px;
  height: 85px;
  position: absolute;
  left: -1500px;
  background: #d5253a;
  top: 0;
  z-index: -1;
}

@media screen and (max-width: 768px) {
  #header:after {
    content: none;
  }
}

.header-top {
  padding-top: 9px;
}

.overall-wrapper {
  overflow: hidden;
}

#categories > .categories:not(.active) {
  display: none;
}

@media screen and (min-width: 768px) {
  .header-top .btn.cart-count::before {
    color: #fff;
  }
  .header-top .cart-count span {
    color: #fff;
  }
  .header-top .cart-count i {
    background: #fff;
    color: #f3283e;
  }
  .in-index .banners-footer {
    display: none;
  }
  .navigation-in {
    background: #656565;
  }
  .navigation-in > ul > li {
    border-left-color: #888;
  }
  /*#navigation {
		z-index: 9999999;
	}

	#header {
		z-index: 9999999;
	}

	.menu {
		transform: translate3d(0,0,0);
	}*/
  .jpFixed {
    z-index: 999999;
    position: fixed;
    top: 0;
    right: 0;
    margin: auto;
    left: 0;
    width: 100%;
    max-width: 1418px;
  }
}

@media screen and (max-width: 768px) {
  .banners-footer {
    flex-wrap: wrap;
  }
  .banner-footer {
    flex: 1 1 100%;
    margin-bottom: 8px;
  }
  .jpHomeBanner {
    display: block;
  }
  .jpHomeBanner > .banners-footer {
    padding: 0 !important;
  }
  #header .site-name {
    text-align: left;
    margin-top: -53px;
    width: 135px;
  }
  #header .site-name a {
    max-height: 40px;
    max-width: 135px;
    margin-left: -10px;
  }
  .header-top {
    padding-top: 0;
    width: 135px;
  }
  .header-top .search {
    width: 280px;
  }
  .responsive-tools > a::before, .btn.cart-count::before, a.btn.cart-count::before {
    color: #fff;
  }
  .header-top .btn.cart-count i {
    color: #d5253a;
    background: #fff;
  }
  .top-navigation-bar {
    background: #d5253a;
  }
  .responsive-tools > a[data-target="login"] {
    position: absolute;
    right: 105px;
  }
  .responsive-tools {
    height: 61px;
  }
  .responsive-tools > a[data-target="search"] {
    position: absolute;
    right: 140px;
  }
  #header {
    margin-bottom: 8px;
  }
  .navigation-in a, .menu-helper a {
    color: #444;
  }
}

#header .site-name a {
  background: url(https://www.denishenry.cz/user/icons/denishenry.png) no-repeat center center/contain;
}

#header .site-name a img {
  visibility: hidden;
}

.mcwidget-embed ._3L7815pw ._2VTUkLwb._133Zu3Ki, .jpArtText .mcwidget-embed > div > div > div {
  width: 190px !important;
}

.in-denis-henry-chef-club .sidebar-left {
  display: none;
}

.in-denis-henry-chef-club .content header {
  display: none;
}

.in-denis-henry-chef-club #content {
  padding: 0;
}

.in-denis-henry-chef-club .content-inner {
  width: 100%;
  max-width: 100%;
}

@media screen and (max-width: 640px) {
  .in-denis-henry-chef-club #content-wrapper {
    padding: 0;
  }
}

.in-denis-henry-chef-club .jpZwilling h3, .in-denis-henry-chef-club .jpZwilling h2, .in-denis-henry-chef-club .jpZwilling h4 {
  text-align: left;
}

.in-denis-henry-chef-club .jpZwilling .jpGrey {
  background: #efefef;
  padding: 20px;
}

.in-denis-henry-chef-club .jpZwilling .jpGrey h2 {
  margin-top: 0;
}

.in-denis-henry-chef-club .jpZwilling .jpGrey .jpInner {
  width: 450px;
  margin: auto;
}

@media screen and (min-width: 1200px) {
  .in-denis-henry-chef-club .jpZwilling .jpGrey .jpInner {
    margin-left: 52%;
    margin-top: 50px;
    margin-bottom: 70px;
  }
}

@media screen and (max-width: 500px) {
  .in-denis-henry-chef-club .jpZwilling .jpGrey .jpInner {
    width: 100%;
  }
}

@media screen and (min-width: 1200px) {
  .in-denis-henry-chef-club .jpZwilling .jpGrey.jpMcw .mcwidget-embed {
    position: relative;
    left: -130%;
    margin-top: -100px;
    top: -50px;
  }
}

@media screen and (max-width: 640px) {
  .in-denis-henry-chef-club .jpZwilling .jpGrey {
    padding-top: 40px;
    padding-bottom: 40px;
  }
}

.in-denis-henry-chef-club .jpZwilling .jpImage {
  padding: 20px;
  color: #fff;
}

.in-denis-henry-chef-club .jpZwilling .jpImage h2, .in-denis-henry-chef-club .jpZwilling .jpImage h4 {
  color: #fff;
}

.in-denis-henry-chef-club .jpZwilling .jpImage.img1 {
  background: url("https://www.denishenry.cz/user/documents/upload/ÄlĂĄnky/Chef & Club 1.jpg") no-repeat center;
}

.in-denis-henry-chef-club .jpZwilling .jpImage.img2 {
  background: url("https://www.denishenry.cz/user/documents/upload/ÄlĂĄnky/Chef & Club 2.jpg") no-repeat center;
}

@media screen and (min-width: 1200px) {
  .in-denis-henry-chef-club .jpZwilling .jpImage.img2 .jpSoc {
    position: relative;
    right: -125%;
    margin-top: -70px;
    top: -60px;
  }
}

.in-denis-henry-chef-club .jpZwilling .jpImage .jpInner {
  width: 450px;
  margin: auto;
}

@media screen and (min-width: 1200px) {
  .in-denis-henry-chef-club .jpZwilling .jpImage .jpInner {
    margin-left: 10%;
    margin-top: 50px;
    margin-bottom: 70px;
  }
}

@media screen and (max-width: 500px) {
  .in-denis-henry-chef-club .jpZwilling .jpImage .jpInner {
    width: 100%;
  }
}

.in-denis-henry-chef-club .jpZwilling .jpImage .jpSoc img {
  max-width: 50px;
  margin-right: 25px;
}

@media screen and (max-width: 640px) {
  .in-denis-henry-chef-club .jpZwilling .jpImage {
    padding-top: 40px;
    padding-bottom: 40px;
  }
}

aside {
  visibility: hidden;
}

aside.jpShown {
  visibility: visible !important;
}

aside.jpHidden {
  visibility: hidden !important;
}

@media screen and (max-width: 768px) {
  .top-navigation-bar {
    position: relative;
  }
  .top-navigation-bar:after {
    content: "";
    height: 4px;
    width: 100%;
    background: #fff;
    position: absolute;
    bottom: 0;
    left: 0;
  }
}

@media screen and (min-width: 768px) {
  #category-filter-hover {
    display: block !important;
    position: static !important;
    max-width: initial;
    max-height: initial;
    overflow: auto;
    transform: none;
  }
  .filter-section-button {
    display: none !important;
  }
}

@media screen and (min-width: 1440px) {
  #eapps-instagram-feed-1 {
    width: 1433px !important;
    margin-left: -322px;
  }
}

/*# sourceMappingURL=extend.css.map */
