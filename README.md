<p align="center"><img src="https://webdoors.ge/partners/martivia/img/martivia.png" width="400"></p>

<p align="center">
<a href="https://webdoors.ge"><img src="https://webdoors.ge/partners/martivia/img/build.svg" alt="Build Status"></a>
<a href="https://webdoors.ge"><img src="https://webdoors.ge/partners/martivia/img/total.svg" alt="Total Downloads"></a>
<a href="https://webdoors.ge"><img src="https://webdoors.ge/partners/martivia/img/stable.svg" alt="Latest Stable Version"></a>
<a href="https://webdoors.ge"><img src="https://webdoors.ge/partners/martivia/img/license2.svg" alt="License"></a>
</p>

# About Martivia

Martivia is a cross platform (Php,Python,Node.js,c#,java and etc.) web application framework. The simplicity and the novelty of the paradigm used in this framework enables web applications to load much faster and use as little resources as possible in the process.
<pre>
function func(a,b){
    var FD = new FormData();
    FD.append('function',a);
		for (var key in b) {
			if(b!=undefined){
				FD.append(key,b[key]);			
			}
		}
	$.ajax({  
		type: "POST", 
		cache: false,
		contentType: false,
		processData: false, 
		url: "func/func.php",
		data: FD,
		success: function (result) {
			if (result) {
				if(a=="logout"){
					location.reload();
				}
				if(a=="login"){
					location.reload();
				}
				if(a=="register"){
					location.reload();
				}
			}
		}
	});
}



//Logout Example
$(document).on("click",".LGT",function(){
	func("logout");
});



//Login Example
$(document).on("click",".SIIN",function(){
	var params = {
		email: $(".A1").val(), 
		password:$(".A2").val()
	};
	func("login",params);
});
</pre>