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
![avatar2](https://github.dev.xero.com/github-enterprise-assets/0000/0601/0000/6347/c471e3ea-5555-11e5-91f5-b2cbb913666e.jpg)

#### Avatar with imageUrl ####
![avatar1](https://github.dev.xero.com/github-enterprise-assets/0000/0601/0000/6348/c4727a94-5555-11e5-90f8-787aad4fef3a.jpg)
