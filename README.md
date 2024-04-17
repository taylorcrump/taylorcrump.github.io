<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taylor Crump - Resume</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 40px;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            text-align: left;
            background-color: #3498db;
            color: #fff;
            padding: 20px;
            border-radius: 8px;
        }

        h1, h2 {
            color: #3498db;
        }

        section {
            margin-bottom: 20px;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
        }

        ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
        }

        li {
            display: inline;
            margin-right: 20px;
        }

        img {
            display: block;
            margin: auto;
            border-radius: 50%;
            margin-top: 20px;
        }

        a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
            background-color: #3498db;
        }

        a:hover {
            background-color: #2980b9;
        }

        .education, .experience, .skills {
            margin-bottom: 30px;
        }
    </style>
</head>
<body>
    <!-- Navigation Links -->
    <ul>
        <li><a href="index.html">Jalen Hurts</a></li>
        <li><a href="#">Resume</a></li>
    </ul>

    <!-- Photo -->
    <img src="Taylor.JPG" height="150" alt="Taylor Crump BYU">

    <header>
        <h1>Taylor Crump</h1>
        <h3>Sales Specialist</h3>
    </header>

    <!-- Mission Statement -->
    <p>Mission Statement: I want to help whoever I work for achieve success</p>

    <!-- LinkedIn Link -->
    <p>See my <a href="https://www.linkedin.com/in/taylorcrump/" target="_blank" title="LinkedIn Page for Taylor Crump">LinkedIn page</a></p>

    <!-- Contact Information -->
    <section class="contact">
        <h2>Contact Information</h2>
        <ul>
            <li>Email: Taylorcrump6@gmail.com</li>
            <li>Phone: (801) 369-9937</li>
            <li>Address: 9862 N Cambridge Ct, Highland UT, 84003</li>
            <li>LinkedIn: linkedin.com/in/taylorcrump</li>
        </ul>
    </section>

    <!-- Education Section -->
    <section class="education">
        <h2 id="edu">Education</h2>
        <ul>
            <li>
                <strong>Brigham Young University</strong> - Bachelor of Finance<br>
                Graduation Date: May 2026
            </li>
        </ul>
    </section>

    <!-- Experience Section -->
    <section class="experience">
        <h2 id="exp">Work Experience</h2>
        <ul>
            <li>
                <strong>Boomcloud</strong> - SDR<br>
                Duration: August 2023 - May 2024<br>
                Responsibilities:
                <ul>
                    <li>Exceeded monthly and quarterly sales targets, earning recognition multiple times for outstanding performance.</li>
                    <li>Execute outbound prospecting strategies to generate and qualify leads, resulting in a 130% increase in sales opportunities within the first quarter.
                    </li>
                </ul>
            </li>
        </ul>
    </section>

    <!-- Skills Section -->
    <section class="skills">
        <h2 id="ski">Skills</h2>
        <ul>
            <li>HTML, CSS, JavaScript</li>
            <li>React, Node.js</li>
            <li>Git, GitHub</li>
            <li>Responsive Web Design</li>
        </ul>

        <a href="#top">Back to Top</a>
    </section>
<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>
</body>
</html>

# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses


[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
