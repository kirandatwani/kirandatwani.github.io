---
layout: essay
type: essay
title: Asking Smart Questions for Great Answers
# All dates must be YYYY-MM-DD format!
date: 2021-01-27
labels:
  - Smart Questions
---

<img class="ui medium right floated image" src="../images/smart1.jpg">

What exactly does it mean to ask "smart" questions? To one person, it could be a question that has a thought-provoking, open-ended answer, and to another, it might be a question that many other people were curious about, but weren't sure how to ask. Since we are young, we are told to always ask questions: to your teacher, professors, potential employers, and the list goes on. At a young age, we are told that there are no "stupid" questions, but in any field, there is a right way and a wrong way to ask a question. Smart questions are questions that are precise, intriguing and to-the-point. Most importantly, the audience, such as an experienced programmer or hacker, should not feel like they wasted their valuable time answering a question a person didn't put effort in asking. The person asking questions without much thought isn't well-respected or regarded by any community, and usually left unanswered or with sarcasm. As written by Eric Steven Raymond, *"it's simply not efficient for us to try to help people who are not willing to help themselves. It's OK to be ignorant; it's not OK to play stupid"*. (Image retrieved <a href="https://telebid-pro.com/how-to-ask-questions-the-smart-way/">here</a>.)

## Asking a Question: The Right Way

<img class="ui medium left floated image" src="../images/smart2.jpg">

<a href="https://stackoverflow.com/">Stack Overflow</a>, a site used by developers, programmers, and students is home to thousands upon thousands of questions and answers. Many questions are asked and answers given on a daily basis; while some are asked in the smart way, others are not.

A question asked in a <a href="https://stackoverflow.com/questions/218384/what-is-a-nullpointerexception-and-how-do-i-fix-it">"smart way"</a> is by this programmer who offeres a precise and straight-forward question that received a good amount of feedback and answers from the community. This person asked a question the smart way, which allowed the person to receive a few hundred upvotes along with a variety of answers. The main part of this question which deemed it as a smart question was that after a decade, the question received efficient and effective help from programmers and the community. This question was interesting enough for programmers to answer them, along with supplemented others users were just starting on the basics. (Image retrieved <a href="https://www.brightermonday.co.ug/blog/questions-for-interviewer/">here</a>.)

```
Q: What is a NullPointerException, and how do I fix it?

What are Null Pointer Exceptions (java.lang.NullPointerException) and what causes them?

What methods/tools can be used to determine the cause so that you stop the exception from causing the program to terminate prematurely?

```


## Asking a Question: The Wrong Way

On the other hand, a person who asked a question in the <a href="https://stackoverflow.com/questions/65934719/how-do-you-do-a-chain-of-if-statements-in-c">"not smart way"</a>, proceeded exactly the way the author Raymond wrote not to. Although this question was decent, and clear, it could have been worded better. The main issue was not the question in itself, but the way this person approached it. A lengthy piece of code with no explantion of the error was given, and a question asking for the answers goes against precisely with what Raymond spoke about. This person was not willing to work on finding the issues caused, but rather requesting for the solution to his code, which also diverged from his original question. The question asked "how something was done" rather than "what is wrong with my code?"

```
Q: How do you do a chain of if statements in C? [closed]

  if (grade >= 75) {
    printf("\nPASSING");
    getch();
    goto Sol;

    if (grade >= 90) {
        printf("\nWITH HONORS");
        getch();
        goto Sol;

        if (grade >= 95) {
            printf("\nWITH HIGH HONORS");
            getch();
            goto Sol;

            if (grade >= 98) {
                printf("\nWITH HIGHEST HONORS");
                getch();
                goto Sol;

                if (grade >= 101) {
                    printf("INVALID");
                    getch();
                    goto Sol;
                }
            }
        }
    }
    else {
        printf("FAILURE");
        getch();
        goto Sol;
    }
    
This is my code so far but it won't work. What should I do to make it work?

```

Not only did this person receive four downvotes in two hours, and have the question closed after 90-100 minutes, but the people answering the question weren't in agreement either, leading to nearly all answers associated with this question having downvotes too. The writer of the question was fortuante that the people weren't too harsh or sarcastic, and continued to answer and help the best they could. This affected the audience who possibly had the same questions, but were eventually confused by the original person who asked the questions, and the confusing, ineffective and inefficient answers that were given. Some comments on ineffective answers included:

```

C: Whoever downvoted should explain what is wrong... – Gerhardh

C: If you switch the order of your conditions, you can avoid needing to check for an upper boundary. Start with highest value and continue towards lower. – Gerhardh

C: Although the OP did not express themselves clearly, I believe it is the intent of the OP to output "PASSING WITH HIGHEST HONORS" instead of only "WITH HIGHEST HONORS". In that case, both cases must be combined. See my answer for a solution which does this. – Andreas Wenzel 
    
```


## Final Thoughts

The goal of this exercise is not to “prove” that asking questions the smart way is always better. Instead, the goal of this exercise is to help you form a deeper understanding of what constitutes “smart” and “not smart” questions so that you are more likely to ask smart ones in the future.

Write a technical essay that discusses why smart questions are important for smart software engineers, how the chosen questions fulfill (or not) the precepts for smart questions, how the responses reflect the smartness (or lack thereof), and the insights you gained as a result of this experience.


time of others -- how important it is -- making others feel less important
