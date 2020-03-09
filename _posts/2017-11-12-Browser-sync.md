---
layout: post
title: 'Using Browser-sync'
date: 2017-11-12
author: Christina
lang: en
tags: TOOLS
---

---

What is [Browser-sync](https://www.browsersync.io/ )？

### 1. Installing Node.js & Browser-sync    

*Browser-sync* depends on *Node.js* (or simply "*Node*") , so you need to install *Node* firstly by downloading the installer from *[nodejs.org](https://nodejs.org/en/)*. And then install *browser-sync* using this command at the command line:


<pre><code class="language-css">npm install -g browser-sync</code></pre>


### 2. Using Browser-sync 

Open the terminal and change directory to your working folder:

<pre><code class="language-css">cd /Users/xhz1/Desktop/poi</code></pre>

If Chrome is your default browser:
<pre><code class="language-css">browser-sync start --server --files "stylesheets/*.css, *.html"</code></pre>     

Or not:
<pre><code class="language-css">browser-sync start --server --browser "Google Chrome"
                          --files "stylesheets/*.css, *.html"</code></pre>   
### 3. Quit Browser-sync 


<pre><code class="language-css">ctrl+c</code></pre>

 