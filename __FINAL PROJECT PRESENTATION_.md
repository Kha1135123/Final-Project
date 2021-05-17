


<h1><center>

<img src="https://i.imgur.com/8mgCvjY.jpg" alt="FuKaKuKKu"
	title="FuKaKukku" width="1280" height="720" />
<h5>FINAL PROJECT PRESENTATION</h5>

</center></h1>

Link to [slide](https://hackmd.io/@Kha/BkUvYPqeO#/)




---



<h3><center> フカクック  </h3></center>
<h4><center>
FukaKukku
</h4></center>
<center>
<img src="https://i.imgur.com/RTJdLnG.png" 
     alt="FukkaKukku" width="800" height="450"> 
</center>


- Thành viên:

. Nguyễn Mạnh Kha

. Trần Thiên Phú
- Project: Food Recommender System
- Mục đích: Phục vụ cho những người dùng đang phân vân về việc chọn món ăn.




---

# Giới thiệu đề tài
<br>

- Tạo ra hệ thống gợi ý về món ăn ứng với mong muốn của người dùng về thể loại món ăn đó.

- Sử dụng mô hình LightFM để tạo một Recommender System.


<img src="https://i.imgur.com/bviWjwp.gif" 
alt="FuKaKuKKu" width="1100" height="560" >




---

# TEFPA

- **Task:** input là id của users, còn output là những gợi ý về món ăn ứng với mong muốn của người dùng

- **Experience**: tương tác của users với items cùng với các đặc trưng items

- **Function space**: LightFM

-  **Performance measures**: AUC score, WARP loss

-  **Algorithm to search/optimize** : Stochastic Gradient Descent (SGD)

---

# LightFM - Hybrid Models

<img src="https://i.imgur.com/o1JG8vl.png"
alt="FukkaKukku" width="950" height="550"> 

----

- Tại sao chọn mô hình LightFM ?
    - Đưa ra đưa ra điểm dự đoán từ tương tác của người dùng và đặc trưng của món ăn $\rightarrow$ Hiệu quả đề xuất tốt hơn.
    - Giải quyết vấn đề Cold-start.
    - AUC score trên tập train - test của:
        - Collaborative Filtering (CF): 0.98 - 0.88
        - Hybrid Model: 0.53597 - 0.53274
        
        Tuy AUC score của CF RecSys cao hơn nhưng Hybrid Model đưa ra dự đoán hợp lý hơn với người dùng.

---

# Dữ liệu


- Dataset: [Link to dataset](https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions) 
<br>

<img src="https://i.imgur.com/jBuTYhZ.png"
alt="FuKaKuKKu"
	title="FuKaKukku" width="800" height="450" >
<br>

- Dataset bao gồm các file csv, nội dung về food.

- Dataset bao gồm 2 file raw và 2 file preprocess (của recipe và user interactions)







---


# Quá trình xử lí dữ liệu, Coding, Demo

<br>

- Link to [Google Colaboratory Notebook](https://colab.research.google.com/drive/12iekGMM91SJrE0vqo9hK4i5P_t7tcF-G#scrollTo=tg4ac5NwnGjL)























---
<img src="https://i.imgur.com/2hqtz5L.png"
alt="FuKaKuKKu"
	title="FuKaKukku" width="700" height="750" >


<h3><center> **「おわり」**  </h3></center>



