# JPEG Visual Repair Tool
<img src="JVRTmain.jpg" width="600"></img>

JPEG visual repair tool can load JPEG images while preserving MCU (Minimum Coded Unit) coding data and allows editing at MCU level.
It is written in JavaScript and resides in a single html document; it can be simply saved for offline use, there are no library dependencies. It is based on jpeg-decomp.

Using it you can:

- view image info
- delete, insert, copy, paste MCUs
- change DC level of each MCU
- view the image as RGB, Y, Cb, Cr
- automatically fix color differences
- view MCU pixel levels, coefficients, and binary data-stream

Controls:

- mouse wheel→zoom image
- left click → select MCU; a black or white rectangle appears on selected MCU
- shift+left click → extend selection
- left button drag → drag image
- right click → select MCU for color fixing; a red rectangle appears on selected MCU
- right button drag → extend selection for color fixing
- ctrl-c → copy selected MCUs
- ctrl-v → paste before selected MCU
- arrows → change selected MCU
- i → open MCU info dialog
- del → delete MCU
- 1-2-3-4 → change view (RGB, Y, Cb, Cr)

A crossed red rectangle appears on MCUs that produced decode errors.

