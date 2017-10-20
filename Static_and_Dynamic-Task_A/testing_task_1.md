### Testing task 1 code:

# Carry out static testing on the code below.  
# Read through the code.  
# Comment any errors you can see without correcting them.

 ```
//in next line, argument val should be in brackets, and the equals sign should be doubled//
def func1 val
  if val = 1
  return true
  else
  return false
  end
end

//miss-spelling of def, and arguments should be in brackets with a comma on line 19//

dif max a b
  if a > b
      return a
  else
  b
  end
end
end
//One too many ends at the end of the function. And the b should be returned on line 23//

//below requires an if statement stating that if i == 10, return i//
def looper
  for i in 1..10
  puts i
  end
end

failures = 0
//below function requires end//
if looper == 10
  puts "looper passed"
else
  puts "looper failed"
  failures = failures + 1

if func1(3) == false
  puts "func1(3) passed"
else
  puts "func1(3) failed"
  failures = failures + 1
end

//miss-spelling of failures on line 56, also line 55 should read "max(100,1) failed".//
if max(100,1) == 100
  puts "max(100,1) passed"
else
  puts "func1(3) failed"
  failrues = failures + 1
end

//next line should read "if failures > 0"//
if failures
  puts "Test Failed"
else
  puts "Test Passed"
end

```
