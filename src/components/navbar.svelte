<script>
    import NusantaraPLogo from '../figmaAssets/Logos/NSTR_Outlined_Logo.svg'
</script>

<div id="navbarSpace">

</div>
<div id="navbar">
    <img class="navbarItems" id="NusantaraLogo" src={NusantaraPLogo} alt="nusantar pathway">
    <div class="navbarItems" id="links">
        <a href="./">Home</a>
        <a href="./#about">About</a>
        <a href="./#roadmapBody">Roadmap</a>
        <a href="./#approach">Approach</a>
    </div>
</div>

<style>
    * { 
        padding: 0;
        margin: 0;
    }

    #navbarSpace {
        height: 58px;
    }

    #navbar {
        background-color: #F0F0F0;
        display: flex;
        position: fixed;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
        width: 100%;
        height: 58px;
        padding: 10px 2.5% 10px 2.5%;
        margin: 0;

        box-sizing: border-box;
    }

    .navbarItems {
        height: 100%;
    }

    #links {
        display: flex;
        flex-direction: row;
        gap: 20px;
        height: 100%;
        justify-content: space-between;

    }

    a {
        text-decoration: none;
        color: black;
        display: flex;
        justify-content: center;
        align-items: center;

        scale: 1.1;
    }

</style>