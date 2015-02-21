<h4>What is the Access-Map?</h4>

The Access Map is a tool that visualizes a handicapped person's perspective by wiping out all the stations that are not accessible. The map was originally created by the initiative <a href="http://mappable.info">Mappable</a> from Hamburg. The idea:

<blockquote>Taking the tube or suburban railway for your daily commute is quite comfortable if you live in a city with a well developed public transport network. But as so often in life we quickly take things for granted and tend to forget that such amenities are not accessible for everyone. [...] Fortunately there are projects like Raul Krauthausen's phenomenal <a href="http://wheelmap.org/en/">wheelmap</a> [...] While this and other tools help to improve the situation of handicapped people, we nevertheless think that from time to time it's useful and necessary to remind 'the public' about the limitations of 'public transport'.</blockquote>

<p>I think, apps that support people with mobility restrictions in their everyday life are great - but they are not the final answer to the greater problem that needs to be solved, namely too few accesible stations. With this map we want to raise more awareness for the topic, by visualizing how a city looks like for a person in a wheelchair.<br>
We strongly encourage you to redploy this tool in your city. It's really easy and no coding skills are needed. We'll explain how to do that below. In case you have any questions that are not answered here, feel free to <a href="mailto:fiona.krakenbuerger@okfn.de">contact</a>me and ask.<p>

<hr>

<h4>How does it work?</h4>

<p>This Readme explains step by step how to redeploy the Access Map in your city. You will make your own maps, copy the repository and adapt it to your city. In the end we will put your map online with github-pages and you're done!</p>

You'll need:
	<ul>
		<li>a map of your public transport system</li>
		<li>an image manipulation program like GIMP</li>
		<li>A github Account</li>
		<li>The github App (Or basic git skills on your command line)</li>
		<li>An editor like Sublime</li>
	</ul>

<b>1. Find a map</b>

<p>First you need to chose a map for the visualization. It certainly makes sense to use the public transportation map by your city, but often these are restricted by copyright laws. Nevertheless you could ask for permission or check whether there is a free version available. This can be quite a hassle, decide for yourself, how you want to proceed on that, just keep in mind that you might be breaking a law if you simply use the map from your city without permission.</p>

<b>2. Edit the map</b>

<p>This is probably the part that consumes most of the time - which isn't much though. Make a copy of whatever map image you want to use and rename it for example map_erased.jpg. Open it in an editing program and erase all the stations that are not accessible. I used the stamp tool in GIMP which worked perfectly fine. It took me about half an hour.</p>

<b>3. Set up a github account</b>

<p>Now we want to join the maps and put them online. For that matter you need to create a github account, if you don't have one yet, go to <a href="http://github.com">github</a> and create one. After that, I would recommend to install the github App. I'll be going through the How-To expecting you to use the app. You can also use the command line for that, but I won't explain that here.</p> 

<b>4. clone the repository</b>

<p>After you've created your account, go to the <a href="https://github.com/arduina/access_map">repository</a> on my account and "clone" it to your Desktop. You will see the repository appearing in your github app. You can see the changes you made here and "push" them to the repository when you sync it. By syncing you also "pull" all the changes that were made by other people, in case you have other collaborators. This is now your very own repository. You can also rename it if you want to and add other people on github in the "settings" section.</p>

<b>5. Adjust it to your city</b>

<p>Now you should find out where the repository has been saved on your computer. Probably in your home folder. Drag the entire folder in a text editor like <a href="http://www.sublimetext.com">Sublime</a>. Go to the index.html file and adjus the text between the "<body>" tags to whatever you want to say. You can also change the font and the color in the style.css file, if you want to. Save your changes. Then you need to go back to your folder and replace the images with your pictures.</p>

<b>6. Does it work? Check locally.</b>

<p>This is not mandatory: If you have python installed, you can see whether your adjustments work by going into your terminal and typing:</p>

python -m SimpleHTTPServer

<p>You can then go to your browser, type in "localhost:8000" or replace the 8000 with whatever port python is serving (It usually says that when you execute the command). Does it work? Perfect!</p>

<b>7. Push it!</b>

<p>You are now ready to put everything online. See whether the github app noted all the changes you made, then you can sync everything. Check your github repository on the github site. Is everything in there? Good!</p>

<b>8. Go online!</b>

<p>Now go ahead and check your new awesome website on  http://username.github.io/access_map. Replace "username" with the name you chose for your account and "access_map" with the name of your respository. You did it, awesome!</p>

<p>You can now make an important statement on accessibility. Share this and talk to people about accessibility. It's important. Feel free to teach other people how to build this app. Thank you for your commitment <3</p>










