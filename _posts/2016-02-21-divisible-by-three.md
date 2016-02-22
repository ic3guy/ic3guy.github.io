---
published: true
layout: post
---



This is probably something I learned in grade school, but must have forgot along the way. Math is all about tricks or rules of thumb such as this.

As John von Neumann once said
> ...in mathematics you don't understand things. You just get used to them.

Here's a quick way to determine if a number is divisible by 3.

Take the number, say \\(12345\\). Sum the numbers of the number and if that sum is divisible by 3, then the number is divisible by 3.

$$ 1 + 2 + 3 + 4 + 5 = 15$$

So in this case \\(12345\\) is divisible by 3. Let's check in our calculator

$$12345/3 = 4115$$

The question is why does this work? We can decompose an integer like so

$$ 1 \times 10000 + 2 \times 1000 + 3 \times 100 + 4 \times 10 + 5 \times 1$$

equivalently

$$ 1 \times (9999+1) + 2 \times (999+1) + 3 \times (99 +1) + 4 \times (9+1) + 5 \times 1$$

multply that out

$$ 1(9999) + 1 + 2(999) + 2 + 3(99) + 3 + 4(9) + 4 + 5 $$

for the whole term to be divisible by 3, each term has to be evenly divisible by 3. Each term that is 9, 99, 999 etc. is obviously divisible by 3. Therefore we are left with

$$ 1 + 2 + 3 + 4 + 5 $$

which must be divisible by 3, to imply the original number is divisible by 3. The cool thing it works at the second level as well

$$ 1 + 2 + 3 + 4 + 5 = 15$$

$$ 1 + 5 = 6$$

And \\(6\\) is obviously divisible by 3. Voila!
