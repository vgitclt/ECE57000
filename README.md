# ECE57000
ECE57000 Term Paper code
## Note when notebook says invalid, please open it via google colab, as Github cannot render it

Name: Venu Thamodharan

Program: MSAI

LLM-as-a-judge is a common technique to evaluate LLM-powered products.
It grew in popularity for a reason: it’s a practical alternative to costly human evaluation when assessing open-ended text outputs. We can see it as an automated testing tool for LLMs effectiveness Judging generated texts is tricky — whether it's a “simple” summary or a chatbot conversation. Metrics like accuracy don’t work well because there are many ways to be “right” without exactly matching the example answer. And things like style or tone are subjective and hard to pin down. Humans can handle these nuances, but manually reviewing every response doesn’t scale. LLM-as-a-judge emerged as an alternative: you can use LLMs to evaluate the generated texts. Interestingly, the LLM is both the source of the problem and the solution!

Abstract
Evaluating chat assistants based on large language
models (LLM) is a complex task due to their wide-
ranging capabilities and the inadequacy of current
benchmarks in capturing human preferences. To
address this, this implementation will explore the
use of advanced LLMs as judges to assess these
models on more open-ended questions. We in-
vestigate the strengths and limitations of using
LLMs as judges, including issues related to po-
sition, verbosity, self-enhancement biases, and
limited reasoning ability, and propose potential
solutions to mitigate some of these challenges.
This implementation will examine the benefits
and drawbacks of using LLMs as judges, in-
cluding problems with verbosity, position, self-
enhancement biases, and weak reasoning skills.
This implementation will also suggest possible
ways to address some of these concerns and will
present a benchmark using predefined multi-turn
questions to assess how effectively LLM judges
match human preferences. According to results,
strong LLM judges like GPT-4 can successfully
match controlled human preferences, attaining
80% agreement1, which is comparable to the de-
gree of human-to-human agreement. Because
human preferences are usually expensive to col-
lect, LLM-as-a-judge offers a scalable and inter-
pretable way to approximate them
