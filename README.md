# pysvgo
in progress - Python version of Node.js tool for optimizing SVG files


List of plugins
https://github.com/svg/svgo/issues/1621
workon

 - [ ] [enabled] cleanupAttrs : cleanup attributes from newlines, trailing, and repeating spaces
 - [ ] [enabled] mergeStyles : merge multiple style elements into one
 - [ ] [enabled] inlineStyles : move and merge styles from ``<style>`` elements to element style attributes
 - [ ] [enabled] removeDoctype : remove doctype declaration
 - [ ] [enabled] removeXMLProcInst : remove XML processing instructions
 - [ ] [enabled] removeComments : remove comments
 - [ ] [enabled] removeMetadata : remove ``<metadata>``
 - [ ] [enabled] removeTitle : remove ``<title>``
 - [ ] [enabled] removeDesc : remove ``<desc>``
 - [ ] [enabled] removeUselessDefs : remove elements of ``<defs>`` without id
 - [ ] [disabled] removeXMLNS : removes the xmlns attribute (for inline SVG)
 - [ ] [enabled] removeEditorsNSData : remove editors namespaces, elements, and attributes
 - [ ] [enabled] removeEmptyAttrs : remove empty attributes
 - [ ] [enabled] removeHiddenElems : remove hidden elements
 - [ ] [enabled] removeEmptyText : remove empty Text elements
 - [ ] [enabled] removeEmptyContainers : remove empty Container elements
 - [ ] [enabled] removeViewBox : remove viewBox attribute when possible
 - [ ] [enabled] cleanupEnableBackground : remove or cleanup enable-background attribute when possible
 - [ ] [enabled] minifyStyles : minify ``<style>`` elements content with CSSO
 - [ ] [disabled] convertStyleToAttrs : convert styles into attributes
 - [ ] [enabled] convertColors : convert colors (from rgb() to #rrggbb, from #rrggbb to #rgb)
 - [ ] [enabled] convertPathData : convert Path data to relative or absolute (whichever is shorter), convert one segment to another, trim useless delimiters, smart rounding, and much more
 - [ ] [enabled] convertTransform : collapse multiple transforms into one, convert matrices to the short aliases, and much more
 - [ ] [enabled] removeUnknownsAndDefaults : remove unknown elements content and attributes, remove attributes with default values
 - [ ] [enabled] removeNonInheritableGroupAttrs : remove non-inheritable group's "presentation" attributes
 - [ ] [enabled] removeUselessStrokeAndFill : remove useless stroke and fill attributes
 - [ ] [enabled] removeUnusedNS : remove unused namespaces declaration
 - [ ] [disabled] prefixIds : prefix IDs and classes with the SVG filename or an arbitrary string
 - [ ] [enabled] cleanupIDs : remove unused and minify used IDs
 - [ ] [enabled] cleanupNumericValues : round numeric values to the fixed precision, remove default px units
 - [ ] [disabled] cleanupListOfValues : round numeric values in attributes that take a list of numbers (like viewBox or enable-background)
 - [ ] [enabled] moveElemsAttrsToGroup : move elements' attributes to their enclosing group
 - [ ] [enabled] moveGroupAttrsToElems : move some group attributes to the contained elements
 - [ ] [enabled] collapseGroups : collapse useless groups
 - [ ] [disabled] removeRasterImages : remove raster images
 - [ ] [enabled] mergePaths : merge multiple Paths into one
 - [ ] [enabled] convertShapeToPath : convert some basic shapes to ``<path>``
 - [ ] [enabled] convertEllipseToCircle : convert non-eccentric <ellipse> to ``<circle>``
 - [ ] [disabled] sortAttrs : sort element attributes for epic readability
 - [ ] [enabled] sortDefsChildren : sort children of ``<defs>`` in order to improve compression
 - [ ] [disabled] removeDimensions : remove width/height and add viewBox if it's missing (opposite to removeViewBox, disable it first)
 - [ ] [disabled] removeAttrs : remove attributes by pattern
 - [ ] [disabled] removeAttributesBySelector : removes attributes of elements that match a CSS selector
 - [ ] [disabled] removeElementsByAttr : remove arbitrary elements by ID or className
 - [ ] [disabled] addClassesToSVGElement : add classnames to an outer ``<svg>`` element
 - [ ] [disabled] addAttributesToSVGElement : adds attributes to an outer ``<svg>`` element
 - [ ] [disabled] removeOffCanvasPaths : removes elements that are drawn outside of the viewbox
 - [ ] [disabled] removeStyleElement : remove ``<style>`` elements
 - [ ] [disabled] removeScriptElement : remove ``<script>`` elements
 - [ ] [disabled] reusePaths : Find duplicated elements and replace them with links