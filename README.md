<!DOCTYPE html>
<html>
<body>
pagina 1<p>La clubul nostru, cursurile pentru copii se desfasoara dupa cum urmeaza, pe baza de abonament:
</p>
<button onclick="myFunction()">luni</button>
<button onclick="myFunction()">Marti</button>
<button onclick="myFunction()">Miercuri</button>
<button onclick="myFunction()">Joi</button>
<button onclick="myFunction()">Vineri</button>
<div ng-app="">
 
<p>   Balet ora 17: </p><p>Numele: <input type="text" ng-model="name" value="abcdef"></p>
<p ng-bind="name"></p><p>Nr.telefon: <input type="text" ng-model="name" value="abcdef"></p>
<p ng-bind="name"></p>
</div>
<button onclick="myFunction()">Inregistrare</button>
<p>   Balet ora 18: </p><p>Numele: <input type="text" ng-model="name" value=""></p>
<p ng-bind="name"></p><p>Nr.telefon: <input type="text" ng-model="name" value=""></p>
<p ng-bind="name"></p>
</div>
<button onclick="myFunction()">Inregistrare</button>
<script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.2.15/angular.min.js"></script>
<script>
function myFunction() {
    var x = document.getElementById("venus").target;
    document.getElementById("demo").innerHTML = x;
}
</script>
<p>Weekend-urile sunt alocate petrecerilor aniversare, pentru mici si mari!!! Clientii fideli ai cursurilor noastre beneficiaza de reduceri.</p>
<button onclick="myFunction()">Sambata</button>
<button onclick="myFunction()">Duminica</button>

</body>
</html>
