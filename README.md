# Qhacks

### Functionality and Implementation

Meet StudySquid, a tool that allows Engineering students to study infinite amounts of Linear Algebra and Calculus problems. StudySquid does this with problem templates in MathJSON formatting with variables determined by random number generation, creating a unique problem everytime. Additionally, StudySquid implements Wolfram functionality to check the correctness of student answers via HTTP requests to the Woflram API. If a student sends a correct answer, regardless of its forms, if it is logically equivalent to the expected result it will be evaluated correct. If a student sends an incorrect answer, Wolfram's API will then send over the steps as an image link contained in a JSON file, and the Javascript frontend will embed this into the page.

### Usecases and Raving Reviews

In StudySquid, students are able to answer infinite unique generated questions and see the steps for every single unique problem. This gives students an excellent tool to add to their study routine, that currently works for Calculus topics such as limits, derivatives, and integrals. Additionally, it works for Linear Algebra problems such as bringing a matrix to row reduced echelon form. 

Nine out of 10 Queens Computer Science professors present at QHacks say "This is really amazing, so much better than my students plagiarizing off Chegg!"

### Future Expansion

StudySquid has proven to be an impressive proof of concept, and expandability for this project is planned. We plan to create more problem templates, clean up the code, and polish the frontend to make it more appealing. Additionally we are hoping to Natural Language Processing to receive answers to application questions or word problems that often make most sense answered in plain English rather than proper math syntax.
