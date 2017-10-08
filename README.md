# A D3 rally

This is a roundup of material about D3 that I assembled while learning it and it serves the purpose of the reference point for code examples when creating some viz. 

## Materials used

I used a few material around, all the code here is somehow inspired or blatanly taken and edited from there. Here is the list of resources.

### Tutorials

* [dashingd3](https://www.dashingd3js.com/table-of-contents), Sebastian Gutierrez, a classic primer 
* [alignedleft](http://alignedleft.com/tutorials/d3), S Murray, very useful bunch of code examples with explanation
* D3 itself keeps track of a list of tutorials people have written, in [its wiki](https://github.com/d3/d3/wiki/Tutorials)

### Books

* [Interactive Data Visualisations for the Web](http://chimera.labs.oreilly.com/books/1230000000345/index.html): S Murray (see above), O'Reilly
* [D3.js in action](https://livebook.manning.com/#!/book/d3js-in-action-second-edition/part-1/v-6/), E Meeks
* [D3 Tips and Tricks](https://leanpub.com/D3-Tips-and-Tricks/read), M Maclean

### D3 docs

* The original [docs](https://d3js.org)
* The [gallery](https://github.com/d3/d3/wiki/Gallery) of D3 examples, with code for each


## Using S3 in a project

### D3 source code

D3 is open source and [on Github](). When writing this, we used the current release of D3, 4.11.0. To use the library code in a project, you can

* Download it into your project itself (full or minified version), and call it from locally, like this

    ```
    <script type="text/javascript" src="d3_source/4.11.0/d3.min.js"></script>
    ```
 
* Embed the code in the HTML of your project, like this

    ```
    <script src="https://d3js.org/d3.v4.min.js"></script>
    ```

### Using D3 - memento

* always put the meta tag in the head as `<meta charset="utf-8">`, as this ensures browser parses D3 right
