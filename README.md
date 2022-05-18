# Học DevOps 101

## DevOps là gì?

![DevOps Processes](./assets/images/devops-processes.png "Các giai đoạn của chuỗi DevOps")

- “DevOps” viết tắt của cụm từ **Dev**elopment và **Op**eration**s**, là sự kết hợp của “phát triển” (development – Dev) và “vận hành” (operations – Ops).

- DevOps đảm bảo sự hợp tác giữa các nhóm phát triển và vận hành để triển khai code lên môi trường production một cách nhanh chóng theo quy trình lặp lại và tự động.

  - Quá trình phát triển phần mềm (Software Development) là quá trình viết mã lệnh được thực hiện bởi các lập trình viên để tạo ra phần mềm cho người sử dụng.

  - Sau khi phần mềm được tạo ra thì cần triển khai để chạy trên hệ thống. Các công việc như: xác định bao nhiêu máy chủ cần thiết, cách cấu hình các máy chủ như thế nào để có thể vận hành được phần mềm... **không** thuộc phạm vi của các lập trình viên mà thay vào đó sẽ được thực hiện bởi các người quản trị hệ thống (System Admin).

- Do đó sự giao tiếp giữa hai bộ phận là điều không thể tránh khỏi để có thể tiến hành công việc một cách trơn tru. Vấn đề nảy sinh khi các System Admin thường không hiểu rõ về lập trình phần mềm và ngược lại các lập trình viên lại thường không rành về quản trị hệ thống.

=> Mục đích của DevOps ra đời để giải quyết vấn đề và cải tiến mối quan hệ giữa hai quá trình này.

---

## DevOps làm gì ?

![DevOps là gì](./assets/images/devops-la-lam-gi.png "DevOps - sự giao thoa giữa 3 bên: phát triển phần mềm (lập trình viên), quản trị phần mềm và đảm bảo chất lượng phần mềm (QA)")

- DevOps giữ vai trò quan trọng trong quy trình phát triển phần mềm Agile, hỗ trợ hoàn thiện quá trình chuyển đổi cho quy trình phát triển, vận hành phần mềm từ mô hình Waterfall chuyển sang CI/CD.

- Quá trình này phục vụ cho mục đích cải thiện khả năng triển khai phần mềm được nhanh chóng hơn. Và cuộc hành trình của DevOps sẽ bao gồm các công việc như sau:

  - CI (Continuous Integration): Một hình thức phát triển phần mềm và các developer thường gộp hoặc chuyển những thay đổi trong code về một repo master và build rồi test sau đó chạy tự động. Mục tiêu của CI là tìm ra bug nhanh hơn từ sớm, để có thể cải thiện được chất lượng của phần mềm, giảm thiểu được các thời gian cho việc xác thực và ra mắt cho các update mới nhất.

  - CD (Continuous Deployment): Mọi thay đổi đều sẽ được test tự động để có thể triển khai được production. Nghĩa là cần pull bản build mới nhất ngay hoặc tìm ra repo mới nhất nếu như đã được test rồi tiến hành deploy trên production. CD là một trong những cách để tăng tốc quá trình deploy sản phẩm liên tục và có thể đáp ứng được mọi yêu cầu liên tục từ phía khách hàng.

  - Xây dựng kiến trúc (Infrastructure as code): Hệ thống tương tự như code mục đích đảm bảo cho bạn có thể maintain chất lượng version control khi đang sử dụng CI. Infrastructure sẽ cần được cấu hình tự động hoàn toàn để đảm bảo cho các server được chuẩn hóa dựa theo các bản patch và version mới nhất.

  - Communication và Collaboration: là 2 nhân tố có thể giúp cho doanh nghiệp có thể phát triển và đánh giá DevOps tốt hơn. Nó sẽ đẩy cho quá trình làm việc phát triển nhanh hơn, vận hành hiệu quả hơn và còn hỗ trợ cho các team khác phát triển cùng như: marketing, sales,... Từ đó, các bộ phận quan trọng này của tổ chức sẽ dễ dàng đạt được mục tiêu của mình hơn

---

## DevOps Engineer là gì?

