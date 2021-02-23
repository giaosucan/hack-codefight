Given the string, check if it is a palindrome.

Example

For inputString = "aabaa", the output should be
```
checkPalindrome(inputString) = true;
```
For inputString = "abac", the output should be
```
checkPalindrome(inputString) = false;
```
For inputString = "a", the output should be
```
checkPalindrome(inputString) = true.
```
Code Java

``` Java
boolean checkPalindrome(String inputString) {
    String reverse = new StringBuffer(inputString).reverse().toString();
    if (inputString.equals(reverse)) {
        return true;
    } else {
        return false;
    }
}
```
