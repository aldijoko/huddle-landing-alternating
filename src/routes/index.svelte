<script>
</script>

<header>
	<nav class="navbar">
		<div class="icon">
			<img src="images/logo.svg" alt="" />
		</div>
		<div class="btnHeader">
			<button>Try It Free</button>
		</div>
	</nav>
</header>
<section class="topContainer">
	<div class="topContent">
		<div class="txtContent">
			<h1 class="topHeader">Build The Community Your Fans Will Love</h1>
			<p class="topTxt">
				Huddle re-imagines the way we build communities. You have a voice, but so does your
				audience. Create connections with your users as you engage in genuine discussion.
			</p>
			<button class="topBtn">Get Started For Free</button>
		</div>
		<div class="topImg">
			<img class="imgMock" src="images/illustration-mockups.svg" alt="" />
		</div>
	</div>
</section>
<section class="bottomContainer">
	<div class="card">
		<div class="cardContent">
			<h1 class="cardHeader">Grow Together</h1>
			<p class="cardSubtitle">
				Generate meaningful discussions with your audience and build a strong, loyal community.
				Think of the insighful conversations you miss out on with a feedback form.
			</p>
		</div>
		<div class="cardBg">
			<img class="imgCard" src="images/illustration-grow-together.svg" alt="" />
		</div>
	</div>
	<div class="card">
		<div class="cardBg">
			<img class="imgCard" src="images/illustration-flowing-conversation.svg" alt="" />
		</div>
		<div class="cardContent">
			<h1 class="cardHeader">Flowing Conversations</h1>
			<p class="cardSubtitle">
				You wouldn't paginate a conversation in a real life. so why do it online? Our threads have
				just-in-time loading for a more natural flow.
			</p>
		</div>
	</div>
	<div class="card">
		<div class="cardContent">
			<h1 class="cardHeader">Your Users</h1>
			<p class="cardSubtitle">
				It takes no time at all to integrate Huddle with your app's authentication solution. This
				means, once signed in to your app, your users can start chatting immediately.
			</p>
		</div>
		<div class="cardBg">
			<img class="imgCard" src="images/illustration-your-users.svg" alt="" />
		</div>
	</div>
	<div class="cardFloat">
		<h1 class="floatHeader">Ready To Build Your Community?</h1>
		<button class="floatBtn">Get Started For Free</button>
	</div>
</section>
<footer>
	<div class="footerContainer">
		<img class="logoFooter" src="images/footer-logo.svg" alt="" />
		<div class="footerContent">
			<div class="footerContact">
				<div class="contentContact">
					<img class="contactIcon" src="images/icon-location.svg" alt="" />
					<p class="contactTxt">
						Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
						incididunt ut labore et dolore magna aliqua
					</p>
				</div>
				<div class="contentContact">
					<img class="contactIcon" src="images/icon-phone.svg" alt="" />
					<p class="contactTxt">+1-543-123-4567</p>
				</div>
				<div class="contentContact">
					<img class="emailIcon" src="images/icon-email.svg" alt="" />
					<p class="contactTxt">example@huddle.com</p>
				</div>
			</div>
			<div class="footerList">
				<ul>
					<li>About Us</li>
					<li>What We Do</li>
					<li>FAQ</li>
				</ul>
			</div>
			<div class="footerList">
				<ul>
					<li>Career</li>
					<li>Blog</li>
					<li>Contact Us</li>
				</ul>
			</div>
			<div class="sosmed">
				<span><i class="fab fa-facebook-f" /></span>
				<span><i class="fab fa-twitter" /></span>
				<span><i class="fab fa-instagram" /></span>
			</div>
		</div>
        <p class="footerCopy">&copy; Copyright 2018 Huddle. All rights reserved.</p>
	</div>
</footer>

