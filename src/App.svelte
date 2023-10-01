<script>
	let editP = document.getElementById("P0");
	let EDB = document.querySelector("#EDB");
	let PVal = localStorage.getItem("PValStore");

	EDB.addEventListener("click", () => {
		PVal += 1
		localStorage.setItem("PValStore", PVal)
	})


</script>

<div>

	<h1 style="font-family: Arial;">

			<strong>1 DAY</strong>
			<a id="EDB" href="#top">
			<img style="width: 52px; padding-left: 20px;" src="https://cdn.iconscout.com/icon/free/png-256/free-heart-like-love-card-game-favorite-37955.png?f=webp&w=256" alt="heart">
			</a>
			<br>
			<p style="margin-right: 20px;" id="P0">{PVal}</p>

	</h1>

</div>