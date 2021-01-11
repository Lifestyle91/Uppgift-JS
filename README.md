# Uppgift-JS


// Copyright när man klickar på bilden //

function protect()
{
alert("This image is copyrighted!");
return false;
}

-------------------------------------------------------------------------------
-------------------------------------------------------------------------------
// Detta ligger sen på img src:
onmousedown="alert('This image is copyrighted!'); return false;" 

-------------------------------------------------------------------------------
-------------------------------------------------------------------------------
// Like knapp //

function myFunctions(x) {
	 x.classList.toggle("fa-thumbs-down");
	}
	
-------------------------------------------------------------------------------
-------------------------------------------------------------------------------
// Login script - http://www.monsterankan.se/javascript/2loginsida.html //

function password() {

x = document.getElementById("username").value;
y = document.getElementById("password").value;


if (x == "Marcus" && y == "1337" ) {

window.open("../index.html");
}


else {
document.getElementById("myAnswer").innerHTML = "Username or Password is wrong. Please try again. ";
}
}

-------------------------------------------------------------------------------
-------------------------------------------------------------------------------

