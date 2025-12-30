<script>
	import AboutInfo from '../../figmaAssets/Logos/AboutInfo.svg';
</script>

<div id="about">
	<div id="aboutMain" class="halfHorizontal">
		<div class="halfVertical">
			<h2>Selamat Datang di</h2>
			<div id="nstrTitle">
				<h1>Nusantara</h1>
				<h1>Pathway</h1>
			</div>
		</div>
        <div class="halfVertical">
            <img id="aboutInfo" src={AboutInfo} alt="AboutInfo" />
        </div>
		
	</div>
	<div id="aboutDescriptionContainer">
		<div id="aboutDescription" class="halfHorizontal">
			<p id="aboutLeadParagraph">
				Nusantara Pathway merupakan program pendidikan menengah yang dirancang untuk memberikan
				jalur akademik yang terstruktur bagi siswa Indonesia yang berorientasi pada pendidikan
				tinggi internasional.
			</p>
			<p>
				Program ini dikembangkan sejak tahun 2023 dengan mengintegrasikan penguatan fondasi
				akademik, standar asesmen internasional, serta pembinaan keterampilan berpikir kritis dan
				kemandirian belajar yang dibutuhkan pada jenjang universitas.
			</p>
			<p>
				Melalui pendekatan kurikulum yang terarah, sistem asesmen berbasis kriteria, dan
				pendampingan akademik yang berkelanjutan, Nusantara Pathway membantu siswa membangun
				kesiapan akademik dan non-akademik untuk melanjutkan studi ke luar negeri secara bertahap
				dan realistis.
			</p>
		</div>
	</div>
</div>

<style>
	h2 {
		font-weight: 700;
		font-size: 2vw;
	}
	h1 {
		font-weight: 500;
		font-size: 3vw;
	}
	p {
		font-size: 1.25vw;
		font-weight: 500;
	}
	#about {
		width: 100%;
		height: 100%;

		display: flex;
		flex-direction: row;
	}

	#aboutInfo {
		height: 100%;
	}

	.halfHorizontal {
		width: 50%;
		height: 100%;
	}

    .halfVertical {
        width: 100%;
        height: 50%;
    }

	#aboutMain,
	#aboutDescriptionContainer {
		padding: 5% 0 5% 2%;
	}

	#nstrTitle {
		margin-top: 2%;
	}

	#aboutDescriptionContainer {
		padding-right: 50px;
		width: 50%;
		height: 100%;
		display: flex;
		flex-direction: column;

		justify-content: flex-end;
	}

	#aboutDescription {
		width: 100%;
		height: 75%;

		display: flex;
		flex-direction: column;
		justify-content: space-between;
	}

	#aboutLeadParagraph {
		font-weight: 700;
	}
</style>
