# GauriSCMproject
<html>
    <head>
        <body>
            
            
            <p><input type="number" placeholder="Enter first number"id="fnum" /></p>
<p>
    <select id="op">
        <option>select operator</option>
        <option>+</option>
        <option>/</option>
        <option>-</option>
        <option>*</option>
    </select>
</p>
<p><input type="number" placeholder="Enter second number" id="snum" /></p>
<p><button onclick="calculator()">Calculate</button></p>
<p id="cvalue"></p>
<script>
    function calculator() {
    var x = document.getElementById('fnum').value;
    var y = document.getElementById('snum').value;
    var op = document.getElementById('op').value;
    switch(op) {
        case '+':
            result = parseInt(x)+parseInt(y);
            document.getElementById('cvalue').innerHTML = result;
            break;
            
        case '/':
            result = parseInt(x)/parseInt(y);
            document.getElementById('cvalue').innerHTML = result;
            break;
            
        case '-':
            result = parseInt(x)-parseInt(y);
            document.getElementById('cvalue').innerHTML = result;
            break;
            
        case '*':
            result = parseInt(x)*parseInt(y);
            document.getElementById('cvalue').innerHTML = result;
            break;
            
        default:
            document.getElementById('cvalue').innerHTML = result;
            break;
    }
}
</script>       
</body>
    </head>
</html>
