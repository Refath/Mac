# AMC 10
Tracking my path to the Math Olympiad. 


<div class="table-title">
<h3><b>AMC 10 Scores</b>: Refath Bari</h3>
</div>
<table class="table-fill">
<thead>
<tr>
<th class="text-left">Test</th>
<th class="text-left">Score</th>
</tr>
</thead>
<tbody class="table-hover">
<tr>
<td class="text-left">AMC 10A 2005</td>
<td class="text-left">12/25 = 48%</td>
</tr>
<tr>
<td class="text-left">AMC 10B 2005</td>
<td class="text-left">20/25 = 80%</td>
</tr>
<tr>
<td class="text-left">AMC 10A 2009</td>
<td class="text-left">TBA</td>
</tr>
<tr>
<td class="text-left">AMC 10A 2008</td>
<td class="text-left">TBA</td>
</tr>
<tr>
<td class="text-left">AMC 10A 2007</td>
<td class="text-left">TBA</td>
</tr>
</tbody>
</table>
  <br>  <br>  <br>  <br>
   <div class = "gruph"> <canvas id="chartJSContainer"  width="20" height="10"></canvas>   <div class = "gruph">
<script>var options = {
  type: 'line',
  data: {
    labels: ["AMC 10A 2005", "AMC 10B 2005"],
    datasets: [
	    
			{
				label: 'Score',
				data: [48, 80],
				borderWidth: 3 
			}
		]
  },
  options: {
  	scales: {
    	yAxes: [{
        ticks: {
					reverse: false
        }
      }]
    }
  }
}

var ctx = document.getElementById('chartJSContainer').getContext('2d');
new Chart(ctx, options);
Chart.defaults.global.defaultFontColor = "#fff";

</script>

<style>
  div.table-title {
   display: block;
  margin: auto;
  max-width: 600px;
  padding:5px;
  width: 100%;
}

.table-title h3 {
   color: #fafafa;
   font-size: 30px;
   font-weight: 400;
   font-style:normal;
   font-family: "Roboto", helvetica, arial, sans-serif;
   text-shadow: -1px -1px 1px rgba(0, 0, 0, 0.1);
   text-transform:uppercase;
}


/*** Table Styles **/

.table-fill {
  background: white;
  border-radius:3px;
  border-collapse: collapse;
  height: 320px;
  margin: auto;
  max-width: 600px;
  padding:5px;
  width: 100%;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
  animation: float 5s infinite;
}
 
th {
  color:#D5DDE5;;
  background:#1b1e24;
  border-bottom:4px solid #9ea7af;
  border-right: 1px solid #343a45;
  font-size:23px;
  font-weight: 100;
  padding:24px;
  text-align:left;
  text-shadow: 0 1px 1px rgba(0, 0, 0, 0.1);
  vertical-align:middle;
}

th:first-child {
  border-top-left-radius:3px;
}
 
th:last-child {
  border-top-right-radius:3px;
  border-right:none;
}
  
tr {
  border-top: 1px solid #C1C3D1;
  border-bottom-: 1px solid #C1C3D1;
  color:#666B85;
  font-size:16px;
  font-weight:normal;
  text-shadow: 0 1px 1px rgba(256, 256, 256, 0.1);
}
 
tr:hover td {
  background:#4E5066;
  color:#FFFFFF;
  border-top: 1px solid #22262e;
  border-bottom: 1px solid #22262e;
}
 
tr:first-child {
  border-top:none;
}

tr:last-child {
  border-bottom:none;
}
 
tr:nth-child(odd) td {
  background:#EBEBEB;
}
 
tr:nth-child(odd):hover td {
  background:#4E5066;
}

tr:last-child td:first-child {
  border-bottom-left-radius:3px;
}
 
tr:last-child td:last-child {
  border-bottom-right-radius:3px;
}
 
td {
  background:#FFFFFF;
  padding:20px;
  text-align:left;
  vertical-align:middle;
  font-weight:300;
  font-size:18px;
  text-shadow: -1px -1px 1px rgba(0, 0, 0, 0.1);
  border-right: 1px solid #C1C3D1;
}

td:last-child {
  border-right: 0px;
}

th.text-left {
  text-align: left;
}

th.text-center {
  text-align: center;
}

th.text-right {
  text-align: right;
}

td.text-left {
  text-align: left;
}

td.text-center {
  text-align: center;
}

td.text-right {
  text-align: right;
}</style>
