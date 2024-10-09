###Survey State Machine
The State Machine Diagram consists of Five States which are
1. Created
2. Editing in Progress
3. Completed
4. Verified
5. Deleted.
1)	In the Created Stage we just add a question which makes us move it to the EIP stage.
2)	 In EIP Stage we can add or remove question and there is also a limit on amount to add or remove questions.If number of questions are greater than 5 we can’t add further and if number of questions are zero we can’t remove questions
3)	In the Completed Stage of Survey we check if it meets the completion criteria whether the number of questions are greater than zero or not.
4)	In the Verifying stage we use external review and automated tool review to verify the survey. If it verifies, the survey is accepted or it is put back into EIP Stage.
5)	In the Deletion Stage, once we delete a given survey, we can’t do further process and it remains deleted forever.
