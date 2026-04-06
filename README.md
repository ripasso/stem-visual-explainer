# stem-visual-explainer
This is a project which customises your claude with a skill specifically for IB STEM subjects (Physics, Chemistry, Biology, Computer Science, Math and ESS) that require visualisations to make learning easier.

# What this skill in claude does:
- Loads a bundled IB syllabus reference file (Physics, Maths, Chemistry, Biology, CS, ESS) to find the exact topic and HL/SL terminology
- Supplements with a web search of revision sites (Save My Exams, Revision Village, Revision Dojo) for common misconceptions and exam tips
- Cites the exact IB syllabus reference at the top of every response (e.g. "IB Physics HL — A.2")
- Extracts the concept being tested from a question, without solving it so you can better learn and remember the concept.
- Always builds an inline visual first (diagram, graph, animation, interactive widget) using the question's actual values
- Follows the visual with a concrete worked analogy or real-world example and a step-by-step conceptual walkthrough
- Ends every explanation with an IB Language box - exact terms to use, terms to avoid, and what the IB command term expects
- Renders all equations in LaTeX, making them easier to understand.

# How to use?
- You can download the file, and upload it under the 'customise' tab in claude with the button 'upload a skill'.
<div align="center">
<img width="335" height="277" alt="image" src="https://github.com/user-attachments/assets/25d11999-bc27-4420-93c3-6894bca6646d" />

<img width="479" height="149" alt="image" src="https://github.com/user-attachments/assets/6a037c8c-2385-4fb1-872c-e508506a7f27" />
</div>

- If you want to tailor it to yourself, you can edit the skill with claude after you start using it, and also bring it up in the 'discussions' tab so I can roll out a new version.

# Examples of how it works:
The visualisations that are triggered and which part of the syllabus they are from, so you can look back and revise.
<div align="center">
<img width="947" height="517" alt="Screenshot 2026-04-06 at 8 42 49 PM" src="https://github.com/user-attachments/assets/bd13fac4-3cb1-4975-ad0d-b25f905a983f" />
</div>
The specific language that should be used in paper 2, rather than colloquial language that is used or misconceptions that people might have.
<div align="center">
<img width="890" height="259" alt="image" src="https://github.com/user-attachments/assets/1b51aa4a-faed-4e31-a0b8-89a9df47d530" />
</div>
The common mistakes that one might make and why they are wrong.
<div align="center">
<img width="835" height="157" alt="image" src="https://github.com/user-attachments/assets/e4bc786e-1cee-47fc-adb6-97cd1b13a5d6" />
</div>
