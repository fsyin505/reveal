<h1>Responsive Reveal: A <em>Responsive</em> jQuery Plugin For Modals</h1>
<p>Based on the original Reveal modal plugin (https://github.com/zurb/reveal), which was an excellent starting point for adding a super light-weight modal function to a site.  The minor drawback is that modal sizes were bit responsively displayed for mobile or arbitrary screen sizes.</p>
<p>This fork converts it into responsive display by converting widths to percentages and hiding modal elements using display:none, instead of visibility:hidden</p>

<h3>Download & Documentation </h3>
<p>Documentation is in the code.  To run, unpack reveal_responsive.zip and launch demo.html</p>

<p class="muted">[Below this is the original README]</p>


<h1>Reveal: A jQuery Plugin For Modals</h1>
<p>Reveal is a jQuery plugin for dead simple modals that comes with some sexy base CSS and can be implemented programatically or with the new HTML5 custom data attributes (data-attribute).</p>

<p><strong>Note: This version of Reveal has been deprecated and will no longer be developed or supported. For the most recent code, check out the responsive version of Reveal included in <a href="http://foundation.zurb.com">Foundation</a>, our rapid prototyping and production framework.</p>

<h3>Download & Documentation </h3>
<p>All of the docs and the download link are on a playground page here: <a href="http://www.zurb.com/playground/reveal-modal-plugin">http://www.zurb.com/playground/reveal-modal-plugin</a></p>

<h3>Feature Request List</h3>
<p>Below are the features that have been requested or that we have seen an opportunity for and are going to try to tackle in future iterations of the plugin (in no particular order). These will, if implemented, be added to the plugin as part of Foundation.</p>

<ul>
<li>Callable method for closing a modal</li>
<li>Have close button close "all active modals" (if multiple modals are somehow surfaced)</li>
<li>Keyboard close with esc key</li>
<li>Document easy way to AJAX modal content</li>
<li>Add lightbox feature to make it easy to hookup custom data attributes to a lightbox functionality </li>
<li>Fix IE background to have opacity</li>
</ul>