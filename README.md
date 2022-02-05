# Machine learning process

## Define the problem

### Step 1: What is the problem? Describe the problem informally and formally and list assumptions and similar problems.

### Step 2: Why does the problem need to be solved? List your motivation for solving the problem, the benefits a solution provides and how the solution will be used.

### Step 3: How would I solve the problem? Describe how the problem would be solved manually to flush domain knowledge.

## Prepare Data
### Step 1: Data Selection: Consider what data is available, what data is missing and what data can be removed.

### Step 2: Data Preprocessing: Organize your selected data by formatting, cleaning and sampling from it.

### Step 3: Data Transformation: Transform preprocessed data ready for machine learning by engineering features using scaling, attribute decomposition and attribute aggregation.


## Spot Check Algroithms
### Algorithm Diversity: You want a good mix of algorithm types. I like to include instance based methods (live LVQ and knn), functions and kernels (like neural nets, regression and SVM), rule systems (like Decision Table and RIPPER) and decision trees (like CART, ID3 and C4.5).

### Best Foot Forward: Each algorithm needs to be given a chance to put it’s best foot forward. This does not mean performing a sensitivity analysis on the parameters of each algorithm, but using experiments and heuristics to give each algorithm a fair chance. For example if kNN is in the mix, give it 3 chances with k values of 1, 5 and 7.

### Formal Experiment: Don’t play. There is a huge temptation to try lots of different things in an informal manner, to play around with algorithms on your problem. The idea of spot-checking is to get to the methods that do well on the problem, fast. Design the experiment, run it, then analyze the results. Be methodical. I like to rank algorithms by their statistical significant wins (in pairwise comparisons) and take the top 3-5 as a basis for tuning.

### Jumping-off Point: The best performing algorithms are a starting point not the solution to the problem. The algorithms that are shown to be effective may not be the best algorithms for the job. They are most likely to be useful pointers to types of algorithms that perform well on the problem. For example, if kNN does well, consider follow-up experiments on all the instance based methods and variations of kNN you can think of.

### Build Your Short-list: As you learn and try many different algorithms you can add new algorithms to the suite of algorithms that you use in a spot-check experiment. When I discover a particularly powerful configuration of an algorithm, I like to generalize it and include it in my suite, making my suite more robust for the next problem.


## Improving the results

### Algorithm Tuning: where discovering the best models is treated like a search problem through model parameter space.

### Ensemble Methods: where the predictions made by multiple models are combined.

### Extreme Feature Engineering: where the attribute decomposition and aggregation seen in data preparation is pushed to the limits.

## Present Results
### Context (Why): Define the environment in which the problem exists and set up the motivation for the research question.

### Problem (Question): Concisely describe the problem as a question that you went out and answered.

### Solution (Answer): Concisely describe the solution as an answer to the question you posed in the previous section. Be specific.

### Findings: Bulleted lists of discoveries you made along the way that interests the audience. They may be discoveries in the data, methods that did or did not work or the model performance benefits you achieved along your journey.

### Limitations: Consider where the model does not work or questions that the model does not answer. Do not shy away from these questions, defining where the model excels is more trusted if you can define where it does not excel.

### Conclusions (Why+Question+Answer): Revisit the “why”, research question and the answer you discovered in a tight little package that is easy to remember and repeat for yourself and others.

