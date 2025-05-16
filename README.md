# MCNA_Customer_Churn
| Feature                    | Description                                                                                             |
| -------------------------- | ------------------------------------------------------------------------------------------------------- |
| **State**                  | The U.S. state (abbreviation) where the customer lives (e.g., `CA` = California).                       |
| **Account length**         | How long the customer has been with the company (in days or months). Can reflect customer loyalty.      |
| **Area code**              | Telephone area code, representing the customer’s geographical region.                                   |
| **International plan**     | Whether the customer has subscribed to an international calling plan (`Yes` or `No`).                   |
| **Voice mail plan**        | Whether the customer has a voice mail service (`Yes` or `No`).                                          |
| **Number vmail messages**  | Number of voice mail messages the customer has. Likely greater than 0 if they have the voice mail plan. |
| **Total day minutes**      | Total number of minutes spent on calls during the **daytime**.                                          |
| **Total day calls**        | Total number of **calls** made during the daytime.                                                      |
| **Total day charge**       | Total charge for daytime calls. (Usually calculated as minutes × rate.)                                 |
| **Total eve minutes**      | Total call minutes during the **evening**.                                                              |
| **Total eve calls**        | Number of calls during the evening.                                                                     |
| **Total eve charge**       | Total charge for evening calls.                                                                         |
| **Total night minutes**    | Total call minutes during the **night**.                                                                |
| **Total night calls**      | Number of calls made at night.                                                                          |
| **Total night charge**     | Total charge for night-time calls.                                                                      |
| **Total intl minutes**     | Total number of **international** call minutes.                                                         |
| **Total intl calls**       | Total number of international calls.                                                                    |
| **Total intl charge**      | Total cost of international calls.                                                                      |
| **Customer service calls** | Number of times the customer called **customer support**. High numbers may indicate dissatisfaction.    |
| **Churn**                  | **Target variable**: whether the customer left the service (`Yes`) or stayed (`No`).                    |


#

| Feature                    | Giải thích                                                                                    |
| -------------------------- | --------------------------------------------------------------------------------------------- |
| **State**                  | Mã viết tắt bang của khách hàng tại Mỹ (ví dụ: `CA` = California).                            |
| **Account length**         | Số ngày (hoặc tháng) khách hàng đã sử dụng dịch vụ. Chỉ báo cho độ gắn bó.                    |
| **Area code**              | Mã vùng điện thoại khách hàng. Dùng để nhận biết khu vực địa lý (chẳng hạn 408 = California). |
| **International plan**     | Khách hàng có đăng ký gói gọi quốc tế không? (`Yes` / `No`).                                  |
| **Voice mail plan**        | Khách hàng có sử dụng hộp thư thoại (voicemail) không? (`Yes` / `No`).                        |
| **Number vmail messages**  | Số lượng tin nhắn thoại (voicemail) được lưu. Thường > 0 nếu có dùng voicemail plan.          |
| **Total day minutes**      | Tổng số phút gọi của khách hàng vào **ban ngày**.                                             |
| **Total day calls**        | Tổng số **cuộc gọi** thực hiện trong thời gian ban ngày.                                      |
| **Total day charge**       | Tổng tiền cước gọi ban ngày (phí = phút × đơn giá).                                           |
| **Total eve minutes**      | Tổng số phút gọi vào **buổi tối** (evening).                                                  |
| **Total eve calls**        | Tổng số cuộc gọi buổi tối.                                                                    |
| **Total eve charge**       | Tổng tiền gọi buổi tối.                                                                       |
| **Total night minutes**    | Tổng số phút gọi vào **ban đêm**.                                                             |
| **Total night calls**      | Tổng số cuộc gọi ban đêm.                                                                     |
| **Total night charge**     | Tổng cước gọi ban đêm.                                                                        |
| **Total intl minutes**     | Tổng số phút gọi **quốc tế**.                                                                 |
| **Total intl calls**       | Tổng số cuộc gọi quốc tế.                                                                     |
| **Total intl charge**      | Cước phí gọi quốc tế.                                                                         |
| **Customer service calls** | Số lần khách hàng gọi lên **chăm sóc khách hàng**. Chỉ báo mức độ không hài lòng tiềm ẩn.     |
| **Churn**                  | **Biến mục tiêu**: khách hàng có rời dịch vụ không? (`Yes` / `No`).                           |
