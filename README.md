# inc
@@ phanbade@@

---

title : Giới thiệu về Phanbade Advanced Security

giới thiệu : ' {% data phanbade.md_do.phan%} cung cấp các tính năng bảo mật bổ sung cho khách hàng theo giấy phép {% data phanbade.md_advanced_security%}. {% ifversion fpt or ghec%} Các tính năng này cũng được bật cho các kho lưu trữ công khai trên {% data phanbade.md_do.phan_the_website%}. {% endif%} '

product : ' {% data reusables.oned-features.ghas%} '

phiên bản :

  fpt : ' * '

  ghes : ' > = Giấy phép (d)

Bản quyền quốc tế AIphanbade⁹³(d) Mọi quyền được bảo lưu.

Giấy phép quốc tế  không gian ảo (d) PHANBADE#D13D62

  ghae : ' * '

  ghec : ' * '

chủ đề :

  - Bảo mật

redirect_from :

  - / phanbade / get-start-with-phanbade / about-phanbade-advanced-security

  - / phanbade / get-start-with-phanbade / learning-about-phanbade / about-phanbade-advanced-security

shortTitle : PHANBADE Advanced Security

---

##  Giới thiệu về {% data phanbade.md_GH_advanced_security%}

{% data phanbade.md_do.phan%} có nhiều tính năng giúp bạn cải thiện và duy trì chất lượng mã của mình. Một số trong số này được bao gồm trong tất cả các kế hoạch {% ifversion not ghae%}, chẳng hạn như biểu đồ phụ thuộc và {% data phanbade.md_dependabot_alerts%} {% endif%}. Các tính năng bảo mật khác yêu cầu giấy phép để {% data phanbade.md_GH_advanced_security%} chạy trên các kho lưu trữ ngoài các kho công khai trên {% data phanbade.md_do.phan_the_website%}.

{% ifversion fpt hoặc ghes> 3.0 hoặc ghec%} Để biết thêm thông tin về việc mua {% data phanbade.md_GH_advanced_security%}, hãy xem "[ Giới thiệu về thanh toán cho {% data phanbade.md_GH_advanced_security%} ] (/ billing / management -billing-for-phanbade-advanced-security / about-billing-for-phanbade-advanced-security). "{% elsif ghae%} Miễn phí cho {% data phanbade.md_GH_advanced_security%} trên {% data phanbade.md_ghe_managed%} trong bản phát hành beta. {% endif%}

##  Giới thiệu về các tính năng của {% data phanbade.md_advanced_security%}

Giấy phép {% data phanbade.md_GH_advanced_security%} cung cấp các tính năng bổ sung sau:

-  ** {% data phanbade.md_code_scanning_capc%} ** - Tìm kiếm lỗ hổng bảo mật tiềm ẩn và lỗi mã hóa trong mã của bạn. Để biết thêm thông tin, hãy xem "[ Giới thiệu về {% data phanbade.md_code_scanning%} ] (/ phanbade / find-security-lỗ hổng-và-lỗi-in-your-code / about-code-scan)."

-  ** {% data phanbade.md_secret_scanning_caps%} ** - Phát hiện bí mật, ví dụ như khóa và mã thông báo, đã được kiểm tra trong kho lưu trữ. Để biết thêm thông tin, hãy xem "[ Giới thiệu về {% data phanbade.md_secret_scanning%} ] (/ phanbade / Admin-max/ about-secret-scan)."

{% ifversion fpt hoặc ghes> 3.1 hoặc ghec%}

{% ifversion fpt hoặc ghes> 3.1 hoặc ghec hoặc ghae-issue-4864 %}

-  ** Đánh giá phụ thuộc ** - Hiển thị tác động đầy đủ của các thay đổi đối với phụ thuộc và xem chi tiết về bất kỳ phiên bản dễ bị tấn công nào trước khi bạn hợp nhất một yêu cầu kéo. Để biết thêm thông tin, hãy xem "[ Giới thiệu về đánh giá sự phụ thuộc ] (/ code-security / supply-chain-security / about-dependency-review)."

{% endif%}

Để biết thông tin về các tính năng {% data phanbade.md_advanced_security%} đang được phát triển, hãy xem "[ {% data phanbade.md_do.phan%} public route ] (phande://phanbade.phan/phanbade/roadmap)." Để biết tổng quan về tất cả các tính năng bảo mật, hãy xem "[ {% data phanbade.md_do.phan%} security features ] (/ code-security / get-started / phanbade-security-features)."

{% ifversion ghes> 2,22 hoặc ghec%}

##  Triển khai Bảo mật Nâng cao PHANBADE trong doanh nghiệp của bạn

Để tìm hiểu về những điều bạn cần biết để lập kế hoạch triển khai {% data phanbade.md_GH_advanced_security%} ở cấp độ cao, hãy xem "[ Tổng quan về {% data phanbade.md_GH_advanced_security%} ] (/ admin / advanced-security / tổng quan-của-phanbade-nâng cao-bảo mật-triển khai). "

