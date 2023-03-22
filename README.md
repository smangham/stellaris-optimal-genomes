Lithoid & plantoid advanced traits
Intelligent -> Erudite
Adaptive -> Robust
Slave -> Nerve Stapled (not trait_zombie)
trait_presapient_proles -> Optimal Genome
trait_presapient_natural_intellectuals -> Erudite

Switch to Optimal Habitability


[b]Version 3.7.*[/b]

Genetic Ascension lets you tailor your species to meet any need, serve any niche. The UI... does not. You need to a massive stable of templates you have to constantly re-apply, and still end up with pops with the wrong traits. 

This mod should make Genetic Ascension slightly less painful - all the benefits, with less of the busywork.

[h1]Optimal Genomes[/h1]
Advanced gene-modding unlocks the new 2-point trait [b]Optimised Genome[/b], that adds:
[list][*]+15% Energy, Food & Minerals production [i](replacing Ingenious, Agrarian & Industrious)[/i]
[*]+10% Alloy & Consumer Goods production [i](replacing Natural Machinist)[/i]
[*]+25% Trade Value from jobs [i](replacing Thrifty)[/i]
[*]0.5 Society Research upkeep [i](replacing the cost of running multiple Modify Species projects)[/i]
[/list]
Since there's (almost) no jobs the original traits overlap for, there's no problem with just combining them into one! You can easily reduce the upkeep cost, too:
[list][*][b]Retroviral Manipulation[/b], the Genetics talent that reduces the cost to modify species by 50%, also reduces Society upkeep by 50%.
[*][b]Gene Clinics[/b] and [b]Cyto-Revitalization Centers[/b] reduce Society upkeep by 15% and 30%.
[*][b]Harsh Trush[/b], an archeology reward that reduces the cost to modify species by 20%, also reduces Society upkeep by 20%.
[/list]
Advanced gene-modding also unlocks [b]Optimised Habitability[/b], a flat 80% habitability across all basic planet types. This prevents you from needing an extra template for each planet type.

Once you finish the Genetic Ascension tree, you unlock [b]Genetic Optimisation Policy[/b], which can be left as special projects only or as:
[list][*][b]Remediate Habitability:[/b] Replaces basic habitabilities with [b]Optimised Habitibility[/b], once per month.
[*][b]Upgrade Traits:[/b] Replaces obsoleted production traits with [b]Optimised Genome[/b], as well as replacing Extremely Adaptive with [b]Robust[/b] (as they cost the same), once per month. Applies a 5 Society Research upkeep to pops who will have their traits replaced.[/list]

[h1]FAQ[/h1]
[quote]Why doesn't Optimised Genomes also include [b]Traditional[/b] (+Unity), [b]Charismatic[/b] (+Amenities), [b]Intelligent[/b] (+Research) or [b]Natural Physicists/Engineers/Sociologists[/b] (+Research)?[/quote]
[list]
	[*][b]Charismatic[/b] has extra effects related to diplomacy and Xenophile appeal. You'd still need to take it for those.
	[*][b]Intelligent[/b] conflicts with the advanced trait Erudite. Folding it in would effectively allow you to take both.
	[*][b]Natural Physicists/Engineers/Sociologists[/b] overlap too much - researchers would benefit from all of them.
	[*][b]Traditional[/b] only costs 1. I'm not quite sure about this one, if the admin benefits of including it outweigh the costs of effectively doubling its price.
[/list]

[quote]Can you make Optimised Habitability compatible with other mods that add extra planet types?[/quote]
No, sorry. Don't use any mods like that, and I don't have time to make stuff I won't use.

[quote]Can you make it intelligently add extra traits to species?[/quote]
No, there's no way to get the current number of unused trait points. [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2938437888&searchtext=]Genemod Micromanagement[/url] does that, but on a much lower cadence (decades) than this mod, due to the performance cost of manually checking every trait. I tried it, but made my own as I didn't really like the number of new species it made.

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
	[*][url=https://steamcommunity.com/sharedfiles/filedetails/?id=2949670744]Shared Burden Balance - People Power:[/url] Adds a flat bonus to political power to the Shared Burden living standard to remove its effective faction influence penalty.
[/list]