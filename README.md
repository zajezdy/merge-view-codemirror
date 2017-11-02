# merge-view-codemirror

npm package for http://codemirror.net/demo/merge.html

## Installation

    npm install merge-view-codemirror 
    
## Dependencies
CodeMirror library is required for this component :
- `npm install codemirror`
- `npm install diff-match-patch`
    
## Usage    
    
```javascript
import * as DiffMatchPatch from 'diff-match-patch';
import * as CodeMirror from 'codemirror';
import * as MergeViewCodeMirror from 'merge-view-codemirror';


// ...

MergeViewCodeMirror.init(CodeMirror, DiffMatchPatch);
CodeMirror.MergeView(host.nativeElement, this.config);

```

## Configuration
* `config`: The configuration object for CodeMirror MergeView see http://codemirror.net/doc/manual.html#addon_merge