<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/lxhau/DocumentAndProduct">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">XÂY DỰNG ỨNG DỤNG ĐẶT MÓN BOOFOOD</h3>

  <p align="center">
    <br />
    <br />
	Sinh Viên Thực Hiện
	<br />
	<br />
    <a href="https://www.facebook.com/lexuanhau99">Lê Xuân Hậu</a>
    ·
    <a href="https://www.facebook.com/fuzethien">Trần Ngọc Thiên</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Mục lục</summary>
  <ol>
    <li>
      <a href="#about-the-project">Giới Thiệu Về Đề Tài</a>
      <ul>
        <li><a href="#built-with">Công nghệ sử dụng</a></li>
		<li><a href="#built-with">Hệ Quản Trị Sử Dụng</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Bắt đầu</a>
      <ul>
        <li><a href="#prerequisites">Chuẩn bị công cụ</a></li>
        <li><a href="#installation">Cài đặt và triển khai</a></li>
      </ul>
    </li>
    <li><a href="#document">Tài liệu hệ thống</a></li>
    <li><a href="#download">Ứng dụng thực tế</a></li>
    <li><a href="#license">Giấy phép</a></li>
    <li><a href="#contact">Liên hệ</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Hình 1.1: Hình ảnh giới thiệu ứng dụng.

Dây là đâu:
* Trong quảng thời gian ngắn của Luận Văn Tốt Nghiệp hi vọng những gì chúng em mang lại nhận được nhiều đánh giá và góp ý để nhóm có thể cải thiện và phát triển trong tương lai.
* Ứng dụng hiện thực trên nền tảng android và nền tảng web.
* Hiện tại đã có phiên bản productions đã triển khai trên kho ứng dụng CHPlay dành cho thiết bị android.
* Hi vọng nó sẽ mang lại trãi nghiệm tốt cho các bạn, và hãy để lại cho chúng tôi ý kiến nhé.


### Built With

Ứng dụng được viết bởi các ngôn ngữ sau và thư viện sau:
* [Java](https://go.java)
* [ReactJs](https://reactjs.org)
* [NodeJs](https://nodejs.org)
* [MySQL](https://www.mysql.com/)

Ứng dụng được triển khai như sau:
* [Database](https://azure.microsoft.com)
* [Server](https://www.heroku.com)
* [App-BooFood](https://play.google.com/)

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

Hệ thống có thể triển khải trên các nền tảng hệ điều hành Windows lẫn MacOS, Linux. Chỉ cần cấu hình để có thể chạy được NodeJs, MySQL, Android Studio

[NodeJs][ExpressJs] -- Triển khai server và API

[MySQL] -- Triển khai Hệ quản trị CSDL

[Android Studio] -- Xây dựng ứng dụng android

[Android Emulator] -- Thiết bị chạy ứng dụng. -- Lưu ý: Cần hổ trợ GPS.

[Ngrok] -- Public Ip Local ra internet

Chỉ cần cài đặt và cấu hình.

### Installation
 
1. Tạo tài khoản git-lab liên hệ [lexuanhau99@gmail] để được add vào.

2. tải xuống source code server về máy

   ```sh
   git clone https://gitlab.com/lexuanhau99/lvtn-boofood.git
   ```
   
3. Tải xuống source code android về máy

   ```sh
   git clone https://gitlab.com/lexuanhau99/boofood-app.git
   ```
   
   ```sh
   git clone https://gitlab.com/lexuanhau99/app-merchant-boo.git
   ```
   
   ```sh
   git clone https://gitlab.com/lexuanhau99/driver-boo.git
   ```
   
4. Cài đặt thư viện cho project

   ```sh
   npm run lib
   ```
   
5. Cài đặt thư viện cho project web

   ```sh
   npm run lib-fe
   ```
   
	```sh
   npm run lib-mc
   ```
   
6. Cấu hình cho key cho và password cho DB ở .ENV ở root

7. Cấu hình mailService cho root/configs/configEmail.js

8. Cấu hình FCM Service cho root/configs/configFirebase.js

9. Chạy ứng dụng với 3 terminal

	```sh
   npm run be
   ```
   
	```sh
   npm run fe
   ```
   
   ```sh
   npm run mc
   ```
   
10. Sau khi ứng dụng biuld thành công sẽ xuất hiện lệnh sau.

	```sh
	Server running on port: http://localhost:3100
	Connected to the MySQL server.
	{ status: false, message: 'Administrator account has been created.' } 
   ```

<!-- Document EXAMPLES -->
## Document

1. Lược đồ quan hệ ERD
[https://drive.google.com/file/d/1kKjPk0qD7Q8oPvcwKCFqOURNrJ84cAF9/view?usp=sharing]

[https://drive.google.com/file/d/1UPQsBQF2z40QlPTzaBHMkCQqjoqkZNPd/view?usp=sharing]

2. File DOC Luận Văn Tốt Nghiệp

[https://drive.google.com/file/d/1FFFiE0NRNXlUNuuDKAaFdU-1iGjxUFsA/view?usp=sharing]

3. File Trình Bài Powerpoint

[https://docs.google.com/presentation/d/1nYuqH8TK9qtUC8YWEk1_VOFw6CuBs_1X/edit?usp=sharing&ouid=117094946688487088045&rtpof=true&sd=true]

4. Cập thêm sau khi hoàn tất.


<!-- Download -->
## Download

1. BooFood

	1.1. CHPlay
	
	
	1.2. Tải trực tiếp.
	

2. Merchant

	2.1 CHPlay
	

	2.2 Tải trực tiếp
	
	
3. Rider

	3.1 CHPlay
	

	3.2 Tải trực tiếp



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
