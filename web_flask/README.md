<div data-target="readme-toc.content" class="Box-body px-5 pb-5">
            <article class="markdown-body entry-content container-lg" itemprop="text"><h1 dir="auto"><a id="user-content-web-flask" class="anchor" aria-hidden="true" href="#web-flask"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Web Flask</h1>
<p dir="auto">This was a sub-project within AirBnB in which I began working with Flask
and Jinja2. In this project, I began integrating the back-end storage engine
with the web static HTML/CSS pages written earlier.</p>
<p dir="auto">Files 0 - 6 were introductory tasks familiarizing myself with
using Flask. Files 7 forward involved gradually putting together more and more
complex Jinja templates based on the HBnB HTML pages.</p>
<p dir="auto">The most complete Flask/Jinja app-template combo in this directory is defined
in Flask module <a href="/karllucas/AirBnB_clone_v2/blob/master/web_flask/100-hbnb.py">100-hbnb.py</a> and Jinja template
<a href="/karllucas/AirBnB_clone_v2/blob/master/web_flask/100-hbnb.html">100-hbnb.html</a>.</p>
<p dir="auto">To run the Flask app, execute the following command from the root directory
of the project:</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>~ $ HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost
HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m web_flask.100-hbnb
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="~ $ HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost
HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m web_flask.100-hbnb" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">The app can be accessed at <code>0.0.0.0:5000/hbnb</code>.</p>
<p dir="auto">Screenshots:</p>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/bdbaraban/AirBnB_clone_v2/blob/master/assets/hbnb_screenshot_0.png"><img src="https://github.com/bdbaraban/AirBnB_clone_v2/raw/master/assets/hbnb_screenshot_0.png" alt="HolbertonBnB logo" style="max-width: 100%;"></a>
</p>
<hr>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/bdbaraban/AirBnB_clone_v2/blob/master/assets/hbnb_screenshot_1.png"><img src="https://github.com/bdbaraban/AirBnB_clone_v2/raw/master/assets/hbnb_screenshot_1.png" alt="HolbertonBnB logo" style="max-width: 100%;"></a>
</p>
<hr>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/bdbaraban/AirBnB_clone_v2/blob/master/assets/hbnb_screenshot_2.png"><img src="https://github.com/bdbaraban/AirBnB_clone_v2/raw/master/assets/hbnb_screenshot_2.png" alt="HolbertonBnB logo" style="max-width: 100%;"></a>
</p>
</article>
          </div>
