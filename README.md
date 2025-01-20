
<html>
<head>
<title>Page Title</title>
</head>
<style>
input[type=text], select, textarea {
  width: 100%; 
  padding: 12px; 
  border: 1px solid #ccc; 
  border-radius: 4px; 
  box-sizing: border-box; 
  margin-top: 6px; 
  margin-bottom: 16px; 
  resize: vertical 
}


input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}


.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
<body>

<div class="container">
  <form action="action_page.php">

    <label for="fname"> Họ và Tên</label> 
    
            

    <input type="text" id="fname" name="firstname" placeholder="Nhập tên của bạn..">
    

    <label for="country">clb muốn chọn</label>
    <select id="country" name="country">
      <option value="clb Tiếng anh">clb Thể thao</option>
      <option value="clb Bóng chuyền">clb Âm Thực</option>
      <option value="clb cờ vua">clb Nghệ Thuật</option></select>  
      <label for="class">Lớp:</label>
    <select id="class" name="class">
            <option value="10">10</option>
             <option value="11">11</option>
              <option value="12">12</option>
            
            
         

    </select>

    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">

  </form>
</div>

</body>
</html>
