---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** AI Giám Sát Hành Vi Phát Hiện Té Ngã Qua Camera 

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [x] **1 nhóm người dùng chính**
- [x] **1 hoàn cảnh / tình huống rõ**
- [x] **1 job cốt lõi**
- [x] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:**  Hệ thống giám sát an toàn thụ động, bảo vệ quyền riêng tư, giúp phát hiện té ngã của người cao tuổi tại nhà và cảnh báo cho gia đình.
- **Lát cắt tôi chọn để phân tích hôm nay là:** Người nhà hoặc người chăm sóc đang ở xa cần nhận biết, đánh giá và phản ứng kịp thời khi người cao tuổi sống một mình có khả năng bị ngã (do nhiều nguyên do) tại nhà.
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là lát cắt chứa giá trị cốt lõi nhất của sản phẩm, có hậu quả cao nếu xử lý chậm và có workflow rõ ràng từ theo dõi, xác nhận sự cố, liên hệ hỗ trợ đến kết thúc sự kiện. Các phần như dashboard dài hạn, báo cáo ngày và cấu hình, chat chỉ là phần hỗ trợ, không phải job chính của MVP.

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| AI bảo vệ người cao tuổi | Giúp người nhà ở xa biết và phản ứng kịp thời khi người cao tuổi sống một mình có khả năng bị ngã tại nhà |
| Camera AI phát hiện té ngã | Nhận biết một sự cố ngã có thể đã xảy ra, đánh giá mức độ và điều phối hỗ trợ từ xa |
| Ứng dụng cảnh báo an toàn | Giảm thời gian từ lúc sự cố xảy ra đến khi gia đình có đủ thông tin để hành động |
> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Người chăm sóc (người thân) đi làm cả ngày ,không có thời gian để lúc nào cũng để ý người già ở nhà. Khi người cao tuổi ở nhà một mình bị ngã hoặc nằm bất động, họ có thể không tự gọi trợ giúp được, trong khi người nhà ở xa không biết và phản ứng kịp thời.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Người thân hoặc người chăm sóc (không thể ở cạnh và quan sát trực tiếp cả ngày)

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Kiểm tra cam định kỳ, hoặc thuê người giúp việc, hoặc dùng thiết bị đeo, hoặc thậm chí phải nghỉ việc để ở nhà.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Gia đình và người chăm sóc có bố mẹ/người thân cao tuổi sống một mình hoặc ở nhà một mình nhiều giờ, trong khi họ đi làm (từ sáng tới tối) hoặc sống ở xa.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   >  Khi người cao tuổi bị ngã, trượt chân hoặc nằm bất động trong nhà nhưng không thể với tới điện thoại, bấm nút trợ giúp hay gọi người khác; gia đình không theo dõi camera liên tục nên chỉ biết khi chủ động gọi hoặc kiểm tra muộn.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Kiểm tra thủ công qua điện thoại/camera, nhờ người gần nhà, thuê người chăm sóc, lắp camera có cảnh báo chuyển động, hoặc dùng đồng hồ/nút gọi khẩn cấp và cảm biến chuyên dụng.


4. **Vì sao đây là thời điểm đáng giải?**  
   > UNFPA nhận định Việt Nam là một trong những quốc gia già hóa nhanh; tỷ lệ người từ 60 tuổi trở lên là 11,9% năm 2019 và được dự báo vượt 25% vào năm 2050. Một cập nhật năm 2025 cho biết trong vòng khoảng một thập kỷ, hơn một phần năm dân số Việt Nam sẽ trên 60 tuổi. Hiện, mức sinh trung bình của mỗi phụ nữ Việt Nam là 1,93 con (T12/2025), với tình trạng áp lực kinh tế, chi phí nuôi dạy trẻ quá cao, và văn hóa làm việc quá tải, khoảng cách giữa tốc độ tăng giá nhà và tốc độ tăng tiền lương đang giãn rộng ở mức báo động thì giới trẻ ngại kết hôn và sinh con => tỉ suất sinh giảm => người già nhiều. Điều này không tự động chứng minh mọi gia đình sẽ sử dụng camera AI (Camera gia đình đã phổ biến hơn), nhưng cho thấy nhóm người có thể cần các giải pháp hỗ trợ chăm sóc tại nhà đang tăng lên.

