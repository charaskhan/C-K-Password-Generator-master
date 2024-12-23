# C-K-Password-Generator-master


This project is a Java Console Application designed to create random passwords and evaluate their strength.

## Overview

I embarked on this project during the Winter Break of my second year after completing an Object-Oriented Effective Java Programming course. My goal was to develop something engaging with Java to enhance my skills and explore my capabilities independently. One evening, while discussing the significance of strong passwords for social media accounts with my father, I was inspired to create a random password generator. A week later, I completed it.

During the development process, I decided to incorporate a password strength checker that assesses the robustness of any entered password. I was pleased with the outcome, but I recognized that it might not be user-friendly for those unfamiliar with its functionality. Therefore, I plan to develop a graphical user interface (GUI) for the application in a future iteration, which will be available in the Password-Services repository.

## Features

### 1. Password Generation:

- Users respond with "Yes" or "No" to questions regarding the inclusion of uppercase letters, lowercase letters, numbers, or symbols.
- Users specify their desired password length.
- Based on the user's responses, a character set is created that includes the selected types of characters.
- Random characters are then chosen from this character set and combined to form a completely random password according to user preferences.
- The generated password is displayed in the console.

### 2. Password Strength Evaluation:

The strength assessment is based on several criteria:
- The presence of uppercase letters.
- The presence of lowercase letters.
- The inclusion of numbers.
- The inclusion of symbols.
- A minimum length of 8 characters (which is often considered the minimum for a decent password).
- A recommended length of at least 16 characters (which is regarded as a strong password).

These criteria are utilized to compute a score for the password, which determines a message indicating its strength (weak/medium/good/great) displayed to the user.

### 3. Providing Helpful Information:

This feature offers users valuable insights about password security through console messages. It advises against reusing passwords, repeating characters, using keyboard patterns, dictionary words, or sequential letters and numbers.

Feel free to let me know if you need any further modifications or additional information!
