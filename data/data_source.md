#The data is at the ssh server of the Chair TUM info group 31, you should download the data to here. 
#Keep them the same name and leave them in this folder.

#The data should have the folowing 6 files

zhoudi@chameleon:/vol/chameleon/projects/eeg/data$ ls -lh
total 3.1G
-rw-rw-r-- 1 tuo i31adlm 2.6G Oct 17 11:52 data_Dinh_fs200.pt
-rw-rw-r-- 1 tuo i31adlm 560M Oct 17 11:33 data_Heitmann_fs200.pt
-rw-rw-r-- 1 tuo i31adlm 2.2K Oct 17 11:52 labels_Dinh_fs200.pt
-rw-rw-r-- 1 tuo i31adlm 1.1K Oct 17 11:33 labels_Heitmann_fs200.pt
-rw-rw-r-- 1 tuo i31adlm  21K Oct 17 12:19 tabular_Dinh.xlsx
-rw-rw-r-- 1 tuo i31adlm 7.0K Oct 17 12:22 tabular_Heitmann.xlsx



#To download the date, the following code may help:
rsync -av zhoudi@131.159.110.3:/vol/chameleon/projects/eeg/data/ ./


#During downloading, the output in terminal should be like this:

dingzhou@dingzhou-ASUS-TUF-Gaming-A15-FA506QR-FA506QR:~/Desktop/Self_Supervised_Learning_on_EEG/data$ rsync -av zhoudi@131.159.110.3:/vol/chameleon/projects/eeg/data/ ./
Password: 
receiving incremental file list
./
data_Dinh_fs200.pt
data_Heitmann_fs200.pt
labels_Dinh_fs200.pt
labels_Heitmann_fs200.pt
tabular_Dinh.xlsx
tabular_Heitmann.xlsx

sent 141 bytes  received 3,289,836,847 bytes  11,898,144.62 bytes/sec
total size is 3,289,033,345  speedup is 1.00