### Tóm tắt market context trong 3-4 dòng

> Người nhà cần bảo đảm an toàn cho người cao tuổi nhưng không thể hiện diện hoặc quan sát liên tục. Các giải pháp hiện tại thường phụ thuộc vào kiểm tra thủ công, sự chủ động của người cao tuổi hoặc chi phí nhân sự cao. Khoảng trống lớn nhất là thiếu một tín hiệu đáng tin cậy ngay khi sự cố có khả năng xảy ra, đồng thời vẫn phải tôn trọng quyền riêng tư (nếu cần).


---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Người thân hoặc người chăm sóc chính chịu trách nhiệm theo dõi và phản ứng khi người cao tuổi ở nhà một mình gặp sự cố.
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Vì người mà họ đang chăm sóc là người quan trọng đối với họ, hoặc là người thân trong gia đình. Họ là người nhận tín hiệu, mở thông tin sự kiện, đánh giá tình huống, gọi cho người cao tuổi hoặc người hỗ trợ gần nhà và quyết định có cần escalation hay không. Người cao tuổi là người được bảo vệ và là beneficiary chính, nhưng trong lát cắt này không phải người trực tiếp thao tác để hoàn thành workflow phản ứng từ xa.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Theo dõi bố mẹ bằng camera AI và nhận cảnh báo khi họ bị ngã.
### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: `camera`, `AI`, `cảnh báo`, tên sản phẩm và cách triển khai kỹ thuật.

### Bản chốt

**Core JTBD cuối cùng:**  
> Nhận biết và phản ứng kịp thời trước một sự cố ngã có thể xảy ra với người cao tuổi đang ở nhà một mình, ngay cả khi người chăm sóc đang ở xa.
---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Khi tôi đang đi làm hoặc ở xa và bố/mẹ ở nhà một mình nhiều giờ | Tôi muốn được biết ngay khi có dấu hiệu họ vừa bị ngã hoặc nằm bất động bất thường | Tôi có thể gọi kiểm tra hoặc nhờ người gần nhà hỗ trợ trước khi tình trạng trở nên nghiêm trọng | Nhu cầu cốt lõi là giảm thời gian “không ai biết”, không phải xem camera liên tục |
| JS2 | Khi tôi nhận một tín hiệu nghi có sự cố | Tôi muốn nhanh chóng biết sự việc có khả năng là ngã thật, xảy ra ở đâu và mức độ khẩn cấp đến đâu | Tôi có thể quyết định gọi trực tiếp, nhờ hàng xóm, liên hệ người thân khác hoặc gọi hỗ trợ khẩn cấp mà không hoảng loạn hoặc chậm trễ | Product phải giúp xác nhận và cung cấp đủ context, không chỉ phát một âm báo |
| JS3 | Khi đã có cảnh báo nhưng tôi không thể phản hồi ngay hoặc người cao tuổi không nghe máy | Tôi muốn hệ thống tiếp tục theo dõi trạng thái và chuyển thông tin cho người liên hệ kế tiếp | Sự cố không bị bỏ sót chỉ vì một người bận, tắt máy hoặc không thấy notification | Workflow cần escalation và nhiều người liên hệ, không phụ thuộc vào một notification duy nhất |

### Tự kiểm nhanh

