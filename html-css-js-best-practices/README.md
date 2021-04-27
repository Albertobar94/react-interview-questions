<article class="markdown-body entry-content container-lg" itemprop="text"><h1><a id="user-content-frontend-guidelines" class="anchor" aria-hidden="true" href="#frontend-guidelines"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Frontend Guidelines</h1>
<h2><a id="user-content-html" class="anchor" aria-hidden="true" href="#html"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>HTML</h2>
<h3><a id="user-content-semantics" class="anchor" aria-hidden="true" href="#semantics"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Semantics</h3>
<p>HTML5 provides us with lots of semantic elements aimed to describe precisely the content. Make sure you benefit from its rich vocabulary.</p>
<div class="highlight highlight-text-html-basic"><pre><span class="pl-c">&lt;!-- bad --&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">div</span> <span class="pl-c1">id</span>=<span class="pl-s">main</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">div</span> <span class="pl-c1">class</span>=<span class="pl-s">article</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">div</span> <span class="pl-c1">class</span>=<span class="pl-s">header</span><span class="pl-kos">&gt;</span>
      <span class="pl-kos">&lt;</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>Blog post<span class="pl-kos">&lt;/</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>
      <span class="pl-kos">&lt;</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>Published: <span class="pl-kos">&lt;</span><span class="pl-ent">span</span><span class="pl-kos">&gt;</span>21st Feb, 2015<span class="pl-kos">&lt;/</span><span class="pl-ent">span</span><span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;/</span><span class="pl-ent">div</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>…<span class="pl-kos">&lt;/</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;/</span><span class="pl-ent">div</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;/</span><span class="pl-ent">div</span><span class="pl-kos">&gt;</span>

<span class="pl-c">&lt;!-- good --&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">main</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">article</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">header</span><span class="pl-kos">&gt;</span>
      <span class="pl-kos">&lt;</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>Blog post<span class="pl-kos">&lt;/</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>
      <span class="pl-kos">&lt;</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>Published: <span class="pl-kos">&lt;</span><span class="pl-ent">time</span> <span class="pl-c1">datetime</span>=<span class="pl-s">2015-02-21</span><span class="pl-kos">&gt;</span>21st Feb, 2015<span class="pl-kos">&lt;/</span><span class="pl-ent">time</span><span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;/</span><span class="pl-ent">header</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>…<span class="pl-kos">&lt;/</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;/</span><span class="pl-ent">article</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;/</span><span class="pl-ent">main</span><span class="pl-kos">&gt;</span></pre></div>
<p>Make sure you understand the semantics of the elements you're using. It's worse to use a semantic
element in a wrong way than staying neutral.</p>
<div class="highlight highlight-text-html-basic"><pre><span class="pl-c">&lt;!-- bad --&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">figure</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">img</span> <span class="pl-c1">alt</span>=<span class="pl-s">Company</span> <span class="pl-c1">src</span>=<span class="pl-s">logo.png</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;/</span><span class="pl-ent">figure</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;/</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>

<span class="pl-c">&lt;!-- good --&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">img</span> <span class="pl-c1">alt</span>=<span class="pl-s">Company</span> <span class="pl-c1">src</span>=<span class="pl-s">logo.png</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;/</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span></pre></div>
<h3><a id="user-content-brevity" class="anchor" aria-hidden="true" href="#brevity"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Brevity</h3>
<p>Keep your code terse. Forget about your old XHTML habits.</p>
<div class="highlight highlight-text-html-basic"><pre><span class="pl-c">&lt;!-- bad --&gt;</span>
<span class="pl-c1">&lt;!doctype html<span class="pl-kos">&gt;</span></span>
<span class="pl-kos">&lt;</span><span class="pl-ent">html</span> <span class="pl-c1">lang</span>=<span class="pl-s">en</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">head</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">meta</span> <span class="pl-c1">http-equiv</span>=<span class="pl-s">Content-Type</span> <span class="pl-c1">content</span>="<span class="pl-s">text/html; charset=utf-8</span>" /&gt;
    <span class="pl-kos">&lt;</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>Contact<span class="pl-kos">&lt;/</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">link</span> <span class="pl-c1">rel</span>=<span class="pl-s">stylesheet</span> <span class="pl-c1">href</span>=<span class="pl-s">style.css</span> <span class="pl-c1">type</span>=<span class="pl-s">text/css</span> /&gt;
  <span class="pl-kos">&lt;/</span><span class="pl-ent">head</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">body</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>Contact me<span class="pl-kos">&lt;/</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">label</span><span class="pl-kos">&gt;</span>
      Email address:
      <span class="pl-kos">&lt;</span><span class="pl-ent">input</span> <span class="pl-c1">type</span>=<span class="pl-s">email</span> <span class="pl-c1">placeholder</span>=<span class="pl-s">you@email.com</span> <span class="pl-c1">required</span>=<span class="pl-s">required</span> /&gt;
    <span class="pl-kos">&lt;/</span><span class="pl-ent">label</span><span class="pl-kos">&gt;</span>
    <span class="pl-kos">&lt;</span><span class="pl-ent">script</span> <span class="pl-c1">src</span>=<span class="pl-s">main.js</span> <span class="pl-c1">type</span>=<span class="pl-s">text/javascript</span><span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">script</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;/</span><span class="pl-ent">body</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;/</span><span class="pl-ent">html</span><span class="pl-kos">&gt;</span>

<span class="pl-c">&lt;!-- good --&gt;</span>
<span class="pl-c1">&lt;!doctype html<span class="pl-kos">&gt;</span></span>
<span class="pl-kos">&lt;</span><span class="pl-ent">html</span> <span class="pl-c1">lang</span>=<span class="pl-s">en</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">meta</span> <span class="pl-c1">charset</span>=<span class="pl-s">utf-8</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>Contact<span class="pl-kos">&lt;/</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">link</span> <span class="pl-c1">rel</span>=<span class="pl-s">stylesheet</span> <span class="pl-c1">href</span>=<span class="pl-s">style.css</span><span class="pl-kos">&gt;</span>

  <span class="pl-kos">&lt;</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>Contact me<span class="pl-kos">&lt;/</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">label</span><span class="pl-kos">&gt;</span>
    Email address:
    <span class="pl-kos">&lt;</span><span class="pl-ent">input</span> <span class="pl-c1">type</span>=<span class="pl-s">email</span> <span class="pl-c1">placeholder</span>=<span class="pl-s">you@email.com</span> <span class="pl-c1">required</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;/</span><span class="pl-ent">label</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">script</span> <span class="pl-c1">src</span>=<span class="pl-s">main.js</span><span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">script</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;/</span><span class="pl-ent">html</span><span class="pl-kos">&gt;</span></pre></div>
<h3><a id="user-content-accessibility" class="anchor" aria-hidden="true" href="#accessibility"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Accessibility</h3>
<p>Accessibility shouldn't be an afterthought. You don't have to be a WCAG expert to improve your
website, you can start immediately by fixing the little things that make a huge difference, such as:</p>
<ul>
<li>learning to use the <code>alt</code> attribute properly</li>
<li>making sure your links and buttons are marked as such (no <code>&lt;div class=button&gt;</code> atrocities)</li>
<li>not relying exclusively on colors to communicate information</li>
<li>explicitly labelling form controls</li>
</ul>
<div class="highlight highlight-text-html-basic"><pre><span class="pl-c">&lt;!-- bad --&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span><span class="pl-kos">&lt;</span><span class="pl-ent">img</span> <span class="pl-c1">alt</span>=<span class="pl-s">Logo</span> <span class="pl-c1">src</span>=<span class="pl-s">logo.png</span><span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span>

