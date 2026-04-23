# Day 16 Submission — Đặng Tuấn Anh (2A202600025)

---

## 1. Idea reframed

Original idea:
> Xây dựng một ứng dụng AI phân tích chuyển động qua camera để giúp những người mới tập gym tự chỉnh sửa tư thế và ghi chép tiến độ tập luyện.

Reframed as a product opportunity:
> Đối với thế hệ trẻ (Gen Z & Millennials), việc đi tập gym không chỉ vì sức khỏe mà còn vì ngoại hình và sự tự tin, nhưng chi phí thuê PT lại là một rào cản quá lớn. Cơ hội ở đây là bình dân hóa việc huấn luyện cá nhân bằng một "PT ảo bỏ túi": tự động hóa sự an toàn và loại bỏ cảm giác "quê" khi tập sai bằng phản hồi âm thanh thời gian thực ngay trong lúc nâng tạ.

---

## 2. Customer / Segment Card

- **Segment name:** Người trẻ (Gen Z & Millennials, 16-28 tuổi) mới tập gym dưới 3 tháng, bao gồm học sinh, sinh viên và nhân viên văn phòng có ngân sách hạn hẹp.
- **Operational context:** Tự tập luyện một mình tại các phòng gym bình dân (gym cỏ) hoặc gym sinh viên. Bị ảnh hưởng mạnh bởi các trào lưu Fitness trên TikTok/YouTube. Thường mang các tật sai tư thế (gù lưng, cổ rùa) do thói quen ngồi học và bấm điện thoại/máy tính kéo dài.
- **Recurring workflow:** Lướt xem clip hướng dẫn trên TikTok/Reels -> Ra phòng gym bắt chước lại -> Bối rối trước gương vì thấy mình tập không giống idol -> Ngại ngùng lướt điện thoại giữa hiệp để xem lại clip -> Tập tiếp với tâm lý hoang mang, sợ bị người xung quanh đánh giá.
- **Pain moment:** Cảm thấy xấu hổ, "quê độ" khi loay hoay với một cái máy tập hoặc mức tạ nhẹ; hoặc cảm thấy chán nản, đau mỏi thắt lưng/khớp do tập sai form trong thời gian dài mà không ai chỉ bảo.
- **Why now:** Gen Z đang cực kỳ quan tâm đến "wellness" và ngoại hình, thúc đẩy làn sóng người trẻ đến phòng gym. Đồng thời, công nghệ AI Computer Vision trên camera smartphone hiện nay đã đủ mạnh để xử lý chuyển động theo thời gian thực (real-time) mà không cần thiết bị đeo đắt tiền.
- **Access path:** TikTok fitness trends (#GymTok, #GlowUp), các group Facebook "Hội sinh viên tập gym", "Hội những người mới tập gym", Word-of-mouth (bạn bè rủ nhau đi tập).

One-sentence description:
> Những bạn trẻ từ 16-28 tuổi mới đi tập gym, rất khát khao cải thiện ngoại hình nhưng thiếu tự tin về kỹ thuật, sợ bị phán xét và không có tiền thuê PT.

---

## 3. Need Map (2–3 needs)

### Need #1 (priority)
- **Statement (JTBD):** When [thực hiện các bài tập ở phòng gym đông người], I want [biết chắc chắn mình đang tập đúng kỹ thuật ngay lập tức], so I can [tự tin đẩy tạ mà không sợ bị chấn thương hay trông ngớ ngẩn, "quê mùa" trước mặt người khác].
- **Current workaround:** Liên tục nhìn gương hất cằm lên (làm sai form cổ), hoặc lén quay video điện thoại rồi xem lại sau set tập, thỉnh thoảng nhắn tin hỏi bạn bè.
- **Pain signal:** Dừng tập giữa hiệp với vẻ mặt bối rối, bỏ qua các bài tập hiệu quả (Squat, Deadlift) chỉ vì sợ tập sai, chỉ dám tập các loại máy cố định (machines).
- **Evidence / proxy evidence:** Tần suất xuất hiện dày đặc của các video tự quay gửi lên group Facebook/TikTok với caption "Mọi người check form giúp em với ạ, em tập thấy đau lưng quá".
- **Why underserved:** PT tại phòng tập thường chèo kéo mua gói chứ hiếm khi sửa lỗi miễn phí; video TikTok/YouTube chỉ là tương tác một chiều, không thể cảnh báo ngay lúc người dùng đang gù lưng.

### Need #2
- **Statement (JTBD):** When [trải qua 1-2 tháng đầu tiên nỗ lực tập luyện], I want [nhìn thấy bằng chứng trực quan về sự tiến bộ (dù là nhỏ nhất) về kỹ thuật và tư thế], so I can [có thứ để "flex" (khoe) với bản thân/bạn bè và duy trì động lực không bỏ cuộc].
- **Current workaround:** Chụp ảnh trước gương (mirror selfie) liên tục, tự lưu các video quay lộn xộn trong máy để tự so sánh cảm tính.
- **Pain signal:** Đăng status than vãn "Tập mãi không thấy lên cơ", tỷ lệ bỏ tập (churn rate) cực kỳ cao vào tháng thứ 2 và thứ 3.
- **Evidence / proxy evidence:** Sự phổ biến của các video trào lưu "Gym Transformation" (thay đổi sau 3 tháng/6 tháng) trên TikTok.
- **Why underserved:** Các app fitness hiện tại (như Strong, Hevy) chỉ tập trung vào việc ghi chép con số (khối lượng tạ, số rep) rất khô khan, không có tính năng ghi nhận sự tiến bộ về mặt kỹ thuật chuyển động (biomechanics).

---

## 4. Strategy Statement

For **[người trẻ từ 16-28 tuổi mới tập gym]**
who struggle with **[sự thiếu tự tin về kỹ thuật và nỗi sợ chấn thương/bị phán xét]**,
our product helps them **[tự tin làm chủ động tác và an toàn ngay từ buổi đầu tiên]**
through **[phản hồi âm thanh thời gian thực phân tích chuyển động qua camera smartphone]**,
unlike **[các ứng dụng nhập liệu tạ thủ công hay video hướng dẫn một chiều trên YouTube]**,
because we can leverage **[hồ sơ cơ sở hạ tầng sinh học cá nhân hóa (Personalized Biomechanics Profile) học được từ thói quen vận động của chính họ]**.

---

## 5. Moat Hypothesis

**Moat mechanism:** Personalized Biomechanics Profile & Domain-learning flywheel.

If we deploy **[hàng chục ngàn lượt tập]** in **[ngách tập luyện tại phòng gym cho giới trẻ Việt Nam]**, the following improve:
1. AI thu thập được biên độ vận động (ROM), tỷ lệ cơ thể và tiền sử lỗi sai đặc thù của giới trẻ (ví dụ: gù lưng do ngồi học/máy tính nhiều).
2. Khả năng AI cá nhân hóa các lời nhắc (audio cues) ngày càng tinh tế, khớp hoàn toàn với giới hạn vật lý của chính user đó.
3. Độ chính xác của việc phát hiện lỗi trong môi trường khắc nghiệt (gym sinh viên đông đúc, máy móc che khuất, ánh sáng yếu) tăng lên vượt bậc.

Why competitors cannot easily replicate this:
> Đối thủ có thể copy giao diện hoặc dùng chung một mô hình Pose Estimation nguồn mở, nhưng họ không có **lịch sử dữ liệu sinh lý học của riêng từng user**. Nếu người dùng đổi app, họ sẽ mất đi "bộ nhớ" về giới hạn cơ thể mình, AI mới sẽ không biết rằng user này có tật gù lưng bẩm sinh hoặc cổ chân kém linh hoạt, dẫn đến việc nhắc nhở sai lệch. Chi phí chuyển đổi (Switching cost) này chính là rào cản phòng thủ.

---

## 6. Initial TAM / SAM / SOM view

| Layer | Estimate | Key assumptions | Confidence |
|---|---|---|---|
| TAM | ~$2.5M - $3.5M/year | Toàn bộ quy mô dân số trẻ (16-30) quan tâm đến fitness/gym tự do tại Việt Nam có smartphone. | med |
| SAM | ~$0.5M - $0.8M/year | Người trẻ (16-28 tuổi) tại các đô thị lớn, tập tại các chuỗi gym bình dân/phòng tập sinh viên. | med |
| SOM | 15,00 paid users (~$45K - $70K) | Đạt được trong 12-18 tháng đầu bằng cách đánh vào các cộng đồng trường Đại học và hợp tác Micro-Influencer (GymTok). | low |

**Top 3 unknowns requiring further research:**
1. Rào cản không gian: Sinh viên/người trẻ có tìm được góc đặt điện thoại an toàn trong một phòng gym cỏ đông đúc, chật hẹp mà không bị người khác đá trúng hay không?
2. Độ nhạy giá (Price sensitivity): Tệp 16-22 tuổi (học sinh/sinh viên) có mức sẵn sàng chi trả (Willingness to pay) rất thấp, mô hình Freemium nào sẽ hiệu quả nhất để convert họ?
3. Tính bảo mật và riêng tư: Người dùng, đặc biệt là nữ giới trong độ tuổi này, có e ngại việc một app AI sử dụng camera quay lại cơ thể họ trong trang phục tập luyện không?

**Judgment:**
- [ ] Worth pursuing now
- [x] Worth pursuing but not now (need to validate [hành vi đặt camera ở phòng gym & rào cản privacy] first)
- [ ] Not worth pursuing as currently framed

---

## 7. Positioning Note (2 sentences)

**What we are:**
> Chúng tôi là một "PT ảo" trên điện thoại di động, hoạt động như một người bạn đồng hành theo dõi và chỉnh sửa tư thế trực tiếp bằng giọng nói, giúp người trẻ tập gym an toàn và tự tin hơn.

**What we are not / not yet:**
> Chúng tôi chưa phải là nền tảng cung cấp giáo án tập luyện chuẩn thi đấu (Powerlifting/Bodybuilding), cũng không phải là ứng dụng tư vấn chế độ ăn uống hay tính toán calo phức tạp.

---

## 8. Self-assessment before Day 17

Trong 6 mắt xích (Idea - Customer - Need - Strategy - Moat - Market Size), mắt xích đang khó nhằn nhất khi mở rộng độ tuổi xuống 16-28 là **Market Size (Mô hình doanh thu)** và **Customer (Sự khác biệt trong hành vi)**.

> Việc gộp chung học sinh/sinh viên (nhiều thời gian, ít tiền) và nhân viên văn phòng trẻ (ít thời gian, có thu nhập) khiến chúng tôi băn khoăn về cách thiết kế mô hình giá (Pricing). Hơn nữa, việc validate hành vi đặt camera quay phim tại phòng gym vẫn là một ẩn số lớn chưa có dữ liệu thực tế chứng minh.

Open questions chúng tôi muốn khám phá thêm ở Day 17:
1. Làm sao để xây dựng một phễu Acquisition qua TikTok (GymTok) mà có thể thuyết phục người dùng tải app ngay lập tức?
2. Có thể tạo ra một tính năng chia sẻ (Share/Flexing) nào từ dữ liệu tiến bộ của AI để tạo ra Viral Growth Loop (Word of mouth) cho tệp sinh viên không?
3. Cách thiết kế mô hình Freemium thế nào để thu hút tệp 16-22 tuổi nhưng vẫn kiếm được tiền từ tệp 23-28 tuổi?
