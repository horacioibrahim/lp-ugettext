lp-ugettext
============

lp-ugettext provides the language from browser via javascript. It's based in the
piece of code of the Hamid posted in StackOverflow. It's was polymered!
[Stack](http://stackoverflow.com/a/29106129/2283488)

Usage
=====

```
<body unresolved>


        <!-- end elements -->
        <lp-ugettext></lp-ugettext>

        <script>
          window.addEventListener('polymer-ready', function(e) {
            var uget = document.querySelector('lp-ugettext');
            console.log("mylanguage" + uget.language);
          });
        </script>
</body>
```
