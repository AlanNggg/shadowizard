# shadowizard

Get shadows every time for non-designer.

# Installation

`npm i shadowizard --save`

Then...

```
import { shadowizard } from 'shadowizard';

shadowizard({
    shadow_type: 'soft',
    padding: false
});
```

## Options

Shadowizard supports 2 options, both of which are optional:

-   _shadow_type_ - _hard | soft_ (Defaults to soft)
-   _padding_ - _boolean_ (Defaults to false)
