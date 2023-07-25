# Excel_xiao

=LEFT(A1,SEARCH("@",SUBSTITUTE(A1,"-","@",LEN(A1)-LEN(SUBSTITUTE(A1,"-",""))-1))-1)  //删除倒数第二个"-"之后的数据 例如：H30-H214-1300-1 =H30-H214

---
