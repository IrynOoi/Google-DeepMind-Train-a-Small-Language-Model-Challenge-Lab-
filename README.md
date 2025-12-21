# Challenge Scenario

## Cymbal Chat: Developing a Chatbot for the Arabic-Speaking Market

Cymbal Chat is an AI language modeling small startup. They would like to expand the languages they cover to include **Arabic**. Arabic has a very different grammar than English and uses a different character set than what their AI researchers are used to.

You are going to help them with their first steps by exploring the use of **character-based language models**.

---

> ℹ️ **Info**
>
> Sometimes, character-based language models may work better for Arabic NLP tasks than word-based models [1]. This is because subwords can be attached to the beginning or end of words to add meaning.
>
> For example, a noun (*book*) can be modified as:
>
> - **كتاب (kitāb)** — a book  
> - **كتابي (kitāb-ī)** — my book  
> - **كتابك (kitāb-uk)** — your (masculine) book  
> - **كتابه (kitāb-uh)** — his book  
>
> Arabic is read from **right to left**, and in these examples the modifiers are added to the **end** of the host word (*book*).
>
> Modifiers can also be added **before** the host word, such as:
>
> - Conjunctions: **و** (*wa-*, meaning *and*), **ف** (*fa-*, meaning *so* or *then*)
> - Prepositions: **ب** (*bi-*, meaning *with* or *in*), **ل** (*li-*, meaning *for* or *to*)

---

## Tasks

Exploring the use of character-based language models will involve the following tasks:

- **Task 1:** Define helper functions and load data.
- **Task 2:** **Character tokenizer** — Create a simple character-level tokenizer for Arabic text.
- **Task 3:** **N-gram text generator** — Develop an n-gram-based text generator as a baseline against which to evaluate a more sophisticated model.
- **Task 4:** **Data preparation** — Prepare an Arabic dataset so that it can be used for training a character-based transformer language model on restricted resources.



