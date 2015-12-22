---
template: index.jade
---

## Introduction

Collection of base classes for use with Babel projects. **esbases** provides base
classes for common native types such as Error and Number. These native types,
which, when extended directly, will lead to unwanted side effects and even
dysfunctional subclasses such as

- subclasses of error cannot have properties or methods, or,
- Number#getValueOf is not generic.

So, if you ever ran into these problems, then **esbases** is definitely for you.

