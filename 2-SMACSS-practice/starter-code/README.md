##### How did you determine which rules should be placed in each new CSS file?

I considered the criteria for each category and then made decisions as best I could based on the content. There were at least a few things where I kinda put them into one file and then into another. I probably should have utilized base and layout.css a bit more, but module just seemed to fit virtually all of the site's content, so I went with that more often than not.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I initially tried to consider the SMACSS rules a little more closely, but I quickly started breaking things, so I decided that in the interest of time, my main goal would be to make sure that none of the selectors were raw HTML tags. It felt a little like the first time we wrapped code into functions in 201. While it seems a little silly to do it to already-finished code, the added semantic meaning makes it easier to figure out exactly what's going on and how different elements interact. If I had more time, I'd start poking around to see if I could DRY the code out better.
