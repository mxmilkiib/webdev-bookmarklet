webdev-bookmarklet
==================

JS bookmarklet for highlighting html elements

    javascript:(function(){var t=['div','header','nav','main','section','footer','table','th','td','tr','form','fieldset','label','img','address','blockquote','h1','h2','h3','h4','h5','h6','p','pre','dd','dl','dt','ol','ul','li'];var c=['blue','blue','blue','blue','blue','blue','teal','teal','teal','teal','orange','orange','orange','red','red','red','red','red','red','red','red','red','red','green','green','green','green','green','green','yellow'];for (var i in t){var l=document.getElementsByTagName(t[i]);var j=0,e;while(e=l.item(j++)){e.style.outline='solid '+c[i]+' 1px';}}})();

Quick ref; http://en.wikipedia.org/wiki/Web_colors#HTML_color_names
