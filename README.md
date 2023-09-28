# Writing Good Documentation

# Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for take people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (```)
- Not to be confused with quotation (''')

- [x] Finish step 1
- [] Finish step 2
- [] Finish step 3

```ruby
  def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
number = 5
result = factorial(number)
puts "The factorial of #{number} is #{result}"

```

## References

- [Github Flavored Markdown -Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
