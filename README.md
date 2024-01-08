# IoT_mini_project
# 醫療資訊整合平台  
## 簡介 
### 建立一個基於物聯網和 OneM2M 框架的應用程式，涉及到數據的獲取、處理和返回，而病人的身體數據包含體溫、心律、血壓、血氧，是來自MIT所模擬生成，以及以三間病房，每間病房各一個病人來做小規模模擬。此系統可以將不同間病房的資訊做彙整，且可根據選擇的病房來查看該病房的病人的身體數據。
### 使用步驟
- Step1 利用 postman 建 MN、IN 的 AE ，名為 hospital (create_ae_in、create_ae_mn)。
- Step2 利用 flow1、flow2 建 MN、IN 的 三間病房 container，名為 Hospital_Room_01、Hospital_Room_02、Hospital_Room_03。
- Step3 利用 postman 建 Hospital_Room_01、Hospital_Room_02、Hospital_Room_03 的 subscription (create_con_data_room1、create_con_data_room2、create_con_data_room3)。
- Step4 利用模擬器打開 apk檔
- Step5 輸入想檢視的病房號碼(1~3)
- Step6 傳送資料至MN、IN
