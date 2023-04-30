Download Link: https://assignmentchef.com/product/solved-csc421-assignment-3
<br>
For Q1, Q2: a photo/scan/file of your solution.

For Q3-Q4: FOL formulation and Prover9 proof.

Q1.Using propositional resolution, show the following propositional sentence is unsatisfiable.

(p | q | -r) &amp; ((-r | q | p) -&gt; ((r | q) &amp; -q &amp; -p))

To do this, convert this sentence to clausal form and derive the empty clause using resolution.

Q2.

Every horse can outrun every dog.

Some greyhounds can outrun every rabbit.

Show that every horse can outrun every rabbit.

Write a FOL formulation, negate the conclusion, convert to clausal form, then, using resolution derive the empty clause.

For Q3 and Q4, express them in FOL, then, using Prover9, attempt to prove the conclusions.

Q3.

All hummingbirds are richly colored.

No large birds live on honey.

Birds that do not live on honey are dull in color.

Conclusion: All hummingbirds are small.

Hint. Add a background knowledge premise not explicitly mentioned in the problem:

all x (hummingbird(x) -&gt; bird(x)).




Q4.

My gardener is well worth listening to on military subjects;

No one can remember the battle of Waterloo, unless he is very old;

Nobody is really worth listening to on military subjects, unless he can remember the battle of Waterloo.

Conclusion: My gardener is very old.




Q5. (3 pt) Redo the probability calculation for pits in [1,3], [2,2] assuming that each square contains a pit with probability 0.01, independent of the other squares. What can you say about the relative performance of a logical versus a probabilistic agent in this case?

Q6. (9 pts) [Adapted from a CMU machine learning assignment]

As part of a comprehensive study of the role of CMU 10-601 (Machine Learning) on people’s happiness, CMU has been collecting data from graduating students. In an optional survey, the following questions were asked:

<ul>

 <li>Do you party frequently [Party: Yes/No]?</li>

 <li>Are you wicked smart [Smart: Yes/No]?</li>

 <li>Are you very creative [Creative: Yes/No]? (Please only answer Yes or No)</li>

 <li>Did you do well on all your homework assignments? [HW: Yes/No]</li>

 <li>Do you use a Mac? [Mac: Yes/No]</li>

 <li>Did your course project succeed? [Project: Yes/No]</li>

 <li>Did you succeed in your most important class (which is 10-601)? [Success: Yes/No]</li>

 <li>Are you currently Happy? [Happy: Yes/No]</li>

</ul>




You can obtain the comma-separated survey results from the accompanying file.

Each row in <em>students.csv</em> corresponds to the responses of a separate student.

The columns in <em>students.csv</em> correspond to each question (random variable) in the order Party, Smart, Creative, HW, Mac, Project, Success, and Happy.

The entries are either zero, corresponding to a No response, or one, corresponding to a Yes response.

After consulting a behavioral psychologist they obtained the following complete set of conditional relationships:

<ul>

 <li>HW depends only on Party and Smart</li>

 <li>Mac depends only on Smart and Creative</li>

 <li>Project depends only on Smart and Creative</li>

 <li>Success depends only on HW and Project</li>

 <li>Happy depends only on Party, Mac, and Success</li>

</ul>




<ol>

 <li> Draw the Bayesian network.</li>

 <li>Estimate the probabilities of the conditional probability tables using the data provided (you can use Excel pivot tables for counting).</li>

 <li> What is the probability of being happy given that you party often, are wicked smart, but not very creative? Show details of computation.</li>

 <li> What is the probability of being happy given that you are wicked smart and very creative? No details required. Use the AIspace tool.</li>

 <li> What is the probability of being happy given you do not party, and do well on all your homework and class project? No details required. Use the AIspace tool.</li>

 <li>What is the probability of being happy given you own a mac? No details required. Use the AIspace tool.</li>

 <li>What is the probability that you party often given you are wicked smart? No details required. Use the AIspace tool.</li>

 <li> What is the probability that you party often given you are wicked smart and happy? No details required. Use the AIspace tool.</li>

</ol>


