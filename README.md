## WEB SERVICE
### I. GIỚI THIỆU
Web service là một ứng dụng phần mềm được thiết kế để trao đổi dữ liệu giữa các ứng dụng khác nhau qua mạng Internet sử dụng các giao thức tiêu chuẩn như HTTP, XML, JSON, SOAP, RESTful, ... Web service cho phép các ứng dụng có thể giao tiếp và trao đổi dữ liệu với nhau một cách liên tục, đáng tin cậy và độc lập với nền tảng và ngôn ngữ lập trình.
### II. Các khái niệm cơ bản về Web service
- SOAP: Sử dụng XML để truyền tải dữ liệu giữa các ứng dụng, được sử dụng trong các hệ thống phức tạp với tính bảo mật cao.
- REST (Representational State Transfer): Sử dụng các phương thức HTTP để truyền tải dữ liệu, được sử dụng trong các ứng dụng web đơn giản với tính mở và linh hoạt cao.
- UDDI (Universal Description, Discovery & Integration): UDDI là một tiêu chuẩn dựa trên XML để mô tả, xuất bản và tìm kiếm các dịch vụ web. UDDI là một open framework và là nền tảng độc lập. UDDI có thể giao tiếp qua SOAP, CORBA và Giao thức RMI Java. UDDI sử dụng WSDL để mô tả giao diện cho các dịch vụ web.
### III. Ưu nhược điểm của Web service
#### 1. Ưu điểm
- Tính tương thích: Web service cho phép các ứng dụng khác nhau truy cập và chia sẻ dữ liệu một cách độc lập với nền tảng, ngôn ngữ hoặc hệ điều hành của ứng dụng.
- Tính tái sử dụng: Web service có thể được sử dụng lại trong các ứng dụng khác nhau mà không cần phải viết lại mã.
- Tính mở: Web service cho phép các ứng dụng truy cập và chia sẻ dữ liệu một cách dễ dàng và linh hoạt.
- Tính bảo mật: Các Web service có thể được bảo mật bằng các phương thức như SSL (Secure Socket Layer) hoặc mã hóa dữ liệu.
- Tính khả chuyển: Web service có thể được triển khai trên nhiều nền tảng khác nhau như Java, .NET, PHP, Python, v.v.
#### 2. Nhược điểm
- Phức tạp: Web service có thể phức tạp và khó hiểu đối với người mới bắt đầu.
- Tốc độ chậm: Truyền tải dữ liệu qua Web service có thể chậm hơn so với truyền tải trực tiếp giữa các ứng dụng.
- Có thể bị lỗi: Web service có thể gây ra các lỗi như mất kết nối hoặc lỗi phần mềm.
### V. Ứng dụng của Web service
- Cung cấp dịch vụ cho người dùng: Web service được sử dụng để cung cấp các dịch vụ như thanh toán trực tuyến, chia sẻ dữ liệu, tìm kiếm, v.v.
- Tích hợp giữa các ứng dụng: Web service được sử dụng để tích hợp giữa các ứng dụng khác nhau, giúp chúng có thể truy cập và chia sẻ dữ liệu với nhau.
- Phát triển ứng dụng di động: Web service có thể được sử dụng để cung cấp dịch vụ cho các ứng dụng di động, giúp chúng có thể truy cập và chia sẻ dữ liệu với các ứng dụng khác.
### VI. Kết luận
Web service đóng vai trò quan trọng trong việc cung cấp dịch vụ và chia sẻ dữ liệu giữa các ứng dụng khác nhau, đặc biệt là trong các ứng dụng web. Tuy nhiên, để sử dụng Web service hiệu quả, người phát triển cần phải hiểu rõ về các loại Web service, ưu nhược điểm của chúng và cách triển khai Web service trong các ứng dụng của mình.
### VII. Webservice và API
#### 1. Giống nhau:
- Đều là các công nghệ được sử dụng để truyền tải dữ liệu giữa các ứng dụng và hệ thống khác nhau.
- Đều có khả năng tích hợp giữa các ứng dụng và hệ thống khác nhau.
- Có khả năng truyền tải dữ liệu giữa các ứng dụng và hệ thống khác nhau.
#### 2. Khác nhau:
- Webservice thường sử dụng giao thức SOAP (Simple Object Access Protocol) để truyền tải dữ liệu, trong khi API không bắt buộc phải sử dụng giao thức nào cụ thể.
- Webservice thường được sử dụng để hỗ trợ các ứng dụng và hệ thống truyền tải dữ liệu giữa các nền tảng khác nhau, trong khi API thường được sử dụng để hỗ trợ các ứng dụng truy cập vào các chức năng của ứng dụng hoặc hệ thống khác.
- Webservice có tính đồng nhất hơn API do sử dụng giao thức SOAP, trong khi API không có tính đồng nhất.
- Webservice hỗ trợ nhiều giao thức truyền tải dữ liệu như HTTP, FTP, SMTP, và các giao thức khác, trong khi API chủ yếu sử dụng các giao thức HTTP và HTTPS.
- API được sử dụng rộng rãi hơn Webservice trong các ứng dụng hiện đại.
### VIII. Chi tiết các option trong config file webservice
- Port: Đây là cổng mà webservice sẽ lắng nghe trên. Mặc định thường là port 80 cho HTTP và port 443 cho HTTPS.
- Document root: Đây là thư mục chứa các tệp tin và thư mục được phục vụ bởi webservice. Thư mục này thường được chỉ định bằng đường dẫn tuyệt đối.
- Server name: Đây là tên miền hoặc địa chỉ IP mà webservice sẽ phục vụ.
- Access control: Tùy chọn này cho phép ta quản lý quyền truy cập vào webservice của người dùng bằng cách chỉ định các quy tắc truy cập.
- Logging: Tùy chọn này cho phép ta cấu hình các tệp nhật ký để ghi lại các hoạt động của webservice.
- SSL: Tùy chọn này cho phép ta cấu hình kết nối bảo mật HTTPS bằng SSL hoặc TLS.
- Proxy: Tùy chọn này cho phép ta cấu hình webservice để chuyển tiếp các yêu cầu tới một server khác.
- CGI: Tùy chọn này cho phép ta cấu hình webservice để sử dụng các tệp CGI để thực thi các kịch bản.
- Virtual host: Tùy chọn này cho phép ta cấu hình nhiều tên miền khác nhau để phục vụ trên cùng một địa chỉ IP hoặc cổng.
- MIME types: Tùy chọn này cho phép ta cấu hình các loại MIME được hỗ trợ bởi webservice.
- Error handling: Tùy chọn này cho phép ta cấu hình cách xử lý các lỗi phát sinh trong quá trình thực hiện webservice.
- Cache: Tùy chọn này cho phép ta cấu hình bộ nhớ đệm để tăng tốc độ phục vụ của webservice.
- Compression: Tùy chọn này cho phép ta cấu hình nén dữ liệu để giảm kích thước tệp tin được phục vụ.
##### Tóm lại, Webservice và API đều là các công nghệ quan trọng để truyền tải dữ liệu giữa các ứng dụng và hệ thống khác nhau. Tùy thuộc vào yêu cầu của ứng dụng, người sử dụng có thể lựa chọn sử dụng Webservice hoặc API để tích hợp các hệ thống và truyền tải dữ liệu giữa các ứng dụng.

