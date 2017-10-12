# UM System Status

A neat embeddable web element that reads the [UM System Status page](https://status.missouri.edu/). Built within the [Material Design Lite framework](https://getmdl.io/)

### Usage

Include the script and stylesheet.

```html
<link rel="stylesheet" href="./umSystemStatus.css" />
<script src="./umSystemStatus.js"></script>
```

Set up a content element. Include MDL elements as needed. Here, I've used some classes and added a spinner element.
```html
<div class="systemStatus">
	<span class="systemStatus-button material-icons">error_outline</span>
	<div class="systemStatus-content mdl-shadow--4dp mdl-card">
		<div class="mdl-spinner mdl-js-spinner is-active"></div>
	</div>
</div>
```

## Author

* **Stuart Miller** - <sm67c@mst.edu> - [Website](http://web.mst.edu/~sm67c/)
