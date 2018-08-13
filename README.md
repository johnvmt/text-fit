# <text-fit>

WebComponent that reiszes text to fit inside a container.

Uses [STRML/textFit](https://github.com/STRML/textFit)

## Example

	<link rel="import" href="bower_components/text-fit/text-fit.html">
	
	<text-fit style="width: 300px; height: 100px; background-color: #ff0000;" align-vert="false" max-font-size="300">Some<br />Text</text-fit>
	
## Attributes (Options)

The web componentsupports the same options as [STRML/textFit](https://github.com/STRML/textFit).
Simply change the camelCase options to dashed-attributes (eg: alignVert becomes align-vert,a s in the example above)

#### Defaults from [STRML/textFit](https://github.com/STRML/textFit):

| Attribute Name| Default | Notes |
| :-------------: |:-------------:| :-----:|
| align-vert      | false | if true, textFit will align vertically using css tables |
| align-horiz      | false      | if true, textFit will set text-align: center |
| multi-line		 | false      | if true, textFit will not set white-space: no-wrap |
| detect-multi-line	| true | disable to turn off automatic multi-line sensing |
| min-font-size	| 6 | |
| max-font-size | 80 | |
| re-process | true | if true, textFit will re-process already-fit nodes. Set to 'false' for better performance |
| width-only | false | if true, textFit will fit text to element width, regardless of text height |
| align-vert-with-flexbox | false | if true, textFit will use flexbox for vertical alignment |