# MEMD-ABSA
 A multi-element multi-domain dataset for Aspect-Based Sentiment Analysis. [[paper]]([https://arxiv.org/pdf/2306.16956.pdf)

## Data Description:

1. "raw_words" is the review sentence;
2. "quadruples" is the quadruple list of the given review sentence;
3. "aspect" contains the start ("from") and end ("to") indexes of the aspect span, the indexes are "-1" and "-1" when the is "aspect" implicit;
4. "category" is selected from the predefined category set;
5. "opinion" contains the start ("from") and end ("to") indexes of the opinion span, the indexes are "-1" and "-1" when the is "opinion" implicit;
6. "sentiment" is sentiment polarity from {"POS", "NEG", "NEU"}.
