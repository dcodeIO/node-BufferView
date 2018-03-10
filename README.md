BufferView
==========

A [DataView](https://developer.mozilla.org/en-US/docs/Web/API/DataView) for node Buffers.

Additional API
--------------

* `BufferView.create(Buffer|ArrayBuffer):BufferView|DataView`<br />
  Creates a BufferView if wrapping a Buffer and a DataView otherwise
* `BufferView.isBufferView(*):boolean`<br />
  Tests if a view is a BufferView wrapping a Buffer
* `BufferView.isDataView(*):boolean`<br />
  Tests if a view is a DataView wrapping an ArrayBuffer

**License:** [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)
