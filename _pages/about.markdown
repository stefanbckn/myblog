---
layout: single
title: About
author_profile: true
permalink: /about/
---
<script>
</script>

Hallo, Ik ben [Stefan][Mailto] en ik werk als een IAM architect bij Cegeka. Sinds een aantal jaren ben ik begonnen met een budget eerst alleen en sinds kort samen met mijn vrouw Kristl. We hebben een zoon, Emiel (<span id="age"></span>) en zijn getrouwd sinds 2011.
Hier ga je onze avonturen kunnen volgen en zal er geregeld gepost worden over ons, budgeteren, sport en technologie.

Veel leesplezier.


[Mailto]: mailto:stefan@bckn.be

<script>
	function ageOfEmiel(){
		const birthday = new Date("2015-12-01");
		const d = new Date();
		const today = new Date();
		var year = d.getFullYear();
		var age;
		var bd_thisyear = new Date (year + "-12-01");
		
		if (today > bd_thisyear){
			age = today.getFullYear() - birthday.getFullYear();
			return age;
		} else {
			age = today.getFullYear() - birthday.getFullYear() - 1;
			return age;
		}
	}

	document.getElementById("age").innerHTML = ageOfEmiel();
</script>