# kltn
Repo gồm 4 notebook chính:

- **MovieTweeting.ipynb**  
  Tiền xử lý và phân tích dữ liệu MovieTweetings (đọc dữ liệu, làm sạch, thống kê mô tả, trực quan hóa cơ bản).

- **ContentBased.ipynb**  
  Xây dựng hệ gợi ý **dựa trên nội dung** (content-based filtering): trích xuất đặc trưng phim, tính độ tương đồng và gợi ý các phim tương tự.

- **User_Item.ipynb**  
  Xây dựng hệ gợi ý **dựa trên quan hệ người dùng – sản phẩm** (user–item / collaborative filtering).  
  File này bao gồm: xây dựng ma trận tương tác, tính độ tương đồng giữa người dùng/mục tiêu, dự đoán rating, và triển khai **Truncated SVD** để giảm chiều dữ liệu và cải thiện hiệu suất mô hình.

- **Hybrid.ipynb**  
  Kết hợp hai phương pháp trên thành **mô hình lai (hybrid recommender)**, so sánh, đánh giá và tối ưu chất lượng gợi ý.
