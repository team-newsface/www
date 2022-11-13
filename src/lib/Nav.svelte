<script>
    import Logo from "../assets/newsface_logo.png";
</script>

<div class="nav_bar">
    <img class="nav_Logo_Img" src={Logo} alt="" />
    <p class="text_Logo">NEWSFACE</p>
</div>

<style>
    .nav_bar {
        width: 100%;
        height: 60px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
        backdrop-filter: blur(28px);
        -webkit-backdrop-filter: blur(28px);
        border-radius: 10px;
        position: sticky;
        padding-top: 18px;
        top: -18px;
    }
    .nav_Logo_Img {
        height: 78%;
        margin-right: 1%;
        margin-left: 1%;
    }
    .text_Logo {
        font-size: 24px;
        font-family: PyeongChangPeace-Bold;
    }
</style>
