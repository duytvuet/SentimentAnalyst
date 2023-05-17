# SentimenAnalysClassification

Sử dụng GOOGLE COLAB: 
 
# Cài đặt transformers
!pip install transformers

# Cài đặt fast BPE, fairseq
!pip install fastBPE
!pip install fairseq

* Sau đó giải nén tệp .tar.gz sau khi cài fastBPE, fairseq
!wget https://public.vinai.io/PhoBERT_base_fairseq.tar.gz
!tar -xzvf PhoBERT_base_fairseq.tar.gz
!wget https://public.vinai.io/PhoBERT_base_transformers.tar.gz
!tar -xzvf PhoBERT_base_transformers.tar.gz

# Cài đặt vncorenlp 

!pip install vncorenlp

!mkdir -p vncorenlp/models/wordsegmenter 
!wget https://raw.githubusercontent.com/vncorenlp/VnCoreNLP/master/VnCoreNLP-1.1.1.jar 
!wget https://raw.githubusercontent.com/vncorenlp/VnCoreNLP/master/models/wordsegmenter/vi-vocab
!wget https://raw.githubusercontent.com/vncorenlp/VnCoreNLP/master/models/wordsegmenter/wordsegmenter.rdr
!mv VnCoreNLP-1.1.1.jar vncorenlp/ 
!mv vi-vocab vncorenlp/models/wordsegmenter/
!mv wordsegmenter.rdr vncorenlp/models/wordsegmenter/
# Cài đặt underthesea để chuẩn hóa tiếng Việt:
!pip install underthesea

# Để không mất thời gian, khi mà mỗi lần chạy thì nó tải lại 1 lần thì nhóm đã lưu các file cài đặt:
https://drive.google.com/drive/u/0/folders/1GMwqkymMp6ZUC9riluiUrFIHiWcSrAMl
# Link Github:
https://github.com/NhatLH/SentimenAnalysClassification

# Link Submit code trên Kaggle:
https://www.kaggle.com/code/vuminhnhatuet/sentiment-analys (đã chạy thành công)
