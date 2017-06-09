# Fullscrenn-Menu-Jquery-Plugin
==================================================

What is?
--------------------------------------

A simple and litle jQuery library to control fullscreen and navegation menu

Options:
----------------------------

- TARGET A ELEMENT TO CONTROLL SCROLL
- SIMPLE WAY TO NAVEGATE MENU ON PAGE
- CHANGE THE COLOR OFF MENU

How to use:
----------------------------
```
//Exemplo
/*Iniciação e configuração da biblioteca de acessibilidade*/
		$(document).ready(function()
		{
			$('body').mln_full(
			{
				'target' : '.mln_sec', //the elements target to receive a fullscreen controll
        			'color' : '#455a64', //the color off menu
        			'hover' : '#607d8b', //the color off hover menu
        			'full' : true, //resize the target to te fullscreen
        			'itens' : ['Home', 'Empresa', 'Onde Estamos', 'Contato'], //the name off the menus itens
			});
		});
```

Requisitos:
----------------------------
It's necessary add the jQuery library
```
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript" src="./mln_full.js"></script>
<script type="text/javascript">
	$(document).ready(function()
	{
		//your code here
	}
</script>    
```

