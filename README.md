java c
School of Natural and Computing Sciences
Department of Computing Science
MSc in Artificial Intelligence
2024 – 2025
CS502K – Symbolic AI
Assessment Item 3 – Part I – Individual Coursework (no groupwork)
This part of the assessment contributes with 30% of the overall mark for the module. Marks for individual questions and items appear in the specification below.
Learning Outcomes
This assessment, through its various tasks, has the following learning outcomes
• Knowledge and understanding of specific topics covered in the course
• Communication skills
• Problem solving
• Critical thinking and evaluation
Assessment Specification
Provide answers to the items below clearly indicating in your submission what each part refers to. If we cannot work out which item that parts of your submission refer to then you may miss marks.
1. (Propositional Logic) Hurkle World Environment -

Hurkle (H) is a beast that lives in a 4x4 grid world. Hurkle can at most be in only one square. Consider the environment definition of the Hurkle world as shown above which uses the notation used for the Wumpus world in Figure 7.3 in the book Artificial Intelligence: A Modern Approach. To avoid clutter the grid numbers are not shown here. Hurkle world is a lot simpler than the Wumpus world – no gold, no pits, no breeze and no stench.
In this question, you will use the logic module of the AIMA-Python code repository, which you have used in the lab classes. Your task is to create a Python Jupyter Notebook that uses AIMA-Python code to implement the Hurkle world environment incrementally using Propositional Logic. The environment should allow a human user to play the ‘Hurkle Hunt’ game. There are several versions of this game – e.g. the MSDOS Hurkle Hunt game.
Our version of this coursework is simpler than any of these. The main idea behind our version is that the Hurkle environment knows from the start where the Hurkle is in the Hurkle world and the user has a fixed number of attempts to guess the location of the Hurkle. Initially, the user guesses the Hurkle location randomly. If the user is lucky and the random guess is correct the Hurkle environment should confirm that the Hurkle is ‘caught’ by the user and the game stops. Otherwise, the environment gives a clue to the user asking her to move in one of the eight directions - N, E, W, S, NE, SE, SW, NW from the wrongly guessed location. The user then makes another guess informed by the clue. The game continues until the user makes the correct guess of Hurkle’s location. The number of guesses used to locate the Hurkle is the user’s score (low scores are better).
You will not implement the Hurkle environment fully. You will incrementally build the Hurkle environment in each of the tasks below. Although the Hurkle environment is new to you, you will benefit from a good understanding of the Wumpus world discussed in lectures which is also discussed thoroughly in sections 7.3 and 7.4 in the AIMA textbook. The inferences in the Wumpus world as demonstrated in the logic Jupyter notebook in AIMA-Python code repository will be useful to you while working on the tasks below.
NOTE:
1. Each of you will assume a different randomly chosen location for the Hurkle which will remain the same for you in all the tasks below.
2. The tasks below are described using the Hurkle location H13 as shown above in the figure. You shall have to interpret the instructions relative to your chosen Hurkle location.
3. For all the parts below, higher marks are given for clear explanations.
4. All the explanations should be directly added to the Jupyter notebook in the markdown cells.
i. Initial Simple Environment: Add the required Symbols and only one Sentence ‘telling’, in Propositional Logic to a PropKB knowledgebase, the location of the Hurkle which is ‘known’ to the Hurkle World Environment. Expla代 写CS502K – Symbolic AI 2024 – 2025 Assessment Item 3Python
代做程序编程语言in (directly in a markdown cell) this simple environment using the contents of the knowledgebase. In this task, you will play only the first initial random guess. In this task consider that as a user you make a wrong guess such as H42 (Since H13 is chosen (which will be different for each of you), this is a wrong guess). Is your simple environment created in this task able to logically ‘infer’ that this guess of H42 is false (not true)? Make the required inference in the notebook and explain your findings.     (5 marks)
ii. Intermediate-level Environment: Feel free to reinitialize your knowledgebase if required in this task. One of the constraints on the Hurkle location is that the Hurkle can at most be in only one square. Add the required sentences or rules to the knowledgebase and rerun the inference from the above task I and explain your findings.     (5 marks)
iii. Advanced-level Environment: Feel free to reinitialize your knowledgebase if required in this task. Define the required symbols for this task. Add rules to the knowledgebase that allow user to check each of the eight directions to learn the direction clue from the environment. Run one example check in your notebook. Your check for NW should call the usual inference mechanism as shown below:
Hurkle_kb.ask_if_true(NW), Hurkle_kb.ask_if_true(~NW) (5 marks)
2. (First Order Logic). Consider the following paragraph which you will use to create a FolKB (a knowledgebase in First Order Logic) using the code in the AIMA-Python Knowledge and Reasoning module:
“Olympians who are physically and mentally healthy win gold medals. Persons who eat healthy, sleep well and exercise regularly are always physically healthy. Persons who have positive friends and watch less TV are always mentally healthy. Sports persons have positive friends. Sports persons always do a lot of physical exercise and always eat a healthy diet. Sports persons always watch less TV. Simone Biles is a gymnast and an Olympian. She sleeps well.”
i. Create a FolKB using the information content (knowledge) in the above paragraph. Add any general knowledge required to complete your knowledgebase.          (8 marks)
ii. Using the forward chaining algorithm, fol_fc_ask in Knowledge and Reasoning module, list the Olympians who win gold medals showing the intermediate steps in the inference process.   (2 marks)
Marking Criteria
CGS D: For Task 1, the notebook partially provides the required inferences and explanations. For task 2.i, the notebook provides a partial FOL representation of the meaning of the given text. For task 2.ii, the notebook fails to make a correct inference but does not show the steps to achieve the inferences.
CGS C: For Task 1, the notebook provides the required inferences and explanations reasonably completely. For task 2.i, the notebook provides a reasonably complete FOL representation of the meaning of the given text. For task 2.ii, the notebook makes the required inference and partially shows the steps involved in making the inference.
CGS B: For Task 1, the notebook provides the required inference and explanations completely. For task 2.i, the notebook provides a complete FOL representation of the meaning of the given text. For task 2.ii, the notebook makes the required inference and shows the steps to achieve the inferences.
CGS A: For Task 1, the notebook provides the required inference and explanations completely. The explanations particularly will show the depth of student’s understanding of the challenges involved in applying propositional logic to solve complex AI tasks. For task 2.i, the notebook provides a complete FOL representation of the meaning of the given text along with excellent explanations. For task 2.ii, the notebook makes the required inference and shows the steps to achieve the inferences along with excellent explanations.


         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
