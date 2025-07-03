Task 6: Password Strength Testing – Step-by-Step Guide

This guide walks you through how to complete Task 6 of the internship: testing password strength with online tools, analyzing the results, and documenting your findings. We will use free web tools (such as PasswordMeter and Security.org’s password checker) to evaluate sample passwords of varying complexity. Follow each step carefully, and always ensure no real or reused passwords are exposed.

1. Access a Password-Strength Checker Tool

Open a web browser and navigate to an online password-strength tester. For example:
	•	PasswordMeter.com – a simple strength meter. It requires at least 8 characters and a mix of character types (uppercase, lowercase, numbers, symbols) ￼.
	•	Security.org “How Secure Is My Password?” – another free checker. It evaluates factors like length, character variety, and matches against a database of common weak passwords ￼ ￼.

To find tools, you can search for “free password strength checker.” Choose one or more tools, and bookmark them. Read any on-page instructions. For example, PasswordMeter displays live feedback and a numeric score as you type ￼. The Security.org tool shows an estimated “time to crack” (like years) for your input ￼.

2. Create Sample Passwords of Varying Strength

Before testing, prepare 3–5 dummy passwords with different complexity levels (all fictional, not used in any real accounts). For instance:
	•	Weak (simple): e.g. sunshine, abc123, or a common word/phrase. (No special characters, maybe all letters or all digits.)
	•	Medium (moderate): e.g. BlueSky2025, Hello@123, or a mix of letters and numbers with maybe one symbol.
	•	Strong (complex): e.g. Th!sIs@Tr0ngP@ss, C0mpl3x#Word$2025, or a long passphrase with mixed types. Include uppercase, lowercase, digits, and symbols. Ideally use 16–20 characters for the strongest examples ￼ ￼.

Best practices for sample creation: never use any real personal info or actual used passwords. Do not reuse the same password across accounts ￼. Use nonsense phrases or random character strings. For example, turn a sentence into a passphrase (MyCatAteFish!23) or use a password-generator tool to get a random string.

3. Test the Passwords in the Tool

One by one, enter each sample password into the strength checker:
	•	In PasswordMeter, type or paste the password into the input box. The tool will instantly display a score (%) and a Complexity label (e.g. “Too Short”, “Weak”, “Strong”). It also shows points added for length and character variety, and points deducted for patterns ￼ ￼.
	•	In Security.org’s checker, input the password and submit. It will show an estimated time to crack (e.g. “34,000 years” for a very strong password) ￼. It bases this on factors like number of characters and variety ￼.

Record the output for each test. Note the numerical score (if any), the complexity rating, and the time-to-crack or similar feedback. For example, a very simple password may show a low score or “seconds” to crack, while a strong, long password shows a much higher score or millions of years ￼ ￼.

4. Explain and Analyze the Results

For each tested password, interpret why the tool gave that result:
	•	Factors affecting strength: All checkers consider password length and character diversity. Longer passwords with mixed upper/lowercase letters, digits, and symbols score higher ￼ ￼. For example, PasswordMeter adds +4 points per character ￼, and gives extra points for including uppercase, lowercase, numbers, and symbols ￼. It also penalizes weak patterns (e.g. all letters, repeated characters, or sequences) ￼.
	•	Tool feedback: If your password lacked certain character types or was very short, the tool will reflect that with a low score or “Too Short” complexity. A secure password typically gets a high percentage or a very long “time to crack.” For instance, Security.org notes that a seemingly random 11-character password could take thousands of years to crack ￼, whereas a common short password can be cracked in seconds ￼.
	•	Comparison: Contrast your samples. A weak password (e.g. just letters or numbers) will usually be marked “Weak” or show a short crack time. A strong one (long, varied) will show “Strong” or an extremely large crack time ￼ ￼. Make note of what changes made the difference (e.g. adding symbols raised the score, or length alone made it stronger).

Write a brief explanation for each password’s result in your report, referring to length and composition. For example, “Password1 had no symbols or uppercase and only 9 characters, so the tool rated it weak with a short crack time. In contrast, Th!sIs@Tr0ngP@ss (16 chars, mixed types) scored very high and estimated 46 million years to crack ￼.”

5. Capture Screenshots Safely

For each password test, take a screenshot of the tool’s result display. Use your operating system’s screenshot utility (e.g. Windows Snipping Tool or Print Screen, Mac Cmd+Shift+4, etc.). Save each image with a clear filename, such as test1_weak.png, test2_medium.png, test3_strong.png, etc. These images will be included in your GitHub report.

Safety tip: Before capturing, ensure no sensitive information is visible. If the password itself is shown in plaintext on the screen, either replace it with asterisks or a dummy value first. Screenshot privacy is important – you should not expose any real passwords or personal data in your images ￼. For example, you might blur out or cover the password field, or take the shot in a way that only shows the score/rating. This way, the screenshots illustrate the results without leaking any real credentials.

6. Summarize Password Best Practices

