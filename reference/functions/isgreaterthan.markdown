---
layout: default
title: isgreaterthan
published: true
tags: [reference, data functions, functions, isgreaterthan]
---

[%CFEngine_function_prototype(value1, value2)%]

**Description:** Returns whether `value1` is greater than `value2`.

The comparison is made numerically if possible. If the values are
strings, the result is identical to that of comparing with strcmp().

[%CFEngine_function_attributes(value1, value2)%]

**Example:**

[%CFEngine_include_snippet(isgreaterthan.cf, #\+begin_src cfengine3, .*end_src)%]

Output:

[%CFEngine_include_snippet(isgreaterthan.cf, #\+begin_src\s+example_output\s*, .*end_src)%]
