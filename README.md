# billy
Confused about how your money is all spent from your bank account ? Maybe billy
can shed some light!

billy categorizes text based bank statements. You inform it the structure
of your bank(s) statement in regex (with a "trans" file). Then feed it with
a "cat" file that specifies the regex to be matched with the narration (of
each transaction) for each category. You can add "hooks" to change the
standard behaviour. Then you input your bank statements and billy will tell
you (indirectly) where you need to loosen/tighten your purse strings ;)

Take a look at the example cat and trans file in the repo to get a better
idea.
