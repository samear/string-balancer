A`string which contain only the characters '(', ')', '{','}', '[' and ']' is considered valid, if all
the brackets are closed in the correct order.
for example, "()" and "()[]{}" are all valid but "(]" and "([)]" are not.
Given an array of several string as the input, print "Valid" or "Not valid" on separate lines for each
input string.
If the input string contains any characters other than '(', ')', '{', '}', '[' and ']', then just
print "Not valid". Empty string are always valid.
Test cases:
i/p -> Empty string: valid
i/p -> (): valid
i/p -> []: valid
i/p -> (){}: valid
i/p -> {]: Not valid
i/p -> ([)]: Not valid
i/p -> {([])}: valid
i/p -> {[)}(]: not valid
i/p -> ;{}: not valid string-balancer
