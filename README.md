[b]Version 3.7.*[/b]

Genetic Ascension offers you the opportunity to tailor your species to meet any need, serve any niche. The UI... does not. It's just not practical. You need to maintain a massive stable of templates, one per habitability type, that you have to constantly re-apply. Even then, you end up with pops with inappropriate traits for their jobs. 

This is my attempt at making getting the most out of Genetic Ascension slightly less painful.

[h1]Optimized Genomes[/h1]
The mod adds a new 2-point advanced trait, [b]Optimised Genome[/b], that rolls together the benefits of [b]Industrious[/b], [b]Agrarian[/b], [b]Thrifty[/b], [b]Ingenious[/b], and the advanced trait [b]Natural Machinist[/b]. It adds +15% to Energy, Food and Minerals production, +10% to Alloy and Consumer Goods production, as well as +25% Trade Value from jobs! No longer must you be annoyed by the fact you can't modify individuals to match their jobs, or have to constantly re-run Modify Species projects.

However, there's a cost for this - the trait adds a 0.5 Society Research upkeep to pops with it (replacing the cost of Modify Species). This can be reduced by taking the Genetics tradition [b]Retroviral Manipulation[/b] (-50%), or building [b]Gene Clinics[/b] (-15%) or [b]Cyto-Revitalization Centers[/b] (-30%).

It also changes the [b]Harsh Truth[/b] modifier from the Engineered Species archaeology chain, so that it reduces the Society Research upkeep of pops by the amount it reduces the cost of Modify Species projects.

Plus, the mod also adds a new habitability type - [b]Optimised Habitability[/b], which just grants a flat 80% habitability across all basic planet types.

[h1]FAQ[/h1]
[quote]Why doesn't Optimised Genomes also include [b]Traditional[/b] (+Unity), [b]Charismatic[/b] (+Amenities), [b]Intelligent[/b] (+Research) or [b]Natural Physicists/Engineers/Sociologists[/b] (+Research)?[/quote]
[list]
	[*][b]Charismatic[/b] has extra effects related to diplomacy and Xenophile appeal. Folding it in would require making a lot of very wide-ranging changes.
	[*][b]Intelligent[/b] conflicts with the advanced trait Erudite. Folding it in would effectively allow you to take both.
	[*][b]Natural Physicists/Engineers/Sociologists[/b] overlap too much. There's no jobs that produce both Minerals and Food, so folding Industrious and Agrarian into one trait is fine, but researcher jobs produce Physics, Engineering and Society research so you'd get 3 points worth of benefit from a 2 point trait.
	[*][b]Traditional[/b] only costs 1. I'm not quite sure about this one, if the admin benefits of including it outweigh the costs of effectively doubling its price.
[/list]
[quote]Can you make Optimised Habitability compatible with another mod that adds a bunch of extra planet types?[/quote]
No, sorry. Don't use any mods like that, and I don't have time to make stuff I won't use.

[h1]Compatibility[/h1]
This mod overrides the following:
[table]
	[tr]
		[td][i]inline_scripts/pop_categories/regular_upkeep.txt[/i][/td]	
		[td]This will probably make it incompatible with any other mods that add new upkeep types to pops.[/td]
	[/tr]
	[tr]
		[td][i]tr_genetics_retrovirus[/i][/td]
		[td][b]Retroviral Manipulation:[/b] Tradition in the Genetics tradition tree[/td]
	[/tr]
	[tr]
		[td][i]engineered_species_revelation[/i][/td]
		[td][b]Harsh Truth:[/b] Empire modifier[/td]
	[/tr]
	[tr]
		[td][i]building_clinic[/i][/td]
		[td][b]Gene Clinic:[/b] Building[/td]
	[/tr]
	[tr]
		[td][i]building_hospital[/i][/td]
		[td][b]Cyto-Revitalization Centers:[/b] Building[/td]
	[/tr]
[/table]

[h1]My other mods:[/h1]
If you like this, you might also like:
[list]
	[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1355094979]Claims Decay - Dynamic Diplomacy:[/url] Friendly empires will renounce their claims on each other over time. Diplomatic Grants makes neutral empires do it too.
	[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=1319264195]Loyal Subjects Have Nothing to Fear (from the Colossus):[/url] Loyal vassals and tributaries no longer suffer opinion penalties when you crack a planet.
[/list]