## NGINX
### I. Giới thiệu chung về Nginx
Nginx là một web server mã nguồn mở phổ biến được sử dụng để phục vụ các trang web tĩnh (static) và động (dynamic). Nó được phát triển bởi Igor Sysoev vào năm 2002 và hiện nay được sử dụng rộng rãi trên toàn thế giới.
### II. Các tính năng của Nginx
- Xử lý tải: Nginx có khả năng xử lý hàng ngàn kết nối đồng thời với tốc độ nhanh và ít tài nguyên hơn so với các web server khác.
- Cân bằng tải: Nginx có khả năng phân phối tải đều cho các server trong cụm, giúp tăng hiệu suất và độ tin cậy.
- Hỗ trợ HTTP, HTTPS, SMTP, POP3 và IMAP: Nginx có khả năng hỗ trợ nhiều giao thức khác nhau.
- Hỗ trợ proxy: Nginx có khả năng hoạt động như một proxy server, giúp tăng cường tính bảo mật và giảm tải cho các server trong cụm.
- Hỗ trợ giao thức WebSocket: Nginx có khả năng hỗ trợ giao thức WebSocket, giúp tăng cường tính tương tác và trải nghiệm người dùng.
### III. Ưu nhược điểm của Nginx
#### 1. Ưu điểm
- Hiệu suất cao: Nginx có khả năng xử lý hàng ngàn kết nối đồng thời với tốc độ nhanh và ít tài nguyên hơn so với các web server khác.
- Tính ổn định cao: Nginx có khả năng chịu tải tốt và độ ổn định cao, giúp đảm bảo tính khả dụng của trang web.
- Bảo mật: Nginx có khả năng hỗ trợ nhiều tính năng bảo mật, giúp ngăn chặn các cuộc tấn công và bảo vệ dữ liệu.
- Dễ dàng cấu hình: Nginx có cấu trúc cấu hình đơn giản và dễ dàng, giúp người quản trị có thể điều chỉnh và tùy chỉnh dễ dàng.
- Hỗ trợ mở rộng: Nginx có khả năng hỗ trợ nhiều module bổ sung, giúp mở rộng tính năng và sử dụng cho nhiều mục đích khác nhau.
#### 2. Nhược điểm
- Hạn chế về tính năng: Nginx không hỗ trợ các tính năng động (dynamic) như PHP hoặc Java Servlets mà cần phải sử dụng các ứng dụng bên ngoài để xử lý.
- Phức tạp đối với người mới bắt đầu: Nginx có cấu trúc cấu hình đơn giản nhưng có thể phức tạp đối với người mới bắt đầu.
### V. Ứng dụng của Nginx
- Phục vụ trang web tĩnh và động
- Cân bằng tải
- Proxy server
- Load balancer
- Reverse proxy
### VI. Kết luận
Nginx là một web server mã nguồn mở phổ biến được sử dụng để phục vụ các trang web tĩnh và động. Với khả năng xử lý tải tốt, tính ổn định cao, tính bảo mật và dễ dàng cấu hình, Nginx đã được sử dụng rộng rãi trên toàn thế giới. Tuy nhiên, Nginx cũng có nhược điểm như hạn chế về tính năng và phức tạp đối với người mới bắt đầu.
### VIII. Chi tiết các option trong config file nginx
- worker_processes: Số lượng tiến trình worker được tạo ra bởi Nginx để xử lý các yêu cầu. Giá trị mặc định là 1, nhưng ta có thể tăng giá trị này để tận dụng tốt hơn các lõi CPU trên máy chủ.
- worker_connections: Số lượng kết nối được phép đồng thời trên mỗi worker. Giá trị mặc định là 1024, nhưng nên tăng giá trị này nếu ta đang xử lý một lượng lớn các yêu cầu với Nginx.
- http: Phần này định nghĩa cấu hình cho các máy chủ web HTTP. ta có thể định nghĩa các tùy chọn cho máy chủ, như cổng, tên miền, các tệp tin index mặc định và các trang báo lỗi.
- server: Phần này định nghĩa các tùy chọn cho mỗi máy chủ web. ta có thể định nghĩa các tùy chọn cho máy chủ, như cổng, tên miền, các tệp tin index mặc định và các trang báo lỗi.
- location: Phần này định nghĩa các tùy chọn cho mỗi vị trí URL trên mỗi máy chủ web. ta có thể định nghĩa các tùy chọn cho các vị trí URL, như cấu hình cho các tệp tin - tĩnh, các ứng dụng web và các giao thức khác nhau như HTTP và WebSocket.
- error_log: Định nghĩa đường dẫn tới tệp log lỗi của Nginx.
- access_log: Định nghĩa đường dẫn tới tệp log truy cập của Nginx.
- include: Cho phép ta định nghĩa các tệp cấu hình phụ để tái sử dụng hoặc tách các cấu hình ra để quản lý dễ dàng hơn.
### IX. Cài đặt
- Cập nhật hệ thống:
```
sudo apt-get update
sudo apt-get upgrade
```
- Sau đó ta tiến hành cài nginx:
```
sudo apt-get install nginx
```
- Sau đó ta tiến hành kiểm tra phiên bản của nginx:
```
nginx -v
```
Hiện thông báo `nginx version: nginx/1.18.0 (Ubuntu)` 
- Sau đó ta kiểm tra trạng thái của nginx:
```
sudo systemctl status nginx
```
```
● nginx.service - A high performance web server and a reverse proxy server
     Loaded: loaded (/lib/systemd/system/nginx.service; enabled; vendor preset: enabled)
     Active: active (running) since Tue 2023-04-25 09:06:49 +07; 5h 41min ago
       Docs: man:nginx(8)
   Main PID: 1025 (nginx)
      Tasks: 2 (limit: 949)
     Memory: 2.5M
     CGroup: /system.slice/nginx.service
             ├─1025 nginx: master process /usr/sbin/nginx -g daemon on; master_process on;
             └─1026 nginx: worker process
             Apr 25 09:06:43 2402 systemd[1]: Starting A high performance web server and a reverse proxy server...
             Apr 25 09:06:49 2402 systemd[1]: Started A high performance web server and a reverse proxy server.
```
Khi hiện thông báo active(running) là nginx của chúng ta đang chạy.
- Mở cổng truy cập http trên tường lửa:
```
sudo ufw allow 'Nginx HTTP'
```
![nginx](https://assets.digitalocean.com/articles/nginx_1604/default_page.png)
## APACHE
### I. Giới thiệu chung về Apache
Apache là một web server phổ biến và được sử dụng rộng rãi trên toàn thế giới. Nó được phát triển bởi Apache Software Foundation và được phát hành dưới giấy phép Apache.
### II. Các tính năng của Apache
- Xử lý tải: Apache có khả năng xử lý hàng ngàn kết nối đồng thời với tốc độ nhanh và ít tài nguyên hơn so với các web server khác.
- Hỗ trợ HTTP, HTTPS, FTP và Gopher: Apache có khả năng hỗ trợ nhiều giao thức khác nhau.
- Hỗ trợ CGI, Perl, PHP và Python: Apache có khả năng hỗ trợ các ngôn ngữ lập trình phổ biến để tạo ra trang web động.
- Hỗ trợ SSL/TLS: Apache có khả năng hỗ trợ SSL/TLS để bảo vệ dữ liệu truyền tải giữa máy khách và máy chủ.
- Dễ dàng cấu hình: Apache có cấu trúc cấu hình đơn giản và dễ dàng, giúp người quản trị có thể điều chỉnh và tùy chỉnh dễ dàng.
### III. Ưu nhược điểm của Apache
#### 1. Ưu điểm
- Tính ổn định cao: Apache có khả năng chịu tải tốt và độ ổn định cao, giúp đảm bảo tính khả dụng của trang web.
- Tính bảo mật cao: Apache có khả năng hỗ trợ nhiều tính năng bảo mật, giúp ngăn chặn các cuộc tấn công và bảo vệ dữ liệu.
- Hỗ trợ mở rộng: Apache có khả năng hỗ trợ nhiều module bổ sung, giúp mở rộng tính năng và sử dụng cho nhiều mục đích khác nhau.
- Được sử dụng rộng rãi: Apache là một trong những web server phổ biến nhất trên thế giới, được sử dụng rộng rãi trong các doanh nghiệp và tổ chức.
- Hỗ trợ cộng đồng lớn: Apache có một cộng đồng lớn và sôi động, cung cấp hỗ trợ và giải đáp các câu hỏi liên quan đến việc sử dụng Apache.
#### 2. Nhược điểm
- Hiệu suất chưa cao: Apache có thể không đạt được hiệu suất cao như một số web server khác như Nginx.
- Không hỗ trợ WebSocket: Apache không hỗ trợ giao thức WebSocket, điều này có thể khiến cho việc phát triển các ứng dụng web tương tác trở nên khó khăn.
### V. Ứng dụng của Apache
- Phục vụ trang web tĩnh và động
- Cân bằng tải
- Proxy server
- Load balancer
- Reverse proxy
### VII. Chi tiết các option trong config file apache
- ServerRoot: Đường dẫn tới thư mục chứa các tệp cấu hình và các tài nguyên khác của Apache.
- Listen: Cổng mà Apache lắng nghe yêu cầu từ client. Giá trị mặc định là 80 cho HTTP và 443 cho HTTPS.
- ServerName: Tên miền của máy chủ web.
- DocumentRoot: Thư mục chứa các tệp tài nguyên của trang web.
- Directory: Phần này định nghĩa các tùy chọn cho một thư mục cụ thể trên máy chủ web.
- VirtualHost: Phần này định nghĩa các tùy chọn cho một tên miền cụ thể trên máy chủ web.
- LogLevel: Độ chi tiết của các thông báo lỗi được ghi vào các tệp nhật ký.
- ErrorLog: Đường dẫn tới tệp nhật ký lỗi của Apache.
- AccessLog: Đường dẫn tới tệp nhật ký truy cập của Apache.
- DirectoryIndex: Các tệp mặc định được hiển thị khi truy cập vào một thư mục trên máy chủ.
### VI. Kết luận
Apache là một web server phổ biến và được sử dụng rộng rãi trên toàn thế giới. Với tính ổn định cao, tính bảo mật và dễ dàng cấu hình, Apache đã được sử dụng rộng rãi trong các doanh nghiệp và tổ chức. Tuy nhiên, Apache cũng có nhược điểm như hiệu suất chưa cao và không hỗ trợ giao thức WebSocket.
### VIII. Cài đặt
- Cập nhật hệ thống:
```
sudo apt-get update
sudo apt-get upgrade
```
- Sau đó ta tiến hành cài apache:
```
sudo apt-get install apache2
```
- Sau đó ta kiểm tra trạng thái của apache:
```
sudo systemctl status apache2
```
```
● apache2.service - The Apache HTTP Server
     Loaded: loaded (/lib/systemd/system/apache2.service; enabled; vendor preset: enabled)
     Active: active (running) since Thu 2023-04-27 02:09:06 UTC; 32min ago
       Docs: https://httpd.apache.org/docs/2.4/
   Main PID: 917 (apache2)
      Tasks: 55 (limit: 2234)
     Memory: 7.8M
     CGroup: /system.slice/apache2.service
             ├─917 /usr/sbin/apache2 -k start
             ├─918 /usr/sbin/apache2 -k start
             └─919 /usr/sbin/apache2 -k start

Apr 27 02:09:04 1111 systemd[1]: Starting The Apache HTTP Server...
Apr 27 02:09:06 1111 apachectl[877]: AH00558: apache2: Could not reliably determine the server's fully qualified domain>
Apr 27 02:09:06 1111 systemd[1]: Started The Apache HTTP Server.
```
![alt](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/original/2X/7/771159b35c97e429247aac754ad44bf06cc1efa8.png)
### VII. NGINX và Apache
#### Giống nhau:
- Đều là các phần mềm máy chủ web được sử dụng để phục vụ các trang web và ứng dụng web.
- Đều có khả năng xử lý các yêu cầu HTTP và HTTPS.
- Đều hỗ trợ các tính năng như cân bằng tải, bộ đệm động, bộ đệm tĩnh, định tuyến URL và nhiều tính năng khác.
- Đều có thể được cấu hình một cách linh hoạt để phù hợp với yêu cầu của các ứng dụng web khác nhau.
- Đều có tính năng tùy chỉnh và mở rộng thông qua các module và plugin.
#### Khác nhau:
- Nginx được thiết kế để xử lý các yêu cầu web đồng thời nhiều hơn Apache, do đó Nginx có hiệu suất tốt hơn đối với các ứng dụng web có lưu lượng truy cập lớn.
- Apache được sử dụng rộng rãi hơn Nginx và có thư viện module phong phú hơn, nên Apache thường được sử dụng cho các ứng dụng web phức tạp hơn.
- Nginx sử dụng một kiến trúc tương đối đơn giản và có tiêu thụ tài nguyên ít hơn so với Apache.
- Apache hỗ trợ nhiều hệ điều hành hơn so với Nginx, bao gồm Windows, Linux, MacOS và nhiều hơn nữa.
- Nginx có khả năng chịu lỗi tốt hơn so với Apache khi có nhiều yêu cầu đồng thời.
##### Tóm lại, cả Apache và Nginx đều là các phần mềm máy chủ web được sử dụng rộng rãi trong các ứng dụng web hiện đại. Tuy nhiên, với một số yêu cầu cụ thể của ứng dụng web, người dùng có thể lựa chọn sử dụng Nginx hoặc Apache để đạt được hiệu suất và tính linh hoạt tốt nhất.
## Lưu ý
Apache và Nginx là hai máy chủ web phổ biến và có thể được cài đặt trên cùng một hệ thống. Tuy nhiên, nếu chúng ta cài đặt cả hai trên cùng một máy chủ và cấu hình chúng để lắng nghe cổng mặc định của mình (Apache là cổng 80, Nginx là cổng 8080), thì ta cần phải thay đổi cấu hình của một trong hai máy chủ để tránh xung đột cổng.

Ngoài ra, nếu muốn sử dụng cả hai máy chủ trên cùng một máy tính,ta có thể cấu hình Nginx để chuyển tiếp các yêu cầu tới Apache hoặc ngược lại. Việc này có thể giúp tăng hiệu suất và bảo mật của máy chủ web của mình. Tuy nhiên, việc cấu hình này phức tạp và yêu cầu kiến thức chuyên sâu về hệ thống và máy chủ web.
