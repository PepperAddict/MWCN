<center class="main_header"><h1> Grow with Google Challenge Notes: Chapter 2</h1>

<h2>The Benefits of Offline First</h2></center>
<h1>2.1</h1>
<h2>Intro</h2>

We first meet our instructors:</br>
<b>Jake Archibald</b> from London who will do most of the teaching.</br>
<b>Mike Wales</b> from USA who gives us the quizzes.</br></br>

Jake goes on to show the importance of having offline first.
He says that what we will be working on will work great on whatever
type of connection.
We will be working on the dev tools, IDB the in browser database, use user
interface strategy to deal varying network conditions and updates.

<h1>2.2</h1>
<h2>The Problem</h2>

Jake talks about an app we will be working on. It's not quite a progressive app yet, but what we will work on is to make it progressive. 
So what does progressive app mean?<br><br>
<blockquote>

<b><a href="https://en.wikipedia.org/wiki/Progressive_web_app">Progressive app</a></b>:<br>
In 2015, designer Frances Berriman and Google Chrome engineer Alex Russell coined the term "Progressive Web Apps" [3] to describe apps taking advantage of new features supported by modern browsers, including service workers and web app manifests, that let users upgrade web apps to progressive web applications in their native operating system (OS). According to Google Developers,[3][4][5] these characteristics are:
<br><br>
Progressive - Work for every user, regardless of browser choice because they’re built with progressive enhancement as a core tenet.<br>
Responsive - Fit any form factor: desktop, mobile, tablet, or forms yet to emerge.<br>
Connectivity indepreplacementent - Service workers allow work offline, or on low quality networks.<br>
App-like - Feel like an app to the user with app-style interactions and navigation.<br>
Fresh - Always up-to-date thanks to the service worker update process.<br>
Safe - Served via HTTPS to prevent snooping and ensure content hasn’t been tampered with.<br>
Discoverable - Are identifiable as “applications” thanks to W3C manifests[6] and service worker registration scope allowing search engines to find them.<br>
Re-engageable - Make re-engagement easy through features like push notifications.<br>
Installable - Allow users to “keep” apps they find most useful on their home screen without the hassle of an app store.<br>
Linkable - Easily shared via a URL and do not require complex installation.<br>
Progressive Web Apps described by Shoaib in a follow-up post:[7] are an enhancement of existing web technology. As such, they do not require separate bundling or distribution. Publication of a Progressive Web App is as it would be for any other web page. As of 2017, Progressive Web Apps are supported by the Chrome browser, but more browsers may support the features needed in the future.
<br><br>
The technical baseline criteria for a site to be considered a Progressive Web App by browsers were described by Russell in a follow-up post:[8]<br>
<br>
Originate from a Secure Origin. Served over TLS and green padlock displays (no active mixed content).<br>
Load while offline (even if only a custom offline page). By implication, this means that Progressive Web Apps require Service Workers.<br>
Reference a Web App Manifest with at least the four key properties: name, short_name, substr_url, and display (with a value of standalone or fullscreen)<br>
An icon at least 144×144 large in png format. E.g.: "icons": [ { "src": "/images/icon-144.png", "sizes": "144x144", "type": "image/png" } ]<br>

</blockquote>

<h1>2.3</h1>
<h2>The Benefits of Offline First</h2>
Offline first means getting as much content as possible from the cache then the internet ONLY IF we get content from the network.
If you do get content from the network, all new information will get stored into the cache.
If you just can't get content from the network, we just use what is in the cache. It might be outdated, but at least it's better than nothing.

<h1>2.4</h1>
<h2>Quiz: What can Slow Us Down</h2>

Pretty much anything might slow down your connection.
This page was pretty much stressing us the importance of offline first.

<h1>2.5</h1>
<h2>Quiz: What Does Online First Look Like</h2>

The quiz website is online first, but if it's offline, it will pull something from the cache for fallback content or special page for offline.

<br>In which of the following conditions will our app work well?</br>
<br>1. Good connection. </br>
<br>2. Bad connection. </br>
<br>3. Offline </br>

Summary: Mike is mainly trying to tell you that offline first is better since online first will struggle horribly on bad connection type of networks.

<h1>2.6</h1>
<h2>Quiz: What are Ways To Be Offline First</h2>


<h1>2.7</h1>
<h2>Introducing the Demo App</h2>


<h1>2.8</h1>
<h2>Quiz: Installing the Demo App</h2>


<h1>2.9</h1>
<h2>Quiz: Running the Demo app</h2>

<h1>2.10</h1>
<h2>Exploring the Demo Apps Code</h2>

<h1>2.11</h1>
<h2>Quiz: Changing Connection Types</h2>

<h1>2.12</h1>
<h2>Quiz: Testing Lie Fi Mode</h2>

<h1>2.13</h1>
<h2>Introducing Service Worker</h2>

</div>
</article>
