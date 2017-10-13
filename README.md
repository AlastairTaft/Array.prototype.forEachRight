# `Array.prototype.forEachRight` polyfill

A polyfill for `forEachRight`, works very much the same way as `forEach` but
instead iterates in reverse. Useful if you're removing items from the array 
while you iterate as it won't impact your current index pointer.