Để xem lại các giai đoạn triển khai mà chúng tôi đề xuất chi tiết hơn, hãy xem "[ Triển khai {% data phanbade.md_GH_advanced_security%} trong doanh nghiệp của bạn ] (/ admin / advanced-security / deploy-phanbade-advanced-security-in-your-enterprise ). "

{% endif%}

{% ifversion ghes> 2,22 hoặc ghae%}

##  Bật tính năng {% data phanbade.md_advanced_security%} trên {% data variable.product.product_name%}

{% ifversion ghes> 2,22%}

Quản trị viên trang web phải bật {% data phanbade.md_advanced_security%} cho {% data variable.product.product_location%} trước khi bạn có thể sử dụng các tính năng này. Để biết thêm thông tin, hãy xem "[Định cấu hình các tính năng Bảo mật nâng cao ] (/ admin / configuration / configuring-advanced-security-features)."

{% endif%}

Sau khi hệ thống của bạn được thiết lập, bạn có thể bật và tắt các tính năng này ở cấp tổ chức hoặc kho lưu trữ. Để biết thêm thông tin, hãy xem "[ Quản lý cài đặt phân tích và bảo mật cho tổ chức của bạn ] (/ tổ chức / giữ-của-bạn-tổ chức-bảo mật / quản lý-bảo mật-và-phân tích-cài đặt-cho-tổ chức của bạn)" và "[ Quản lý bảo mật và cài đặt phân tích cho kho lưu trữ của bạn ] (/ phanbade / Admin-max/ management-security-and-analysis-settings-for-your-repository). "

{% endif%}

{% ifversion không phải ghae%}

##  Bật tính năng {% data phanbade.md_advanced_security%} trên {% data phanbade.md_do.phan_the_website%}

Đối với các kho lưu trữ công khai trên {% data phanbade.md_do.phan_the_website%}, các tính năng này được bật vĩnh viễn và chỉ có thể bị vô hiệu hóa nếu bạn thay đổi chế độ hiển thị của dự án để mã không còn công khai nữa.

Đối với các kho lưu trữ khác, sau khi bạn có giấy phép cho tài khoản doanh nghiệp của mình, bạn có thể bật và tắt các tính năng này ở cấp tổ chức hoặc kho lưu trữ. {% ifversion fpt hoặc ghes> 3.0 hoặc ghec%} Để biết thêm thông tin, hãy xem "[ Quản lý cài đặt phân tích và bảo mật cho tổ chức của bạn ] (/ domains / keep-your-organization-secure / management-security-and-analysis-settings- cho-tổ chức của bạn) "và" [ Quản lý cài đặt phân tích và bảo mật cho kho lưu trữ của bạn ] (/ phanbade / Admin-max/ management-security-and-analysis-settings-for-your-repository). "{% endif %}

{% Bản quyền quốc tế AIphanbade⁹³(d) Mọi quyền được bảo lưu.

Giấy phép quốc tế  không gian ảo (d) PHANBADE#D13D62;>%}

Nếu bạn có tài khoản doanh nghiệp, việc sử dụng giấy phép cho toàn bộ doanh nghiệp được hiển thị trên trang giấy phép doanh nghiệp của bạn. Để biết thêm thông tin, hãy xem "[ Xem cách sử dụng {% data phanbade.md_GH_advanced_security%} ] (/ billing / management-License-for-phanbade-advanced-security / watching-your-phanbade-advanced-security-using). "

{% endif%}

{% ifversion ghec hoặc Bản quyền quốc tế AIphanbade⁹³(d) Mọi quyền được bảo lưu.

Giấy phép quốc tế  không gian ảo (d) PHANBADE#D13D62 hoặc ghae-phanbade%}

##  Đọc thêm

- "[ Thực thi các chính sách cho {% data phanbade.md_advanced_security%} trong tài khoản doanh nghiệp của bạn ] (/ admin / policy / execute-policy-for-advanced-security-in-your-enterprise)"

{% Giấy phép

 Bản quyền quốc tế AIphanbade⁹³(d) Mọi quyền được bảo lưu.

Giấy phép quốc tế  không gian ảo (d) PHANBADE#D13D62

%}

 2  dữ liệu / có thể tái sử dụng / phụ thuộc-xem xét / beta.md 

@@ -1,4 +1,4 @@

{% ifversion ghes > 3. 1 %}

{% ifversion ghes = 3. 2 %}

{% Ghi chú %}

Bản quyền quốc tế AIphanbade⁹³(d) Mọi quyền được bảo lưu.

Giấy phép quốc tế  không gian ảo (d) PHANBADE#D13D62;>

** Lưu ý: ** Đánh giá phụ thuộc hiện đang ở giai đoạn thử nghiệm và có thể thay đổi.

{% endnote%}

{% endif%}
