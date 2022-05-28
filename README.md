# finding-anagram
#function  returning True  if they are anagrams, else  False
# Check if two words are anagrams
# Example:
# find_anagrams("hello", "check") --> False
# find_anagrams("below", "elbow") --> True


def find_anagram(word, anagram):
    print(sorted(word), sorted(anagram))
    # [assignment] Add your code here
    if (sorted(word) == sorted(anagram)):
        print(sorted(word), sorted(anagram))
        return True
    return False


print(find_anagram("hello", "check"))
print(find_anagram("below", "elbow"))
