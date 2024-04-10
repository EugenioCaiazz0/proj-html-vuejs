<script>
export default {}
</script>

<template>
<header>

    <!--TOP SECTION-->
    <div class="container d-flex justify-content-between" id="headerTop">
        <div> <!--selettore lingua-->
            <p> English <i class="fa-solid fa-arrow-down"></i></p>
        </div> 
        <div>
            <ul> <!--nav 1-->
                <li>Home</li>
                <li>Pages</li>
                <li>Course Formats</li>
                <li>Courses</li>
                <li>Demos</li>
            </ul>
            <ul> <!--nav 2-->
                <li><i class="fa-brands fa-facebook"></i></li>
                <li><i class="fa-brands fa-twitter"></i></li>
                <li><i class="fa-brands fa-instagram"></i></li>
                <li><i class="fa-brands fa-linkedin"></i></li>
                <li><i class="fa-brands fa-google-plus-g"></i></li>
                <li><i class="fa-brands fa-youtube"></i></li>
            </ul>
        </div>
    </div>
    <!--TOP SECTION-->

    <!--MIDDLE SECTION-->
    <div class="container d-flex" id="headerMiddle">
        <div class="d-flex flex-row">
            <img src="proj-html-vuejs/src/assets/images/footer-logo2x-50x56.png" alt="MASTER STUDY">
            <h2 style="line-height: inherit;">
                <span style="color:#292f47; font-weight: bolder;">MASTER</span>
                <span style="color: #292f47; font-weight: lighter;">STUDY</span>
            </h2>
        </div> <!--logo-->
        <div class="d-flex">
            <p> <i class="fa-solid fa-bars"></i> CATEGORY</p>
            <div class="input-group">
                <input type="text" class="form-control" placeholder="Search courses" aria-label="" aria-describedby="">
                <button class="btn btn-outline-secondary" type="button" style="color: #334453;" ><i class="fa-solid fa-magnifying-glass"></i></button>
            </div>
        </div> <!--searchbar-->
        <div class="d-flex justify-content-between" >
            <div> <!--call to arms-->
                <p> <i class="fa-solid fa-bullhorn"></i> Become an instructor</p>
                <p> <i class="fa-solid fa-briefcase"></i> For enterprise</p>
            </div>
            <div class="d-flex"><!--login menu-->
                <p><i class="fa-regular fa-user"></i> Log In</p>
                <!--SIGN UP BUTTON !!!!-->
                <p><i class="fa-regular fa-bookmark"></i></p>
            </div>
        </div> 
    </div>
    <!---MIDDLE SECTION-->

    <!--BOTTOM SECTION-->
    <div class="container d-flex justify-content-around" id="headerBottom">
        <span><i class="fa-solid fa-chart-simple"></i> Business</span>
        <span><i class="fa-solid fa-palette"></i> Design</span>
        <span><i class="fa-solid fa-gear"></i> Development</span>
        <span><i class="fa-regular fa-face-smile"></i> Lifestyle</span>
        <span><i class="fa-solid fa-folder-open"></i> Office Productivity</span>
    </div>
    <!--BOTTOM SECTION-->

</header>
</template>

<style lang="scss" scoped>

header{
    color: gray;
}

header ul {
    display: flex;
    flex-direction: column;
    text-align: center;
}

header ul li{
    margin-left: 5px;
    margin-right: 5px;
}

#headerTop{
    border-bottom: 1px solid gray;
    height: 50px;
    line-height: 50px;
}

#headerMiddle{
    height: 105px;
    line-height: 105px;
}

#headerBottom{
    height: 75px;
    background-color: #292f47;
    color: white;
    line-height: 75px;
}
</style>