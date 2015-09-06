Avatar
===========

A simple React avatar component 

## Getting Started ##

```
$ npm install && npm test
```

## Usage ##

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
				value="Magic Unicorn's Fairy Dust"
				size="small"
				colour= "#800080"
				identifier="XfCqgf"
				imageUrl="rainbow.png"/>
		</div>, 
		document.getElementById('app')
	);
})();
```

#### Property Precedence ####
**imageUrl**: The image will always be used if specified

**colour**: Colour will be used if there is no imageUrl. Will also contain the first letter of the value property

**identifier**: A random colour will be generated using the identifier if there is no imageUrl or colour.  Will also contain the first letter of the value property

## Example ##

#### Avatar with identifier ####
![](example/avatar_identifier.png)

#### Avatar with imageUrl ####
![](example/avatar_imageUrl.png)
