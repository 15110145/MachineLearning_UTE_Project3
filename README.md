# MachineLearning_UTE_Project3
Đồ án 3
GVHD: thầy Nguyễn Thiên Bảo
Thành viên nhóm : 15110145 Nguyễn Xuân Tuấn
                  15110     Nguyễn Đoàn Nam Anh

HƯỚNG DẪN 

Phiên bản python sử dụng: 3.6.5 (64 bit) cho window
Các thư viện (Sử dụng lệnh cmd: "pip install [tên_thư_viện]" để cài đặt): keras tensorflow numpy sklearn nltk 
Chú ý: ntlk cần thêm một thư viện con nên ta phải download bằng lệnh: 
python 
=> import nltk
=> nltk.download('stopwords')


# Cài đặt ban đầu
B1: copy thư mục txt_sentoken vào ổ D:/ (đường dẫn sau khi copy: "D:/txt_sentoken")

B2: chạy file definevocab.py để xây dựng tập từ vựng và xuất ra file vocab.txt được lưu tại đường dẫn "D:/"

B3: chạy file sentimentmodel.py để training cho model và lưu model lại (mục đích sau này sử dụng lại mà không cần phải train lại cho model)

B4: chạy file MovieReviewClassify và nhập review sau đó chương trình sẽ tự phân loại (1 là good review, 0 là bad review)
