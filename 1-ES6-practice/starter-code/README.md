# 1-ES6-practice

## Feature Tasks

Follow these instructions carefully and in order.

1. Open the HTML file in the browser to ensure that it works.
2. Turn all `var` variable declarations into `let`.
3. After you do, there will be one error. Find that line in the code, delete that line and respond to the adjacent TODO item.
4. Return to the browser to ensure that the code works again.
5. **Save the code, and do a Git "add" and "commit".**
6. Now, in the code, convert all `let` variable declarations into `const`.
7. Bugs will erupt everywhere. Debug by using the error messages in the browser console, turning `const` declarations back into `let` where necessary. Expect there to be some back-and-forth between your code editor and your browser.
8. When you think you have things working, clear local storage and reload the page to ensure that the code still works when starting from a totally clean state.
9. **Save the code, and do a Git "add" and "commit".**
10. Now find all concatenations in the code and convert them into template literal notation.
11. Reload the browser to ensure that the code works as expected.
12. **Save the code, and do a Git "add" and "commit".**
13. Answer the following questions:

---

##### Investigate how `let` and `const` are now used in the code. Where did you need to convert `const` into `let` to make the code work? Can you identify any patterns/similarities?

allProducts needs to be a let, I thiiiiink because it gets stringified, but to be honest, I'm not totally sure. totalClicks also needs to be a let, because it's assigned new values throughout the code. Aside from those two variables, all of the loops require let rather than const by definition of a loop. If you can't increment your loop counter, you can't loop!

Basically, if you're going to assign something new to a variable, it needs to be a let. If it's an object or a DOM element, const is fine, because (at most) you're only adding to what's already been defined. Or, at least, that's how I think it works.

---

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

It looked weird when I read about it, but I picked it up pretty quickly. It's definitely easier to see exactly what you're doing with the template literal notation, and I like that spaces are preserved as you'd expect them to be, rather than requiring you to remember the space before/after the ' depending on how you want things formatted. I'll definitely try to use it from now on, though in a pinch, my brain may still choose concatenation by default at times.
