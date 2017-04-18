All check points and results for neural-chatbot
To train drl seq-2-seq, cd to drl_dialog:
UDA_VISIBLE_DEVICES=2 python run_seq2seq.py --data_dir /data2/xiao/neural-inputs/movie/sess-idx --train_dir /data2/xiao/data-neural-chatbot/final/checkpoint --vocab_size 50005
