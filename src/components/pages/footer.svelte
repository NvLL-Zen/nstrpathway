<script>
	import Logo from '../../figmaAssets/Logos/NSTR_White_Logo.svg';
	import WaLogo from '../../figmaAssets/Logos/watrs.png';
	import EmailLogo from '../../figmaAssets/Logos/email.png';
	import WALink from '../../figmaAssets/Logos/WA.svg';
</script>

<div id="footer">
	<div id="footerContainer">
		<div id="footerDesc" class="footerEntry">
			<img src={Logo} alt="NusantaraLogo" />
			<p id="footerDescText">
				Nusantara Pathway merupakan program pendidikan menengah yang dirancang untuk memberikan
				jalur akademik yang terstruktur bagi siswa Indonesia yang berorientasi pada pendidikan
				tinggi internasional.
			</p>
		</div>
		<div class="footerEntry">
			<div class="footerInput">
				<h2 id="footerInputDesc">Tertarik dengan Nusantara Pathway?</h2>
				<a target="_blank" href="https://wa.me/62859106710339" class="whatsapp">
					<img src={WALink} id="linkWA" alt="Link WA" />
				</a>
			</div>
		</div>
		<div class="footerEntry">
			<h2>Follow us</h2>
			<a id="linkIG" target="_blank" href="https://www.instagram.com/nusantara_pathway/">
				<h3>@nusantara_pathway</h3></a
			>
		</div>
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
		height: 100%;
		box-sizing: border-box;
		/* border: 1px solid red; */
	}

	.footerInput {
		display: flex;
		flex-direction: column;
		height: 100%;
	}

	.whatsapp {
		padding-top: 10px;
	}

	#linkWA {
		width: min-content;
		height: 100%;
	}

	#linkIG {
		background-image: linear-gradient(
			90deg,
			rgba(255, 176, 41, 1) 0%,
			rgba(254, 11, 93, 1) 50%,
			rgba(217, 36, 191, 1) 100%
		);
		background-clip: text;
		-webkit-background-clip: text; /* Vendor prefix for compatibility */
		/* Make the text transparent so the background shows through */
		-webkit-text-fill-color: transparent; /* Vendor prefix for compatibility */
		color: transparent; /* Standard property */
		width: fit-content;
		height: fit-content;
	}

	img {
		width: 70%;
	}

	p {
		font-weight: 100;
	}

	a {
		color: #00bb38;
		text-decoration: none;
		display: flex;
		height: 40%;
		align-items: center;
	}
</style>