<span class="pl-c">&lt;!-- good --&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span><span class="pl-kos">&lt;</span><span class="pl-ent">img</span> <span class="pl-c1">alt</span>=<span class="pl-s">Company</span> <span class="pl-c1">src</span>=<span class="pl-s">logo.png</span><span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">h1</span><span class="pl-kos">&gt;</span></pre></div>
<h3><a id="user-content-language--character-encoding" class="anchor" aria-hidden="true" href="#language--character-encoding"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Language &amp; character encoding</h3>
<p>While defining the language is optional, it's recommended to always declare
it on the root element.</p>
<p>The HTML standard requires that pages use the UTF-8 character encoding.
It has to be declared, and although it can be declared in the Content-Type HTTP header,
it is recommended to always declare it at the document level.</p>
<div class="highlight highlight-text-html-basic"><pre><span class="pl-c">&lt;!-- bad --&gt;</span>
<span class="pl-c1">&lt;!doctype html<span class="pl-kos">&gt;</span></span>
<span class="pl-kos">&lt;</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>Hello, world.<span class="pl-kos">&lt;/</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>

<span class="pl-c">&lt;!-- good --&gt;</span>
<span class="pl-c1">&lt;!doctype html<span class="pl-kos">&gt;</span></span>
<span class="pl-kos">&lt;</span><span class="pl-ent">html</span> <span class="pl-c1">lang</span>=<span class="pl-s">en</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">meta</span> <span class="pl-c1">charset</span>=<span class="pl-s">utf-8</span><span class="pl-kos">&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>Hello, world.<span class="pl-kos">&lt;/</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;/</span><span class="pl-ent">html</span><span class="pl-kos">&gt;</span></pre></div>
<h3><a id="user-content-performance" class="anchor" aria-hidden="true" href="#performance"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Performance</h3>
<p>Unless there's a valid reason for loading your scripts before your content, don't block the
rendering of your page. If your style sheet is heavy, isolate the styles that are absolutely
required initially and defer the loading of the secondary declarations in a separate style sheet.
Two HTTP requests is significantly slower than one, but the perception of speed is the most
important factor.</p>
<div class="highlight highlight-text-html-basic"><pre><span class="pl-c">&lt;!-- bad --&gt;</span>
<span class="pl-c1">&lt;!doctype html<span class="pl-kos">&gt;</span></span>
<span class="pl-kos">&lt;</span><span class="pl-ent">meta</span> <span class="pl-c1">charset</span>=<span class="pl-s">utf-8</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">script</span> <span class="pl-c1">src</span>=<span class="pl-s">analytics.js</span><span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">script</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>Hello, world.<span class="pl-kos">&lt;/</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>...<span class="pl-kos">&lt;/</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>

<span class="pl-c">&lt;!-- good --&gt;</span>
<span class="pl-c1">&lt;!doctype html<span class="pl-kos">&gt;</span></span>
<span class="pl-kos">&lt;</span><span class="pl-ent">meta</span> <span class="pl-c1">charset</span>=<span class="pl-s">utf-8</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>Hello, world.<span class="pl-kos">&lt;/</span><span class="pl-ent">title</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>...<span class="pl-kos">&lt;/</span><span class="pl-ent">p</span><span class="pl-kos">&gt;</span>
<span class="pl-kos">&lt;</span><span class="pl-ent">script</span> <span class="pl-c1">src</span>=<span class="pl-s">analytics.js</span><span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">script</span><span class="pl-kos">&gt;</span></pre></div>
<h2><a id="user-content-css" class="anchor" aria-hidden="true" href="#css"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>CSS</h2>
<h3><a id="user-content-semicolons" class="anchor" aria-hidden="true" href="#semicolons"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Semicolons</h3>
<p>While the semicolon is technically a separator in CSS, always treat it as a terminator.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">color</span><span class="pl-kos">:</span> red
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">color</span><span class="pl-kos">:</span> red;
}</pre></div>
<h3><a id="user-content-box-model" class="anchor" aria-hidden="true" href="#box-model"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Box model</h3>
<p>The box model should ideally be the same for the entire document. A global
<code>* { box-sizing: border-box; }</code> is fine, but don't change the default box model
on specific elements if you can avoid it.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">width</span><span class="pl-kos">:</span> <span class="pl-c1">100<span class="pl-smi">%</span></span>;
  <span class="pl-c1">padding</span><span class="pl-kos">:</span> <span class="pl-c1">10<span class="pl-smi">px</span></span>;
  <span class="pl-c1">box-sizing</span><span class="pl-kos">:</span> border-box;
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">padding</span><span class="pl-kos">:</span> <span class="pl-c1">10<span class="pl-smi">px</span></span>;
}</pre></div>
<h3><a id="user-content-flow" class="anchor" aria-hidden="true" href="#flow"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Flow</h3>
<p>Don't change the default behavior of an element if you can avoid it. Keep elements in the
natural document flow as much as you can. For example, removing the white-space below an
image shouldn't make you change its default display:</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">img</span> {
  <span class="pl-c1">display</span><span class="pl-kos">:</span> block;
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">img</span> {
  <span class="pl-c1">vertical-align</span><span class="pl-kos">:</span> middle;
}</pre></div>
<p>Similarly, don't take an element off the flow if you can avoid it.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">width</span><span class="pl-kos">:</span> <span class="pl-c1">100<span class="pl-smi">px</span></span>;
  <span class="pl-c1">position</span><span class="pl-kos">:</span> absolute;
  <span class="pl-c1">right</span><span class="pl-kos">:</span> <span class="pl-c1">0</span>;
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">width</span><span class="pl-kos">:</span> <span class="pl-c1">100<span class="pl-smi">px</span></span>;
  <span class="pl-c1">margin-left</span><span class="pl-kos">:</span> auto;
}</pre></div>
<h3><a id="user-content-positioning" class="anchor" aria-hidden="true" href="#positioning"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Positioning</h3>
<p>There are many ways to position elements in CSS. Favor modern layout specifications
such as Flexbox and Grid, and avoid removing elements from the normal document flow, for example
with <code>position: absolute</code>.</p>
<h3><a id="user-content-selectors" class="anchor" aria-hidden="true" href="#selectors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Selectors</h3>
<p>Minimize selectors tightly coupled to the DOM. Consider adding a class to the elements
you want to match when your selector exceeds 3 structural pseudo-classes, descendant or
sibling combinators.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span><span class="pl-kos">:</span><span class="pl-c1">first-of-type</span> <span class="pl-kos">:</span><span class="pl-c1">last-child</span> <span class="pl-c1">&gt;</span> <span class="pl-ent">p</span> <span class="pl-c1">~</span> <span class="pl-ent"><span class="pl-c1">*</span></span>

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span><span class="pl-kos">:</span><span class="pl-c1">first-of-type</span> .<span class="pl-c1">info</span></pre></div>
<p>Avoid overloading your selectors when you don't need to.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">img</span>[<span class="pl-c1">src</span><span class="pl-c1">$=</span><span class="pl-s">svg</span>]<span class="pl-kos">,</span> <span class="pl-ent">ul</span> <span class="pl-c1">&gt;</span> <span class="pl-ent">li</span><span class="pl-kos">:</span><span class="pl-c1">first-child</span> {
  <span class="pl-c1">opacity</span><span class="pl-kos">:</span> <span class="pl-c1">0</span>;
}

<span class="pl-c">/* good */</span>
[<span class="pl-c1">src</span><span class="pl-c1">$=</span><span class="pl-s">svg</span>]<span class="pl-kos">,</span> <span class="pl-ent">ul</span> <span class="pl-c1">&gt;</span> <span class="pl-kos">:</span><span class="pl-c1">first-child</span> {
  <span class="pl-c1">opacity</span><span class="pl-kos">:</span> <span class="pl-c1">0</span>;
}</pre></div>
<h3><a id="user-content-specificity" class="anchor" aria-hidden="true" href="#specificity"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Specificity</h3>
<p>Don't make values and selectors hard to override. Minimize the use of <code>id</code>'s
and avoid <code>!important</code>.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
.<span class="pl-c1">bar</span> {
  <span class="pl-c1">color</span><span class="pl-kos">:</span> green <span class="pl-k">!important</span>;
}
.<span class="pl-c1">foo</span> {
  <span class="pl-c1">color</span><span class="pl-kos">:</span> red;
}

