# Businesslab-Discourse-Theme

Giao diện được thiết kế và custom từ [Discourse Air Theme](https://meta.discourse.org/t/discourse-air-theme/197703) và [FKB Pro theme](https://meta.discourse.org/t/fkb-pro-social-theme/234323) và hiện đang được áp dung tại dự án[Businesslab.vn](https://businesslab.vn/)

## Mục tiêu thiết kế:

- Giúp người dùng dễ dàng truy cập các nhóm danh mục
- Giao diện được thiết kế tối ưu cho thiết bị điện thoại => Mang lại trải nghiệm tương tự như cách người dùng đang tương tác với các ứng dụng mạng xã hội khác
- Tiết giảm các chi tiết thừa, gây xao nhãng quá trình đọc nội dung và thảo luận trên diễn đàn
- Ngôn ngữ thiết kế:
  - Hiện đại, mềm mại, tối giản
  - Sử dụng tone màu sáng (dự kiến sẽ phát triển thêm tuỳ chọn Dark-mode và Reader-mode)
  - Một số website truyền cảm hứng:
    - Github
    - Qiita
    - Asana
    - Viblo
    - Coda
    - Notion
    - Vietcetera
    - Spiderum
    - Careerly
    - Ứng dụng Fig (tương tự Discourse hub, nhưng đơn giản hơn)
    - Tính năng forum trên Discord
    - Feedly
    - MEDIUM
    - Ứng dụng điện thoại WIT Daily

## Theme-component hiện đang sử dụng
- [Alternative Voting Category Style for FKB Pro theme](https://github.com/VaperinaDEV/fkb-pro-alternative-voting-category-style.git): Theme-component giúp hiển thị biểu tựng voting ra bên ngoài dùng với [Discourse Voting plugin](https://meta.discourse.org/t/discourse-voting/40121).
- [Auto linkify words](https://meta.discourse.org/t/linkify-words-in-post-theme-component/82193): Tự động gắn link điều hướng với từ khoá đã được cài đặt
- [Custom user menu tab](https://meta.discourse.org/t/custom-user-menu-tab/130091): Thêm liên kết tuỳ biến trong menu user
- [DiscoTOC](https://meta.discourse.org/t/discotoc-automatic-table-of-contents/111143): Tự động tạo danh mục bài viết

### Tuỳ chỉnh danh mục (Category)
- [Categories Layout Override (Mobile Only)](https://github.com/CyanLabs/discourse-categories-layout-override): Cho phép tuỳ chọn bố cục trang danh mục trên điện thoại cùng với tuỳ biến bởi theme-componet [Enhanced category-box display component](https://meta.discourse.org/t/enhanced-category-box-display-component/156954)
- 
- [Category Headers theme component](https://meta.discourse.org/t/discourse-category-headers-theme-component/148682): Tuỳ chỉnh hiển thị phần header và title của trang danh mục
- [Category Icons](https://meta.discourse.org/t/category-icons/104683): Cho phép tuỳ biến hiển thị biểu tưởng bên cạnh tên danh mục

  
- [Category List Banners][def4]
- [DiscoTOC](https://meta.discourse.org/t/discotoc-automatic-table-of-contents/111143)
- [Discourse Clickable Topic](https://meta.discourse.org/t/clickable-topic/183339)
- [Discourse Composer Footnote Button](https://meta.discourse.org/t/composer-footnote-button/243487)
- [Discourse easy footer](https://meta.discourse.org/t/easy-responsive-footer/95818)
**Tính năng mở rộng**
- [Add to homescreen](https://github.com/discourse/discourse-apple-add-to-homescreen.git): Hiển thị 1 popup hướng dẫn người dùng bookmark trang website ra màn hình chính^[Áp dụng trên thiết bị chạy hệ điều hành IOS]


## Plugin hiện đang sử dụng

---

**Thông tin thêm:**
- [Hướng dẫn cài đặt mã nguồn Discourse][def9]
- [Hướng dẫn cài đặt thêm Plugin trên Discourse][def7]
- [Hướng dẫn cài đặt theme và theme component trên Discourse][def8]
- [Hướng dẫn sử dụng Discourse Theme][def5]
- [HƯớng dẫn phát triển Discourse Theme][def6]

[def4]: https://meta.discourse.org/t/category-list-with-banners/201280
[def5]: https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966
[def6]: https://meta.discourse.org/t/beginners-guide-to-developing-discourse-themes/93648
[def7]: https://meta.discourse.org/t/install-plugins-in-discourse/19157
[def8]: https://meta.discourse.org/t/install-a-theme-or-theme-component/63682
[def9]: https://github.com/discourse/discourse/blob/main/docs/INSTALL-cloud.md
