<script>
	let experiences = [
		{
			"name": "FluidSecure",
			"location": "Tallahassee, FL",
			"title": "Software Engineer Intern",
			"dates": "Jun 2022 - Aug 2022",
			"description": ["- Made commits to Apple Watch app", "- Created marketing content and webpages to display it", "- Made various website fixes/changes"]
		},
		{
			"name": "0xRay",
			"location": "Remote",
			"title": "Co-Owner / Software Engineer",
			"dates": "Sep 2021 - Present",
			"description": ["- Created and hosted a free application with 2.5k+ users", "- Worked with a team to advertise and monetize product"]
		},
		{
			"name": "Jolt Industries",
			"location": "Remote",
			"title": "Software Engineer / Sales",
			"dates": "Nov 2020 - Jan 2022",
			"description": ["- Created free, consumer-oriented software that enabled users to profit", "- Marketed software and IP proxy solutions"]
		}
	]

	let projects = [
		{
			"name": "Sables (Hack NYU 2022)",
			"date": "Feb 2022",
			"caption": ">>Website",
			"link": "https://sables.tech",
			"description": ["- Created an application that increases computer accessibility for persons with visual impairments", "- Created a website to promote the application"]
		},
		{
			"name": "Eno Delete",
			"date": "Jul 2022",
			"caption": ">>GitHub Repo",
			"link": "https://github.com/hhhtylerw/eno-delete",
			"description": ["- Created a script that automatically deletes Capital One virtual cards", "- Useful for persons in the \"Sneaker Botting\" community"]
		},
		{
			"name": "UF Course Monitor",
			"date": "Apr 2022",
			"caption": ">>GitHub Repo",
			"link": "https://github.com/hhhtylerw/class-monitor",
			"description": ["- Created an application that monitors for openings in classes and notifies via text", "- Successfully notified users of openings"]
		},
		{
			"name": "Jolt Eats",
			"date": "Dec 2021",
			"caption": ">>GitHub Repo",
			"link": "https://github.com/hhhtylerw/marley-gen",
			"description": ["- Created a script that generates vouchers for free food at major restaurant chains"]
		},
		{
			"name": "Jolt AutoQuickTask",
			"date": "May 2021",
			"caption": ">>User Success",
			"link": "https://google.com",
			"description": ["- Created a free, consumer-oriented application that automatically starts tasks on sneaker bots for users on random e-commerce restocks", "- Successfully bought profitable shoes for multiple people"]
		}
	]
</script>

<!-- Main Content -->
<main>
	<!-- Header -->
	<header class="header">
		Tyler Woodruff
	</header>

	
	
	<div class="flex-container wrapper" style="padding:0 1rem">
		<!-- Sidebar -->
		<div class="sidebar">
			<aside class="sidebarinfo">
				>About               
				<p>
					I am a self-taught software engineer attending the University of Florida. I enjoy making things that people can benefit from and improve their lives with.
				</p>
				<table><tr><td><a target="_blank" href="https://cdn.discordapp.com/attachments/819783862762209299/1016523560208048168/Tyler_Woodruff_Resume.pdf">>>Resume</a></td></tr></table>
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
				<p style="margin-bottom:0">
					University of Florida<br>
					Computer Science<br>
					Grad. <a class="notlink">May 2024</a>
				</p>
			</aside>
		</div>
		
		<!-- Content -->
		<div class="content">
			<section class="contentinfo">
				>Experience
				{#each experiences as experience}
					<div>
						<p style="float:left;margin-bottom:0">{experience.name}<br><a class="notlink">{experience.title}</a></p>
						{#if window.innerWidth > 900}
							<p style="float:right;text-align:right;margin-bottom:0;">{experience.location}<br>{experience.dates}</p>
						{:else}
							<div style="clear: both;"></div>		
							<p style="float:left;text-align:left;margin-top:0">{experience.location}<br>{experience.dates}</p>
						{/if}
						<div style="clear: both;"></div>
						{#each experience.description as description}
						<p style="margin:0">{description}</p>
						{/each}
					</div>
				{/each}
			</section>
			<section class="contentinfo">
				>Projects
				{#each projects as project}
					<div>
						<p style="float:left;margin-bottom:0">{project.name}<br><a target="_blank" href={project.link}>{project.caption}</a></p>
						{#if window.innerWidth > 900}
							<p style="float:right;text-align:right;margin-bottom:0">{project.date}</p>
						{:else}
							<p style="float:right;text-align:right">{project.date}</p>
						{/if}
						<div style="clear: both;"></div>
						{#each project.description as description}
							<p style="margin:0">{description}</p>
						{/each}
					</div>
				{/each}
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

	<!-- Dolphin -->
	<div>
		<img src="https://images-ext-1.discordapp.net/external/nUqZz1eJj6Xl7z_lCZgi2Jq5TRexi9KEG315US8AGAI/http/juliannes.website/_n/_images/dolphin-swimming-animation.gif" alt="dolphin" style="display:block;margin-left:auto;margin-right: auto;min-width: 50%;max-width:100%">
	</div>

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
	.header{border:0;text-align: center; font-size: 70px;font-weight: 900;}
	@media screen and (min-width:640px){.flex-container{display:flex}}
	.content{flex:1;}
	.contentinfo{flex:1;background:transparent;margin:10px 5px}
	.sidebar{flex:0 1 300px;}
	.sidebarinfo{flex:1;background:transparent;margin:10px 5px}
	.footer{border:2px solid #213c53;background:transparent;padding:0;text-align:center;}
	a{color:aqua;background-color: none;}
	.notlink{text-decoration: none;}
</style>