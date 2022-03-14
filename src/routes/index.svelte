<svelte:head>
	<title>Dog Class &heartsuit; Home</title>
</svelte:head>

<div class="main">
	<div class="section-intro">
		<div class="img-box">
			<img src="../../static/images/three-good-boys.jpg" alt="dog" />
		</div>
		<div class="right-column">
			<h2 id="top">It's a Dog's Life</h2>
			<p>
				Dog Obedience Training is good for you and your dog. Your dog is your companion and a member
				of your family, it is worth taking the time to learn how to better communicate with them.
				With consistent practice and the proper techniques you can establish the foundation for an
				obedient dog, which makes for a happy home.
			</p>
			<p>
				Paula Mckenzie has been working with dogs for over 50 years. She has done it all, from
				breeding to showing, grooming to training and everything in between. She has taught numerous
				people how to work with their dogs, starting with beginners level all the way to advanced.
			</p>

			<ul>
				<li><a href="#expect">What to expect</a></li>
				<li><a href="#learn">What you will learn</a></li>
				<li><a href="#supplies">What you will need for class</a></li>
			</ul>
		</div>
	</div>

	<div class="section">
		<h2 id="expect">What To Expect</h2>
		<p>
			We will meet once a week for one hour of class time. The class lasts for 8 weeks. You will
			need to practice with your dog for at least 30 minutes per day outside of class. The final
			class you and your dog will be tested to show standards. Once you have completed the class,
			you need to continue working with your dog every day, keep on practicing. You truly get out
			what you put into it.
		</p>
	</div>

	<div class="section">
		<h2 id="learn">What You Will Learn</h2>
		<p>
			We will start with some basic obedience commands and practice working with our dogs to
			reinforce these skills throughout the class.
		</p>
		<ul>
			<li>Heel</li>
			<li>Sit</li>
			<li>Stay</li>
		</ul>
		<p>
			That will be our foundation, and we will build on that as we progress, yet always coming back
			to these basics. Short, frequent training sessions throughout the week are highly recommended.
		</p>
	</div>

	<div class="section">
		<h2 id="supplies">What You Need for Class</h2>
		<p>There are some basic supplies you will need for this class.</p>
		<ul>
			<li>Pinch Collar</li>
			<li>A 3ft lead</li>
			<li>Comfortable clothing and shoes</li>
			<li>Treats</li>
		</ul>
		<p>
			Don't worry, we will go over these items during the first class, Paula will show you how to
			get a properly fitted collar. We will be walking and moving the entire class, so you should
			dress comfortably and be prepared to move.
		</p>
	</div>
</div>

<style>
	.section-intro {
		display: grid;
		grid-template-columns: 1fr 1fr;
	}
	.img-box {
		width: 100%;
		padding-right: 1rem;
	}

	img {
		width: 100%;
		margin: 1rem auto;
	}

	.right-column {
		padding: 1rem;
	}

	.right-column li {
		margin: 1rem 0;
	}

	.section-intro p {
		margin: 1rem 0;
		line-height: 1.5;
	}

	.section {
		padding: 2rem 0;
	}

	.section p {
		margin: 1rem 0;
		line-height: 1.5;
	}
</style>
