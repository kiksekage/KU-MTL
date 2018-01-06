# SemEval 2018 Task 1

Running example

python3 semeval2018.py --train data/2018-EI-reg-En-anger-train.txt data/2018-EI-reg-En-fear-train.txt data/2018-EI-reg-En-joy-train.txt data/2018-EI-reg-En-sadness-train.txt --dev data/2018-EI-reg-En-anger-dev.txt data/2018-EI-reg-En-fear-dev.txt data/2018-EI-reg-En-joy-dev.txt data/2018-EI-reg-En-sadness-dev.txt --test data/2018-EI-reg-En-anger-dev.txt data/2018-EI-reg-En-fear-dev.txt data/2018-EI-reg-En-joy-dev.txt data/2018-EI-reg-En-sadness-dev.txt --rnn --epochs 10 --char-embedding-dim 400 --rnn-dim 250 --resnet 4  --chars --aux data/2018-E-c-En-train.txt data/2018-E-c-En-dev.txt  --dropout 0.3 --words