<span class="pl-c">/* good */</span>
.<span class="pl-c1">foo</span>.<span class="pl-c1">bar</span> {
  <span class="pl-c1">color</span><span class="pl-kos">:</span> green;
}
.<span class="pl-c1">foo</span> {
  <span class="pl-c1">color</span><span class="pl-kos">:</span> red;
}</pre></div>
<h3><a id="user-content-overriding" class="anchor" aria-hidden="true" href="#overriding"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Overriding</h3>
<p>Overriding styles makes selectors and debugging harder. Avoid it when possible.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">li</span> {
  <span class="pl-c1">visibility</span><span class="pl-kos">:</span> hidden;
}
<span class="pl-ent">li</span><span class="pl-kos">:</span><span class="pl-c1">first-child</span> {
  <span class="pl-c1">visibility</span><span class="pl-kos">:</span> visible;
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">li</span> <span class="pl-c1">+</span> <span class="pl-ent">li</span> {
  <span class="pl-c1">visibility</span><span class="pl-kos">:</span> hidden;
}</pre></div>
<h3><a id="user-content-inheritance" class="anchor" aria-hidden="true" href="#inheritance"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Inheritance</h3>
<p>Don't duplicate style declarations that can be inherited.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span> <span class="pl-ent">h1</span><span class="pl-kos">,</span> <span class="pl-ent">div</span> <span class="pl-ent">p</span> {
  <span class="pl-c1">text-shadow</span><span class="pl-kos">:</span> <span class="pl-c1">0</span> <span class="pl-c1">1<span class="pl-smi">px</span></span> <span class="pl-c1">0</span> <span class="pl-pds"><span class="pl-kos">#</span>fff</span>;
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">text-shadow</span><span class="pl-kos">:</span> <span class="pl-c1">0</span> <span class="pl-c1">1<span class="pl-smi">px</span></span> <span class="pl-c1">0</span> <span class="pl-pds"><span class="pl-kos">#</span>fff</span>;
}</pre></div>
<h3><a id="user-content-brevity-1" class="anchor" aria-hidden="true" href="#brevity-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Brevity</h3>
<p>Keep your code terse. Use shorthand properties and avoid using multiple properties when
it's not needed.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">transition</span><span class="pl-kos">:</span> all <span class="pl-c1">1<span class="pl-smi">s</span></span>;
  <span class="pl-c1">top</span><span class="pl-kos">:</span> <span class="pl-c1">50<span class="pl-smi">%</span></span>;
  <span class="pl-c1">margin-top</span><span class="pl-kos">:</span> <span class="pl-c1">-10<span class="pl-smi">px</span></span>;
  <span class="pl-c1">padding-top</span><span class="pl-kos">:</span> <span class="pl-c1">5<span class="pl-smi">px</span></span>;
  <span class="pl-c1">padding-right</span><span class="pl-kos">:</span> <span class="pl-c1">10<span class="pl-smi">px</span></span>;
  <span class="pl-c1">padding-bottom</span><span class="pl-kos">:</span> <span class="pl-c1">20<span class="pl-smi">px</span></span>;
  <span class="pl-c1">padding-left</span><span class="pl-kos">:</span> <span class="pl-c1">10<span class="pl-smi">px</span></span>;
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">transition</span><span class="pl-kos">:</span> <span class="pl-c1">1<span class="pl-smi">s</span></span>;
  <span class="pl-c1">top</span><span class="pl-kos">:</span> <span class="pl-en">calc</span>(<span class="pl-c1">50<span class="pl-smi">%</span></span> <span class="pl-c1">-</span> <span class="pl-c1">10<span class="pl-smi">px</span></span>);
  <span class="pl-c1">padding</span><span class="pl-kos">:</span> <span class="pl-c1">5<span class="pl-smi">px</span></span> <span class="pl-c1">10<span class="pl-smi">px</span></span> <span class="pl-c1">20<span class="pl-smi">px</span></span>;
}</pre></div>
<h3><a id="user-content-language" class="anchor" aria-hidden="true" href="#language"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Language</h3>
<p>Prefer English over math.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-kos">:</span><span class="pl-c1">nth-child</span>(<span class="pl-c1">2<span class="pl-smi">n</span></span> <span class="pl-c1">+</span> <span class="pl-c1">1</span>) {
  <span class="pl-c1">transform</span><span class="pl-kos">:</span> <span class="pl-en">rotate</span>(<span class="pl-c1">360<span class="pl-smi">deg</span></span>);
}

<span class="pl-c">/* good */</span>
<span class="pl-kos">:</span><span class="pl-c1">nth-child</span>(<span class="pl-ent">odd</span>) {
  <span class="pl-c1">transform</span><span class="pl-kos">:</span> <span class="pl-en">rotate</span>(<span class="pl-c1">1<span class="pl-smi">turn</span></span>);
}</pre></div>
<h3><a id="user-content-vendor-prefixes" class="anchor" aria-hidden="true" href="#vendor-prefixes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Vendor prefixes</h3>
<p>Kill obsolete vendor prefixes aggressively. If you need to use them, insert them before the
standard property.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">transform</span><span class="pl-kos">:</span> <span class="pl-en">scale</span>(<span class="pl-c1">2</span>);
  <span class="pl-c1">-webkit-transform</span><span class="pl-kos">:</span> <span class="pl-en">scale</span>(<span class="pl-c1">2</span>);
  <span class="pl-c1">-moz-transform</span><span class="pl-kos">:</span> <span class="pl-en">scale</span>(<span class="pl-c1">2</span>);
  <span class="pl-c1">-ms-transform</span><span class="pl-kos">:</span> <span class="pl-en">scale</span>(<span class="pl-c1">2</span>);
  <span class="pl-c1">transition</span><span class="pl-kos">:</span> <span class="pl-c1">1<span class="pl-smi">s</span></span>;
  <span class="pl-c1">-webkit-transition</span><span class="pl-kos">:</span> <span class="pl-c1">1<span class="pl-smi">s</span></span>;
  <span class="pl-c1">-moz-transition</span><span class="pl-kos">:</span> <span class="pl-c1">1<span class="pl-smi">s</span></span>;
  <span class="pl-c1">-ms-transition</span><span class="pl-kos">:</span> <span class="pl-c1">1<span class="pl-smi">s</span></span>;
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">-webkit-transform</span><span class="pl-kos">:</span> <span class="pl-en">scale</span>(<span class="pl-c1">2</span>);
  <span class="pl-c1">transform</span><span class="pl-kos">:</span> <span class="pl-en">scale</span>(<span class="pl-c1">2</span>);
  <span class="pl-c1">transition</span><span class="pl-kos">:</span> <span class="pl-c1">1<span class="pl-smi">s</span></span>;
}</pre></div>
<h3><a id="user-content-animations" class="anchor" aria-hidden="true" href="#animations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Animations</h3>
<p>Favor transitions over animations. Avoid animating other properties than
<code>opacity</code> and <code>transform</code>.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span><span class="pl-kos">:</span><span class="pl-c1">hover</span> {
  <span class="pl-c1">animation</span><span class="pl-kos">:</span> move <span class="pl-c1">1<span class="pl-smi">s</span></span> forwards;
}
<span class="pl-k">@keyframes</span> move {
  <span class="pl-c1">100<span class="pl-smi">%</span></span> {
    <span class="pl-c1">margin-left</span><span class="pl-kos">:</span> <span class="pl-c1">100<span class="pl-smi">px</span></span>;
  }
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span><span class="pl-kos">:</span><span class="pl-c1">hover</span> {
  <span class="pl-c1">transition</span><span class="pl-kos">:</span> <span class="pl-c1">1<span class="pl-smi">s</span></span>;
  <span class="pl-c1">transform</span><span class="pl-kos">:</span> <span class="pl-en">translateX</span>(<span class="pl-c1">100<span class="pl-smi">px</span></span>);
}</pre></div>
<h3><a id="user-content-units" class="anchor" aria-hidden="true" href="#units"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Units</h3>
<p>Use unitless values when you can. Favor <code>rem</code> if you use relative units. Prefer seconds over
milliseconds.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">margin</span><span class="pl-kos">:</span> <span class="pl-c1">0<span class="pl-smi">px</span></span>;
  <span class="pl-c1">font-size</span><span class="pl-kos">:</span> <span class="pl-c1">.9<span class="pl-smi">em</span></span>;
  <span class="pl-c1">line-height</span><span class="pl-kos">:</span> <span class="pl-c1">22<span class="pl-smi">px</span></span>;
  <span class="pl-c1">transition</span><span class="pl-kos">:</span> <span class="pl-c1">500<span class="pl-smi">ms</span></span>;
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">margin</span><span class="pl-kos">:</span> <span class="pl-c1">0</span>;
  <span class="pl-c1">font-size</span><span class="pl-kos">:</span> <span class="pl-c1">.9<span class="pl-smi">rem</span></span>;
  <span class="pl-c1">line-height</span><span class="pl-kos">:</span> <span class="pl-c1">1.5</span>;
  <span class="pl-c1">transition</span><span class="pl-kos">:</span> <span class="pl-c1">.5<span class="pl-smi">s</span></span>;
}</pre></div>
<h3><a id="user-content-colors" class="anchor" aria-hidden="true" href="#colors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Colors</h3>
<p>If you need transparency, use <code>rgba</code>. Otherwise, always use the hexadecimal format.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">color</span><span class="pl-kos">:</span> <span class="pl-en">hsl</span>(<span class="pl-c1">103</span><span class="pl-kos">,</span> <span class="pl-c1">54<span class="pl-smi">%</span></span><span class="pl-kos">,</span> <span class="pl-c1">43<span class="pl-smi">%</span></span>);
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">color</span><span class="pl-kos">:</span> <span class="pl-pds"><span class="pl-kos">#</span>5a3</span>;
}</pre></div>
<h3><a id="user-content-drawing" class="anchor" aria-hidden="true" href="#drawing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Drawing</h3>
<p>Avoid HTTP requests when the resources are easily replicable with CSS.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span>::<span class="pl-ent">before</span> {
  <span class="pl-c1">content</span><span class="pl-kos">:</span> <span class="pl-en">url</span>(white-circle.svg);
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span>::<span class="pl-ent">before</span> {
  <span class="pl-c1">content</span><span class="pl-kos">:</span> <span class="pl-s">""</span>;
  <span class="pl-c1">display</span><span class="pl-kos">:</span> block;
  <span class="pl-c1">width</span><span class="pl-kos">:</span> <span class="pl-c1">20<span class="pl-smi">px</span></span>;
  <span class="pl-c1">height</span><span class="pl-kos">:</span> <span class="pl-c1">20<span class="pl-smi">px</span></span>;
  <span class="pl-c1">border-radius</span><span class="pl-kos">:</span> <span class="pl-c1">50<span class="pl-smi">%</span></span>;
  <span class="pl-c1">background</span><span class="pl-kos">:</span> <span class="pl-pds"><span class="pl-kos">#</span>fff</span>;
}</pre></div>
<h3><a id="user-content-hacks" class="anchor" aria-hidden="true" href="#hacks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Hacks</h3>
<p>Don't use them.</p>
<div class="highlight highlight-source-css"><pre><span class="pl-c">/* bad */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c1">/</span><span class="pl-c1">/</span> position<span class="pl-kos">:</span> <span class="pl-c1">relative</span>;
  <span class="pl-ent">transform</span><span class="pl-kos">:</span> <span class="pl-c1">translateZ</span>(<span class="pl-c1">0</span>);
}