- [x] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [x] 3 story không trùng hệt nhau
- [x] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Gọi điện/nhắn tin kiểm tra định kỳ và nhờ hàng xóm hoặc người thân gần nhà | Xác nhận người cao tuổi vẫn ổn và tạo một mạng lưới hỗ trợ thủ công | Rẻ, quen thuộc, không cần lắp thêm hệ thống phức tạp; khi có người gần nhà thì xử lý trực tiếp tốt | Không liên tục; phụ thuộc người cao tuổi nghe máy và người hỗ trợ có mặt; có thể phát hiện sự cố muộn | Thấp về tiền, nhưng cao về thói quen và sự tin tưởng vào người quen |
| Camera IP thông thường, mở app để xem trực tiếp hoặc xem lại | Quan sát tình trạng tại nhà từ xa | Cho hình ảnh trực tiếp, thiết bị đã phổ biến, gia đình quen dùng | Người dùng phải chủ động mở xem; cảnh báo chuyển động quá chung; không thể theo dõi 24/7; có rủi ro riêng tư | Trung bình vì có thể đã lắp camera và quen app hiện tại |
| Thiết bị đeo/nút SOS/cảm biến té ngã chuyên dụng | Phát hiện sự cố hoặc để người cao tuổi chủ động gọi trợ giúp | Không cần camera trong không gian riêng tư; một số thiết bị có cảm biến trực tiếp trên cơ thể | Người cao tuổi có thể quên đeo, quên sạc, tháo ra hoặc không thể bấm nút khi bất tỉnh; cần thay đổi thói quen | Trung bình đến cao vì phải mua thiết bị và duy trì mức tuân thủ |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
>  Kết hợp gọi điện kiểm tra định kỳ, mở camera khi thấy bất an và nhờ người thân/hàng xóm gần nhà hỗ trợ; một số gia đình có thể thử wearable nhưng vẫn phải chấp nhận rủi ro người cao tuổi không sử dụng đều đặn.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Xác định tình huống nào được xem là nguy hiểm, mức nào cần báo và ai chịu trách nhiệm phản ứng | Thỏa thuận miệng trong gia đình, kinh nghiệm cá nhân, lịch gọi định kỳ | Tiêu chí không thống nhất; mỗi người hiểu “khẩn cấp” khác nhau; dễ báo quá nhiều hoặc bỏ sót | Med |
| Locate | Biết người cao tuổi đang ở khu vực nào và ai ở gần có thể tiếp cận nhanh | Gọi hỏi, mở từng camera, hỏi hàng xóm/người thân | Không biết chính xác vị trí khi người cao tuổi không trả lời; mất thời gian tìm đúng camera hoặc người hỗ trợ | Med |
| Prepare | Chuẩn bị camera, số liên hệ, quyền truy cập và kế hoạch xử lý trước khi sự cố xảy ra | Camera IP, danh bạ điện thoại, nhóm chat gia đình, wearable nếu có | Thiết lập phân tán; danh sách liên hệ có thể cũ; không rõ ai là người ưu tiên | Med |
| Confirm | Xác định tín hiệu có phải ngã thật hay báo động giả, mức độ và thời gian bất động | Gọi điện, xem live camera hoặc clip, hỏi người gần nhà | Khi không liên lạc được, gia đình thiếu context; báo giả gây hoảng loạn, còn chờ quá lâu có thể nguy hiểm | High |
| Execute | Thực hiện hành động phù hợp: gọi người cao tuổi, gọi người gần nhà, di chuyển tới nhà hoặc gọi hỗ trợ khẩn cấp | Điện thoại, Zalo, nhóm chat, gọi từng người theo trí nhớ | Dễ chậm, gọi trùng hoặc bỏ sót người; không có luồng escalation rõ ràng | High |
| Monitor | Duy trì khả năng phát hiện sự cố trong thời gian người cao tuổi ở một mình và theo dõi xem đã có ai phản hồi chưa | Kiểm tra thủ công, notification chuyển động chung, gọi định kỳ | Không ai có thể quan sát liên tục; sự cố có thể xảy ra giữa hai lần kiểm tra; một push duy nhất dễ bị bỏ lỡ | High |
| Modify | Điều chỉnh mức phản ứng khi có thêm thông tin hoặc khi tín hiệu là báo giả | Tự đổi quyết định qua điện thoại/nhóm chat, chỉnh thủ công cài đặt camera | Không có trạng thái chung; khó dừng escalation đúng lúc; ngưỡng cảnh báo không phù hợp với thói quen riêng | Med |
| Conclude | Xác nhận kết quả cuối, lưu lại sự kiện và rút kinh nghiệm cho lần sau | Tin nhắn rời rạc, trí nhớ cá nhân, lịch sử camera | Không có dữ liệu có cấu trúc để biết báo giả, thời gian phản ứng hoặc xu hướng lặp lại | Med |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:**`Monitor` — không thể quan sát liên tục mọi chỗ và thường không có tín hiệu ngay khi sự cố xảy ra. 
**Bước đau nhất #2:** `Confirm` — khi có tín hiệu, người nhà cần phân biệt ngã thật/báo giả và hiểu mức độ đủ nhanh để quyết định.

