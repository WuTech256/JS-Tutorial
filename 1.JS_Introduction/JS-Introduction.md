# JavaScript Tutorial
	- JavaScript là ngôn ngữ lập trình phổ biến nhất thế giới
	- Là ngôn ngữ lập trình web
	- Dễ học
	
# JS Introduction

## What is JavaScript?
		- JavaScript là một ngôn ngữ lập trình Web.
		- Nó có thể cập nhật và thay đổi cả HTML và CSS.
		- Nó có thể tính toán, xử lý và xác thực dữ liệu.
	
## Why Study JavaScript?
		- JavaScript là 1 trong 3 ngôn ngữ mà các Web developers phải học:
			1. HTML để xác định nội dung của các trang web.
			2. CSS để chỉ định bố cục của trang web.
			3. JS để lập trình hành vi của các trang web.
	
## JS có thể thay đổi HTML content
		- Eg: 
			`document.getElementById("demo").innerHTML = "Hello JavaScript"`
			Tìm một phần tử có id là "demo" và thay đổi nội dung phần tử innerHTML thành "Hello JavaScript"
		- JS chấp nhận cả dấu `'` và `"`
		- JS có thể thay đổi giá trị của thuộc tính trong HTML
			Eg:
				`document.getElementById('myImgae').src = 'toan.gif'`
			Trong ví dụ này, JS thay đổi giá trị của thuộc tính `src`
	
## JS có thể thay đổi HTML Styles (CSS)
		- Thay đổi kiểu của một phần tử HTML là 1 biến thể của việc thay đổi thuộc tính HTML:
			`document.getElementById("demo").style.fontSize = "35px";`
			
	
## JS có thể ẩn các đối tượng HTML
		- Có thể ẩn các phần tử HTML bằng cách thay đổi kiểu hiển thị:
			`document.getElementById("demo").style.display = "none";`
		
## JS có thể show các phần tử HTML:
		- Việc hiển thị các phần tử HTML ẩn cũng có thể được thực hiện bằng cách thay đổi kiểu hiển thị:
			`document.getElementById("demo").style.display = "block";`