After testing, compile the common best practices that make passwords strong. Based on the tools’ feedback and general guidelines, note points such as:
	•	Length: Longer is better. Aim for at least 12 characters, and ideally 16–20 for high security ￼. (Security.org recommends 16–20 characters for top strength ￼.)
	•	Complexity: Use a mix of uppercase letters, lowercase letters, numbers, and symbols ￼ ￼. Avoid using only letters or only numbers ￼.
	•	Unpredictability: Don’t use common words, repeated patterns, or easy sequences (like “1234” or “abcd”) ￼ ￼. Dictionary and brute-force attacks exploit such patterns ￼ ￼.
	•	No personal or reused data: Don’t include personal info (names, birthdays) or reuse passwords across sites ￼ ￼. A password manager can help generate and store unique passwords for each account ￼.
	•	Passphrases: Consider using a random passphrase or sentence of words (with some modifications) – it can be long yet memorable.

These practices come directly from security recommendations. For example, Security.org advises against any password that “contains personal information” or common phrases ￼, and notes that longer, random combinations are far stronger ￼ ￼.

7. Prepare the GitHub README.md

Finally, you will write a README.md in Markdown that documents your process and findings. Create a new GitHub repository for this task and include:
	•	A title and introduction explaining that this repo covers password strength testing (why and how you did it).
	•	A List of Tools used (e.g. “PasswordMeter.com”, “Security.org Password Checker”), using bullet points.
	•	A table of passwords tested and their ratings. For safety, show generic examples (don’t use actual secret passwords). For instance:

Password Sample	Strength Result
testpass1	Weak
BlueSky2025!	Moderate
C0mpl3x#Word$	Strong


	•	Key observations and a Summary of best practices (from step 6) in paragraph or bullet form.
	•	A list of your screenshot file names (like test1_weak.png, test2_medium.png, etc.), indicating which test each one represents.
	•	A short section on Learning Outcomes (what you learned about password strength and security).

Use Markdown formatting (headers #, ##, bullet points -, tables, etc.) to make the README clear. Follow GitHub’s markdown style: a top-level # for the repo title, and ## for subsections ￼. Preview the README in GitHub to ensure formatting is correct before submitting.

Example README.md Content

# Password Strength Testing

## Introduction
This project demonstrates how to test and analyze password strength using online tools. We created several sample passwords (none of which are actual user passwords) and evaluated them with free strength-checkers. The goal was to learn how length and character variety affect security, and to document best practices.

## Tools Used
- PasswordMeter (https://passwordmeter.com/)
- Security.org “How Secure Is My Password?” checker

## Passwords Tested and Ratings
| Sample Password   | Strength Rating           |
|-------------------|---------------------------|
| `testpass1`       | Weak (scored ~20%, cracked in seconds) |
| `BlueSky2025!`    | Moderate (~60%)           |
| `C0mpl3x#Word$`   | Strong (>90%,  Millions of years to crack) |

## Observations and Best Practices
- **Length:** Passwords shorter than 8 characters score very weak. Strong passwords were 15+ characters long [oai_citation:41‡security.org](https://www.security.org/how-secure-is-my-password/#:~:text=An%20example%20of%20a%20secure,46%20million%20years%20to%20crack).  
- **Character Variety:** Including uppercase, lowercase, numbers, and symbols greatly increases strength [oai_citation:42‡passwordmeter.com](https://passwordmeter.com/#:~:text=Number%20of%20Characters%20Flat%20%2B%28n) [oai_citation:43‡security.org](https://www.security.org/how-secure-is-my-password/#:~:text=,characters%2C%20with%20unique%20combinations%20instead).  
- **Avoid Common Patterns:** Simple words or sequences (like `testpass` or `1234`) are marked weak and can be cracked almost instantly [oai_citation:44‡security.org](https://www.security.org/how-secure-is-my-password/#:~:text=,most%20common%20passwords) [oai_citation:45‡kaspersky.com](https://www.kaspersky.com/resource-center/definitions/what-is-a-dictionary-attack#:~:text=Dictionary%20attacks%3A%20A%20definition).  
- **No Personal Info:** Best passwords had no personal names or dates [oai_citation:46‡security.org](https://www.security.org/how-secure-is-my-password/#:~:text=,same%20letter%20or%20number%20repeated). 
- **Uniqueness:** We note that using a different password for each account is essential to prevent breaches [oai_citation:47‡security.org](https://www.security.org/how-secure-is-my-password/#:~:text=,ABCD%2C%201234%2C%20etc).
  

## Learning Outcomes
We learned that **password length and complexity are critical** for security. The tools showed that longer passwords with mixed characters are exponentially harder to crack [oai_citation:48‡security.org](https://www.security.org/how-secure-is-my-password/#:~:text=An%20example%20of%20a%20secure,46%20million%20years%20to%20crack) [oai_citation:49‡security.org](https://www.security.org/how-secure-is-my-password/#:~:text=Using%20these%20factors%2C%20the%20tool,computer%2034%2C000%20years%20to%20crack). We also practiced documenting our process clearly. By avoiding real passwords and following safe screenshot practices, we completed the task securely.  
