# Define a recursive function that returns true if a string is a palindrome and false otherwise
def palindrome(string)
  if string.length == 1 || string.length == 0
    true 
  else 
    string[0] == string[-1] ? palindrome(string[1..-2]) : false
  end 
end

# Define a recursive function that finds the factorial of a number
def factorial(n)
  if n == 1 
    return 1 
  else 
    n * factorial(n - 1)
  end 
end

# Define a recursive function that takes an argument n and prints "n bottles of beer on the wall," "(n-1) bottles of beer on the wall", "no more bottles of beer on the wall"
def bottles(n)
  if n == 0 
    puts "No more bottles of beer on the wall"
  else 
    puts "#{n} bottles of beer on the wall"
    bottles(n - 1)
  end
end 

# Define a recursive function that takes an argument n and returns the fibonacci value of that position.
def fib(n)
  if n == 0
    return 0
  elsif n == 1
    return 1 
  else 
    fib(n-1) + fib(n-2)
  end
end

#Define a recursive function that flattens an array
def flatten(arr)
  result = []
  arr.each do |item| 
    if item.is_a?(Array) 
      flatten(item) 
    else 
      result << item
    end 
  end 
  result
end
