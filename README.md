# Ra1nUSB_HT

- File Ra1nUSB_HT này gồm có các phiên bản Checkra1n từ 0.9 đến 0.12.4
- Blog https://tuanrobert.blogspot.com/2020/04/ra1nusbht.html
- Khi có bản Checkra1n mới mà bạn không muốn tạo lại bộ cài thì xem [Video](https://youtu.be/sEdw-bNmmVg) để tự thêm bản Checkra1n mới vào

---
## Yêu Cầu

1. USB dung lượng tối thiểu 4GB
2. Máy tính CPU Intel hoặc AMD

- ***Case***

  + Các CPU Intel Core I, Xeon, Pentium, Celeron đều có thể cài.
  + Đối với dòng Pentium và Celeron sẽ cần phải FakeCPUID thành Core I tương ứng.

- ***Laptop và Case đồng bộ***

  + Các CPU Intel Core I

---
## Cài đặt

- Dùng phần mềm [balenaEtcher] hoặc [Transmac] để tạo USB Boot (Dùng [balenaEtcher] sẽ nhanh hơn [Transmac] rất nhiều)
- Vào [BIOS] và Tắt Secure boot, SATA Mode:**`AHCI`**
- Bản Intel: Đã Fix khi boot **Legacy** . Ưu tiên boot **UEFI** nếu máy có
- Bản AMD: Chỉ có thể boot **UEFI**
- Boot UEFI có các **`Options`** còn **Legacy** sẽ không có (file Ra1nUSB_HT thì boot chuẩn nào cũng sẽ ra **UEFI**)

[balenaEtcher]:https://docs.google.com/document/d/e/2PACX-1vSbvfkATDeTByNbg7BSQGu6lCsdGVjDTrKKWfCFDuY6l-nlJeTreYH7P9UWY9DaEfAHOZ4AhSrVi3oo/pub
[Transmac]:https://www.mediafire.com/file/0hrk9haby7dm0g0/
[BIOS]:https://docs.google.com/document/d/e/2PACX-1vQ-lgeAgC5cHErtuU658zOMIdCimsdcimiW6VUzEfKFyr4W2uz3ZQ8XX9GKY4UMgH8LG93X0YAKWYEC/pub

   ![UEFI vs Legacy](https://i.ibb.co/jvdxbDw/image.png)

---

## Lưu Ý

- Checkra1n chỉ hỗ trợ từ iPhone **5s** (Chip **A7**) đến iPhone **X** (Chip **A11**)
- iOS **14.5** > **14.7** dùng Checkra1n **0.12.3** > **0.12.4**
- iOS **14.0** > **14.4.2** dùng Checkra1n **0.11.0** > **0.12.4**
- iOS **13.4** > **13.7** dùng Checkra1n **0.9.9** > **0.12.4**
- iOS **12.3** > **13.3.1** dùng Checkra1n **0.9.2** > **0.12.4** (Trừ **5**s là khó có thể dùng được bản **0.9.8**, **0.9.8.x** ,**099**)

---

## Link Download

 ### :link: [Download](https://docs.google.com/document/d/e/2PACX-1vSdmy_3zDG7vxs3cZu9hS22xp53JRDKds5-EIRjpgE8nWJlToeAgjw8WzaulPzWptMEw1HMONdkaKNf/pub)
 
---

## Donate

#### [**Paypal:**] https://www.paypal.me/hoangtuan09

#### [**MoMo:**] https://nhantien.momo.vn/hoangtuan

[**Paypal:**]:https://www.paypal.me/hoangtuan09
[**MoMo:**]:https://nhantien.momo.vn/hoangtuan

   ![MoMo](https://i.ibb.co/hmZKmjx/image.png)

:bank: **HOANG TRONG TUAN** :bank:

   > **MBBank: ``9704229201330339034``** ViettelPay

   > **Bản Việt - Viet Capital Bank: ``9007041112687``**

---
## Gõ lệnh trong Terminal

- #### *Chế độ thông thường bảng checkra1n màu trắng*

  - nhập **`09`**     sẽ ra **`Checkra1n 0.9`**
  - nhập **`091`**    sẽ ra **`Checkra1n 0.9.1`**
  - nhập **`092`**    sẽ ra **`Checkra1n 0.9.2`**
  - nhập **`093`**    sẽ ra **`Checkra1n 0.9.3`**
  - nhập **`0932`**   sẽ ra **`Checkra1n 0.9.3.2`**
  - nhập **`095`**    sẽ ra **`Checkra1n 0.9.5`**
  - nhập **`096`**    sẽ ra **`Checkra1n 0.9.6`**
  - nhập **`097`**    sẽ ra **`Checkra1n 0.9.7`**
  - nhập **`098`**    sẽ ra **`Checkra1n 0.9.8`**
  - nhập **`0981`**   sẽ ra **`Checkra1n 0.9.8.1`**
  - nhập **`0982`**   sẽ ra **`Checkra1n 0.9.8.2`**
  - nhập **`099`**    sẽ ra **`Checkra1n 0.9.9`**
  - nhập **`100`**    sẽ ra **`Checkra1n 0.10.0`**
  - nhập **`101`**    sẽ ra **`Checkra1n 0.10.1`**
  - nhập **`102`**    sẽ ra **`Checkra1n 0.10.2`**
  - nhập **`110`**    sẽ ra **`Checkra1n 0.11.0`**
  - nhập **`120`**    sẽ ra **`Checkra1n 0.12.0`**
  - nhập **`121`**    sẽ ra **`Checkra1n 0.12.1`**
  - nhập **`122`**    sẽ ra **`Checkra1n 0.12.2`**
  - nhập **`123`**    sẽ ra **`Checkra1n 0.12.3`**
  - nhập **`124`**    sẽ ra **`Checkra1n 0.12.4`**
  - nhập **`fix20`**  sẽ ra **`minaUSB V1.1`** (Dùng để fix lỗi -20 khi JailBreak)
  - nhập **`purple`** sẽ ra **`purple pro`**
  
   ![](https://i.ibb.co/3hW948M/image.png)


- #### *Chế độ cli (chế độ chờ DFU - tất cả các bản checkra1n đều có chế độ này)*

	- Thêm **`-cli`** ở sau: Ví Dụ: **`097-cli`** , **`122-cli`** , ...

   ![Mặc định](https://i.ibb.co/2N0cbx9/image.png)

> Lưu ý

   - Khi hiện chữ *Waiting for DFU decives* thì bạn phải tự đưa máy về DFU
   - Chế độ DFU màn hình sẽ không hiện gì (màn hình màu đen) - còn Recovery Mode sẽ hiện như ảnh

   ![](https://i.ibb.co/q9PSydP/image.png)

- #### *Chế độ bảng checkra1n màu đen (dùng được bàn phím để di chuyển - chỉ có từ checkra1n 0.9.8)*

  - Thêm **`d`** ở sau: Ví Dụ: **`098d`**, **`122d`** , ...

   ![-cli](https://i.ibb.co/KG0qVmY/image.png)

---

## Cách Fix Một Số Lỗi (Tiêu đề lỗi có gán link video)

1. **Fix lỗi khi bấm Start (Máy không tự động vào Recovery Mode)**

![](https://i.ibb.co/nfc0PCh/789897.png)

- Kết nối lại điện thoại với  PC và bấm Tin cậy
- Nếu không bạn phải tự đưa máy vào Recovery Mode

   ![](https://i.ibb.co/q9PSydP/image.png)

 -Cách vào Recovery Mode cho bạn nào chưa biết-

*a. iPhone 5s, 6, 6 Plus, 6s, 6s Plus*

- Cắm cable kết nối với PC
- Giữ đồng thời phím nguồn và home đến khi hiện logo táo
- Thả phím nguồn nhưng vẫn giữ phím home cho đến khi máy vào Recovery Mode

*b. iPhone 7, 7 Plus*

- Cắm cable kết nối với PC
- Giữ đồng thời phím nguồn và giảm âm lượng đến khi hiện logo táo
- Thả phím nguồn nhưng vẫn giữ phím giảm âm lượng cho đến khi máy vào Recovery Mode

*c. iPhone 8, 8 Plus, X*

- Cắm cable kết nối với PC
- Bấm tăng âm lượng (thả ra luôn)
- Bấm giảm âm lượng (thả ra luôn)
- Giữ phím nguồn cho đến khi máy vào Recovery Mode

2. [**Fix lỗi -20 ( Error code: -20 ) khi jailbreak**](https://www.youtube.com/watch?v=x3mNPRHzNmU)

   ![-20](https://i.ibb.co/Y0jT1mM/image.png)

   - Mở **minaUSB** (bằng cách nhập **`fix20`** trên terminal)  rồi thao tác như ảnh

     ![1](https://i.ibb.co/znRG4ZB/image.png)

     ![2](https://i.ibb.co/QnsRBkR/image.png)

3. [**Mở Etcher lên không hiện gì hết**](https://youtu.be/hu2LzbWRDi0)

4. [**Lỗi bị treo khi hiện 2 dòng**](https://youtu.be/01M_bGAfMyw))

   ![](https://i.ibb.co/tCx7r5p/image.png)

5. [**CPU Pentium, Celeron**](https://youtu.be/3JGVwGDNbgU)

   ![](https://i.ibb.co/Sm7t5pb/image.png)

6. [**Lỗi khi boot Legacy( đối với bản Ra1nUSB_HT thì đã được fix sẵn rồi )**](https://youtu.be/3ZRhob7g_CY) Code: 1 , AHCI...

   ![1](https://i.ibb.co/J5qqvBs/image.png)

   ![2](https://i.ibb.co/HNXZtC9/image.png)

7. **Lỗi chỉ hiện gạch ngang khi boot vào**

   ![](https://i.ibb.co/L5Gy5DM/image.png)

> ***Cách khắc phục:***

- Hãy thử các cách bên dưới với bản Ra1nUSB đúng với CPU đang dùng trước, rồi sau đó thử lại với bản của CPU khác

  - Đổi khe cắm Ram nếu đang cắm 1 thanh.  (ưu tiên cắm vào slot 1)
  - Rút bớt Ram ra và thử lại nếu có nhiều thanh (ưu tiên cắm vào slot 1)

- Nếu vẫn bị thì làm theo như sau:

  - Mở phân vùng BOOT của USB dung lượng 200MB rồi vào đường dẫn sau
 BOOT_HT\EFI\ CLOVER\drivers\UEFI và thay file **AptioMemoryFix.efi** bằng file [**OsxAptioFixDrv.efi**] hoặc [**OsxAptioFix2Drv-free2000.efi**]

[**OsxAptioFixDrv.efi**]:https://www.mediafire.com/file/8qswr27dne3t1ub/OsxAptioFixDrv.efi/file
[**OsxAptioFix2Drv-free2000.efi**]:https://www.mediafire.com/file/gz0qeodlyowxyto/OsxAptioFix2Drv-free2000.efi/file

***Không phải tất cả các máy đều fix được theo cách này. Mình đã fix được với 1 số máy case và đa số đều do lỗi ở phần khe cắm Ram***

**- Lỗi này cũng sẽ xảy ra đối với các trường hợp**

+ Cấu hình máy không hỗ trợ
+ File **config** không phù hợp với máy (Bạn phải tự tìm kiếm file **config** phù hợp trong các group cũng như diễn đàn về hackintosh)
+ Chưa chỉnh chuẩn **BIOS**

# Cảm ơn các bạn đã sử dụng

`Copyright by Hoàng Tuân`
