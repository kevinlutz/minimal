+++
check_to_see_if_a_word_is_a_palindrome = ""
draft = true
palindrome_ = ""

+++
palindrome = (string) => {

     const reversed = string.split("").reverse().join("");

     if (reversed === string) ? true : false;

}

palindrome("racecar");     //true