**Vì sao đây là nơi đáng chú ý nhất:**  
> Nếu `Monitor` thất bại, toàn bộ workflow không khởi động vì gia đình không biết có chuyện xảy ra. Nếu `Confirm` thất bại, hệ thống hoặc làm người dùng mệt mỏi vì báo giả, hoặc khiến họ chậm phản ứng trong một sự cố thật. Đây là hai điểm quyết định cả giá trị lẫn niềm tin vào sản phẩm.

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Monitor | Phân tích luồng camera cục bộ để nhận diện tư thế và chuỗi chuyển động có khả năng là té ngã, theo dõi thời gian bất động và tạo tín hiệu chủ động mà không cần người dùng xem liên tục | Đây là tác vụ lặp lại, cần quan sát liên tục, xử lý nhiều frame và phát hiện pattern mà con người không thể duy trì 24/7 | False negative làm bỏ sót sự cố; false positive gây alert fatigue; góc camera, che khuất, ánh sáng và hiệu năng edge làm giảm độ chính xác |
| Confirm | Kết hợp confidence, thời gian bất động, bối cảnh phòng và clip đã làm mờ để ước lượng severity, trình bày thông tin ngắn gọn; con người vẫn là người xác nhận và quyết định hành động | AI có thể tổng hợp tín hiệu nhanh và nhất quán, giảm thời gian người nhà phải tự xem toàn bộ video hoặc đọc dữ liệu kỹ thuật | AI có thể phân loại sai mức độ hoặc viết thông báo quá chắc chắn; clip blur có thể thiếu context; người dùng có thể tin quá mức |


### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
>  Bước `Monitor`: tự động phát hiện dấu hiệu té ngã và bất động từ camera ngay tại edge để tạo tín hiệu kịp thời, sau đó hỗ trợ bước `Confirm` bằng severity và clip đã bảo vệ quyền riêng tư (nếu cần).

**Vì sao không phải ở bước khác:**  
> Các bước như gọi người thân, quyết định đưa đi viện hoặc kết luận sự cố cần phán đoán và trách nhiệm của con người. AI tạo giá trị lớn nhất ở phần quan sát liên tục và tổng hợp tín hiệu, còn quyền xác nhận và hành động cuối phải thuộc về người chăm sóc vì hậu quả của quyết định sai có thể nghiêm trọng và không dễ hoàn tác.


---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp người thân/người chăm sóc chính nhận biết và xác nhận nhanh một sự cố ngã ở các bước `Monitor` và `Confirm`, bằng cách phát hiện tư thế ngã trên thiết bị biên, theo dõi thời gian bất động và gửi cảnh báo kèm clip (có thể đã làm mờ) cùng mức độ nghiêm trọng, thì họ sẽ chuyển từ việc gọi kiểm tra và mở camera thủ công sang sử dụng SilentGuard (tên app) như một lớp giám sát thụ động, vì họ có thể biết sớm hơn và có đủ context để hành động mà không yêu cầu người cao tuổi phải đeo hoặc bấm thiết bị.

### Tín hiệu sớm nếu hypothesis này đúng

