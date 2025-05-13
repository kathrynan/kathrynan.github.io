---
layout: essay
type: essay
title: "Smarter Questions, Not Harder Questions"
# All dates must be YYYY-MM-DD format!
date: 2025-01-30
published: false
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-end pe-4" src="../img/cotton/coding.jpg">

### Work Smarter, Not Harder

I have always found different ways to interpret the aforementioned phrase, and yet it all revolves around intent. What do you intend to convey when you get roll your eyes at someone? What about when you give someone else a gift? The same applies for asking questions: what are you trying to convey when asking a certain question, why are you asking the question in the first place, and what do you want to get out of it?

Now when it comes to asking questions about code, you need to be extremely smart about it. First off, you need to not only have some idea of what's wrong with the code, but you need to have enough understanding to explain how the code works to other people so they can help answer your question.

Here is an example of a smart question:


```
Q: How to validate a receipt on server side with StoreKit 2?

I am using Storekit-2 for InApp purchase. The product is consumable. After the purchase is successful, I need to call API and backend will grant 200 coins to that user.

Now, users can try to access the data with no subscription by simply executing requests to the server. For this reason, I will have to validate receipt on server side.

I have done some R&D and get to know that I need to pass the following receiptData to server.

(They proceed to show a sample of the code they're working on.)

Then the server should send a request to Apple’s verification server at the following URL:

Production: https://buy.itunes.apple.com/verifyReceipt

Sandbox: https://sandbox.itunes.apple.com/verifyReceipt

I also read one article and they suggest to use following:

(They show the sample code suggested to them.)

Is that the right way to do? Also my question is, the following receiptData is not for specific transaction, i.e it is not generated from a transaction. Then how specific transaction is verified?
```

First of all, the question's title is very detailed yet concise, summing the overall question up into one short sentence. Then they explain their code's purpose and show the lines of code they're working with, in case people are curious about the code and to check for syntax errors. They also give a suggested solution, with reveals they have been looking up answers on their own but have not come across anything satisfactory. Finally, they ask very specific questions in order to show their base knowledge in the subject and (hopefully) receive concise answers to their problem. The question was asked today, so unfortunately there are no responses yet; however, I'm very confident people will be able to easily answer the original poster's questions.

Now, here is an example of a not-so smart question:

```
Q: Why doesn't my code work?

I wrote some Python code that should do something, but it isn't working. Here's the code:

(They proceed to show a sample of their code.)

It just doesn't work. Can someone tell me what is wrong?
```

First off, the title of the question does not give any indication as to what the poster is struggling with. No one will be able to understand what their question is until they open up the post; that is, if the poster described the code's purpose and what problems they were running into. Unfortunately, this example shows that all the original poster did was copy/paste their code and ask people to find the error, without giving any context or summary. It also shows that this person has no intention to learn or make their code easy to understand. Not only is it not a smart question, but a question formatted this way would deter people from even engaging with the post.

### Conclusion
Smart questions are not just so we can get the answers we need, but also so people can understand along with us when they try to help solve our code. Especially with larger projects, making our work easier to process is a mandatory courtesy we should extend when asking for help. Smart questions benefit both sides, and everyone learns as a result.

*ChatGPT was used to generate the "not-so smart" question.*
