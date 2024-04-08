<script>
/*import 
export default { 
}; */
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
        <div></div> <!--logo-->
        <div></div> <!--searchbar-->
        <div></div> <!--call to arms-->
        <div></div> <!--login menu-->
    </div>
    <!---MIDDLE SECTION-->

    <!--BOTTOM SECTION-->
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
}

#headerTop{
    border-bottom: 1px solid gray;
    height: 50px;
    text-align: center;
    line-height: 50px;
}

#headerMiddle{
    height: 105px;
}

#headerBottom{
    height: 75px;
    background-color: #292f47;
}
</style>