1. Trong thử nghiệm tình huống, người chăm sóc nhận biết sự cố và bắt đầu hành động nhanh hơn rõ rệt so với cách gọi/mở camera thủ công, với mục tiêu cảnh báo end-to-end dưới 60 giây.
2. Người dùng tiếp tục bật hệ thống sau giai đoạn thử nghiệm, mở phần lớn cảnh báo mức MEDIUM trở lên và đánh giá tỷ lệ báo giả ở mức chấp nhận được thay vì tắt notification hoặc bỏ sử dụng

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1. Người thân/người chăm sóc chính là đúng job executor và có quyền quyết định lắp, cấu hình, phản ứng | Trong một số gia đình, người mua là con cái nhưng người phản ứng thực tế lại là hàng xóm, người giúp việc hoặc cơ sở chăm sóc | Workflow và RBAC hiện tại đã đặt Owner/Member là người nhận alert và review; tuy nhiên đây chủ yếu là quyết định thiết kế nội bộ, chưa phải bằng chứng nghiên cứu người dùng | Phỏng vấn 5–8 gia đình có người cao tuổi ở một mình; lập decision-making unit gồm buyer, executor, beneficiary và người hỗ trợ gần nhà |
| A2. Pain “không biết kịp thời khi có ngã” xảy ra đủ thường xuyên và đủ nghiêm trọng để người dùng thay đổi hành vi hoặc trả phí | Ngã có hậu quả cao nhưng có thể là sự kiện hiếm; nếu người dùng chỉ lo lắng chung chung, họ có thể không duy trì sản phẩm | Có problem statement và nhu cầu logic từ bối cảnh dự án, nhưng chưa có số liệu phỏng vấn, tần suất kiểm tra hay willingness-to-pay của phân khúc mục tiêu | Phỏng vấn theo critical incident; hỏi về lần gần nhất, thời gian phát hiện, cách xử lý, chi phí hiện tại và mức sẵn sàng trả để giảm thời gian phát hiện |
| A3. Gia đình và người cao tuổi chấp nhận camera trong nhà  | Camera trong không gian riêng tư có thể bị từ chối dù kiến trúc bảo mật tốt; người dùng cũng có thể muốn thấy hình rõ khi khẩn cấp | Kiến trúc đã đặt raw video chỉ trong RAM edge và chỉ upload clip blur; đây mới là biện pháp kỹ thuật, chưa chứng minh mức chấp nhận của người dùng | Test concept với 3 phương án: chỉ skeleton, clip blur, clip rõ có consent; đo mức tin tưởng, khu vực chấp nhận lắp và điều kiện để đồng ý |
| A4. Camera IP phổ thông và edge device đủ để phát hiện ngã với precision ≥ 85%, recall ≥ 80% trong góc nhà thực tế | Nếu bỏ sót hoặc báo giả nhiều, leverage point chính sụp đổ và người dùng mất niềm tin; dữ liệu công khai có thể không giống góc camera tại nhà Việt Nam | Dự án đã đặt metric và pipeline YOLOv8-Pose nhưng mô hình chưa được benchmark đầy đủ trên camera/góc lắp thực tế | Quay ít nhất 200 clip staged ở nhiều phòng, ánh sáng, góc nhìn và hành vi gần giống ngã; benchmark precision, recall, FPR, latency trên thiết bị edge mục tiêu |
| A5. Người dùng tin cảnh báo đủ để đưa vào workflow thật nhưng vẫn giữ quyền quyết định, không bị alert fatigue | Quá ít tin thì họ bỏ qua; quá tin thì có nguy cơ hành động sai theo AI; nhiều false positive sẽ khiến họ tắt cảnh báo | Prototype có confirm/dismiss, severity, clip blur và feedback; chưa có dữ liệu sử dụng thực tế dài ngày | Chạy pilot 1–2 tuần với tình huống staged và sinh hoạt bình thường; đo open rate, response time, dismiss rate, số notification bị bỏ qua và phỏng vấn sau pilot |


### Assumption nguy hiểm nhất nếu tôi đang sai

> _______________________________________________

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| | | |
| | | |
| | | |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [ ] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [ ] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [ ] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [ ] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> _______________________________________________  
> _______________________________________________

### Version cuối cùng tôi nộp

**Job executor:**  
> _______________________________________________

**Core JTBD:**  
> _______________________________________________

**2 bước đau nhất trong workflow:**  
> _______________________________________________

**AI leverage point chính:**  
> _______________________________________________

**Product hypothesis:**  
> _______________________________________________

**Assumption cần validate đầu tiên:**  
> _______________________________________________

---

## Checklist trước khi nộp

- [ ] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [ ] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [ ] `Core JTBD` của tôi không nhét solution vào câu.
- [ ] Tôi đã viết đủ 3 `job stories`.
- [ ] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [ ] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [ ] Tôi đã ghi rõ `assumptions to validate`.
- [ ] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.
