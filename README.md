Bulletproof-font-mixin
======================

What about a SCSS mixin who can calculate with a REM font-size the perfect line-height (Golden rule), le letter-spacing (based to photoshop) and add a fallback in pixel!

ex:  <br>
*@include fs(1.2);* &nbsp;&nbsp;&nbsp;&nbsp; //1.2rem

will result in:<br>
*line-height: 19.416px;*<br>
*line-height: 1.9416rem;*<br>
*letter-spacing: 0.24px;*<br>
*letter-spacing: 0.024rem;*<br>
*font-size: 12px;*<br>
*font-size: 1.2rem*
