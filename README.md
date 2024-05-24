# w
漏洞检测测试项目

1. 注意将实验数据保留下来，每个测试的目标代码（libtiff、ffmpeg、openssl、linux）分别有一个对应目录，每个目录下都分别保存不同的数据。例如：使用 vuddy 测试得到的漏洞数据放在 vuddy_data 路径下，其他的以此类推。
2. 漏洞是否正确使用 [VCE-Detail](https://www.cvedetails.com/) 查询，并与测试的目标代码比对，是否已经打过补丁。
3. 将漏洞对比结果保存到“实验项目.xlsx”文件中，每个目标代码使用一个 sheet，保存补丁提交的 commit 证据。

拉取和上传建议先 fetch 再 merge，而非直接 pull。