Các công việc chính của DevOps Engineer gần giống với công việc của Sysadmin, bao gồm: deploy, optimizing, monitoring, analysis… Điểm khác biệt là:

- DevOps Engineer đòi hỏi nhiều kĩ năng hơn như phải có coding skill, scripting để automation hệ thống.

- DevOps Engineer cần tìm hiểu về techstack mà sản phẩm công ty đang sử dụng. Ngoài ra họ cũng có thể cùng review bug hay viết những unit test thông thường.

- DevOps Engineer nay thường phải tham gia ngay vào giai đoạn phát triển nhằm:
  - Chuẩn hóa môi trường làm việc từ local cho đến production.
  - Hiểu sản phẩm hơn, để tối ưu hóa sản phẩm tốt hơn.
  - Nắm được cơ bản logic code, nắm được tiến trình của code chạy như thế nào.v.v…

---

## DevOps cần học gì?

Để làm được DevOps phải biết khá nhiều thứ về System cũng như coding và nhiều kỹ năng sau đây:

- Biết và sử dụng thành thạo Linux, Windows, MacOS. Biết dùng thành thạo lệnh Terminal trong Linux, MacOS. CMD và PowerShell trong Windows.

- Có kiến thức cơ bản về: Process Management, Threads - Concurrency, Sockets, I/O Management, Virtualization, Memory storage và File systems.

- Nên có kiến thức cơ bản về: DNS, HTTP, HTTPS, FTP, SSL. Hoặc tìm hiểu thêm về các lỗ hổng bảo mật thường gặp.

- Biết cài đặt và sử dụng vài Web Server phổ biến như: Apache và Nginx. Tìm hiểu một số khái niệm và chức năng thường được sử dụng: Caching Server, Load balancer, Reverse Proxy, and Firewall. Có thể bắt đầu với một vài thực hành với Docker đơn giản như:
  - Setup thử một vài cache server.
  - Giả lập có nhiều servers dưới local bằng cách dùng các Docker container. Sử dụng chức năng Load balancer của Web server để cân bằng tải cho server.
  - Biết và sử dụng một số dịnh vụ cloud như AWS của amazon, google cloud, và azure của microsoft.
  - Biết code một số ngôn ngữ hệ thống như bashscript, java, javascipt, python, php…
  - Biết dùng 1 số tool để truyển khai CI&CD như jenkins, jira , git (Gitlab, Bitbucket…)… Một DevOps Engineer nên biết Infrastructure as code):
    - Containers: Docker, Kubernetes.
    - Các công cụ quản lý cấu hình: Ansible, Pupet, Chef,..
  - Biết sử dụng các tool monitoring server như: Nagios, Zabbix, Icing, Datadog…

## Lợi ích của DevOps

- Tốc độ : DevOps giúp các developers và team operations đạt được mục tiêu ở một tốc độ khác giúp cải tiến sản phẩm nhanh chóng phục vụ người dùng, thích nghi với thị trường tốt hơn và điều chỉnh hiệu quả kinh doanh hiệu quả hơn.

- Chuyển giao nhanh chóng: Tăng tốc độ release thường xuyên để chúng ta cải thiện sản phẩm nhanh hơn và cho ra mắt các feature nhanh hơn cũng như fix bug, giúp phản hồi cho khách hàng nhanh chóng và xây dựng nên lợi thế cạnh tranh tốt hơn.

- Độ tin cậy : DevOps đảm bảo chất lượng bằng cách áp dụng CI /CD, monitoring và logging process. Bằng cách update mà team infrastructure cấp quyền cho team development để chuyển giao nhanh hơn mà vẫn duy trì được trải nghiệm người dùng tốt.

- Mở rộng : Team vận hành, quản lý infra và các quy trình. Lên kế hoạch về quy mô và nâng cấp môi trường giúp quản trị các hệ thống phức tạp hoặc hay thay đổi hiệu quả cũng như giảm thiểu rủi ro.

- Bảo mật : DevOps giúp di chuyển mà không chịu tổn thất về bảo mật bằng các chính sách, kiểm soát và phương pháp quản lý configuration. Thậm chí các team có thể kêu gọi bạn theo các tiêu chuẩn từ sớm bằng cách cung cấp các setup các tool theo dõi.
