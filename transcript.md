SLIDE: 2021
It is 2021. Or, if you're on pandemic time, the 52nd week of March 2020.
SLIDE: 7.8 billion
There are nearly 8 billion people on the planet right now.
SLIDE: 7139
And they speak about 7000 languages
SLIDE: 200
But only around 200 of those languages have some form of speech recognition support - that is, only around 200 language have supporting technology that allows transcription.
SLIDE: 55 of 135
And of those 200 or so languages, the majority are languages spoken in affluent or rich countries. For example, of the 135 languages supported by Google speech to text, 55 are variants of just three languages - english, spanish and arabic.
SLIDE: Indigenous languages
Indigenous languages don't get much of a look in, which is disappointing considering some Indigenous languages are spoken by millions of people - like Kinyarwanda, spoken by 12 million people in Rwanda. This is one of the reasons why the United Nations declared 2019 the Year of Indigenous Languages, and has declared 2022-2031 the Decade of Indigenous Languages.
SLIDE: What about DeepSpeech
So what does this have to do with DeepSpeech?
Great question, I'm so glad you asked
SLIDE: Two functions
DeepSpeech has two key functions. It can be used for _inference_, which is where speech recognition is performed from a _trained model_.
And DeepSpeech can also be used for _training_ that model.
The way DeepSpeech trains a model uses a new type of algorithm.
SLIDE: seq2seq
DeepSpeech is a _sequence to sequence_ speech recognition engine. This means it doesn't use _phonemes_.
What are _phonemes_? Also a great question.
SLIDE: Phonemes
Phonemes are the building blocks of sound in a language. For example, the English language has 44 phonemes, and every word in English is made up of one or more of these _phonemes_.
SLIDE: acoustic model
Earlier types of speech recognition engines used two types of _model_. They would first use an _acoustic model_ which recognised _phonemes_ from a spoken phrase - like this.
SLIDE: language model
and then they would use a _language_ model to turn the _phonemes_ into a word, like this.
SLIDE: seq2seq
Sequence to sequence algorithms, like DeepSpeech, learn to go straight from a spoken phrase to a transcription. Like this!
But why is this important for under-served languages?
SLIDE: alphabet.txt
During training DeepSpeech is fed an `alphabet.txt` file to train from.
SLIDE: examples of alphabet
Any Unicode character can be in the `alphabet.txt` file.
That means we can train it on Kabyle, or Swahili, or Polish, or Welsh. Without a language model. It learns the words from transcriptions.
SLIDE: Kinyarwanda
And it means that if you can mobilise a language community, and record thousands of phrases, and thousands of hours of speech, you can train a speech recognition model.
SLIDE: 201
And make a small difference in the world.