<span class="pl-c">/* good */</span>
<span class="pl-ent">div</span> {
  <span class="pl-c">/* position: relative; */</span>
  <span class="pl-c1">will-change</span><span class="pl-kos">:</span> transform;
}</pre></div>
<h2><a id="user-content-javascript" class="anchor" aria-hidden="true" href="#javascript"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>JavaScript</h2>
<h3><a id="user-content-performance-1" class="anchor" aria-hidden="true" href="#performance-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Performance</h3>
<p>Favor readability, correctness and expressiveness over performance. JavaScript will basically never
be your performance bottleneck. Optimize things like image compression, network access and DOM
reflows instead. If you remember just one guideline from this document, choose this one.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad (albeit way faster)</span>
<span class="pl-k">const</span> <span class="pl-s1">arr</span> <span class="pl-c1">=</span> <span class="pl-kos">[</span><span class="pl-c1">1</span><span class="pl-kos">,</span> <span class="pl-c1">2</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">,</span> <span class="pl-c1">4</span><span class="pl-kos">]</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-s1">len</span> <span class="pl-c1">=</span> <span class="pl-s1">arr</span><span class="pl-kos">.</span><span class="pl-c1">length</span><span class="pl-kos">;</span>
<span class="pl-k">var</span> <span class="pl-s1">i</span> <span class="pl-c1">=</span> <span class="pl-c1">-</span><span class="pl-c1">1</span><span class="pl-kos">;</span>
<span class="pl-k">var</span> <span class="pl-s1">result</span> <span class="pl-c1">=</span> <span class="pl-kos">[</span><span class="pl-kos">]</span><span class="pl-kos">;</span>
<span class="pl-k">while</span> <span class="pl-kos">(</span><span class="pl-c1">++</span><span class="pl-s1">i</span> <span class="pl-c1">&lt;</span> <span class="pl-s1">len</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
  <span class="pl-k">var</span> <span class="pl-s1">n</span> <span class="pl-c1">=</span> <span class="pl-s1">arr</span><span class="pl-kos">[</span><span class="pl-s1">i</span><span class="pl-kos">]</span><span class="pl-kos">;</span>
  <span class="pl-k">if</span> <span class="pl-kos">(</span><span class="pl-s1">n</span> <span class="pl-c1">%</span> <span class="pl-c1">2</span> <span class="pl-c1">&gt;</span> <span class="pl-c1">0</span><span class="pl-kos">)</span> <span class="pl-k">continue</span><span class="pl-kos">;</span>
  <span class="pl-s1">result</span><span class="pl-kos">.</span><span class="pl-en">push</span><span class="pl-kos">(</span><span class="pl-s1">n</span> <span class="pl-c1">*</span> <span class="pl-s1">n</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-s1">arr</span> <span class="pl-c1">=</span> <span class="pl-kos">[</span><span class="pl-c1">1</span><span class="pl-kos">,</span> <span class="pl-c1">2</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">,</span> <span class="pl-c1">4</span><span class="pl-kos">]</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-en">isEven</span> <span class="pl-c1">=</span> <span class="pl-s1">n</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">n</span> <span class="pl-c1">%</span> <span class="pl-c1">2</span> <span class="pl-c1">==</span> <span class="pl-c1">0</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-en">square</span> <span class="pl-c1">=</span> <span class="pl-s1">n</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">n</span> <span class="pl-c1">*</span> <span class="pl-s1">n</span><span class="pl-kos">;</span>

<span class="pl-k">const</span> <span class="pl-s1">result</span> <span class="pl-c1">=</span> <span class="pl-s1">arr</span><span class="pl-kos">.</span><span class="pl-en">filter</span><span class="pl-kos">(</span><span class="pl-en">isEven</span><span class="pl-kos">)</span><span class="pl-kos">.</span><span class="pl-en">map</span><span class="pl-kos">(</span><span class="pl-en">square</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<h3><a id="user-content-statelessness" class="anchor" aria-hidden="true" href="#statelessness"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Statelessness</h3>
<p>Try to keep your functions pure. All functions should ideally produce no side-effects, use no outside data and return new objects instead of mutating existing ones.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-en">merge</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-s1">target</span><span class="pl-kos">,</span> ...<span class="pl-s1">sources</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-v">Object</span><span class="pl-kos">.</span><span class="pl-en">assign</span><span class="pl-kos">(</span><span class="pl-s1">target</span><span class="pl-kos">,</span> ...<span class="pl-s1">sources</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-en">merge</span><span class="pl-kos">(</span><span class="pl-kos">{</span> <span class="pl-c1">foo</span>: <span class="pl-s">"foo"</span> <span class="pl-kos">}</span><span class="pl-kos">,</span> <span class="pl-kos">{</span> <span class="pl-c1">bar</span>: <span class="pl-s">"bar"</span> <span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; { foo: "foo", bar: "bar" }</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-en">merge</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span>...<span class="pl-s1">sources</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-v">Object</span><span class="pl-kos">.</span><span class="pl-en">assign</span><span class="pl-kos">(</span><span class="pl-kos">{</span><span class="pl-kos">}</span><span class="pl-kos">,</span> ...<span class="pl-s1">sources</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-en">merge</span><span class="pl-kos">(</span><span class="pl-kos">{</span> <span class="pl-c1">foo</span>: <span class="pl-s">"foo"</span> <span class="pl-kos">}</span><span class="pl-kos">,</span> <span class="pl-kos">{</span> <span class="pl-c1">bar</span>: <span class="pl-s">"bar"</span> <span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; { foo: "foo", bar: "bar" }</span></pre></div>
<h3><a id="user-content-natives" class="anchor" aria-hidden="true" href="#natives"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Natives</h3>
<p>Rely on native methods as much as possible.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-en">toArray</span> <span class="pl-c1">=</span> <span class="pl-s1">obj</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">[</span><span class="pl-kos">]</span><span class="pl-kos">.</span><span class="pl-c1">slice</span><span class="pl-kos">.</span><span class="pl-en">call</span><span class="pl-kos">(</span><span class="pl-s1">obj</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-s1">toArray</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span>
  <span class="pl-v">Array</span><span class="pl-kos">.</span><span class="pl-c1">from</span> ? <span class="pl-v">Array</span><span class="pl-kos">.</span><span class="pl-c1">from</span> : <span class="pl-s1">obj</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">[</span><span class="pl-kos">]</span><span class="pl-kos">.</span><span class="pl-c1">slice</span><span class="pl-kos">.</span><span class="pl-en">call</span><span class="pl-kos">(</span><span class="pl-s1">obj</span><span class="pl-kos">)</span>
<span class="pl-kos">)</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<h3><a id="user-content-coercion" class="anchor" aria-hidden="true" href="#coercion"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Coercion</h3>
<p>Embrace implicit coercion when it makes sense. Avoid it otherwise. Don't cargo-cult.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">if</span> <span class="pl-kos">(</span><span class="pl-s1">x</span> <span class="pl-c1">===</span> <span class="pl-c1">undefined</span> <span class="pl-c1">||</span> <span class="pl-s1">x</span> <span class="pl-c1">===</span> <span class="pl-c1">null</span><span class="pl-kos">)</span> <span class="pl-kos">{</span> ... <span class="pl-kos">}</span>

<span class="pl-c">// good</span>
<span class="pl-k">if</span> <span class="pl-kos">(</span><span class="pl-s1">x</span> <span class="pl-c1">==</span> <span class="pl-c1">undefined</span><span class="pl-kos">)</span> <span class="pl-kos">{</span> ... <span class="pl-kos">}</span></pre></div>
<h3><a id="user-content-loops" class="anchor" aria-hidden="true" href="#loops"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Loops</h3>
<p>Don't use loops as they force you to use mutable objects. Rely on <code>array.prototype</code> methods.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-en">sum</span> <span class="pl-c1">=</span> <span class="pl-s1">arr</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">{</span>
  <span class="pl-k">var</span> <span class="pl-s1">sum</span> <span class="pl-c1">=</span> <span class="pl-c1">0</span><span class="pl-kos">;</span>
  <span class="pl-k">var</span> <span class="pl-s1">i</span> <span class="pl-c1">=</span> <span class="pl-c1">-</span><span class="pl-c1">1</span><span class="pl-kos">;</span>
  <span class="pl-k">for</span> <span class="pl-kos">(</span><span class="pl-kos">;</span><span class="pl-s1">arr</span><span class="pl-kos">[</span><span class="pl-c1">++</span><span class="pl-s1">i</span><span class="pl-kos">]</span><span class="pl-kos">;</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
    <span class="pl-s1">sum</span> <span class="pl-c1">+=</span> <span class="pl-s1">arr</span><span class="pl-kos">[</span><span class="pl-s1">i</span><span class="pl-kos">]</span><span class="pl-kos">;</span>
  <span class="pl-kos">}</span>
  <span class="pl-k">return</span> <span class="pl-s1">sum</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span><span class="pl-kos">;</span>

<span class="pl-en">sum</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-c1">1</span><span class="pl-kos">,</span> <span class="pl-c1">2</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">]</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; 6</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-en">sum</span> <span class="pl-c1">=</span> <span class="pl-s1">arr</span> <span class="pl-c1">=&gt;</span>
  <span class="pl-s1">arr</span><span class="pl-kos">.</span><span class="pl-en">reduce</span><span class="pl-kos">(</span><span class="pl-kos">(</span><span class="pl-s1">x</span><span class="pl-kos">,</span> <span class="pl-s1">y</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">x</span> <span class="pl-c1">+</span> <span class="pl-s1">y</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-en">sum</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-c1">1</span><span class="pl-kos">,</span> <span class="pl-c1">2</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">]</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; 6</span></pre></div>
<p>If you can't, or if using <code>array.prototype</code> methods is arguably abusive, use recursion.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-en">createDivs</span> <span class="pl-c1">=</span> <span class="pl-s1">howMany</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">{</span>
  <span class="pl-k">while</span> <span class="pl-kos">(</span><span class="pl-s1">howMany</span><span class="pl-c1">--</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
    <span class="pl-smi">document</span><span class="pl-kos">.</span><span class="pl-c1">body</span><span class="pl-kos">.</span><span class="pl-en">insertAdjacentHTML</span><span class="pl-kos">(</span><span class="pl-s">"beforeend"</span><span class="pl-kos">,</span> <span class="pl-s">"&lt;div&gt;&lt;/div&gt;"</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
  <span class="pl-kos">}</span>
<span class="pl-kos">}</span><span class="pl-kos">;</span>
<span class="pl-en">createDivs</span><span class="pl-kos">(</span><span class="pl-c1">5</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-en">createDivs</span> <span class="pl-c1">=</span> <span class="pl-s1">howMany</span> <span class="pl-c1">=&gt;</span>
  <span class="pl-kos">[</span>...<span class="pl-v">Array</span><span class="pl-kos">(</span><span class="pl-s1">howMany</span><span class="pl-kos">)</span><span class="pl-kos">]</span><span class="pl-kos">.</span><span class="pl-en">forEach</span><span class="pl-kos">(</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span>
    <span class="pl-smi">document</span><span class="pl-kos">.</span><span class="pl-c1">body</span><span class="pl-kos">.</span><span class="pl-en">insertAdjacentHTML</span><span class="pl-kos">(</span><span class="pl-s">"beforeend"</span><span class="pl-kos">,</span> <span class="pl-s">"&lt;div&gt;&lt;/div&gt;"</span><span class="pl-kos">)</span>
  <span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-en">createDivs</span><span class="pl-kos">(</span><span class="pl-c1">5</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-en">createDivs</span> <span class="pl-c1">=</span> <span class="pl-s1">howMany</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">{</span>
  <span class="pl-k">if</span> <span class="pl-kos">(</span><span class="pl-c1">!</span><span class="pl-s1">howMany</span><span class="pl-kos">)</span> <span class="pl-k">return</span><span class="pl-kos">;</span>
  <span class="pl-smi">document</span><span class="pl-kos">.</span><span class="pl-c1">body</span><span class="pl-kos">.</span><span class="pl-en">insertAdjacentHTML</span><span class="pl-kos">(</span><span class="pl-s">"beforeend"</span><span class="pl-kos">,</span> <span class="pl-s">"&lt;div&gt;&lt;/div&gt;"</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
  <span class="pl-k">return</span> <span class="pl-en">createDivs</span><span class="pl-kos">(</span><span class="pl-s1">howMany</span> <span class="pl-c1">-</span> <span class="pl-c1">1</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span><span class="pl-kos">;</span>
<span class="pl-en">createDivs</span><span class="pl-kos">(</span><span class="pl-c1">5</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<p>Here's a <a href="https://gist.github.com/bendc/6cb2db4a44ec30208e86">generic loop function</a> making recursion easier to use.</p>
<h3><a id="user-content-arguments" class="anchor" aria-hidden="true" href="#arguments"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Arguments</h3>
<p>Forget about the <code>arguments</code> object. The rest parameter is always a better option because:</p>
<ol>
<li>it's named, so it gives you a better idea of the arguments the function is expecting</li>
<li>it's a real array, which makes it easier to use.</li>
</ol>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-en">sortNumbers</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span>
  <span class="pl-v">Array</span><span class="pl-kos">.</span><span class="pl-c1">prototype</span><span class="pl-kos">.</span><span class="pl-c1">slice</span><span class="pl-kos">.</span><span class="pl-en">call</span><span class="pl-kos">(</span><span class="pl-smi">arguments</span><span class="pl-kos">)</span><span class="pl-kos">.</span><span class="pl-en">sort</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-en">sortNumbers</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span>...<span class="pl-s1">numbers</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">numbers</span><span class="pl-kos">.</span><span class="pl-en">sort</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<h3><a id="user-content-apply" class="anchor" aria-hidden="true" href="#apply"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Apply</h3>
<p>Forget about <code>apply()</code>. Use the spread operator instead.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">const</span> <span class="pl-en">greet</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-s1">first</span><span class="pl-kos">,</span> <span class="pl-s1">last</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s">`Hi <span class="pl-s1"><span class="pl-kos">${</span><span class="pl-s1">first</span><span class="pl-kos">}</span></span> <span class="pl-s1"><span class="pl-kos">${</span><span class="pl-s1">last</span><span class="pl-kos">}</span></span>`</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-s1">person</span> <span class="pl-c1">=</span> <span class="pl-kos">[</span><span class="pl-s">"John"</span><span class="pl-kos">,</span> <span class="pl-s">"Doe"</span><span class="pl-kos">]</span><span class="pl-kos">;</span>

<span class="pl-c">// bad</span>
<span class="pl-en">greet</span><span class="pl-kos">.</span><span class="pl-en">apply</span><span class="pl-kos">(</span><span class="pl-c1">null</span><span class="pl-kos">,</span> <span class="pl-s1">person</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-en">greet</span><span class="pl-kos">(</span>...<span class="pl-s1">person</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<h3><a id="user-content-bind" class="anchor" aria-hidden="true" href="#bind"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Bind</h3>
<p>Don't <code>bind()</code> when there's a more idiomatic approach.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">,</span> <span class="pl-s">"bar"</span><span class="pl-kos">]</span><span class="pl-kos">.</span><span class="pl-en">forEach</span><span class="pl-kos">(</span><span class="pl-s1">func</span><span class="pl-kos">.</span><span class="pl-en">bind</span><span class="pl-kos">(</span><span class="pl-smi">this</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">,</span> <span class="pl-s">"bar"</span><span class="pl-kos">]</span><span class="pl-kos">.</span><span class="pl-en">forEach</span><span class="pl-kos">(</span><span class="pl-s1">func</span><span class="pl-kos">,</span> <span class="pl-smi">this</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-s1">person</span> <span class="pl-c1">=</span> <span class="pl-kos">{</span>
  <span class="pl-c1">first</span>: <span class="pl-s">"John"</span><span class="pl-kos">,</span>
  <span class="pl-c1">last</span>: <span class="pl-s">"Doe"</span><span class="pl-kos">,</span>
  <span class="pl-en">greet</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
    <span class="pl-k">const</span> <span class="pl-s1">full</span> <span class="pl-c1">=</span> <span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
      <span class="pl-k">return</span> <span class="pl-s">`<span class="pl-s1"><span class="pl-kos">${</span><span class="pl-smi">this</span><span class="pl-kos">.</span><span class="pl-c1">first</span><span class="pl-kos">}</span></span> <span class="pl-s1"><span class="pl-kos">${</span><span class="pl-smi">this</span><span class="pl-kos">.</span><span class="pl-c1">last</span><span class="pl-kos">}</span></span>`</span><span class="pl-kos">;</span>
    <span class="pl-kos">}</span><span class="pl-kos">.</span><span class="pl-en">bind</span><span class="pl-kos">(</span><span class="pl-smi">this</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
    <span class="pl-k">return</span> <span class="pl-s">`Hello <span class="pl-s1"><span class="pl-kos">${</span><span class="pl-s1">full</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">}</span></span>`</span><span class="pl-kos">;</span>
  <span class="pl-kos">}</span>
<span class="pl-kos">}</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-s1">person</span> <span class="pl-c1">=</span> <span class="pl-kos">{</span>
  <span class="pl-c1">first</span>: <span class="pl-s">"John"</span><span class="pl-kos">,</span>
  <span class="pl-c1">last</span>: <span class="pl-s">"Doe"</span><span class="pl-kos">,</span>
  <span class="pl-en">greet</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
    <span class="pl-k">const</span> <span class="pl-en">full</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s">`<span class="pl-s1"><span class="pl-kos">${</span><span class="pl-smi">this</span><span class="pl-kos">.</span><span class="pl-c1">first</span><span class="pl-kos">}</span></span> <span class="pl-s1"><span class="pl-kos">${</span><span class="pl-smi">this</span><span class="pl-kos">.</span><span class="pl-c1">last</span><span class="pl-kos">}</span></span>`</span><span class="pl-kos">;</span>
    <span class="pl-k">return</span> <span class="pl-s">`Hello <span class="pl-s1"><span class="pl-kos">${</span><span class="pl-en">full</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">}</span></span>`</span><span class="pl-kos">;</span>
  <span class="pl-kos">}</span>
<span class="pl-kos">}</span></pre></div>
<h3><a id="user-content-higher-order-functions" class="anchor" aria-hidden="true" href="#higher-order-functions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Higher-order functions</h3>
<p>Avoid nesting functions when you don't have to.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-kos">[</span><span class="pl-c1">1</span><span class="pl-kos">,</span> <span class="pl-c1">2</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">]</span><span class="pl-kos">.</span><span class="pl-en">map</span><span class="pl-kos">(</span><span class="pl-s1">num</span> <span class="pl-c1">=&gt;</span> <span class="pl-v">String</span><span class="pl-kos">(</span><span class="pl-s1">num</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-kos">[</span><span class="pl-c1">1</span><span class="pl-kos">,</span> <span class="pl-c1">2</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">]</span><span class="pl-kos">.</span><span class="pl-en">map</span><span class="pl-kos">(</span><span class="pl-v">String</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<h3><a id="user-content-composition" class="anchor" aria-hidden="true" href="#composition"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Composition</h3>
<p>Avoid multiple nested function calls. Use composition instead.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">const</span> <span class="pl-en">plus1</span> <span class="pl-c1">=</span> <span class="pl-s1">a</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">a</span> <span class="pl-c1">+</span> <span class="pl-c1">1</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-en">mult2</span> <span class="pl-c1">=</span> <span class="pl-s1">a</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">a</span> <span class="pl-c1">*</span> <span class="pl-c1">2</span><span class="pl-kos">;</span>

<span class="pl-c">// bad</span>
<span class="pl-en">mult2</span><span class="pl-kos">(</span><span class="pl-en">plus1</span><span class="pl-kos">(</span><span class="pl-c1">5</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; 12</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-en">pipeline</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span>...<span class="pl-s1">funcs</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">val</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">funcs</span><span class="pl-kos">.</span><span class="pl-en">reduce</span><span class="pl-kos">(</span><span class="pl-kos">(</span><span class="pl-s1">a</span><span class="pl-kos">,</span> <span class="pl-s1">b</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">b</span><span class="pl-kos">(</span><span class="pl-s1">a</span><span class="pl-kos">)</span><span class="pl-kos">,</span> <span class="pl-s1">val</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-s1">addThenMult</span> <span class="pl-c1">=</span> <span class="pl-en">pipeline</span><span class="pl-kos">(</span><span class="pl-en">plus1</span><span class="pl-kos">,</span> <span class="pl-en">mult2</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">addThenMult</span><span class="pl-kos">(</span><span class="pl-c1">5</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; 12</span></pre></div>
<h3><a id="user-content-caching" class="anchor" aria-hidden="true" href="#caching"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Caching</h3>
<p>Cache feature tests, large data structures and any expensive operation.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-en">contains</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-s1">arr</span><span class="pl-kos">,</span> <span class="pl-s1">value</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span>
  <span class="pl-v">Array</span><span class="pl-kos">.</span><span class="pl-c1">prototype</span><span class="pl-kos">.</span><span class="pl-c1">includes</span>
    ? <span class="pl-s1">arr</span><span class="pl-kos">.</span><span class="pl-en">includes</span><span class="pl-kos">(</span><span class="pl-s1">value</span><span class="pl-kos">)</span>
    : <span class="pl-s1">arr</span><span class="pl-kos">.</span><span class="pl-en">some</span><span class="pl-kos">(</span><span class="pl-s1">el</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">el</span> <span class="pl-c1">===</span> <span class="pl-s1">value</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-en">contains</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">,</span> <span class="pl-s">"bar"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-s">"baz"</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; false</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-s1">contains</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span>
  <span class="pl-v">Array</span><span class="pl-kos">.</span><span class="pl-c1">prototype</span><span class="pl-kos">.</span><span class="pl-c1">includes</span>
    ? <span class="pl-kos">(</span><span class="pl-s1">arr</span><span class="pl-kos">,</span> <span class="pl-s1">value</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">arr</span><span class="pl-kos">.</span><span class="pl-en">includes</span><span class="pl-kos">(</span><span class="pl-s1">value</span><span class="pl-kos">)</span>
    : <span class="pl-kos">(</span><span class="pl-s1">arr</span><span class="pl-kos">,</span> <span class="pl-s1">value</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">arr</span><span class="pl-kos">.</span><span class="pl-en">some</span><span class="pl-kos">(</span><span class="pl-s1">el</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">el</span> <span class="pl-c1">===</span> <span class="pl-s1">value</span><span class="pl-kos">)</span>
<span class="pl-kos">)</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">contains</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">,</span> <span class="pl-s">"bar"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-s">"baz"</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; false</span></pre></div>
<h3><a id="user-content-variables" class="anchor" aria-hidden="true" href="#variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Variables</h3>
<p>Favor <code>const</code> over <code>let</code> and <code>let</code> over <code>var</code>.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> <span class="pl-s1">me</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">Map</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">me</span><span class="pl-kos">.</span><span class="pl-en">set</span><span class="pl-kos">(</span><span class="pl-s">"name"</span><span class="pl-kos">,</span> <span class="pl-s">"Ben"</span><span class="pl-kos">)</span><span class="pl-kos">.</span><span class="pl-en">set</span><span class="pl-kos">(</span><span class="pl-s">"country"</span><span class="pl-kos">,</span> <span class="pl-s">"Belgium"</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-s1">me</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">Map</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">me</span><span class="pl-kos">.</span><span class="pl-en">set</span><span class="pl-kos">(</span><span class="pl-s">"name"</span><span class="pl-kos">,</span> <span class="pl-s">"Ben"</span><span class="pl-kos">)</span><span class="pl-kos">.</span><span class="pl-en">set</span><span class="pl-kos">(</span><span class="pl-s">"country"</span><span class="pl-kos">,</span> <span class="pl-s">"Belgium"</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<h3><a id="user-content-conditions" class="anchor" aria-hidden="true" href="#conditions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Conditions</h3>
<p>Favor IIFE's and return statements over if, else if, else and switch statements.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> <span class="pl-s1">grade</span><span class="pl-kos">;</span>
<span class="pl-k">if</span> <span class="pl-kos">(</span><span class="pl-s1">result</span> <span class="pl-c1">&lt;</span> <span class="pl-c1">50</span><span class="pl-kos">)</span>
  <span class="pl-s1">grade</span> <span class="pl-c1">=</span> <span class="pl-s">"bad"</span><span class="pl-kos">;</span>
<span class="pl-k">else</span> <span class="pl-k">if</span> <span class="pl-kos">(</span><span class="pl-s1">result</span> <span class="pl-c1">&lt;</span> <span class="pl-c1">90</span><span class="pl-kos">)</span>
  <span class="pl-s1">grade</span> <span class="pl-c1">=</span> <span class="pl-s">"good"</span><span class="pl-kos">;</span>
<span class="pl-k">else</span>
  <span class="pl-s1">grade</span> <span class="pl-c1">=</span> <span class="pl-s">"excellent"</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-s1">grade</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">{</span>
  <span class="pl-k">if</span> <span class="pl-kos">(</span><span class="pl-s1">result</span> <span class="pl-c1">&lt;</span> <span class="pl-c1">50</span><span class="pl-kos">)</span>
    <span class="pl-k">return</span> <span class="pl-s">"bad"</span><span class="pl-kos">;</span>
  <span class="pl-k">if</span> <span class="pl-kos">(</span><span class="pl-s1">result</span> <span class="pl-c1">&lt;</span> <span class="pl-c1">90</span><span class="pl-kos">)</span>
    <span class="pl-k">return</span> <span class="pl-s">"good"</span><span class="pl-kos">;</span>
  <span class="pl-k">return</span> <span class="pl-s">"excellent"</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<h3><a id="user-content-object-iteration" class="anchor" aria-hidden="true" href="#object-iteration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Object iteration</h3>
<p>Avoid <code>for...in</code> when you can.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-k">const</span> <span class="pl-s1">shared</span> <span class="pl-c1">=</span> <span class="pl-kos">{</span> <span class="pl-c1">foo</span>: <span class="pl-s">"foo"</span> <span class="pl-kos">}</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-s1">obj</span> <span class="pl-c1">=</span> <span class="pl-v">Object</span><span class="pl-kos">.</span><span class="pl-en">create</span><span class="pl-kos">(</span><span class="pl-s1">shared</span><span class="pl-kos">,</span> <span class="pl-kos">{</span>
  <span class="pl-c1">bar</span>: <span class="pl-kos">{</span>
    <span class="pl-c1">value</span>: <span class="pl-s">"bar"</span><span class="pl-kos">,</span>
    <span class="pl-c1">enumerable</span>: <span class="pl-c1">true</span>
  <span class="pl-kos">}</span>
<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// bad</span>
<span class="pl-k">for</span> <span class="pl-kos">(</span><span class="pl-k">var</span> <span class="pl-s1">prop</span> <span class="pl-k">in</span> <span class="pl-s1">obj</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
  <span class="pl-k">if</span> <span class="pl-kos">(</span><span class="pl-s1">obj</span><span class="pl-kos">.</span><span class="pl-en">hasOwnProperty</span><span class="pl-kos">(</span><span class="pl-s1">prop</span><span class="pl-kos">)</span><span class="pl-kos">)</span>
    <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">prop</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span>

<span class="pl-c">// good</span>
<span class="pl-v">Object</span><span class="pl-kos">.</span><span class="pl-en">keys</span><span class="pl-kos">(</span><span class="pl-s1">obj</span><span class="pl-kos">)</span><span class="pl-kos">.</span><span class="pl-en">forEach</span><span class="pl-kos">(</span><span class="pl-s1">prop</span> <span class="pl-c1">=&gt;</span> <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">prop</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<h3><a id="user-content-objects-as-maps" class="anchor" aria-hidden="true" href="#objects-as-maps"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Objects as Maps</h3>
<p>While objects have legitimate use cases, maps are usually a better, more powerful choice. When in
doubt, use a <code>Map</code>.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-s1">me</span> <span class="pl-c1">=</span> <span class="pl-kos">{</span>
  <span class="pl-c1">name</span>: <span class="pl-s">"Ben"</span><span class="pl-kos">,</span>
  <span class="pl-c1">age</span>: <span class="pl-c1">30</span>
<span class="pl-kos">}</span><span class="pl-kos">;</span>
<span class="pl-k">var</span> <span class="pl-s1">meSize</span> <span class="pl-c1">=</span> <span class="pl-v">Object</span><span class="pl-kos">.</span><span class="pl-en">keys</span><span class="pl-kos">(</span><span class="pl-s1">me</span><span class="pl-kos">)</span><span class="pl-kos">.</span><span class="pl-c1">length</span><span class="pl-kos">;</span>
<span class="pl-s1">meSize</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; 2</span>
<span class="pl-s1">me</span><span class="pl-kos">.</span><span class="pl-c1">country</span> <span class="pl-c1">=</span> <span class="pl-s">"Belgium"</span><span class="pl-kos">;</span>
<span class="pl-s1">meSize</span><span class="pl-c1">++</span><span class="pl-kos">;</span>
<span class="pl-s1">meSize</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; 3</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-s1">me</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">Map</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">me</span><span class="pl-kos">.</span><span class="pl-en">set</span><span class="pl-kos">(</span><span class="pl-s">"name"</span><span class="pl-kos">,</span> <span class="pl-s">"Ben"</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">me</span><span class="pl-kos">.</span><span class="pl-en">set</span><span class="pl-kos">(</span><span class="pl-s">"age"</span><span class="pl-kos">,</span> <span class="pl-c1">30</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">me</span><span class="pl-kos">.</span><span class="pl-c1">size</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; 2</span>
<span class="pl-s1">me</span><span class="pl-kos">.</span><span class="pl-en">set</span><span class="pl-kos">(</span><span class="pl-s">"country"</span><span class="pl-kos">,</span> <span class="pl-s">"Belgium"</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">me</span><span class="pl-kos">.</span><span class="pl-c1">size</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; 3</span></pre></div>
<h3><a id="user-content-curry" class="anchor" aria-hidden="true" href="#curry"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Curry</h3>
<p>Currying is a powerful but foreign paradigm for many developers. Don't abuse it as its appropriate
use cases are fairly unusual.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-en">sum</span> <span class="pl-c1">=</span> <span class="pl-s1">a</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">b</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">a</span> <span class="pl-c1">+</span> <span class="pl-s1">b</span><span class="pl-kos">;</span>
<span class="pl-en">sum</span><span class="pl-kos">(</span><span class="pl-c1">5</span><span class="pl-kos">)</span><span class="pl-kos">(</span><span class="pl-c1">3</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; 8</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-en">sum</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-s1">a</span><span class="pl-kos">,</span> <span class="pl-s1">b</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">a</span> <span class="pl-c1">+</span> <span class="pl-s1">b</span><span class="pl-kos">;</span>
<span class="pl-en">sum</span><span class="pl-kos">(</span><span class="pl-c1">5</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// =&gt; 8</span></pre></div>
<h3><a id="user-content-readability" class="anchor" aria-hidden="true" href="#readability"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Readability</h3>
<p>Don't obfuscate the intent of your code by using seemingly smart tricks.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-s1">foo</span> <span class="pl-c1">||</span> <span class="pl-en">doSomething</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-k">if</span> <span class="pl-kos">(</span><span class="pl-c1">!</span><span class="pl-s1">foo</span><span class="pl-kos">)</span> <span class="pl-en">doSomething</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">void</span> <span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span> <span class="pl-c">/* IIFE */</span> <span class="pl-kos">}</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span> <span class="pl-c">/* IIFE */</span> <span class="pl-kos">}</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-s1">n</span> <span class="pl-c1">=</span> <span class="pl-c1">~</span><span class="pl-c1">~</span><span class="pl-c1">3.14</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-s1">n</span> <span class="pl-c1">=</span> <span class="pl-v">Math</span><span class="pl-kos">.</span><span class="pl-en">floor</span><span class="pl-kos">(</span><span class="pl-c1">3.14</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<h3><a id="user-content-code-reuse" class="anchor" aria-hidden="true" href="#code-reuse"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Code reuse</h3>
<p>Don't be afraid of creating lots of small, highly composable and reusable functions.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-s1">arr</span><span class="pl-kos">[</span><span class="pl-s1">arr</span><span class="pl-kos">.</span><span class="pl-c1">length</span> <span class="pl-c1">-</span> <span class="pl-c1">1</span><span class="pl-kos">]</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-en">first</span> <span class="pl-c1">=</span> <span class="pl-s1">arr</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">arr</span><span class="pl-kos">[</span><span class="pl-c1">0</span><span class="pl-kos">]</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-en">last</span> <span class="pl-c1">=</span> <span class="pl-s1">arr</span> <span class="pl-c1">=&gt;</span> <span class="pl-en">first</span><span class="pl-kos">(</span><span class="pl-s1">arr</span><span class="pl-kos">.</span><span class="pl-en">slice</span><span class="pl-kos">(</span><span class="pl-c1">-</span><span class="pl-c1">1</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-en">last</span><span class="pl-kos">(</span><span class="pl-s1">arr</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">const</span> <span class="pl-en">product</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-s1">a</span><span class="pl-kos">,</span> <span class="pl-s1">b</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">a</span> <span class="pl-c1">*</span> <span class="pl-s1">b</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-en">triple</span> <span class="pl-c1">=</span> <span class="pl-s1">n</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">n</span> <span class="pl-c1">*</span> <span class="pl-c1">3</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-en">product</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-s1">a</span><span class="pl-kos">,</span> <span class="pl-s1">b</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">a</span> <span class="pl-c1">*</span> <span class="pl-s1">b</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-s1">triple</span> <span class="pl-c1">=</span> <span class="pl-en">product</span><span class="pl-kos">.</span><span class="pl-en">bind</span><span class="pl-kos">(</span><span class="pl-c1">null</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<h3><a id="user-content-dependencies" class="anchor" aria-hidden="true" href="#dependencies"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Dependencies</h3>
<p>Minimize dependencies. Third-party is code you don't know. Don't load an entire library for just a couple of methods easily replicable:</p>
<div class="highlight highlight-source-js"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-en">require</span><span class="pl-kos">(</span><span class="pl-s">"underscore"</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">_</span><span class="pl-kos">.</span><span class="pl-en">compact</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">,</span> <span class="pl-c1">0</span><span class="pl-kos">]</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">_</span><span class="pl-kos">.</span><span class="pl-en">unique</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">,</span> <span class="pl-s">"foo"</span><span class="pl-kos">]</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">_</span><span class="pl-kos">.</span><span class="pl-en">union</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-kos">[</span><span class="pl-s">"bar"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">]</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// good</span>
<span class="pl-k">const</span> <span class="pl-en">compact</span> <span class="pl-c1">=</span> <span class="pl-s1">arr</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">arr</span><span class="pl-kos">.</span><span class="pl-en">filter</span><span class="pl-kos">(</span><span class="pl-s1">el</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">el</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-en">unique</span> <span class="pl-c1">=</span> <span class="pl-s1">arr</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">[</span>...<span class="pl-k">new</span> <span class="pl-v">Set</span><span class="pl-kos">(</span><span class="pl-s1">arr</span><span class="pl-kos">)</span><span class="pl-kos">]</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-en">union</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span>...<span class="pl-s1">arr</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-en">unique</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-kos">]</span><span class="pl-kos">.</span><span class="pl-en">concat</span><span class="pl-kos">(</span>...<span class="pl-s1">arr</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-en">compact</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">,</span> <span class="pl-c1">0</span><span class="pl-kos">]</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-en">unique</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">,</span> <span class="pl-s">"foo"</span><span class="pl-kos">]</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-en">union</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-kos">[</span><span class="pl-s">"bar"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-kos">[</span><span class="pl-s">"foo"</span><span class="pl-kos">]</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
</article>


