<template>
    <div class="container">
        <div class="content">
            <div class="footercontent">
                <img src="../assets/TEDxCUHKemblem.png" height="100px"><br>
                This independent TEDx event is operated under license from <a href="https://www.ted.com" target="_blank" rel="noreferrer">TED</a>.
            </div>

            <div class="subscribe-wrapper">
                <button id="button">
                    SUBSCRIBE TO OUR NEWSLETTER
                </button>
            </div>

            <div class="socialmedia">

                <span id="hash">#tedxcuhk</span> 
                <br>

                <a target="_blank" href="https://www.facebook.com/TEDxCUHK/" rel="noreferrer"><img alt="facebook icon" src="../assets/f_logo.png"></a> 
                <a target="_blank" href="https://www.instagram.com/tedxcuhk/" rel="noreferrer"><img alt="Instagram icon" src="../assets/ig.png" style="height: 28px;"></a> 
                <a target="_blank" href="https://www.youtube.com/user/TEDxTalks" rel="noreferrer"><img alt="Instagram icon" src="../assets/YouTubeIcon.png" style="height: 25px; padding-bottom: 2px;"></a> 

                <br>
                <span style="padding: 10px 10px 0 10px;"><router-link to="PrivPolicy">Privacy Policy</router-link></span> | 
                <span style="padding: 10px 0 0 10px;"><a target="_blank" href="mailto:tedxcuhkteam@gmail.com">Mail</a></span> <!-- Don't judge me again -->
            </div>
            
        </div>
        
        <br>
        <hr style="border-color: gray;">

        <div class="copyright"> 
            Copyright © TEDxCUHK 2020. All rights reserved.
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
#button:hover {
    color: #e62b1e;
    background-color: transparent;
    transition: ease-in-out 0.17s;
}
#button {
    transition: ease-in-out 0.17s;
    color: white;
    border: None;
    position: relative;
    top: 26%;
    background-color: #e62b1e;
    border: 5px solid #e62b1e;
    padding: 17px;
    font-weight: bolder;
    font-size: 13px;
    cursor: pointer;
}
.subscribe-wrapper {
    text-align: center;
}
#hash {
    font-weight: bolder;
    font-size: 35px;
}
.container {
    min-height: 200px;
    background-color: #303133;
    color: white !important;
}
.content {
    display: grid;
    grid-template-columns: 33% 34% 33%;
    padding-top: 30px;
    margin: 0 17% 0 17%;
}
.copyright {
    display: block; 
    padding: 20px 0 25px 0; 
    font-size: 13px; 
    text-align: center;
}
.footercontent {
    font-size: 13px;
    margin: 0 17% 0 17%;
}
.footercontent a {
    text-decoration: None;
    color: white;
}
.footercontent a:hover {
    color: #e62b1e;
    font-weight: bolder;
}
.socialmedia {
    font-size: 15px;
    text-align: right;
    padding-top: 10px;
}
.socialmedia img {
    height: 30px;
}
.socialmedia a {
    text-decoration: None;
    color: white;
    cursor: pointer;
    padding: 10px;
}
.socialmedia a:hover {
    color: #e62b1e;
}
</style>