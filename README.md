Footnotes Cleanup
=================

TODO:

After figuring out citation sharing with footnotes module, use better regex and method.

New regex:

`/\[((([^f\/\]][^n\/\]]?)*(\<\/)?)*)\/?((([^f\/\]][^n\/\]]?)*(\<\/)?)*)fn((([^f\/\]][^n\/\]]?)*(\<\/)?)*)\]/`

Alternative:

`/\[(([^f\/\]][^n\/\]]?)*(\<\/)?([^f\/\]][^n\/\]]?)*)\/?(([^f\/\]][^n\/\]]?)*(\<\/)?([^f\/\]][^n\/\]]?)*)fn(([^f\/\]][^n\/\]]?)*(\<\/)?([^f\/\]][^n\/\]]?)*)\]/`
