1)Tokenise Hindi corpus.
python indic_tokenizer.py --i  corpus.txt --o corpus_tokenised.txt --l hin


indic_tokenizer is a sentence tokenizer for Indian Languages. "hin" is the code for the language "Hindi"

2)Run the spell checker (Give an input sentence and the index of the word in consideration) 
python BigramModelSpellCheck.py

The code returns a ranked list of word suggestions (with most probable word on the top)
