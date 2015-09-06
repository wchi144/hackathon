Avatar
===========

A simple React avatar component 

## Getting Started

```
$ npm install && npm test
```

## Usage

Install via bower
```bash
$ bower install --save git@github.dev.xero.com:FutureRobot/avatar.git
```

```js
import Avatar from 'Avatar';

(function() {
	React.render(
		<div>
			<Avatar className="my-comp"
				value="Weasleys' Wizard Wheezes"
				size="small"
				colour= "orange"
				identifier="!XfCqgf"
				imageUrl="logo.png"/>
		</div>, 
		document.getElementById('app')
	);
})();
```

### Property Precedence
imageUrl
colour
identifier
