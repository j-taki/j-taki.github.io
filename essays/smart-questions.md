---
layout: essay
type: essay
title: Smarter questions take time and effort
# All dates must be YYYY-MM-DD format!
date: 2019-01-17
labels:
  - Learning
---

Smart questions are really about not being lazy with learning. By taking the time to collect and curate thoughts,
we force ourselves to become thinkers and thus better problem solvers.

![confusion-question](https://imgs.xkcd.com/comics/words_that_end_in_gry.png)

# The Lazy Trap
Our brains are inherently lazy. After all, it is a survival mechanism to complete tasks by using less energy. In the internet age of today, finding the answer to any simple question can be found in a second... so why shouldn't it be that way for the more complex ones? I myself have definitely built up a reliance on using things like calculators for simple math which has in turn made me lazy for even things like adding tip to a restaurant bill. I think that a key theme in asking smart questions is to be deliberately **NOT LAZY** in learning.

# Smart Questions lead to Smart Engineers
Now that we have accomplished the first step of losing the lazy mentality, we can now build an algorithm for forming smart questions. The first block needs to be to build our knowledge base and community. Stack Overflow, Reddit, and specialized communities on Slack are communities that I've identified as useful in learning programming. Taking the time to observe and become familiar with the community is important too. Communities aren't just about receiving help, but giving help and constructively participating as well.

Once you've exhausted resources like documentation, google, previously asked questions on Stack Overflow, etc. and still cannot find a solution, we should at least now have a better understanding of our question.

## Be a good person... nay. A good professional
Remember that people in the communities who help others aren't paid to do so. By no means are they obligated to help us with our problems as we aren't obligated to help them with theirs. Treat everyone with respect and communicate effectively. This means using correct grammar and spelling, keeping a professional tone, and patience. Generally, you will get a better answer (and learn more) by actively trying to understand the problem and solution instead of just receiving the answer.

## You are both the doctor and the patient
In describing your problem, you must try to be as informative and specific as possible while being concise. Much like how a patient describes symptoms of ailment to a doctor, you must describe your symptoms and the surrounding conditions to give the question context. Simply saying "I have a sore stomach" is not good enough. Is it recurring? Only at night? Related to diet or exercise? By adding more context, you might even be able to identify and diagnose it yourself... it was that week-old burrito you ate for lunch yesterday.

Software questions are similar. In saying "[I can't install VSCode](https://stackoverflow.com/questions/52351844/i-cant-install-visual-studio-code/52351910)" on a forum leaves out huge clues as to what might be the problem. A lack of specifics like hardware, software versions, dependencies, and steps taken are indications that the asker is lazy and hasn't even attempted to diagnose the problem.


# A Dumb question
[I can't install VSCode](https://stackoverflow.com/questions/52351844/i-cant-install-visual-studio-code/52351910)



## The subject line
> "I can't install Visual Studio Code"

Even though this subject explains the problem, it does not add any context to which specialists or community members might use to identify thought a thought provoking problem.

Even for the tags, the only associated tag is "Visual Studio Code". Not even a mention to running Windows 10.

## Problem description
> "when I install VScode in Win10 I've got this alert. What's wrong with it?"

> ![dumb-question](https://i.stack.imgur.com/CgHTT.png)
Literally this person pasted this picture and expects the community to determine a solution. The one credit I will give this guy is that they threw in the operating system name.
There is no reference to:
  - Diagnostic steps taken to determine the issue
  - A helpful translation of this Chinese to English since there was no "chinese language" tag
  - Any research done to find understanding
  - Recent changes in environment settings or configuration
  - How to reproduce the issue

## Result
The first result is that within 1 day, the moderators on Stack Overflow closed the post for not asking a clear question. They identified that the question was not clear to details regarding the problem nor exactly what they needed.
> "closed as unclear what you're asking"

The question received 1 answer where the answerer posted links to 3 articles on how to solve the very generic issue. They also provided some diagnostic steps as to how to solve it. In the end, the asker does end up solving the issue, but it is not directly related to the answer.


# A Smart question
[What does “use strict” do in JavaScript, and what is the reasoning behind it?](https://stackoverflow.com/questions/1335851/what-does-use-strict-do-in-javascript-and-what-is-the-reasoning-behind-it)

This is actually a question I had last week while looking at a peer's code. It's easy to tell that this person was seeking more understanding rather than a simple answer.

## The subject line
> "What does "use strict" do in Javascript, and what is the reasoning behind it?"

The asker was direct with the question and gave the context of which language it was in. This makes it easy for people browsing SO to identify the topic instantly.

Asker also provides useful tags that pertain to the question like 'javascript', 'syntax', 'jslint', 'use-strict'

## Problem description
The asker first gives context as to where they ran into this piece of code.
> "Recently, I ran some of my JavaScript code through Crockford's JSLint, and it gave the following error:
`Problem at line 1 character 1: Missing "use strict" statement.`"

The asker even linked to the application in which he encountered the error for the community to reproduce it. They explained succinctly the steps they took to find the answer. It shows htey did the research to look for answers.
> Doing some searching, I realized that some people add "use strict"; into their JavaScript code. Once I added the statement, the error stopped appearing.

The asker then gives context into what they are trying to understand about the topic which was stated in the subject "what is the reasoning behind it?"

> "Unfortunately, Google did not reveal much of the history behind this string statement. Certainly it must have something to do with how the JavaScript is interpreted by the browser, but I have no idea what the effect would be."

The asker describes the goal of his question. He wants understanding into the reasoning and the inner-workings of the language. He explicitly states the things he is looking for.
1. >"So what is "use strict"; all about, what does it imply, and is it still relevant?"

2. >"Do any of the current browsers respond to the "use strict"; string or is it for future use?"

## Result
This question received 25 answers with the top answer earning a 4573 upvote score.

The top answer links to a useful article about 'strict mode', a blockquote containing the most important part of the article, and examples as to how strict mode is helpful.

They even include extra information as to different use cases for 'use-strict' and personalized help.
> "Also note you can apply "strict mode" to the whole file... Or you can use it only for a specific function (still quoting from John Resig's article):"
```
// Non-strict code...

(function(){
  "use strict";

  // Define your library strictly...
})();

// Non-strict code...
```
> "Which might be helpful if you have to mix old and new code ;-)"

Its pretty clear that the quality of this answer is derived from the thoughtfulness of the question asked. I think that because the asker showed that they were interested in gaining understanding, the answer reciprocated in a similar fashion.
