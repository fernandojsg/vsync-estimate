# vsync-estimate
Estimate browser vsync using rAF

# Usage
```javascript
import estimateVSync from 'vsync-estimate';

estimateVSync().then(refreshRate => {
	console.log(`Estimated Vsync: ${Math.round(refreshRate)}Hz`);
});
``` 
