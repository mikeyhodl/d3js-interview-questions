## D3.js Data Visualization Interview Questions

*Click <img src="https://github.com/learning-zone/d3js-interview-questions/blob/master/assets/star.png" width="20" height="20" align="absmiddle" title="Star" /> if you like the project. Pull Request are highly appreciated.*

#### Q. Explain what is d3.js?
D3.js is a JavaScript library for creating and manipulating documents based on data.  It uses digital data to drive the formation and control of dynamic and interactive graphical presentation, which runs in web browsers.

#### Q. When using d3.js is helpful?
D3.js is extremely helpful in viewing huge data reports of account detail, e-commerce budgeting, population, etc.  For such data’s, data visualization is the best way understand, represent and analyze it.

#### Q. Explain what is SVG?
SVG or Scalable Vector Graphics (SVG) is an XML, the markup language for determining two-dimensional vector graphics. SVG is crucial for graphics what XHTML to text.

[Live Example](https://learning-zone.github.io/d3js-interview-questions/a.svg.html) 

#### Q. Explain how D3.js selects method?
D3.js select method uses CSS3 selectors to choose DOM elements.  D3 looks at the document and choose the first descendant DOM element that consists the tag body.  Once the element is selected, D3.js enables you to implement operators to the element selected.

#### Q. Explain about d3.js Scales?
D3.js scales come with

* **Quantitative Scales**: The quantitative scales have a continuous domain like dates, times, real numbers etc.
* **Ordinal Scales**: While the ordinal scales are for separate domains like categories, colors, names,
* **Linear Scales**: It converts one value in the domain interval into a value in the range interval
* **Identity Scales**: It is good for pixel values
* **Power and Logarithmic Scales**: It is used for exponentially increasing values like log,pow,sqrt

#### Q. Mention what are the slider available in d3.js?
The slider available in d3.js are

Default slider
Slider with start value
Slider with slide event
Slider with slide event
Slider with custom axis
Slider with min, max, and step values
Vertical Slider

#### Q. Explain what is Domain in d3.js?
In d3.js, domain is the start and end of your dataset. It can be any kind of value that can be compared in JavaScript. Domains have to change if your dataset changes.

#### Q. Explain what is the role of “Path Data Generator” in d3.js?
In respect to convert our data to the SVG path command, we have to tell the line Path Data Generator, about how to access the y and x co-ordinates from the data.

#### Q. Mention what does path generators include in it?
Path generator includes

svg.line- Make a new line generator
svg.line.radial- Make a new radial line generator
svg.area – Make a new area generator
svg.chord – Make a new chord generator and so on

#### Q. Explain what d3.js enter method does?
D3.js enter method returns the virtual enter selection from the data operator.  This method is only applicable to Data Operator as such data operator is the only one that returns three virtual selections.

#### Q. Mention what is the difference between jQuery and d3.js?
D3.js	JQuery
D3 creates or manipulates data-driven document that is manipulating or creating visual documents from your data using D3’s data/exit/enter methods
D3 has numerous visualization extensions
 JQuery is a general purpose Ajax/js library which offers general Ajax/js functionalities for creating web apps, but it does not provide data-driven functionality of D3
jQuery has many general web app extensions

#### Q. Explain what is the role of D3.js Axis component?
D3.js Axis component enables easy addition of a horizontal axis and the vertical axis to any graph. It shows reference lines for D3.js Scales automatically. It also allows you to draw a horizontal axis line, axis ticks and correct spacing to make axis appear appropriate.

#### Q. Mention the command used to create simple axis in d3.js?
The command to create simple axis in d3.js is var xAxis = d3.svg.axis().

#### Q. Explain what is SVG group element?
SVG group element is used to group SVG element together; each SVG group element is a container which consists of child SVG elements.  It is defined by <g> and </g>.

#### Q. Explain how you can several classes at once?
To set several classes at once you can use the object literal as

selection.classed({ ‘foo’:true, ‘bar’: false})

#### Q. Explain what is a transition in d3.js?
Transition in d3.js gradually interpolate attributes and styles over time, transition is used for animation purpose.  It is based on only two key frames, start, and end.  The starting key frame defines the current state of the DOM, while the ending key frame is a set of styles, attributes and other properties you specified.

#### Q. Mention what is the command to interpolate two objects in d3.js?
To interpolate two objects in d3.js command d3.interpolateObject(a,b) is used. Object interpolation is useful particularly for data space interpolation, where data is interpolated rather than attribute values.

#### Q. Explain what is the command “d3.ascending (a, b)” is used?
This command is comparator function that is used for a natural order, and can be used along with the built-in-array sort method to arrange elements in ascending order.

#### Q. Explain how XML file is called in d3.js?
By using the command d3.xml(url[mimeType][,callback]) XML file can be called. This command will create a request for the XML file at the specified url. If a call back is declared, the request will be immediately processed with the GET method and the call back will be invoked when the file is loaded, or request fails.

#### Q. What happens if no call back is specified for XML file in d3.js?
If no call back is specified, the returned request can be issued using xhr.get and handled using xhr.on.

#### Q. Mention the command to join the specified array of data in d3.js?
To join the specified array of data in d3.js you can use the command selection.data([values[,key]]).  The values here specifies the data for each group in the selection while a key function determines how data is connected to elements.

#### Q. Mention what does the command d3.csv.parseRows(string[,accessor]) ?
This command parses the specified string, which is the content of a CSV file, returning an array of arrays representing the parsed rows.

#### Q. Mention what is the use of “Enter” and “Exit” selection in d3.js?
By using “Enter” and “Exit” selection in d3.js, you can create new nodes for incoming data and eliminate outgoing nodes that are no longer required.

#### Q. Explain selections in d3.js ?
#### Q. How d3.js identify on which elements to operate?
#### Q. What is the best way to create the stacked chart in d3 js?
#### Q. How to import XML data using d3.js?
#### Q. What is different between d3.scale.linear() and d3.scaleLinear().
#### Q. How to set initial zoom level in d3.js?
#### Q. How to resize an SVG when the window is resized in d3.js?
#### Q. How to get mouse position in d3.js?
#### Q. What is the difference between canvas and SVG in d3.js?
#### Q. How to format the date in d3.js?
#### Q. Explain axes in d3.js? How to create d3.js axes without numbering?
#### Q. How to calculate the area of the polygon in d3.js?
#### Q. How data binding work in d3.js?
#### Q. How to handle events in d3.js?
