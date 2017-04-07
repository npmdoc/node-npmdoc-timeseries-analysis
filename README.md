# api documentation for  [timeseries-analysis (v1.0.12)](https://github.com/26medias/timeseries-analysis)  [![npm package](https://img.shields.io/npm/v/npmdoc-timeseries-analysis.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-timeseries-analysis) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-timeseries-analysis.svg)](https://travis-ci.org/npmdoc/node-npmdoc-timeseries-analysis)
#### timeseries-analysis

[![NPM](https://nodei.co/npm/timeseries-analysis.png?downloads=true)](https://www.npmjs.com/package/timeseries-analysis)

[![apidoc](https://npmdoc.github.io/node-npmdoc-timeseries-analysis/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-timeseries-analysis_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-timeseries-analysis/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-timeseries-analysis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-timeseries-analysis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Julien Loutre",
        "email": "julien@twenty-six-medias.com",
        "url": "http://www.twenty-six-medias.com/"
    },
    "bugs": {
        "url": "https://github.com/26medias/timeseries-analysis/issues"
    },
    "dependencies": {
        "google-image-chart": "latest",
        "underscore": "latest"
    },
    "description": "timeseries-analysis",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "30e7d6226953e0ac270d0cc0644b4974ada06d85",
        "tarball": "https://registry.npmjs.org/timeseries-analysis/-/timeseries-analysis-1.0.12.tgz"
    },
    "engines": {
        "node": "*"
    },
    "homepage": "https://github.com/26medias/timeseries-analysis",
    "keywords": [
        "forecast",
        "forecasting",
        "timeseries",
        "chart",
        "charting",
        "stats",
        "std",
        "smoothing",
        "moving average",
        "noise removal",
        "autoregression"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.github.com/26medias/timeseries-analysis/master/LICENSE"
        }
    ],
    "main": "timeseries-analysis.js",
    "maintainers": [
        {
            "name": "26medias",
            "email": "julien@twenty-six-medias.com"
        }
    ],
    "name": "timeseries-analysis",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/26medias/timeseries-analysis.git"
    },
    "version": "1.0.12"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module timeseries-analysis](#apidoc.module.timeseries-analysis)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.</span>main (data, options)](#apidoc.element.timeseries-analysis.main)
1.  object <span class="apidocSignatureSpan">timeseries-analysis.</span>adapter
1.  object <span class="apidocSignatureSpan">timeseries-analysis.</span>main.prototype
1.  string <span class="apidocSignatureSpan">timeseries-analysis.</span>version

#### [module timeseries-analysis.adapter](#apidoc.module.timeseries-analysis.adapter)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>complex (options)](#apidoc.element.timeseries-analysis.adapter.complex)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>fromArray (data)](#apidoc.element.timeseries-analysis.adapter.fromArray)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>fromDB (data, options)](#apidoc.element.timeseries-analysis.adapter.fromDB)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>geometric (options)](#apidoc.element.timeseries-analysis.adapter.geometric)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>sin (options)](#apidoc.element.timeseries-analysis.adapter.sin)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>tan (options)](#apidoc.element.timeseries-analysis.adapter.tan)

#### [module timeseries-analysis.main](#apidoc.module.timeseries-analysis.main)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.</span>main (data, options)](#apidoc.element.timeseries-analysis.main.main)

#### [module timeseries-analysis.main.prototype](#apidoc.module.timeseries-analysis.main.prototype)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>ARLeastSquare (options)](#apidoc.element.timeseries-analysis.main.prototype.ARLeastSquare)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>ARMaxEntropy (options)](#apidoc.element.timeseries-analysis.main.prototype.ARMaxEntropy)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>SolveLE (mat, vec, n)](#apidoc.element.timeseries-analysis.main.prototype.SolveLE)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>chart (options)](#apidoc.element.timeseries-analysis.main.prototype.chart)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>clone ()](#apidoc.element.timeseries-analysis.main.prototype.clone)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>cycle (options)](#apidoc.element.timeseries-analysis.main.prototype.cycle)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>dsp_itrend (options)](#apidoc.element.timeseries-analysis.main.prototype.dsp_itrend)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>durbinWatson ()](#apidoc.element.timeseries-analysis.main.prototype.durbinWatson)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>ema (options)](#apidoc.element.timeseries-analysis.main.prototype.ema)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>fill (value, n)](#apidoc.element.timeseries-analysis.main.prototype.fill)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>lwma (options)](#apidoc.element.timeseries-analysis.main.prototype.lwma)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>ma (options)](#apidoc.element.timeseries-analysis.main.prototype.ma)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>max ()](#apidoc.element.timeseries-analysis.main.prototype.max)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>mean (data)](#apidoc.element.timeseries-analysis.main.prototype.mean)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>min ()](#apidoc.element.timeseries-analysis.main.prototype.min)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>noiseData ()](#apidoc.element.timeseries-analysis.main.prototype.noiseData)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>offset (value, data, ret)](#apidoc.element.timeseries-analysis.main.prototype.offset)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>osc ()](#apidoc.element.timeseries-analysis.main.prototype.osc)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>outliers (options)](#apidoc.element.timeseries-analysis.main.prototype.outliers)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>output ()](#apidoc.element.timeseries-analysis.main.prototype.output)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>pixelize (options)](#apidoc.element.timeseries-analysis.main.prototype.pixelize)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>regression_analysis ()](#apidoc.element.timeseries-analysis.main.prototype.regression_analysis)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>regression_forecast (options)](#apidoc.element.timeseries-analysis.main.prototype.regression_forecast)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>regression_forecast_mse (options)](#apidoc.element.timeseries-analysis.main.prototype.regression_forecast_mse)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>regression_forecast_optimize (options)](#apidoc.element.timeseries-analysis.main.prototype.regression_forecast_optimize)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>reset ()](#apidoc.element.timeseries-analysis.main.prototype.reset)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>save (name, options)](#apidoc.element.timeseries-analysis.main.prototype.save)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>slice (from, to)](#apidoc.element.timeseries-analysis.main.prototype.slice)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>sliding_regression_forecast (options)](#apidoc.element.timeseries-analysis.main.prototype.sliding_regression_forecast)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>smoother (options)](#apidoc.element.timeseries-analysis.main.prototype.smoother)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>standardize (options)](#apidoc.element.timeseries-analysis.main.prototype.standardize)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>stdev (data)](#apidoc.element.timeseries-analysis.main.prototype.stdev)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>supports (options)](#apidoc.element.timeseries-analysis.main.prototype.supports)
1.  [function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>toArray ()](#apidoc.element.timeseries-analysis.main.prototype.toArray)



# <a name="apidoc.module.timeseries-analysis"></a>[module timeseries-analysis](#apidoc.module.timeseries-analysis)

#### <a name="apidoc.element.timeseries-analysis.main"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.</span>main (data, options)](#apidoc.element.timeseries-analysis.main)
- description and source-code
```javascript
main = function (data, options) {
	<span class="apidocCodeCommentSpan">/*
		Data Format:
		[
			[Date Object, value],
			[Date Object, value]
		]
	*/
</span>	this.options 	= _.extend({
		
	}, options);
	
	this.data 		= data;
	this.original	= data.slice(0);
	this.buffer 	= [];
	this.saved 		= [];
	
	return this;
}
```
- example usage
```shell
...
'''
'date' can be in any format you want, but it is recommanded you use date value that is comaptible with a JS Date object.

'value' must be a number.

'''
// Load the data
var t     = new timeseries.main(data);
'''

### Loading from a database ###
Alternatively, you can also load the data from your database:
'''
// Unfiltered data out of MongoDB:
var data = [{
...
```



# <a name="apidoc.module.timeseries-analysis.adapter"></a>[module timeseries-analysis.adapter](#apidoc.module.timeseries-analysis.adapter)

#### <a name="apidoc.element.timeseries-analysis.adapter.complex"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>complex (options)](#apidoc.element.timeseries-analysis.adapter.complex)
- description and source-code
```javascript
complex = function (options) {
	options = _.extend({
		cycles:		10,
		quality:	1,
		inertia:	0
	}, options);
	
	
	var i;
	var j;
	var output = [];
	for (i=0;i<options.cycles;i++) {
		for (j=0;j<360;j+=options.quality) {
			output.push([
				new Date(),
				(Math.sin(j*Math.PI/180)+Math.cos(j*3*Math.PI/180)-Math.sin(j*2.4*Math.PI/180))*100
			]);
			options.quality += options.inertia;
		}
	}
	return output;
}
```
- example usage
```shell
...


Now, let's try on a more complex data.

Wee're going to generate a dataset using ![sin(x)+cos(x*3)-sin(x 2.4)*100](http://rogercortesi.com/eqn/tempimagedir/eqn3983.png),
with a frequency increasing with time.

'''
var t     	= new ts.main(ts.adapter.complex({cycles:10, inertia:0.1}));
'''
![chart](https://chart.googleapis.com/chart?chm=&cht=lc&chs=800x200&chxt=y&chd=s:mmllkjihgfecbZYWUSRQPONOOPRUXaejnsx15799851vpiaTMGCAACGLRXdhjjhdXRKFBACFLSYfmicWROOSakv4882reRGABHQahjgZPGBBGPZmgYQNScq395tcLBBKWgjeTHBCLXmeUORdu78vbIAFTgjbNCBKYmdROXq68sUDCPejaKBESmbPPf09xXDCShhSDCPmaOSn75hHBQhgQBFWmZOWv9vRAKeiRBFYmYNb18jGDXjXDEXmXOg53XALheJBS
&chco=76a4fb&chds=-205.05356081386265,286.52738649942415&chxr=0,-205.05356081386265,286.52738649942415,10)

Now we forecast the same way we did in the previous example on the sin wave:

'''
var t         = new ts.main(ts.adapter.complex({cycles:10, inertia:0.1}));
...
```

#### <a name="apidoc.element.timeseries-analysis.adapter.fromArray"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>fromArray (data)](#apidoc.element.timeseries-analysis.adapter.fromArray)
- description and source-code
```javascript
fromArray = function (data) {
	return _.map(data, function(datapoint) {
		return [new Date(), datapoint];
	});
}
```
- example usage
```shell
...
### Loading from an array ###
Finaly, you can load the data from an array:
'''
// Data out of MongoDB:
var data = [12,16,14,13,11,10,9,11,23,...];

// Load the data
var t     = new timeseries.main(timeseries.adapter.fromArray(data));
'''

### Chaining ###
You can chain the methods. For example, you can calculate the moving average, then apply a Linear Weighted Moving Average on top
 of the first Moving Average:

't.ma().lwma();'
...
```

#### <a name="apidoc.element.timeseries-analysis.adapter.fromDB"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>fromDB (data, options)](#apidoc.element.timeseries-analysis.adapter.fromDB)
- description and source-code
```javascript
fromDB = function (data, options) {
	options = _.extend({
		value:		'close',
		date:		'date'
	}, options);
	
	return _.map(data, function(datapoint) {
		return [new Date(datapoint[options.date]).getTime(), datapoint[options.value]];
	});
}
```
- example usage
```shell
...
        "symbol": "fb",
        "volume": 26440600
    },
    ...
];

// Load the data
var t     = new timeseries.main(timeseries.adapter.fromDB(data, {
    date:   'date',     // Name of the property containing the Date (must be compatible with new Date(date) )
    value:  'close'     // Name of the property containign the value. here we'll use the "close" price.
}));
'''

This is the data I will use in the doc:
![Chart](https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:ebgfqpqtzv40yxvrw740914wswyupqdgPRNOXYLAB&chco=76a4fb
&chm=&chds=56.75,72.03&chxr=0,56.75,72.03,10)
...
```

#### <a name="apidoc.element.timeseries-analysis.adapter.geometric"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>geometric (options)](#apidoc.element.timeseries-analysis.adapter.geometric)
- description and source-code
```javascript
geometric = function (options) {
	options = _.extend({
	}, options);
	
	
	var i;
	var j;
	var output = [];
	for (i=0;i<128;i++) {
		output.push([
			new Date(),
			Math.cos(i*0.01)+0.75*Math.cos(i*0.03)+0.5*Math.cos(i*0.05)+0.25*Math.cos(i*0.11)
		]);
	}
	return output;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.timeseries-analysis.adapter.sin"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>sin (options)](#apidoc.element.timeseries-analysis.adapter.sin)
- description and source-code
```javascript
sin = function (options) {
	options = _.extend({
		cycles:		4,
		quality:	2,
		inertia:	0	
	}, options);
	
	var i;
	var j;
	var output 	= [];
	for (i=0;i<options.cycles;i++) {
		for (j=0;j<360;j+=options.quality) {
			output.push([
				new Date(),
				Math.cos(j*Math.PI/180)*100
			]);
			options.quality += options.inertia;
		}
		console.log("options.quality",options.quality);
	}
	return output;
}
```
- example usage
```shell
...
Both methods have a 'degree' parameter that let you define what AR degree you wish to calculate. The default is 5.

*Both methods were ported to Javascript for this package from [Paul Bourke's C code](http://paulbourke.net/miscellaneous/ar/). Credit
 to Alex Sergejew, Nick Hawthorn and Rainer Hegger for the original code of the Max Entropy method. Credit to Rainer Hegger for
the original code of the Least Square method.*

#### Calculating the AR coefficients ####
Let's generate a simple sin wave:
'''
var t     	= new ts.main(ts.adapter.sin({cycles:4}));
'''

![chart](https://chart.googleapis.com/chart?chm=&cht=lc&chs=800x200&chxt=y&chd=s:999999888877665544332100zyxwwvutsrqponmlkjihgfdcbaZYXWVUTSRQPONNMLKJJIHGGFFEEDDCCBBBBAAAAAAAAAAABBBBCCDDEEFFGGHIJJKLMNNOPQRSTUVWXYZabcdeghijklmnopqrstuvwwxyz00123344556677888899999999999888877665544332100zyxwwvutsrqponmlkjihgfdcbaZYXWVUTSRQPONNMLKJJIHGGFFEEDDCCBBBBAAAAAAAAAAABBBBCCDDEEFFGGHIJJKLMNNOPQRSTUVWXYZabcdeghijklmnopqrstuvwwxyz00123344556677888899999999999888877665544332100zyxwwvutsrqponmlkjihgfdcbaZYXWVUTSRQPONNMLKJJIHGGFFEEDDCCBBBBAAAAAAAAAAABBBBCCDDEEFFGGHIJJKLMNNOPQRSTUVWXYZabcdeghijklmnopqrstuvwwxyz00123344556677888899999999999888877665544332100zyxwwvutsrqponmlkjihgfdcbaZYXWVUTSRQPONNMLKJJIHGGFFEEDDCCBBBBAAAAAAAAAAABBBBCCDDEEFFGGHIJJKLMNNOPQRSTUVWXYZabcdeghijklmnopqrstuvwwxyz00123344556677888899999
&chco=76a4fb&chds=-100,100&chxr=0,-100,100,10)

Now we get the coefficients (default: degree 5) using the Max Entropy method:
'''
var coeffs = t.ARMaxEntropy();
...
```

#### <a name="apidoc.element.timeseries-analysis.adapter.tan"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.adapter.</span>tan (options)](#apidoc.element.timeseries-analysis.adapter.tan)
- description and source-code
```javascript
tan = function (options) {
	options = _.extend({
		cycles:		1
	}, options);
	var i;
	var j;
	var output = [];
	for (i=0;i<options.cycles;i++) {
		for (j=0;j<360;j++) {
			output.push([
				new Date(),
				Math.tan(j*Math.PI/180)
			]);
		}
	}
	return output;
}
```
- example usage
```shell
...
	var i;
	var j;
	var output = [];
	for (i=0;i<options.cycles;i++) {
		for (j=0;j<360;j++) {
			output.push([
				new Date(),
				Math.tan(j*Math.PI/180)
			]);
		}
	}
	return output;
};
...
```



# <a name="apidoc.module.timeseries-analysis.main"></a>[module timeseries-analysis.main](#apidoc.module.timeseries-analysis.main)

#### <a name="apidoc.element.timeseries-analysis.main.main"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.</span>main (data, options)](#apidoc.element.timeseries-analysis.main.main)
- description and source-code
```javascript
main = function (data, options) {
	<span class="apidocCodeCommentSpan">/*
		Data Format:
		[
			[Date Object, value],
			[Date Object, value]
		]
	*/
</span>	this.options 	= _.extend({
		
	}, options);
	
	this.data 		= data;
	this.original	= data.slice(0);
	this.buffer 	= [];
	this.saved 		= [];
	
	return this;
}
```
- example usage
```shell
...
'''
'date' can be in any format you want, but it is recommanded you use date value that is comaptible with a JS Date object.

'value' must be a number.

'''
// Load the data
var t     = new timeseries.main(data);
'''

### Loading from a database ###
Alternatively, you can also load the data from your database:
'''
// Unfiltered data out of MongoDB:
var data = [{
...
```



# <a name="apidoc.module.timeseries-analysis.main.prototype"></a>[module timeseries-analysis.main.prototype](#apidoc.module.timeseries-analysis.main.prototype)

#### <a name="apidoc.element.timeseries-analysis.main.prototype.ARLeastSquare"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>ARLeastSquare (options)](#apidoc.element.timeseries-analysis.main.prototype.ARLeastSquare)
- description and source-code
```javascript
ARLeastSquare = function (options) {
	// Credits to Rainer Hegger (1998)
	// Ported to Javascript by Julien Loutre for timeseries-analysis, from Paul Bourke's C code.
	var scope = this;
	
	options = _.extend({
		degree:			5,
		data:			this.data
	}, options);
	
	var i,j,k,hj,hi;
	var coefficients = [];
	
	var length 	= options.data.length;
	var mat 	= this.fill([], options.degree);
	mat			= _.map(mat, function(d1) {
		return scope.fill(0, options.degree);
	});
	
	for (i=0;i < options.degree;i++) {
		coefficients[i] = 0.0;
		for (j=0;j< options.degree;j++) {
			mat[i][j] = 0.0;
		}
	}
	for (i=options.degree-1;i < length-1;i++) {
		hi = i + 1;
		for (j=0;j < options.degree;j++) {
			hj = i - j;
			coefficients[j] += (options.data[hi][1] * options.data[hj][1]);
			for (k=j;k < options.degree;k++) {
				mat[j][k] += (options.data[hj][1] * options.data[i-k][1]);
			}
		}
	}
	for (i=0;i < options.degree;i++) {
		coefficients[i] /= (length - options.degree);
		for (j=i;j < options.degree;j++) {
			mat[i][j] /= (length - options.degree);
			mat[j][i] = mat[i][j];
		}
	}
	
	var solved = this.SolveLE(mat,coefficients,options.degree);
	
	return coefficients;
	
}
```
- example usage
```shell
...
-0.9993685753936928
]
*/
'''

Now let's calculate the coefficents using the Least Square method:
'''
var coeffs = t.ARLeastSquare();
/* returns:
[
-0.1330958776419982,
1.1764459735164208,
1.3790630711914558,
-0.7736249950234015,
-0.6559429479401289
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.ARMaxEntropy"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>ARMaxEntropy (options)](#apidoc.element.timeseries-analysis.main.prototype.ARMaxEntropy)
- description and source-code
```javascript
ARMaxEntropy = function (options) {
	// Credits to Alex Sergejew, Nick Hawthorn, Rainer Hegger (1998)
	// Zero-Indexed arrays modification by Paul Sanders (the arrays were One-indexed, FORTRAN style)
	// Ported to Javascript by Julien Loutre for timeseries-analysis, from Paul Bourke's C code.
	
	options = _.extend({
		degree:			5,
		data:			this.data,
		intermediates:	false	// Generates and returns the intermediates, a 2D array, instead of the coefficients.
	}, options);
	
	var scope	= this;
	var i;
	var length 	= options.data.length;
	var pef 	= this.fill(0, length);
	var per 	= this.fill(0, length);
	var ar 		= this.fill([], options.degree+1);
	ar			= _.map(ar, function(d1) {
		return scope.fill(0, options.degree+1);
	});
	var h 		= this.fill(0, length);
	var g		= this.fill(0, options.degree+2);
	
	var t1, t2;
	var n;
	
	var coef	= [];
	
	for (n=1; n <= options.degree; n++)
	{
		var sn = 0.0;
		var sd = 0.0;
		var j;
		var jj = length - n;
	
		for (j = 0; j < jj; j++)
		{
			t1 = options.data[j + n][1] + pef[j];
			t2 = options.data[j][1] + per[j];
			sn -= 2.0 * t1 * t2;
			sd += (t1 * t1) + (t2 * t2);
		}
	
		t1 = g[n] = sn / sd;
		if (n != 1)
		{
			for (j = 1; j < n; j++) {
				h[j] = g[j] + t1 * g[n - j];
			}
			for (j = 1; j < n; j++) {
				g[j] = h[j];
			}
			jj--;
		}
	
		for (j = 0; j < jj; j++)
		{
			per [j] += t1 * pef[j] + t1 * options.data[j + n][1];
			pef [j] = pef[j + 1] + t1 * per[j + 1] + t1 * options.data[j + 1][1];
		}
	
		if (options.intermediates) {
			for (j = 0; j < n; j++) {
				ar[n][j] = g[j + 1];
			}
		}
		
	}
	if (!options.intermediates) {
		for (n = 0; n < options.degree; n++) {
			coef[n] = g[n + 1];
		}
		return coef;
	} else {
		return ar;
	}
	
}
```
- example usage
```shell
...
var t     	= new ts.main(ts.adapter.sin({cycles:4}));
'''

![chart](https://chart.googleapis.com/chart?chm=&cht=lc&chs=800x200&chxt=y&chd=s:999999888877665544332100zyxwwvutsrqponmlkjihgfdcbaZYXWVUTSRQPONNMLKJJIHGGFFEEDDCCBBBBAAAAAAAAAAABBBBCCDDEEFFGGHIJJKLMNNOPQRSTUVWXYZabcdeghijklmnopqrstuvwwxyz00123344556677888899999999999888877665544332100zyxwwvutsrqponmlkjihgfdcbaZYXWVUTSRQPONNMLKJJIHGGFFEEDDCCBBBBAAAAAAAAAAABBBBCCDDEEFFGGHIJJKLMNNOPQRSTUVWXYZabcdeghijklmnopqrstuvwwxyz00123344556677888899999999999888877665544332100zyxwwvutsrqponmlkjihgfdcbaZYXWVUTSRQPONNMLKJJIHGGFFEEDDCCBBBBAAAAAAAAAAABBBBCCDDEEFFGGHIJJKLMNNOPQRSTUVWXYZabcdeghijklmnopqrstuvwwxyz00123344556677888899999999999888877665544332100zyxwwvutsrqponmlkjihgfdcbaZYXWVUTSRQPONNMLKJJIHGGFFEEDDCCBBBBAAAAAAAAAAABBBBCCDDEEFFGGHIJJKLMNNOPQRSTUVWXYZabcdeghijklmnopqrstuvwwxyz00123344556677888899999
&chco=76a4fb&chds=-100,100&chxr=0,-100,100,10)

Now we get the coefficients (default: degree 5) using the Max Entropy method:
'''
var coeffs = t.ARMaxEntropy();
/* returns:
[
-4.996911311490191,
9.990105570823655,
-9.988844272139962,
4.995018589153196,
-0.9993685753936928
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.SolveLE"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>SolveLE (mat, vec, n)](#apidoc.element.timeseries-analysis.main.prototype.SolveLE)
- description and source-code
```javascript
SolveLE = function (mat, vec, n) {
	// Gaussian elimination solver.
	// Use the coefficients from the Least Square method and make it into the real AR coefficients.
	// Original code by Rainer Hegger (1998). Modified by Paul Bourke.
	// Ported to Javascript by Julien Loutre for timeseries-analysis, from Paul Bourke's C code.
	
	var i,j,k,maxi;
	var vswap 		= [];
	var mswap 		= [];
	var hvec 		= [];
	var max,h,pivot,q;
	
	for (i=0;i<n-1;i++) {
		max = Math.abs(mat[i][i]);
		maxi = i;
		for (j=i+1;j<n;j++) {
			if ((h = Math.abs(mat[j][i])) > max) {
				max = h;
				maxi = j;
			}
		}
		if (maxi != i) {
			mswap     = mat[i];
			mat[i]    = mat[maxi];
			mat[maxi] = mswap;
			vswap     = vec[i];
			vec[i]    = vec[maxi];
			vec[maxi] = vswap;
		}
	
		hvec = mat[i];
		pivot = hvec[i];
		if (Math.abs(pivot) == 0.0) {
			console.log("Singular matrix - fatal!");
			return false;
		}
		for (j=i+1;j<n;j++) {
			q = - mat[j][i] / pivot;
			mat[j][i] = 0.0;
			for (k=i+1;k<n;k++) {
				mat[j][k] += q * hvec[k];
			}
			vec[j] += (q * vec[i]);
		}
	}
	vec[n-1] /= mat[n-1][n-1];
	for (i=n-2;i>=0;i--) {
		hvec = mat[i];
		for (j=n-1;j>i;j--) {
			vec[i] -= (hvec[j] * vec[j]);
		}
		vec[i] /= hvec[i];
	}
	
	return vec;
}
```
- example usage
```shell
...
		coefficients[i] /= (length - options.degree);
		for (j=i;j < options.degree;j++) {
			mat[i][j] /= (length - options.degree);
			mat[j][i] = mat[i][j];
		}
	}
	
	var solved = this.SolveLE(mat,coefficients,options.degree);
	
	return coefficients;
	
}

timeseries.prototype.SolveLE = function(mat, vec, n) {
	// Gaussian elimination solver.
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.chart"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>chart (options)](#apidoc.element.timeseries-analysis.main.prototype.chart)
- description and source-code
```javascript
chart = function (options) {
	
	options = _.extend({
		main:		false,
		width:		800,
		height:		200,
		bands:		[],
		lines:		[],
		points:		[]
	}, options);
	
	// Google Chart
	var chart = new gimage.line({
		width:	options.width,
		height:	options.height,
		bands:	options.bands,
		hlines:	options.lines,
		points:	options.points,
		autoscale:	true
	});
	chart.fromTimeseries(this.data);
	// Include the original data
	if (options.main) {
		chart.fromTimeseries(this.original);
	}
	
	// Include saved data
	_.each(this.saved, function(saved) {
		chart.fromTimeseries(saved.data);
	});
	
	return chart.render();
}
```
- example usage
```shell
...
'var processed = t.ma().output();'

### Charting ###
#### Charting the current buffer ####
You can plot your data using Google Static Image Chart, as simply as calling the 'chart()' method:

'''
var chart_url = t.ma({period: 14}).chart();
// returns https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:JDOLhghn0s92xuilnptvxz1110zzzyyvrlgZUPMHA&chco=76a4fb
&chm=&chds=63.13,70.78&chxr=0,63.13,70.78,10
'''
![chart](https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:JDOLhghn0s92xuilnptvxz1110zzzyyvrlgZUPMHA&chco=76a4fb
&chm=&chds=63.13,70.78&chxr=0,63.13,70.78,10)

#### Charting the original data ####
You can include the original data in your chart:
'''
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.clone"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>clone ()](#apidoc.element.timeseries-analysis.main.prototype.clone)
- description and source-code
```javascript
clone = function () {
	var buffer = _.map(this.data, function(point) {
		return [
			point[0],
			point[1]*1
		];
	});
	return buffer;
}
```
- example usage
```shell
...
	
	var i;
	var j;
	var l = this.data.length;
	
	var mean	= this.mean();
	this.offset(-mean);
	var backup 	= this.clone();
	var buffer 	= this.clone();
	
	var sample 		= buffer.slice(options.start-1-options.sample, options.start);
	
	// The current data to process is only a sample of the real data.
	this.data		= sample;
	// Get the AR coeffs
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.cycle"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>cycle (options)](#apidoc.element.timeseries-analysis.main.prototype.cycle)
- description and source-code
```javascript
cycle = function (options) {
	options = _.extend({
		period:		10,
		forecast:	false,
		forecast_length:	20
	}, options);
	
	// Smooth the data
	this.smoother(options);
	
	
	
	// Copy the data
	var buffer 				= [];
	var buffer_forecast 	= [];
	
	var i;
	var j;
	var l = this.data.length;
	for (i=0;i<2;i++) {
		buffer[i] = ([
			this.data[i][0],
			this.data[i][1]
		]);
		buffer_forecast[i] = ([
			this.data[i][0],
			this.data[i][1]
		]);
	}
	for (i=2;i<l;i++) {
		// We find the ratio
		var d1 		= this.data[i][1]-this.data[i-1][1];
		var d2 		= this.data[i][1]-this.data[i-2][1];
		var ratio	= d1/d2;
		console.log("ratio",ratio, d1, d2);
		buffer[i] = ([
			this.data[i][0],
			this.data[i][1]
		]);
		
		buffer_forecast[i] = ([
			this.data[i][0],
			this.data[i][1],
			ratio,
			d1>0,
			d2>0
		]);
		
	}
	
	if (options.forecast) {
		for (i=2;i<l;i++) {
			if (options.forecast == i) {
				
				// Generate a two cycles sin wave
				var sin = [];
				for (j=0;j<720;j++) {
					sin.push(Math.sin(j*Math.PI/180));
				}
				console.log("sin",sin);
				
				// Find the closest sin wave
				var MSE = [];
				var minMSE	= 10000000;
				var pos;
				for (j=2;j<720;j++) {
					var d1 		= sin[j]-sin[j-1];
					var d2 		= sin[j]-sin[j-2];
					var ratio	= d1/d2;
					var mse		= (ratio-buffer_forecast[i][2])*(ratio-buffer_forecast[i][2]);
					if (mse <= minMSE && ((d1>0)==buffer_forecast[i][3]) && ((d2>0)==buffer_forecast[i][3])) {
						minMSE 	= mse;
						pos		= j;
					}
				}
				console.log("minMSE",minMSE, pos);
				
				for (j=0;j<=options.forecast_length;j++) {
					buffer_forecast[i+j][1] = Math.sin((pos+j)*Math.PI/180);
					
					//buffer_forecast[i+j][1] = sin[pos+j];
					
					console.log("buffer_forecast["+(i+j)+"]", pos+j, buffer_forecast[i+j][1]);
				}
				
				break;
			}
		}
		this.data = buffer_forecast;
	} else {
		this.data = buffer;
	}
	
	return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.dsp_itrend"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>dsp_itrend (options)](#apidoc.element.timeseries-analysis.main.prototype.dsp_itrend)
- description and source-code
```javascript
dsp_itrend = function (options) {
	// By Ehler
	// http://www.davenewberg.com/Trading/TS_Code/Ehlers_Indicators/iTrend_Ind.html
	options = _.extend({
		alpha:		0.7,
		use:		'main'
	}, options);
	var i;
	var j;
	var l 	= this.data.length;
	
	var trigger 	= [];
	
	// Reset the buffer
	this.buffer 	= [];
	
	// Leave the datapoints [0;period[ intact
	this.buffer 	= this.data.slice(0, 3);
	this.trigger 	= this.data.slice(0, 3);
	
	for (i=3;i<l;i++) {
		this.buffer[i] = [
			this.data[i][0],
			(options.alpha-(options.alpha*options.alpha)/4)*this.data[i][1] + (0.5*(options.alpha*options.alpha)*this.data[i-1][1]) - (options
.alpha - 0.75*(options.alpha*options.alpha)) * this.data[i-2][1] + 2*(1-options.alpha)*this.buffer[i-1][1] - (1-options.alpha)*(
1-options.alpha)*this.buffer[i-2][1]
		];
		this.trigger[i] = [
			this.data[i][0],
			2*this.buffer[i][1]-this.buffer[i-2][1]
		]
	}
	if (options.use == 'trigger') {
		this.data = this.trigger;
	} else{
		this.data = this.buffer;
	}
	
	return this;
}
```
- example usage
```shell
...
});
'''
![chart](https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:ebgfqpghlnstvyzzzxwwxz25322zyvutrnidXUQRQ,ebgfqpqtzv40yxvrw740914wswyupqdgPRNOXYLAB
&chco=76a4fb,ac7cc7&chm=&chds=56.75,72.03&chxr=0,56.75,72.03,10)

#### John Ehlers iTrend ####
Created by John Ehlers to smooth noisy data without lag. 'alpha' must be between 0 and 1.
'''
t.dsp_itrend({
   alpha:   0.7
});
'''
![chart](https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:gdijntstyz140xwst3835630ttxwrpjeXPPOVbUGA,gdigrqru0w41yxvrx741925xtwyvqrfiRTPQZaNDE
&chco=76a4fb,ac7cc7&chm=&chds=56.02406150533825,72.03&chxr=0,56.02406150533825,72.03,10)

## Noise Removal ##
Most smoothing algorithms induce lag in the data. Algorithms like Ehler's iTrend algorithm has no lag, but won't be able to perform
 really well on a really noisy dataset as you can see in the example above.
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.durbinWatson"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>durbinWatson ()](#apidoc.element.timeseries-analysis.main.prototype.durbinWatson)
- description and source-code
```javascript
durbinWatson = function () {
	return this.regression_analysis().durbinWatson;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.ema"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>ema (options)](#apidoc.element.timeseries-analysis.main.prototype.ema)
- description and source-code
```javascript
ema = function (options) {
	options = _.extend({
		period:		12
	}, options);
	var i;
	var j;
	var l 	= this.data.length;
	var sum	= 0;
	
	// Reset the buffer
	this.buffer 	= [];
	
	// Leave the datapoints [0;period[ intact
	this.buffer = this.data.slice(0, options.period);
	
	var m	= 2/(options.period+1);	// Multiplier
	
	for (i=options.period;i<l;i++) {
		this.buffer[i] = [
			this.data[i][0],
			(this.data[i][1]-this.data[i-1][1])*m+this.data[i-1][1]
		];
	}
	this.data = this.buffer;
	return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.fill"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>fill (value, n)](#apidoc.element.timeseries-analysis.main.prototype.fill)
- description and source-code
```javascript
fill = function (value, n) {
	var array = [];
	var i;
	for (i=0;i<n;i++) {
		array.push(value);
	}
	return array;
}
```
- example usage
```shell
...
		data:			this.data,
		intermediates:	false	// Generates and returns the intermediates, a 2D array, instead of the coefficients.
	}, options);
	
	var scope	= this;
	var i;
	var length 	= options.data.length;
	var pef 	= this.fill(0, length);
	var per 	= this.fill(0, length);
	var ar 		= this.fill([], options.degree+1);
	ar			= _.map(ar, function(d1) {
		return scope.fill(0, options.degree+1);
	});
	var h 		= this.fill(0, length);
	var g		= this.fill(0, options.degree+2);
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.lwma"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>lwma (options)](#apidoc.element.timeseries-analysis.main.prototype.lwma)
- description and source-code
```javascript
lwma = function (options) {
	options = _.extend({
		period:		12
	}, options);
	var i;
	var j;
	var l 	= this.data.length;
	var sum	= 0;
	var n	= 0;
	
	// Reset the buffer
	this.buffer 	= [];
	
	// Leave the datapoints [0;period[ intact
	this.buffer = this.data.slice(0, options.period);
	
	for (i=options.period;i<l;i++) {
		sum	= 0;
		n	= 0;
		for (j=options.period;j>0;j--) {
			sum += this.data[i-j][1]*j;
			n += j;
		}
		this.buffer[i] = [this.data[i][0], sum/n];
	}
	this.data = this.buffer;
	return this;
}
```
- example usage
```shell
...
// Load the data
var t     = new timeseries.main(timeseries.adapter.fromArray(data));
'''

### Chaining ###
You can chain the methods. For example, you can calculate the moving average, then apply a Linear Weighted Moving Average on top
 of the first Moving Average:

't.ma().lwma();'

### Getting the data ###
When you are done processing the data, you can get the processed timeseries using 'output()':

'var processed = t.ma().output();'

### Charting ###
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.ma"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>ma (options)](#apidoc.element.timeseries-analysis.main.prototype.ma)
- description and source-code
```javascript
ma = function (options) {
	options = _.extend({
		period:		12
	}, options);
	var i;
	var j;
	var l 	= this.data.length;
	var sum	= 0;
	
	// Reset the buffer
	this.buffer 	= [];
	
	// Leave the datapoints [0;period[ intact
	this.buffer = this.data.slice(0, options.period);
	
	for (i=options.period;i<l;i++) {
		sum	= 0;
		for (j=options.period;j>0;j--) {
			sum += this.data[i-j][1];
		}
		this.buffer[i] = [this.data[i][0], sum/options.period];
	}
	this.data = this.buffer;
	return this;
}
```
- example usage
```shell
...
// Load the data
var t     = new timeseries.main(timeseries.adapter.fromArray(data));
'''

### Chaining ###
You can chain the methods. For example, you can calculate the moving average, then apply a Linear Weighted Moving Average on top
 of the first Moving Average:

't.ma().lwma();'

### Getting the data ###
When you are done processing the data, you can get the processed timeseries using 'output()':

'var processed = t.ma().output();'

### Charting ###
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.max"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>max ()](#apidoc.element.timeseries-analysis.main.prototype.max)
- description and source-code
```javascript
max = function () {
	var array = this.toArray();
	return _.max(array);
}
```
- example usage
```shell
...
## Stats ##
You can obtain stats about your data. The stats will be calculated based on the current buffer.

#### Min ####
'var min = t.min(); // 56.75'

#### Max ####
'var max = t.max(); // 72.03'

#### Mean (Avegare) ####
'var mean = t.mean();   // 66.34024390243898'

#### Standard Deviation ####
'var stdev = t.stdev(); // 3.994277911972647'
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.mean"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>mean (data)](#apidoc.element.timeseries-analysis.main.prototype.mean)
- description and source-code
```javascript
mean = function (data) {
	if (!data) {
		var data = this.data;
	}
	var sum 	= 0;
	var n 		= 0;
	_.each(data, function(datapoint) {
		sum += datapoint[1];
		n++;
	});
	return sum/n;
}
```
- example usage
```shell
...
#### Min ####
'var min = t.min(); // 56.75'

#### Max ####
'var max = t.max(); // 72.03'

#### Mean (Avegare) ####
'var mean = t.mean();   // 66.34024390243898'

#### Standard Deviation ####
'var stdev = t.stdev(); // 3.994277911972647'


## Smoothing ##
There are a few smoothing options implemented:
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.min"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>min ()](#apidoc.element.timeseries-analysis.main.prototype.min)
- description and source-code
```javascript
min = function () {
	var array = this.toArray();
	return _.min(array);
}
```
- example usage
```shell
...
'''
![chart](https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:ebgfqpqthjnptuwyzyzyxyy024211yxusrojfbWUQ,ebgfqpqtzv40yxvrw740914wswyupqdgPRNOXYLAB
,ebgfqpqtknqtvwxyxxyyy0022200zwvrpmidZXVTP,ebgfqpqthjnptuwyzyzyxyy024211yxusrojfbWUQ&chco=76a4fb,9190e1,ac7cc7,c667ad&chm=&chds=
56.75,72.03&chxr=0,56.75,72.03,10)

## Stats ##
You can obtain stats about your data. The stats will be calculated based on the current buffer.

#### Min ####
'var min = t.min(); // 56.75'

#### Max ####
'var max = t.max(); // 72.03'

#### Mean (Avegare) ####
'var mean = t.mean();   // 66.34024390243898'
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.noiseData"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>noiseData ()](#apidoc.element.timeseries-analysis.main.prototype.noiseData)
- description and source-code
```javascript
noiseData = function () {
	var i;
	var j;
	var l 	= this.data.length;
	var sum	= 0;
	
	// Reset the buffer
	this.buffer 	= [];
	
	for (i=0;i<l;i++) {
		this.buffer[i] = [
			this.data[i][0],
			this.original[i][1]-this.data[i][1]
		];
	}
	this.data = this.buffer;
	return this;
}
```
- example usage
```shell
...
});
'''
![chart](https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:ebehknprsuvwxxyzz000zzyxvtqolifcaXUROLHEB,ebgfqpqtzv40yxvrw740914wswyupqdgPRNOXYLAB
&chco=76a4fb,ac7cc7&chm=&chds=56.75,72.03&chxr=0,56.75,72.03,10)

#### Noise separation ####
You can extract the noise from the signal.
'''
t.smoother({period:10}).noiseData();
// Here, we add a line on y=0, and we don't display the orignal data.
var chart_url = t.chart({main:false, lines:[0]})
'''
![chart](https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:cchVrifiugzogaTHTvnd0itbUjurmwYmANKU09lSc,cc&chco=76a4fb
,ABABAB&chm=&chds=-2.772930015555005,3.273743787160555&chxr=0,-2.772930015555005,3.273743787160555,10)

You can also smooth the noise, to attempt to find patterns:
'''
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.offset"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>offset (value, data, ret)](#apidoc.element.timeseries-analysis.main.prototype.offset)
- description and source-code
```javascript
offset = function (value, data, ret) {
	if (!data) {
		var data = this.data;
	}
	var i;
	var j;
	var l 	= data.length;
	var sum	= 0;
	
	// Reset the buffer
	this.buffer 	= data.slice(0);
	
	for (i=0;i<l;i++) {
		this.buffer[i] = [
			this.buffer[i][0],
			this.buffer[i][1]+value
		];
	}
	if (!ret) {
		this.data = this.buffer;
		return this;
	} else {
		return this.buffer;
	}
}
```
- example usage
```shell
...
	},options);
	
	var i;
	var j;
	var l = this.data.length;
	
	var mean	= this.mean();
	this.offset(-mean);
	var backup 	= this.clone();
	var buffer 	= this.clone();
	
	var sample 		= buffer.slice(options.start-1-options.sample, options.start);
	
	// The current data to process is only a sample of the real data.
	this.data		= sample;
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.osc"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>osc ()](#apidoc.element.timeseries-analysis.main.prototype.osc)
- description and source-code
```javascript
osc = function () {
	var i;
	var j;
	var l 	= this.data.length;
	var sum	= 0;
	
	// Reset the buffer
	this.buffer 	= [];
	
	for (i=0;i<l;i++) {
		if (i<=1) {
			this.buffer[i] = [
				this.data[i][0],
				0
			];
		} else {
			this.buffer[i] = [
				this.data[i][0],
				this.data[i][1]-this.data[i-1][1]
			];
		}
	}
	this.data = this.buffer;
	return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.outliers"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>outliers (options)](#apidoc.element.timeseries-analysis.main.prototype.outliers)
- description and source-code
```javascript
outliers = function (options) {
	// Original code by Professor Hossein Arsham - http://home.ubalt.edu/ntsbarsh/Business-stat/otherapplets/Outlier.htm
	// Re-written for timeseries-analysis.
	
	options = _.extend({
		threshold:	2.5
	}, options);
	
	
	// Create a copy of the data;
	this.buffer 	= this.data.slice(0);
	
	// standardize the data
	this.standardize();
	
	var outliers = [];
	
	_.each(this.data, function(datapoint) {
		if (Math.abs(datapoint[1]) > options.threshold) {
			outliers.push(datapoint);
		}
	});
	
	// restore the data
	this.data = this.buffer.slice(0);
	delete this.buffer;
	
	return outliers;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.output"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>output ()](#apidoc.element.timeseries-analysis.main.prototype.output)
- description and source-code
```javascript
output = function () {
	return this.data;
}
```
- example usage
```shell
...
You can chain the methods. For example, you can calculate the moving average, then apply a Linear Weighted Moving Average on top
 of the first Moving Average:

't.ma().lwma();'

### Getting the data ###
When you are done processing the data, you can get the processed timeseries using 'output()':

'var processed = t.ma().output();'

### Charting ###
#### Charting the current buffer ####
You can plot your data using Google Static Image Chart, as simply as calling the 'chart()' method:

'''
var chart_url = t.ma({period: 14}).chart();
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.pixelize"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>pixelize (options)](#apidoc.element.timeseries-analysis.main.prototype.pixelize)
- description and source-code
```javascript
pixelize = function (options) {
	options = _.extend({
		grid:		20
	}, options);
	
	// Calculate the grid values
	var min 	= this.min();
	var max 	= this.max();
	var tile	= (max-min)/options.grid;
	
	this.buffer	= _.map(this.data, function(datapoint) {
		datapoint[1] = Math.round(datapoint[1]/tile)*tile;
		return datapoint;
	});
	this.data = this.buffer;
	return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.regression_analysis"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>regression_analysis ()](#apidoc.element.timeseries-analysis.main.prototype.regression_analysis)
- description and source-code
```javascript
regression_analysis = function () {
	return this.regression_analysis().durbinWatson;
}
```
- example usage
```shell
...
	
	return output;
}

// Get the Durbin-Watson statistic
// http://en.wikipedia.org/wiki/Durbin%E2%80%93Watson_statistic
timeseries.prototype.durbinWatson = function() {
	return this.regression_analysis().durbinWatson;
}

// Get the Durbin-Watson statistic
// http://en.wikipedia.org/wiki/Durbin%E2%80%93Watson_statistic
timeseries.prototype.regression_analysis = function() {
	return this.regression_analysis().durbinWatson;
}
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.regression_forecast"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>regression_forecast (options)](#apidoc.element.timeseries-analysis.main.prototype.regression_forecast)
- description and source-code
```javascript
regression_forecast = function (options) {
	options = _.extend({
		method:		'ARMaxEntropy',	// ARMaxEntropy | ARLeastSquare
		sample:		50,		// points int he sample
		start:		100,	// Where to start
		n:			5,		// How many points to forecast
		degree:		5
	},options);
	
	var i;
	var j;
	var l = this.data.length;
	
	var mean	= this.mean();
	this.offset(-mean);
	var backup 	= this.clone();
	var buffer 	= this.clone();
	
	var sample 		= buffer.slice(options.start-1-options.sample, options.start);
	
	// The current data to process is only a sample of the real data.
	this.data		= sample;
	// Get the AR coeffs
	var coeffs 		= this[options.method]({degree: options.degree});
	console.log("coeffs",coeffs);
	
	for (i=options.start;i<options.start+options.n;i++) {
		buffer[i][1]	= 0;
		for (j=0;j<coeffs.length;j++) {
			if (options.method == 'ARMaxEntropy') {
				buffer[i][1] -= buffer[i-1-j][1]*coeffs[j];
			} else {
				buffer[i][1] += buffer[i-1-j][1]*coeffs[j];
			}
		}
		console.log("buffer["+i+"][1]",buffer[i][1]);
	}
	this.data = buffer;
	this.offset(mean);
	
	return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.regression_forecast_mse"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>regression_forecast_mse (options)](#apidoc.element.timeseries-analysis.main.prototype.regression_forecast_mse)
- description and source-code
```javascript
regression_forecast_mse = function (options) {
	options = _.extend({
		method:		'ARMaxEntropy',	// ARMaxEntropy | ARLeastSquare
		sample:		50,
		degree:		5,
		data:		this.data
	},options);
	
	
	var i;
	var j;
	var l 			= options.data.length;
	
	var mean		= this.mean(options.data);
	options.data 	= this.offset(-mean, options.data, true);
	
	var backup 		= _.map(options.data, function(item) {
		return [
			item[0],
			item[1]*1
		];
	});
	var buffer 		= _.map(options.data, function(item) {
		return [
			item[0],
			item[1]*1
		];
	});
	
	var MSE	= 0;
	var n = 0;
	for (i=options.sample;i<l-1;i++) {
		var sample 		= buffer.slice(i-options.sample, i);
		// Get the AR coeffs
		var coeffs 		= this[options.method]({degree:options.degree, data:sample});
		var knownValue 	= buffer[i+1][1]*1;
		buffer[i+1][1]	= 0;
		for (j=0;j<coeffs.length;j++) {
			if (options.method == 'ARMaxEntropy') {
				buffer[i+1][1] -= backup[i-j][1]*coeffs[j];
			} else {
				buffer[i+1][1] += backup[i-j][1]*coeffs[j];
			}
		}
		
		MSE += (knownValue-buffer[i+1][1])*(knownValue-buffer[i+1][1]);
		n++;
	}
	
	MSE /= n;
	
	
	//this.data = buffer;
	
	// Put back the mean
	//this.offset(mean);
	
	return MSE;
}
```
- example usage
```shell
...
	var deg;	// degree
	var MSEData = [];
	var i;
	for (i=0;i<methods.length;i++) {
		for (ss=3;ss<=maxSampleSize;ss++) {
			for (deg=1;deg<=maxDegree;deg++) {
				if (deg<=ss) {
					var mse = this.regression_forecast_mse({
						method:	methods[i],
						sample:	ss,
						degree:	deg,
						data:	options.data
					});
					console.log("Trying method("+methods[i]+") degree("+deg+") sample("+ss+")\t"+mse);
					if (!isNaN(mse)) {
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.regression_forecast_optimize"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>regression_forecast_optimize (options)](#apidoc.element.timeseries-analysis.main.prototype.regression_forecast_optimize)
- description and source-code
```javascript
regression_forecast_optimize = function (options) {
	options = _.extend({
		data:		this.data,
		maxPct:		0.2,
		maxSampleSize:	false
	},options);
	
	var l 				= options.data.length;
	
	var maxSampleSize	= Math.round(l*options.maxPct);
	if (options.maxSampleSize) {
		maxSampleSize = Math.min(maxSampleSize, options.maxSampleSize);
	}
	
	var maxDegree		= Math.round(maxSampleSize);
	var methods			= ['ARMaxEntropy', 'ARLeastSquare'];
	var ss;		// sample size
	var deg;	// degree
	var MSEData = [];
	var i;
	for (i=0;i<methods.length;i++) {
		for (ss=3;ss<=maxSampleSize;ss++) {
			for (deg=1;deg<=maxDegree;deg++) {
				if (deg<=ss) {
					var mse = this.regression_forecast_mse({
						method:	methods[i],
						sample:	ss,
						degree:	deg,
						data:	options.data
					});
					console.log("Trying method("+methods[i]+") degree("+deg+") sample("+ss+")\t"+mse);
					if (!isNaN(mse)) {
						MSEData.push({
							MSE:	mse,
							method:	methods[i],
							degree:	deg,
							sample:	ss
						});
					}
				} else {
					break;
				}
			}
		}
	}
	
	// Now we sort by MSE
	MSEData = MSEData.sort(function(a,b) {
		return a.MSE>b.MSE;
	});
	
	console.log("Best Settings: ",MSEData[0]);
	
	// Return the best settings
	return MSEData[0];
	
}
```
- example usage
```shell
...
// We fetch the financial data from MongoDB, then use adapter.fromDB() to load that data
var t         = new ts.main(ts.adapter.fromDB(financial_data));

// Now we remove the noise from the data and save that noiseless data so we can display it on the chart
t.smoother({period:4}).save('smoothed');

// Find the best settings for the forecasting:
var bestSettings = t.regression_forecast_optimize(); // returns { MSE: 0.05086675645862624, method: 'ARMaxEntropy', degree: 4, sample
: 20 }

// Apply those settings to forecast the n+1 value
t.sliding_regression_forecast({
	sample:		bestSettings.sample,
	degree: 	bestSettings.degree,
	method: 	bestSettings.method
});
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.reset"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>reset ()](#apidoc.element.timeseries-analysis.main.prototype.reset)
- description and source-code
```javascript
reset = function () {
	this.data = this.original;
	return this;
}
```
- example usage
```shell
...

'save()' will save a copy the current buffer and add it to the list of datasets to chart.

'reset()' will reset the buffer back to its original data.

'''
// Chart the Moving Average and a Linear Weighted Moving Average on on the same chart, in addition to the original data:
var chart_url = t.ma({period: 8}).save('moving average').reset().lwma({period:8}).save('LWMA').chart({main:true});
// returns https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:ebgfqpqthjnptuwyzyzyxyy024211yxusrojfbWUQ,ebgfqpqtzv40yxvrw740914wswyupqdgPRNOXYLAB
,ebgfqpqtknqtvwxyxxyyy0022200zwvrpmidZXVTP,ebgfqpqthjnptuwyzyzyxyy024211yxusrojfbWUQ&chco=76a4fb,9190e1,ac7cc7,c667ad&chm=&chds=
56.75,72.03&chxr=0,56.75,72.03,10
'''
![chart](https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:ebgfqpqthjnptuwyzyzyxyy024211yxusrojfbWUQ,ebgfqpqtzv40yxvrw740914wswyupqdgPRNOXYLAB
,ebgfqpqtknqtvwxyxxyyy0022200zwvrpmidZXVTP,ebgfqpqthjnptuwyzyzyxyy024211yxusrojfbWUQ&chco=76a4fb,9190e1,ac7cc7,c667ad&chm=&chds=
56.75,72.03&chxr=0,56.75,72.03,10)

## Stats ##
You can obtain stats about your data. The stats will be calculated based on the current buffer.
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.save"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>save (name, options)](#apidoc.element.timeseries-analysis.main.prototype.save)
- description and source-code
```javascript
save = function (name, options) {
	options = _.extend({
		color:	'AUTO'
	}, options);
	
	this.saved.push({
		name:	name,
		color:	options.color,
		data:	this.data.slice(0)
	});
	return this;
}
```
- example usage
```shell
...

'save()' will save a copy the current buffer and add it to the list of datasets to chart.

'reset()' will reset the buffer back to its original data.

'''
// Chart the Moving Average and a Linear Weighted Moving Average on on the same chart, in addition to the original data:
var chart_url = t.ma({period: 8}).save('moving average').reset().lwma({period:8}).save('LWMA').chart({main:true});
// returns https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:ebgfqpqthjnptuwyzyzyxyy024211yxusrojfbWUQ,ebgfqpqtzv40yxvrw740914wswyupqdgPRNOXYLAB
,ebgfqpqtknqtvwxyxxyyy0022200zwvrpmidZXVTP,ebgfqpqthjnptuwyzyzyxyy024211yxusrojfbWUQ&chco=76a4fb,9190e1,ac7cc7,c667ad&chm=&chds=
56.75,72.03&chxr=0,56.75,72.03,10
'''
![chart](https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:ebgfqpqthjnptuwyzyzyxyy024211yxusrojfbWUQ,ebgfqpqtzv40yxvrw740914wswyupqdgPRNOXYLAB
,ebgfqpqtknqtvwxyxxyyy0022200zwvrpmidZXVTP,ebgfqpqthjnptuwyzyzyxyy024211yxusrojfbWUQ&chco=76a4fb,9190e1,ac7cc7,c667ad&chm=&chds=
56.75,72.03&chxr=0,56.75,72.03,10)

## Stats ##
You can obtain stats about your data. The stats will be calculated based on the current buffer.
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.slice"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>slice (from, to)](#apidoc.element.timeseries-analysis.main.prototype.slice)
- description and source-code
```javascript
slice = function (from, to) {
	if (!from) {
		from = 0;
	}
	if (!to) {
		to = this.data.length-1;
	}
	
	this.data = this.data.splice(from, to)
	
	return this;
}
```
- example usage
```shell
...


Now, calculating the AR coefficients of the entire dataset might not be really useful for any type of real-life use.
You can specify what data you want to use to calculate the AR coefficients, allowing to use only a subset of your dataset using
the 'data' parameter:
'''
// We'll use only the first 10 datapoints of the current data
var coeffs = t.ARMaxEntropy({
data:   t.data.slice(0, 10)
});
/* returns:
[
-4.728362307674655,
9.12909005456654,
-9.002790480535127,
4.536763868018368,
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.sliding_regression_forecast"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>sliding_regression_forecast (options)](#apidoc.element.timeseries-analysis.main.prototype.sliding_regression_forecast)
- description and source-code
```javascript
sliding_regression_forecast = function (options) {
	options = _.extend({
		method:		'ARMaxEntropy',	// ARMaxEntropy | ARLeastSquare
		sample:		50,
		degree:		5
	},options);
	
	var i;
	var j;
	var l = this.data.length;
	
	var mean	= this.mean();
	this.offset(-mean);
	var backup 	= this.clone();
	var buffer 	= this.clone();
	
	for (i=options.sample;i<l-1;i++) {
		var sample 		= buffer.slice(i-options.sample, i);
		// The current data to process is only a sample of the real data.
		this.data		= sample;
		// Get the AR coeffs
		var coeffs 		= this[options.method]({degree:options.degree});
		buffer[i+1][1]	= 0; //backup[i][1]*1;
		for (j=0;j<coeffs.length;j++) {
			if (options.method == 'ARMaxEntropy') {
				buffer[i+1][1] -= backup[i-j][1]*coeffs[j];
			} else {
				buffer[i+1][1] += backup[i-j][1]*coeffs[j];
			}
		}
		//buffer[i+1][1] -
	}
	
	this.data = buffer;
	
	// Put back the mean
	this.offset(mean);
	
	return this;
}
```
- example usage
```shell
...

Now, we generate the sliding window forecast on the data, and chart the results:
'''
// Our sin wave with its frequency increase
var t     	= new ts.main(ts.adapter.sin({cycles:10, inertia:0.2}));
// We are going to use the past 20 datapoints to predict the n+1 value, with an AR degree of 5 (default)
// The default method used is Max Entropy
t.sliding_regression_forecast({sample:20, degree: 5});
// Now we chart the results, comparing the the original data.
// Since we are using the past 20 datapoints to predict the next one, the forecasting only start at datapoint #21. To show that
on the chart, we are displaying a red dot at the #21st datapoint:
var chart_url = t.chart({main:true,points:[{color:'ff0000',point:21,serie:0}]});
'''

And here is the result:
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.smoother"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>smoother (options)](#apidoc.element.timeseries-analysis.main.prototype.smoother)
- description and source-code
```javascript
smoother = function (options) {
	options = _.extend({
		period:		1
	}, options);
	var i;
	var j;
	var l 	= this.data.length;
	var sum	= 0;
	
	// Reset the buffer
	this.buffer 	= this.data.slice(0);
	
	for (j=0;j<options.period;j++) {
		for (i=3;i<l;i++) {
			this.buffer[i-1] = [
				this.buffer[i-1][0],
				(this.buffer[i-2][1]+this.buffer[i][1])/2
			];
		}
	}
	this.data = this.buffer;
	return this;
}
```
- example usage
```shell
...
## Noise Removal ##
Most smoothing algorithms induce lag in the data. Algorithms like Ehler's iTrend algorithm has no lag, but won't be able to perform
 really well on a really noisy dataset as you can see in the example above.

For that reason, this package has a set of lagless noise-removal and noise-separation algorithms.

#### Noise removal ####
'''
t.smoother({
    period:     10
});
'''
![chart](https://chart.googleapis.com/chart?cht=lc&chs=800x200&chxt=y&chd=s:ebehknprsuvwxxyzz000zzyxvtqolifcaXUROLHEB,ebgfqpqtzv40yxvrw740914wswyupqdgPRNOXYLAB
&chco=76a4fb,ac7cc7&chm=&chds=56.75,72.03&chxr=0,56.75,72.03,10)

#### Noise separation ####
You can extract the noise from the signal.
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.standardize"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>standardize (options)](#apidoc.element.timeseries-analysis.main.prototype.standardize)
- description and source-code
```javascript
standardize = function (options) {
	options = _.extend({}, options);
	
	var stdev	= this.stdev();
	var mean	= this.mean();
	
	this.data = _.map(this.data, function(datapoint) {
		datapoint[1] = (datapoint[1]-mean)/stdev;
		return datapoint;
	});
	
	return this;
}
```
- example usage
```shell
...
	}, options);
	
	
	// Create a copy of the data;
	this.buffer 	= this.data.slice(0);
	
	// standardize the data
	this.standardize();
	
	var outliers = [];
	
	_.each(this.data, function(datapoint) {
		if (Math.abs(datapoint[1]) > options.threshold) {
			outliers.push(datapoint);
		}
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.stdev"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>stdev (data)](#apidoc.element.timeseries-analysis.main.prototype.stdev)
- description and source-code
```javascript
stdev = function (data) {
	if (!data) {
		var data = this.data;
	}
	var sum 	= 0;
	var n 		= 0;
	var mean 	= this.mean();
	_.each(data, function(datapoint) {
		sum += (datapoint[1]-mean)*(datapoint[1]-mean);
		n++;
	});
	return Math.sqrt(sum/n);
}
```
- example usage
```shell
...
#### Max ####
'var max = t.max(); // 72.03'

#### Mean (Avegare) ####
'var mean = t.mean();   // 66.34024390243898'

#### Standard Deviation ####
'var stdev = t.stdev(); // 3.994277911972647'


## Smoothing ##
There are a few smoothing options implemented:

#### Moving Average ####
'''
...
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.supports"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>supports (options)](#apidoc.element.timeseries-analysis.main.prototype.supports)
- description and source-code
```javascript
supports = function (options) {
	options = _.extend({
		grid:		40,
		threshold:	10
	}, options);
	
	// Calculate the grid values
	var min 	= this.min();
	var max 	= this.max();
	var tile	= (max-min)/options.grid;
	
	var prices = {
		
	};
	
	_.each(this.data, function(datapoint) {
		var val = Math.round(datapoint[1]/tile)*tile;
		if (!prices[val]) {
			prices[val] = 0;
		}
		prices[val]++;
	});
	
	var ordered = [];
	var i;
	for (i in prices) {
		ordered.push({
			price:	i,
			count:	prices[i]
		});
	}
	ordered = ordered.sort(function(a,b) {
		return b.count-a.count;
	});
	ordered	= _.filter(ordered, function(support) {
		return support.count >= options.threshold;
	});
	if (options.stats) {
		return 	ordered;
	}
	
	return _.map(ordered, function(support) {
		return support.price;
	});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.timeseries-analysis.main.prototype.toArray"></a>[function <span class="apidocSignatureSpan">timeseries-analysis.main.prototype.</span>toArray ()](#apidoc.element.timeseries-analysis.main.prototype.toArray)
- description and source-code
```javascript
toArray = function () {
	return _.map(this.data, function(datapoint) {
		return  datapoint[1];
	});
}
```
- example usage
```shell
...
	return _.map(this.data, function(datapoint) {
		return  datapoint[1];
	});
}

// Stats: Min, Max, Mean, Stdev
timeseries.prototype.min = function() {
	var array = this.toArray();
	return _.min(array);
}
timeseries.prototype.max = function() {
	var array = this.toArray();
	return _.max(array);
}
timeseries.prototype.mean = function(data) {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
