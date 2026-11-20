# Phiếu QC 1 — Road v1.0

Lô được kiểm (học viên): Nguyễn Xuân Anh        Người kiểm (học viên): Nguyễn Sỹ Kiên  
Ngày: 21/11/2026                                Phiên bản guideline: Road v1.0  
File được kiểm (tên + `revision` trong manifest): `NguyenXuanAnh-fisheye.zip` (revision 1)  
Số ảnh kiểm: 6 (+ 6 ảnh thêm, ghi riêng)   Số nhãn đã kiểm (shape + tag): 60 (36 shapes + 24 tags)  

## Tổng hợp theo mã
| Mã | Loại lỗi | Số mục kiểm | Số lỗi | Mức |
| --- | --- | ---: | ---: | --- |
| QC1-01 tag camera | sai thuộc tính / bỏ sót | 6 | 0 | nặng |
| QC1-02 đủ L1, R1 | bỏ sót | 4 | 0 | nặng |
| QC1-03 position | sai thuộc tính / thừa | 4 | 0 | nặng |
| QC1-04 tâm vạch, chiều, điểm dừng | sai phạm vi / bỏ sót | 4 | 0 | chính |
| QC1-05 vạch đứt, che | sai phạm vi / sai thuộc tính | 4 | 0 | chính |
| QC1-06 style, color, kind | sai thuộc tính | 4 | 0 | chính |
| QC1-07 vùng lái | sai phạm vi / bỏ sót / thừa | 7 | 0 | chính |
| QC1-08 đèn, màu | bỏ sót / sai phạm vi / sai thuộc tính | 8 | 0 | nặng / chính |
| QC1-09 facing, type, group, biển phụ | sai thuộc tính | 8 | 0 | chính |
| QC1-10 hình in, đủ biển | bỏ sót / sai phạm vi | 8 | 0 | chính |
| QC1-11 fisheye | sai phạm vi / sai thuộc tính | 11 | 2 | chính |
| QC1-12 file | lỗi file | 1 | 0 | nhẹ / nặng |

## Danh sách lỗi (mỗi lỗi một dòng)
| # | Mã | Ảnh | Nhãn (label, id) | Mức | Mô tả ngắn |
| --- | --- | --- | --- | --- | --- |
| 1 | QC1-11 | B01_02688_FV.png | road_curb#3@(569,370) | chính | Đường curb chỉ có 3 điểm, chưa uốn mượt theo cung cong fisheye |
| 2 | QC1-11 | B03_04267_RV.png | traffic_sign#12@(1131,361) | chính | Biển báo có tâm ngoài 80% bán kính viền ảnh, cần bật thuộc tính edge_zone |

## Ca mơ hồ
| Ảnh | Câu hỏi cho lead | Lời đáp (nếu có) |
| --- | --- | --- |
| B01_02688_FV.png | Ảnh không thấy rõ vạch sơn L1/R1, chỉ có vỉa hè road_curb thì có được miễn QC1-02 không? | Được miễn trừ theo CHECKPOINTS nếu xác nhận không thấy vạch |

## Quyết định
Lỗi nặng: 0   Lỗi chính: 2 / 60 nhãn = 3.33 %   Lỗi nhẹ: 0   Ca chờ lead: 0  
Quyết định (Release / Hold / Rework): Release  
Lý do (theo luật của phiếu): Không có lỗi nặng nào. Tỉ lệ lỗi chính là 3.33% (2/60 nhãn), nhỏ hơn ngưỡng quy định 5.0%. Các nhãn gán cẩn thận, đúng taxonomy và thuộc tính.  

