<script>
    import Logo from '../../figmaAssets/Logos/NSTR_White_Logo.svg'
</script>

<div id="footer">
    <div id="footerContainer">
        <div id="footerDesc" class="footerEntry">
            <img src={Logo} alt="NusantaraLogo">
            <p id="footerDescText">
                Nusantara Pathway merupakan program pendidikan 
                menengah yang dirancang untuk memberikan jalur 
                akademik yang terstruktur bagi siswa Indonesia 
                yang berorientasi pada pendidikan tinggi internasional.
            </p>
        </div>
        <div class="footerEntry">footer 2</div>
        <div class="footerEntry">footer 3</div>
        
    </div>
    
</div>

<style>
    #footer {
        width: 100%;
        background: black;
        color: white;
        padding: 20px 10px;

        display: flex;
        justify-content: center;
    }

    #footerContainer {
        width: 90%;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
    }

    #footerDesc {
        display: flex;
        flex-direction: column;
        gap: 15px;
    }

    #footerDescText {
        width: 90%;
    }

    .footerEntry {
        width: 100%;
        /* border: 1px solid red; */
    }

    img {
        width: 70%;
    }

    p {
        font-weight: 100;
    }
</style>