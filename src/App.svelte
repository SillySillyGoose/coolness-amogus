<script>
	const date = new Date();
	let Day = date.getDate();
	let week = 7
	let Days_Remaining = 50 - Day;
	const Month = date.getUTCMonth();
	let MT = 'November'
	let trueDay = 24;
	let time = date.getHours();
	var countdownDate = new Date("Dec 20, 2023 03:00:00")

	var x = setInterval(function() {


		var now = new Date().getTime();

		var distance = countdownDate - now;



  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);


		document.getElementById("CD").innerHTML = days + "d"  + " " + hours + "h" + " " + minutes +  "m" + " " + seconds + "s";


		if (distance < 0){

			clearInterval(x)
			document.getElementById("CD").innerHTML = "End Of School!"

		}

	}, 1000)

 // work on later



	function SaveObj(key  = "", object)
	{
		window.localStorage.setItem(key, object)
	}

	function Loadobj(key = "", object)
	{
		object = window.localStorage.getItem(key)
	}


	console.log(Month)

	// Month Automation

	


	

	

	

	

	
	

	// future me, if i come back to this, Hi!

	

	

	



	

	import Hai from './hai.svelte'
	function GETOFFMEBLOODYLAWN(){
		document.querySelector("#getoffmebloodylawn").hidden = false
		document.querySelector("#buton").hidden = true

	}
	function GETONMEBLOODYLAWN(){
		document.querySelector("#getoffmebloodylawn").hidden = true
		document.querySelector("#buton").hidden = false
	}

</script>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap');


	.CD{
		border: 3px solid;
		width: 100px;
		height: 100px;
		display: table-cell;
		overflow: hidden;

	}
	.buton:hover{
		cursor: pointer;
	}
	.hov{
		cursor: pointer;
	}
	.MP{
		font-family: 'Roboto';
    font-size: 90px;
	margin: 0;
	text-align: center;
	}


</style>
<h1 style="text-align: center;" id="CD">Amogus sussy wow</h1>
<h1>It's {MT}!</h1>
<div style="text-align: center;">
<h1>Day {Day}, Week {week}</h1>
<h1>{Days_Remaining} Days Remaining </h1></div>

<div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
</div>
<div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
</div>
<div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
</div>
<div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP">x</p></div>
	<div class="CD"><p class="MP"></p></div>
	<div class="CD"><p class="MP"></p></div>
	<div class="CD"><p class="MP"></p></div>
	<div class="CD"><p class="MP"></p></div>
	<div class="CD"><p class="MP"></p></div>
</div>
<div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
</div>
<div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
</div>
<div>
	<div class="CD"></div>
	<div class="CD"></div>
	<div class="CD"></div>
</div>
<img hidden id="getoffmebloodylawn" class="hov" on:click={GETONMEBLOODYLAWN} style="width: 200px; height: 200px;" src="data:image/jpeg;base64,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" alt="my dog hungry">
<button on:click={GETOFFMEBLOODYLAWN} id="buton" class="buton" style="opacity: 0%;">                                                                                             .............................................................</button>
<Hai/>

