slidingPanel
============

A Javascript library that mimics the sliding panel for a given database. 

<h1>How To Use The Library</h1>
To use the library, you will need the following dependencies:
<ul>
	<li>jQuery</li>
	<li>Animate.css</li>
</ul>

After including the .js file into your html file, call the function _slidingPanelInit(database, containerId,prevBtnId,nextBtnId,numOfCols) and you are ready to go!

Following are the explanations of the parameters:
<ol>
	<li>
		_database <br>
		The database represented in the form of JSON arrays of strings that the sliding panel is retrieving data from.
	</li>
	<li>
		_containerId <br>
		Id in the form of string indicating the id of the container where you want all the columns go!
	</li>
	<li>
		_nextBtnId, _prevBtnId <br>
		Ids of the two buttons which, once clicked, will go the next(previous) panel of elements.
	</li>
	
</ol>