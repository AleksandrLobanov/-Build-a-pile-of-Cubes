<meta charset="utf-8">
<script type="text/javascript">
	/*function getSum(a, b){
		var n = b;
		var m = a;
		if(a < b){
			n = a;
			m = b;
		} if(a == b) return a;
		for(var sum = 0; n <= m; n++){
			sum += n;
		}
		return sum
	}*///my decision
	function getSum(a, b){
		return (Math.abs(a - b) + 1) * (a+b) / 2;
	}	
	alert(getSum(1, 2));
</script>