<style>
	.navbar {
		width: 100%;
		display: flex;
		justify-content: space-between;
		padding: 50px;
	}

	.btnHeader button {
		background-color: white;
		padding: 12px;
		width: 180px;
		border-radius: 20px;
		font-weight: 700;
		box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
		border: 1px solid white;
        cursor: pointer;
	}

    .btnHeader button:hover {
        color: var(--Grayish);
        background-color: rgb(255, 250, 250);
    }

	.topContainer {
		background-color: var(--paleCyan);
		padding: 50px;
		width: 100%;
	}

	.topContent {
		display: flex;
		width: 100%;
		/* justify-content: space-between; */
	}

	.txtContent {
		width: 40%;
		padding-top: 50px;
	}

	.topHeader {
		font-size: 36px;
		width: 100%;
		padding: 50px 150px 0px 0px;
		line-height: 3rem;
	}

	.topTxt {
		width: 100%;
		margin-top: 30px;
	}

	.topBtn {
		margin-top: 30px;
		width: 50%;
		padding: 15px;
		color: white;
		background-color: var(--pink);
		border: 1px solid var(--pink);
		border-radius: 25px;
        cursor: pointer;
        font-weight: 700;
	}

    .topBtn:hover {
        /* background-color: hsl(322, 70%, 68%); */
        background-color: hsl(321, 53%, 77%);
        border: 1px solid hsl(321, 53%, 77%);
    }

	.topImg {
		width: 60%;
	}

	.imgMock {
		width: 90%;
	}

	.bottomContainer {
		background-color: white;
		padding: 200px 50px;
		width: 100%;
		position: relative;
	}

	.card {
		display: flex;
		border-radius: 10px;
		border: 1px solid white;
		box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
		width: 100%;
		height: auto;
		margin-top: 40px;
		padding: 50px;
		justify-content: space-between;
		align-items: center;
	}

	.cardContent {
		width: 50%;
		padding: 50px;
		/* height: 100%; */
	}

	.cardHeader {
		font-size: 36px;
		margin-bottom: 10px;
	}

	.cardSubtitle {
		color: var(--Grayish);
		width: 100%;
		padding: 20px 20px 20px 0px;
		letter-spacing: 1px;
		line-height: 2rem;
	}

	.cardBg {
		width: 50%;
		display: flex;
		justify-content: flex-end;
		/* align-items: center; */
		/* padding: 50px; */
	}

	.imgCard {
		width: 80%;
		height: 80%;
	}

	.cardFloat {
		position: absolute;
		bottom: -125px;
		right: 350px;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		/* left: 0; */
		width: 50%;
		height: 250px;
		border-radius: 10px;
		border: 1px solid white;
		background-color: white;
		box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
		padding: 50px;
	}

	.floatBtn {
		margin-top: 30px;
		width: 50%;
		padding: 20px;
		color: white;
		background-color: var(--pink);
		border: 1px solid var(--pink);
		border-radius: 25px;
        cursor: pointer;
        font-weight: 700;
	}
    
    .floatBtn:hover {
        background-color: hsl(321, 53%, 77%);
        border: 1px solid hsl(321, 53%, 77%);
    }

	.footerContainer {
		padding: 100px 50px;
		background-color: var(--darkCyan);
		color: white;
		width: 100%;
	}

	.logoFooter {
		margin-top: 100px;
	}

	.footerContent {
		display: flex;
		width: 90%;
		justify-content: space-between;
	}

	.footerContact {
		margin-top: 30px;
		width: 30%;
	}

	.footerList {
		margin-top: 30px;
		color: var(--Grayish);
		font-weight: 700;
		cursor: pointer;
	}

	.footerList li {
		list-style: none;
		margin-top: 20px;
	}

    .footerList li:hover {
        text-decoration: underline;
    }

	.sosmed {
		margin-top: 30px;
	}

	.sosmed span {
		padding-right: 10px;
	}

	.sosmed span i {
		height: 35px;
		width: 35px;
		color: var(--Grayish);
		border: 2px solid var(--Grayish);
		border-radius: 50%;
		align-items: center;
		text-align: center;
		cursor: pointer;
		padding: 9px 0;
	}

    .sosmed span i:hover{
        color: var(--pink);
        border: 2px solid var(--pink);
    }

	.contentContact {
		display: flex;
		width: 100%;
		margin-top: 20px;
	}

	.contactIcon {
		width: 15px;
		height: 20px;
	}

	.emailIcon {
		width: 20px;
		height: 20px;
	}
	.contactTxt {
		color: var(--Grayish);
		margin-left: 30px;
		line-height: 2rem;
	}

    .footerCopy {
        width: 100%;
        color: var(--Grayish);
        font-size: 12px;
        display: flex;
        justify-content: flex-end;
    }
</style>
