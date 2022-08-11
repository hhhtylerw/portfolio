<script>
	let experiences = [
		{
			"name": "FluidSecure",
			"location": "Tallahassee, FL",
			"title": "Software Engineer Intern",
			"dates": "June 2022 - August 2022",
			"description": ["- Hello", "- Robot"]
		},
		{
			"name": "FluidSecure",
			"location": "Tallahassee, FL",
			"title": "Software Engineer Intern",
			"dates": "June 2022 - August 2022",
			"description": ["- Hello", "- Robot"]
		},
		{
			"name": "FluidSecure",
			"location": "Tallahassee, FL",
			"title": "Software Engineer Intern",
			"dates": "June 2022 - August 2022",
			"description": ["- Hello", "- Robot"]
		}
	]
</script>

<!-- Main Content -->
<main>
	<!-- Header -->
	<header class="header">
		<!--<img src="https://media.discordapp.net/attachments/774535774913429504/1006949391552237638/coollogo_com-9700947.png" alt="my name" style="display:block;margin-left:auto;margin-right: auto;min-width: 50%;max-width:100%">-->
		Tyler Woodruff
	</header>

	
	<div class="flex-container wrapper" style="padding:0 1rem">
		<!-- Sidebar -->
		<div class="sidebar">
			<aside class="sidebarinfo">
				>About               
				<p>
					I am a self-taught software engineer with a passion for writing software. I enjoy making things that regular people can benefit from and improve their lives with.
				</p>
				<table><tr><td><a target="_blank" href="https://google.com">>>Resume</a></td></tr></table>
			</aside>
			<aside class="sidebarinfo">
				>Contact               
				<p>
					hhhtylerw@gmail.com<br>
					850-508-5707<br>
					Gainesville, FL
				</p>
				<table>
					<tr>
						<td><a target="_blank" href="https://www.linkedin.com/in/tylerhwoodruff/">>>LinkedIn</a></td>
						<td style="min-width:2rem"></td>
						<td><a target="_blank" href="https://github.com/hhhtylerw">>>GitHub</a></td>
					</tr>
				</table>
			</aside>
			<aside class="sidebarinfo">
				>Education
				<p>
					University of Florida<br>
					Computer Science<br>
					Grad. May 2024
				</p>
			</aside>
		</div>
		
		<!-- Content -->
		<div class="content">
			<section class="contentinfo">
				>Experience
				{#each experiences as experience}
					<div>
						<p style="float:left;margin-bottom:0">{experience.name}<br>{experience.title}</p>
						<p style="float:right;text-align:right;margin-bottom:0;">{experience.location}<br>{experience.dates}</p>
						<div style="clear: both;"></div>
						{#each experience.description as description}
							<p style="margin:0">{description}</p>
						{/each}
					</div>
				{/each}
			</section>
			<section class="contentinfo">
				>Projects
				<p>
					Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sumenda potius quam expetenda. Nihil opus est exemplis hoc facere longius. At Zeno eum non beatum modo, sed etiam divitem dicere ausus est. Nunc ita separantur, ut disiuncta sint, quo nihil potest esse perversius. Itaque quantum adiit periculum! ad honestatem enim illum omnem conatum suum referebat, non ad voluptatem. Ergo id est convenienter naturae vivere, a natura discedere. Esse enim quam vellet iniquus iustus poterat inpune. Tu enim ista lenius, hic Stoicorum more nos vexat. Duo Reges: constructio interrete.
				</p>
				<p>
					Quam ob rem tandem, inquit, non satisfacit? Haec quo modo conveniant, non sane intellego. Ita ceterorum sententiis semotis relinquitur non mihi cum Torquato, sed virtuti cum voluptate certatio. Tubulum fuisse, qua illum, cuius is condemnatus est rogatione, P. Quem ad modum quis ambulet, sedeat, qui ductus oris, qui vultus in quoque sit? Miserum hominem! Si dolor summum malum est, dici aliter non potest. Quo tandem modo? Ex rebus enim timiditas, non ex vocabulis nascitur. Deinde prima illa, quae in congressu solemus: Quid tu, inquit, huc? Quod eo liquidius faciet, si perspexerit rerum inter eas verborumne sit controversia.
				</p>                
			</section>

		</div>
	</div>
	
	<!-- Right Dolphin 
	<div>
		<img src="https://images-ext-1.discordapp.net/external/oQhYVctHm6VkxC1G66npb7KfEsuLWYJ8C5Odqwwxhoo/https/i.pinimg.com/originals/af/fb/a2/affba24abd5d2eef5090a9e15f400acc.gif?width=279&height=463" alt="Right Dolphin" style="position:fixed;bottom:0;right:0">
	</div> -->

	<!-- Left Dolphin 
	<div>
		<img src="https://images-ext-1.discordapp.net/external/oQhYVctHm6VkxC1G66npb7KfEsuLWYJ8C5Odqwwxhoo/https/i.pinimg.com/originals/af/fb/a2/affba24abd5d2eef5090a9e15f400acc.gif?width=279&height=463" alt="Left Dolphin" style="position:fixed;bottom:0;left:0;">
	</div> -->

	<!-- Footer -->
	<footer class="footer">
		© 2022 Tyler Woodruff - Thank you to George Hotz, Andrew Haden, and h3x.                
	</footer>

</main>

<style>
	*,:after,:before{box-sizing:border-box}
	.wrapper{margin:auto;max-width:75rem}
	aside,footer,header,main,section{display:block;margin:0;padding:1.25rem;border:2px solid #213c53;color:#fff}
	main{padding:0;margin:0;border:0}
	.header{border:0;text-align: center; font-size: 80px;font-weight: 900;}
	@media screen and (min-width:640px){.flex-container{display:flex}}
	.content{flex:1;}
	.contentinfo{flex:1;background:transparent;margin:10px 5px}
	.sidebar{flex:0 1 300px;}
	.sidebarinfo{flex:1;background:transparent;margin:10px 5px}
	.footer{border:2px solid #213c53;background:transparent;padding:0;text-align:center;}
	a{color:aqua;background-color: none;}
</style>