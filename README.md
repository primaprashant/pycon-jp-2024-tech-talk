# PyCon JP 2024 Tech Talk

[Slides](./pycon-2024-autoreply-talk.pdf)

## Title

AI-powered Automatic Replies in Customer Support: Precision-Focused Approach at Mercari

## Abstract

Have you ever had a frustrating experience with a customer support chatbot? Issues like misunderstandings, irrelevant responses, and endless loops without reaching a human agent are common. So why do we use AI for sending automatic replies to customer inquiries at Mercari? Does it benefit customers? How do we ensure a positive experience?

Along with answering these questions, in this talk, we will look at the design of our highly precise system using machine learning for automatic replies. We will focus on Python content in sections about introduction to transformers, fine-tuning pre-trained transformer models on Japanese text, and the design and training of our ML model. Finally, we'll discuss our A/B testing methodology and the impact on business metrics from using automatic replies.

## Outline

- Introduction (2 minutes)
  -Who am I?
  -Problems with chatbots in customer support
-So why do we use AI for customer support? (3 minutes)
  -Examples of repetitive and trivial inquiries suitable for automatic replies
  -Examples of inquiries where no action is needed, and only information needs to be conveyed
  -Benefits to customers: instant response and resolution
  -Benefits to businesses: cost savings
-Ensuring a good experience with AI replies (3 minutes)
  -Importance of precision in sending automatic replies
  -Design choices for a good customer experience
    -One-click escalation to human support agents
    -Automatic replies only sent as the first response
-Designing a precise system for automatic replies (17 minutes)
  -Analyzing raw data to identify common inquiry patterns (1 minute)
  -Utilizing metadata for extra context (transaction status, shipping method, item price, etc.) (1 minute)
  -Introduction to transformers and their usage for text classification (5 minutes)
  -Introduction to fine-tuning pre-trained transformer models for text classification on Japanese text (5 minutes)
  -Designing and training ML models using inquiry texts and metadata (3 minutes)
  -Calibrating precision using output thresholds (1 minute)
  -Running A/B tests and impact on business metrics (1 minute)
-Conclusion (2 min)
-Q&A (3 min)

## Audience

Developers, data scientists, ML engineers, and business leaders interested in using AI to solve business problems including enhancing customer support operations.

## Outcome

By attending this talk, the audience will gain insights into how AI can be effectively used to enhance customer support while maintaining a positive customer experience. They will learn about the importance of precision in sending automatic replies, the process of analyzing customer inquiry data, and the use of machine learning techniques for text classification. The talk will also discuss the impact of implementing AI-powered automatic replies on business metrics.
