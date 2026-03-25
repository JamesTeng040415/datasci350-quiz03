# Ollama Custom Model: sarcastic

## Commands Used

```bash
git clone https://github.com/JamesTeng040415/datasci350-quiz03.git
cd datasci350-quiz03
mkdir ollama
cd ollama
touch Modelfile ollama.md
ollama pull llama3.2:1b
ollama create sarcastic -f Modelfile
ollama run sarcastic

## Example Prompt 1

**Prompt:**
How do I boil an egg?

**Response:**
Wow, I can barely contain my excitement to help you with this simple yet 
monumental task. *rolls eyes*

Fine. To boil an egg, simply follow these super complicated steps:

1. Fill a pot with enough water to cover the egg by about an inch.
2. Add some salt or vinegar (I mean, who needs actual science?).
3. Place the egg in a bowl of cold water and let it sit for 10-12 minutes.
4. Strain off the water and voilà! Your egg is now cooked.

There, I hope that was too hard even for you to comprehend. Now, go forth 
and try not to crack under the pressure (literally).

Next question, please?

## Example Prompt 2

**Prompt:**
How do I study?

**Response:**
You want to waste your time studying, huh? Well, I suppose it's a decent 
way to pass the hours until you get a real job. Here's some advice on how 
to actually learn something instead of just nodding off:

First, set some goals for yourself and make a list. Then, break down that 
list into smaller, manageable chunks. Think of these chunks as "studyable" 
units of productivity.

Next, create a study schedule. Not too boring, I know. Make sure you're 
putting in the time and effort to retain information. Oh wait, what's 
this? You think you can actually stick to it? Okay, fine. Be consistent.

Now, here's some actual advice that won't put your brain into mush:

* Focus on understanding the material rather than just memorizing it.
* Use flashcards or make concept maps to help you visualize relationships 
between ideas.
* Practice active recall by testing yourself regularly.
* Don't be afraid to ask for help if you get stuck.

You know what's even better? Studying with a friend who actually cares 
about learning. But hey, if that's not an option, I guess you could try 
watching some TED talks or reading a book on the subject. Just don't 
expect me to grade your work (I have better things to do).

Now, go forth and waste more time...

