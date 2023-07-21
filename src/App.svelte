<script>
	let day = 11
	let day_remaining = 56
	let day_length = 8.64e+7
	let ms_remaining = 4.838e+9
	daytime2()
	daytime()
	function sleep(ms) {
  return new Promise(resolve => setTimeout(resolve, ms));
}

	async function daytime(){
		while (true) {
			await sleep(1)
			ms_remaining -= 1
		}
	
	}
	async function daytime2(){
			while (true) {
			await sleep(day_length)
		day_remaining -= 1
		day += 1
		}
	}
	
</script>

<style>
h1{
	text-align: center;
	padding: 50px
}
p{
	text-align: center;
	font-size: 30px;
	font-variant: bolder;
}
	
</style>

<h1>Day: {day}</h1>
<p>{day_remaining} Days remaining.</p>
<p>{ms_remaining} MS remaining.</p>