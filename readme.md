# Hash Tables - Ransom Note Lab

## Overview
Build a function that checks if you can make a ransom note using letters from a magazine. Each letter can only be used once.

## The Problem
Given a `ransomNote` and a `magazine`, return `True` if the ransom note can be built using the magazine's letters, `False` otherwise.

**Example:**
- `can_construct("abc", "aabbcc")` → `True` (enough letters)
- `can_construct("aa", "ab")` → `False` (not enough 'a's)

## Your Task
Complete the `can_construct()` function in `ransom_note.py` using a hash table (dictionary).

## How to Run
1. Implement the function in `ransom_note.py`
2. Test your solution:
   ```bash
   python test_ransom_note.py
   ```
3. All tests should pass!

## Requirements
- Use a dictionary to count characters
- Return `True` if construction is possible, `False` otherwise
- Each magazine letter can only be used once

## Files
- `ransom_note.py` - Your implementation goes here
- `test_ransom_note.py` - Test cases to verify your solution