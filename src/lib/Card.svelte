<article class="card">
	<img src="./image-qr-code.png" alt="QR code" class="image" />
	<header>Improve your front-end skills by building projects</header>
  <p>
    Scan the QR code to visit Frontend Mentor
    and take your coding skills to the next level
  </p>
</article>

<style>
	.card {
		--background-color: var(--white);
		background-color: var(--background-color);
    box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
		width: 300px;
    height: 100%;
		border-radius: 1.2em;
		padding: 1em;
	}
	.image {
		border-radius: 0.5em;
		width: 100%;
    height: 270px;
    margin-bottom: 1em;
	}
  header, p {
    text-align: center;
  }
	header {
    margin-bottom: 0.5em;
    padding: 0 0.5em;
		font-weight: var(--header-font-weight);
    font-size: var(--header-font-size);
    color: var(--dark-blue);
	}
  p {
    padding: 0 1.1em;
    color: var(--grayish-blue);
    margin-bottom: 1.5em;
  }

  @media screen and (min-width:375px) {
		header {
      font-size: 1.2em;
      padding: 0 1em;
    }
    p {
      padding: 0.5em 1em;
      font-size: 0.9em;
    }
	}
</style>
