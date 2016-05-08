Run the scripts as follows:

Part 1:

python train_hmm_tagger.py <training filename> −−\[cpostag\|postag\]

Example: 

python train_hmm_tagger.ipy train/turkish_metu_sabanci_train.conll --cpostag


Part 2:

python hmm_tagger.py <test blind filename> <output filename>

Example:

python hmm_tagger.ipy test/turkish_metu_sabanci_test_blind_sample.conll.txt 


Part 3:

python evaluate_hmm_tagger.py <output filename> <test gold filename>

Example:

python evaluate_hmm_tagger.ipy output_file.txt test/turkish_metu_sabanci_test_gold_sample.conll.txt
